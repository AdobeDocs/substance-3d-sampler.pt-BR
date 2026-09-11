---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-plugin-with-python-and-qml.html"
breadcrumb-title: ''
description: Saiba como criar plug-ins com Python e QML para o Substance 3D Sampler para criar interfaces de usuário personalizadas e estender a funcionalidade.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Plugin with Python and QML
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Criar um plug-in com Python e QML
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# Criar um plug-in com Python e QML

Este guia descreve como criar um plug-in simples de salvamento automático com Python e QML.

## Estrutura do plug-in

Os plug-ins do Sampler requerem pelo menos um arquivo Python e QML para serem importados, mas outros arquivos também podem ser incluídos, como imagens usadas para ícones no painel de plug-ins. No exemplo abaixo, há 3 arquivos:

* **autosave.py** contém a lógica do plug-in e determina como ela funciona.
* O **autosave.qml** define a aparência do plug-in no Sampler.
* **autosave.svg**&#x200B;é um gráfico vetorial usado como ícone do plug-in.

Assim que tiver os arquivos necessários para seu plug-in em uma única pasta, você pode adicionar o plug-in ao Sampler por meio de Editar > Preferências > Plug-ins e scripts. Para saber mais sobre como gerenciar plug-ins, clique [aqui](manage-installed-plugins-and-scripts.md).

## Python

O código abaixo é o arquivo Python completo para o plug-in de salvamento automático. Abaixo há uma breve descrição do que o código está fazendo, mas o código também inclui comentários com mais informações:

1. Importe módulos relevantes.
   1. Qt é um kit de ferramentas multiplataforma GUI. QtcCore, QtQml e QtQuick são módulos que usamos para nos comunicarmos entre autosave.py e autosave.qml.
1. Defina um método **save()** que salva o projeto a cada X minutos.
1. Criar uma classe de salvamento automático. Esta classe especifica como o método **save()** se conecta à interface do usuário do plug-in para que os parâmetros possam alterar o comportamento do plug-in
1. Defina um método **register\_qml\_type()** que execute a configuração do plug-in.
1. Chame o plug-in pelo Sampler.

### autosave.py

```
## Import QT & QML modules to create the UI

from PySide2 import QtCore, QtQml, QtQuick 

## Import Sampler API

import substance_sampler as ssa 

## Import other modules for this specific example

import datetime 

import os 

import threading 

 

 

## Save the project every X minutes

def save(interval): 

    global t 

    ssa.save_project() 

    if ssa.save_project(): 

        now = datetime.datetime.now() 

        print("Autosave: %d:%d:%d" % (now.hour, now.minute, now.second)) 

    t = threading.Timer(interval, save, [interval]) 

    t.start() 

 

 

t = None 

 

 

## Declare the API AutoSave

class AutoSave(QtQuick.QQuickItem): 

    def __init__(self, parent=None): 

        super(AutoSave, self).__init__(parent) 

 

## Declare a first API function

## This function can be called from the QML file

## with 2 arguments, one string and one integer

    @QtCore.Slot(str, int) 

    def start_auto_save(self, default_path, interval): 

        if not ssa.save_project(): 

            ssa.save_project_as(os.path.join(default_path, "autosave.ssa")) 

        global t 

        t = threading.Timer(10, save, [interval]) 

        t.start() 

        print("Launch Autosave") 

 

## Second function of the API

## With no argument

    @QtCore.Slot(None) 

    def stop_auto_save(self): 

        global t 

        t.cancel() 

        print("Stop Autosave") 

 

 

## Function to declare the API and the panel

## First argument is Python class of your API

## Second argument is name of the API you will use in the QML file

## Third and fourth is the API version. In this case, 1.0

## Last is the name of the panel in Sampler UI

def register_qml_type(): 

    QtQml.qmlRegisterType(AutoSave, "AutoSave", 1, 0, "AutoSave") 

 

 

## Execute the plugin in Sampler UI thread

ssa.run_in_main_thread(register_qml_type)
```


## QML

O arquivo QML define a interface do usuário do plug-in. QML significa Qt Markup Language e comporta-se de forma semelhante a outras linguagens de marcação como HTML e XML. Você pode [saber mais sobre o QML aqui](https://doc.qt.io/qt-6/qmlapplications.html#:~:text=QML%20is%20a%20user%20interface%20specification%20and%20programming,imperative%20JavaScript%20expressions%20combined%20with%20dynamic%20property%20bindings.).

A estrutura geral do autosave.qml é a seguinte:

1. Importar módulos.
   1. Os módulos do Qt importados são necessários para os elementos da interface do usuário usados no arquivo.
   1. A classe de API de Salvamento Automático criada em **autosave.py** também é importada. O arquivo QML faz referência a esta classe na linha 20.
1. Crie variáveis que precisam ser controladas.
   1. **autoSaveFolder** é a pasta na qual o arquivo do Sampler será salvo automaticamente.
   1. **duração** é o tempo em segundos entre os salvamentos automáticos.
   1. **textColor** é usado para que a cor do texto na interface do usuário do plug-in possa ser atualizada em um único local.
1. Instanciar a API Python
1. Defina a interface.
   1. Isso inclui ganchos para a API Python criada em **autosave.py**. Por exemplo:
      1. A linha 47 atualiza o valor da variável **timing** no arquivo QML sempre que o elemento “Autossave every (min):” é alterado.
      1. A linha 64 chama a função **start\_auto\_save** da API e transmite as variáveis **timing** e **autoSaveFolder** como parâmetros.
1. Crie um método para limpar o caminho de arquivo padrão.

### autosave.qml

```
/* 

Import Qt modules to design the UI 

https://doc.qt.io/qt-5/qtqml-syntax-basics.html 

*/ 

import QtQuick 2.15 

import QtQuick.Controls 2.15 

import Qt.labs.platform 1.1 

import AutoSave 1.0 // Import API defined in the Python file 

 

Rectangle { 

  id: root 

  anchors.fill: parent 

  color: "#333333" 

 

  property var autoSaveFolder: removeQmlFilePathPrefix(StandardPaths.writableLocation(StandardPaths.DocumentsLocation)) 

  property var timing: 300 

  property var textColor: "#b3b3b3" 

 

  AutoSave { 

      id: api // Instantiate the Python API 

  } 

 

  Column { 

    id: controls 

    anchors.top: parent.top + 10 

    anchors.left: parent.left + 10 

    anchors.right: parent.right 

    width: parent.width 

    spacing: 20 

    leftPadding: 10 

    topPadding: 10 

 

    Column { 

        spacing: 5 

        Text { 

            id: timingTitle 

            text: "Autosave every (min): " 

            color: root.textColor 

        } 

        SpinBox { 

            id: timingControl 

            from: 1 

            to: 10 

            stepSize: 1 

            value: 5 

 

            onValueModified: ()=>{ 

                root.timing = timingControl.value * 60 

            } 

        } 

    } 

    Row { 

        Text { 

            text: "Off" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

        Switch { 

            id: toggle 

            checked: false 

 

            onClicked: ()=>{ 

                if (checked === true) { 

                    api.start_auto_save(root.autoSaveFolder, root.timing) // Call a function of the API with 2 arguments 

                } 

                else if (checked === false) { 

                    api.stop_auto_save() // Call a function of the API 

                } 

            } 

        } 

        Text { 

            text: "On" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

 

    } 

    Column { 

        spacing: 5 

        Text { 

            text: "Default Autosave Path" 

            color: root.textColor 

            } 

        Row { 

            id: folderInput 

            TextField { 

                id: folderText 

                text: root.autoSaveFolder 

                readOnly: true 

            } 

            Button { 

                id: folderSelection 

                text: qsTr("...") 

                width: 40 

                onClicked: ()=>{ 

                    folderDialog.open() 

                    } 

            } 

        } 

    } 

 

    FolderDialog { 

        id: folderDialog 

 

        onAccepted: ()=>{ 

            root.autoSaveFolder = removeQmlFilePathPrefix(folderDialog.currentFolder) 

        } 

    } 

 

  } 

      function qmlFilePathPrefix() { 

        if (Qt.platform.os === "windows") { 

            return "file:///" 

        } 

        return "file://" 

    } 

    function removeQmlFilePathPrefix(filePath) { 

        var prefix = qmlFilePathPrefix() 

        return filePath.toString().replace(prefix, '') 

    } 

}
```


## SVG

Talvez você tenha notado que o **autosave.svg** não é explicitamente chamado ou mencionado no **autosave.py** ou no **autosave.qml**. Isso ocorre porque o Sampler procura um arquivo SVG com o mesmo nome do arquivo PY e o usa automaticamente como ícone de plug-in.

>[!NOTE]
>
> Se a pasta do seu plug-in contiver um SVG com um nome de arquivo que não corresponda ao arquivo PY do plug-in, seu plug-in não incluirá um ícone. Isso pode criar a aparência de que seu plug-in não apareceu na interface do Sampler. Se for esse o caso, mova o cursor sobre a barra direita do Sampler para destacar seu plug-in.
> 
> Seu navegador não é compatível com o elemento de vídeo HTML5

Se a pasta do seu plug-in não contiver um arquivo SVG, um ícone de plug-in padrão será usado.

Veja abaixo um SVG de exemplo que você pode usar para o plug-in de salvamento automático criado acima.

[autosave.svg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455541/234455542/1/1662460696349/autosave.svg)

## Limitações do plug-in de salvamento automático

O plug-in de salvamento automático criado acima é funcional, mas não é perfeito. Por exemplo, ajustar o intervalo de salvamento automático após a ativação do salvamento automático não alterará o tempo entre os salvamentos automáticos. Você precisaria desativar e reativar o salvamento automático para que o valor na interface fosse enviado à API.

Se você é novo no trabalho com Python e QML em conjunto, corrigir esse erro é uma maneira útil de construir uma compreensão de como as diferentes partes do plug-in se comunicam entre si.
