---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/manage-installed-plugins-and-scripts.html"
breadcrumb-title: ''
description: Saiba como gerenciar plug-ins e scripts instalados no Substance 3D Sampler para instalar, modificar e remover extensões personalizadas.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Manage installed plugins and scripts
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Gerenciar plug-ins e scripts instalados
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '499'
ht-degree: 0%

---


# Gerenciar plug-ins e scripts instalados

Para instalar, modificar ou remover plug-ins, use Editar > Preferências e selecione Plug-ins e scripts.

![](../assets/preferences-86.png)

No painel Plug-ins e scripts, você pode ativar o painel Registro, que exibe a saída de plug-ins. Isso pode ser útil para solução de problemas e depuração. Uma vez ativado, você pode abrir o painel Registro na barra à direita da interface principal do Sampler. O painel Log pode ser encaixado assim como outros painéis do Sampler.

## Plug-ins versus scripts

A principal diferença entre plug-ins e scripts é que eles incluem elementos de interface, o que não ocorre com scripts. Os plug-ins requerem pelo menos um arquivo PY e QML. O arquivo QML define os elementos da interface do usuário, enquanto o arquivo PY define o comportamento do plug-in. Os scripts, por outro lado, consistem apenas em um arquivo PY.

Os elementos da interface de um plug-in significam que o comportamento do plug-in pode ser modificado por meio do uso de parâmetros. Por exemplo, o plug-in de salvamento automático de exemplo tem controles que permitem modificar o tempo entre os salvamentos automáticos. Os plug-ins se tornam parte da interface do Sampler e podem ser encaixados e movidos como painéis padrão do Sampler.

Os scripts não permitem esse nível de flexibilidade, mas executam uma determinada tarefa. Por exemplo, o script Exportar tudo sempre se comportará da mesma maneira sempre que for chamado. Os scripts podem ser acessados na barra de menu superior - o menu Script só fica disponível depois que os scripts são adicionados ao Sampler.

## Gerenciar plug-ins

Por padrão, a única opção disponível é “Adicionar um plug-in”. Isso abre um explorador de arquivos onde você pode selecionar um arquivo PY para carregar.

![](../assets/manageplugins.png)

>[!NOTE]
>
> Os plug-ins requerem um arquivo PY e um QML para funcionar. Quando você seleciona um arquivo PY para importar, o Sampler busca na pasta um arquivo QML. Se nenhum arquivo QML for encontrado, o carregamento do plug-in falhará.

Depois que um plug-in é instalado, algumas opções ficam disponíveis:

* Os plug-ins podem ser reordenados arrastando a alça no lado esquerdo do plug-in.
* Ative ou desative plug-ins com o botão de alternância.
* Use o botão do menu à direita de cada plug-in para recarregar, remover ou abrir o local da pasta do plug-in.

Os plug-ins instalados aparecerão inicialmente na barra direita da interface principal do Sampler. A partir daí, você pode abrir, encaixar e mover o painel do plug-in como painéis padrão do Sampler.

## Gerenciar Scripts

Os scripts podem ser gerenciados de forma semelhante aos plug-ins.

![](../assets/managescripts.png)

Após a instalação de um script, algumas opções ficam disponíveis:

* Reordene scripts com a alça no lado esquerdo do script.
* Ative ou desative o script com o botão de alternância.
* Use o botão de menu à direita de cada script para removê-lo ou abra a localização da pasta do script.
* Quando importados, os scripts são copiados em **%\AppData\Roaming\Adobe\Adobe Substance 3D Sampler\scripts**
* Para editar o script, você deve modificar o que foi copiado pelo Sampler
