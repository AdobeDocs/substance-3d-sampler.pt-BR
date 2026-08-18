---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/technical-support/configuration/update-checker.html"
breadcrumb-title: ''
description: Saiba como usar o verificador de atualizações no Substance 3D Sampler para se manter informado sobre novas versões e notas de versão.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Update Checker
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Verificador de Atualização
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---


# Verificador de Atualização

A janela Atualizar indica se uma nova versão do Substance Alchemist está disponível e exibe também as [Notas de versão](../../release-notes/release-notes.md) mais recentes.

Essa janela aparece automaticamente durante a inicialização do Substance Alchemist se uma nova versão estiver disponível para download.

É possível evitar exibir essa janela durante a inicialização com os seguintes métodos:

* Use a configuração “Não lembrar até a próxima versão” na janela para pular temporariamente a exibição da janela até a próxima versão.
* Desabilite a configuração “**Verificar atualizações**” em Editar > Preferências > Verificar atualizações
* Usando a linha de comando **—skip-version-check** Ela não verificará se uma nova versão do aplicativo está disponível quando o Substance Alchemist estiver sendo inicializado
* Usando uma variável de ambiente **SUBSTANCE\_ALCHEMIST\_SKIP\_CHECK\_FOR\_UPDATES**:Value 0 ou 1 (1 = Desabilitar verificação de atualização)

>[!NOTE]
>
> Compatível desde o Substance Alchemist 2020.1 (2.1)
