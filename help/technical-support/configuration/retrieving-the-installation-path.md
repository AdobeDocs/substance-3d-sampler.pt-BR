---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/configuration/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: Saiba como recuperar o caminho de instalação do Substance 3D Sampler em diferentes plataformas para fins de script e configuração.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Recuperação do caminho de instalação
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 5%

---


# Recuperação do caminho de instalação

Esta página reagrupa informações sobre maneiras de recuperar o caminho de instalação do aplicativo, dependendo da versão e da plataforma.

## Windows

### Creative Cloud para desktop

1. Abra o editor do Registro do Windows (**regedit**).
1. Navegue até a chave de registro: ** HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App Paths\**
1. Abra a subchave denominada **Adobe Substance 3D Sampler.exe**
1. O valor da chave contém o caminho para o executável do aplicativo no qual ela está instalada

>[!NOTE]
>
> Esta chave do Registro está disponível somente desde a versão 3.\
> Para versões mais antigas, o caminho de instalação pode ser recuperado das associações de arquivos no **HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts**.

### Substance 3D Autônomo

1. Abra o editor do Registro do Windows (**regedit**).
1. Navegue até a chave do Registro: **HKEY\_LOCAL\_MACHINE\ SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**
1. Localize a subchave correspondente à AppID da versão do seu aplicativo (consulte a tabela abaixo)
1. O valor da chave contém o caminho para o local de instalação do aplicativo

| Versão | AppId |
| --- | --- |
| **1.x (2019.x) para 2.x** | {B3506E85-E98F-4D48-A010-BE4DEE27D108} |
| **3.x (ou mais recente)** | {ED4A4ABC-9B7D-44B8-984A-C8A994B69CFD} |

### Vapor

O aplicativo está instalado na subpasta **steamapps/common/** da pasta de instalação do Steam.

## Mac

No Mac, o aplicativo é instalado no seguinte:

| Versão | Caminho |
| --- | --- |
| **3.x ou mais recente** | **/Aplicativos/Adobe Substance 3D Sampler.app** |
| **Herdado** | **/Aplicativos/Substance Alchemist.app** |

## Linux

No Linux, o pacote rpm é instalado no seguinte caminho:

| Versão | Caminho |
| --- | --- |
| **3.x ou mais recente** | **/opt/Adobe/Adobe\_Substance\_3D\_Sampler** |
| **Herdado** | **/opt/Allegorithmic/Substance\_Alchemist** |
