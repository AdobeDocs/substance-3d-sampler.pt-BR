---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/activation-and-licenses.html"
breadcrumb-title: ''
description: Saiba como ativar e gerenciar licenças para que o Substance 3D Sampler comece a usar o aplicativo e acesse todos os recursos.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Activation and licenses
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ativação e licenças
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 1%

---


# Ativação e licenças

Esta página tem informações sobre como ativar e gerenciar suas licenças para que você possa começar a usar o Sampler.

## Processo de ativação por tipo de aplicativo

O processo de ativação depende de onde você adquiriu ou tem acesso ao Sampler:

| Tipo de Aplicativo | Processo de ativação |
| --- | --- |
| Creative Cloud para desktop | Consulte a página dedicada na [documentação do HelpX](https://helpx.adobe.com/support/substance-3d-sampler.html).Caso haja problemas, a [documentação do Creative Cloud](https://helpx.adobe.com/creative-cloud/user-guide.html) poderá fornecer respostas adicionais. |
| Vapor | Inicie o produto diretamente da biblioteca do Steam. |
| Substance 3D autônomo | Consulte o processo de ativação descrito abaixo. |

## Etapas de ativação

### O assistente de ativação

![](../assets/activation-wizard.png){width="350px"}

Há três opções disponíveis:

* **Avalie este produto**: as versões de avaliação herdadas não estão mais disponíveis. Em vez disso, você pode iniciar uma avaliação de 30 dias para cada aplicativo da Substance 3D [aqui](https://www.adobe.com/creativecloud/3d-augmented-reality.html) ou com o Creative Cloud Desktop. Cada versão de avaliação é independente dos outros aplicativos da Substance 3D, portanto você pode experimentá-los um de cada vez ou todos de uma vez.
* **Ativar usando um arquivo de licença**: ative o produto com um arquivo de licença (**\*.key**) baixado da página da sua conta no [site da Substance 3D](https://store.substance3d.com/user) antes de 30 de setembro de 2022.
* **Ative usando sua conta**: contas do substance herdadas não podem mais ser usadas para ativação. [Mais informações sobre contas Substance estão disponíveis aqui](https://helpx.adobe.com/substance-3d/unlisted/faq-end-of-life-accounts.html).

>[!WARNING]
>
> Para instalar o arquivo de licença com o Assistente de ativação, certifique-se de executar o Sampler como administrador e desativar temporariamente o antivírus.

### Ativação manual

É possível ativar manualmente o Sampler colocando o arquivo **license.key** na seguinte pasta:

<table data-preserve-html="true"><colgroup> <col/> <col/> <col/> <col/> </colgroup><tbody><tr><th>Plataforma</th><th>Versão</th><th colspan="2">Caminho</th></tr><tr><td rowspan="4"><strong>Windows</strong></td><td rowspan="2"><strong>3.0</strong> ou mais recente</td><td colspan="1">Dados do aplicativo (local)</td><td colspan="1">C:\Users\[nome do usuário]\AppData\Local\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">Dados de Aplicativo (roaming)</td><td colspan="1">C:\Users\[nome do usuário]\AppData\Roaming\Adobe\Adobe Substance 3D Sampler</td></tr><tr><td rowspan="2">Legado</td><td colspan="1">Dados do aplicativo (local)</td><td colspan="1">C:\Users\[nome de usuário]\AppData\Local\Allegorithmic\Substance Alchemist</td></tr><tr><td colspan="1">Dados de Aplicativo (roaming)</td><td colspan="1">C:\Users\[nome de usuário]\AppData\Roaming\Allegorithmic\Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Mac</strong></td><td colspan="1"><strong>3.0</strong> ou mais recente</td><td colspan="2">/Users/[nome do usuário]/Library/Application Support/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td colspan="1">Legado</td><td colspan="2">/Users/[nome do usuário]/Library/Application Support/Allegorithmic/Substance Alchemist</td></tr><tr><td rowspan="2"><strong>Linux</strong></td><td colspan="1"><strong>3.0</strong> ou mais recente</td><td colspan="2">/home/[nome do usuário]/.local/share/Adobe/Adobe Substance 3D Sampler</td></tr><tr><td>Legado</td><td colspan="2">/home/[nome do usuário]/.local/share/Allegorithmic/Substance Alchemist</td></tr></tbody></table>

>[!NOTE]
>
> Alguns dos diretórios nos caminhos mencionados acima podem estar ocultos por padrão. Digite o caminho manualmente no explorador de arquivos ou exiba arquivos ocultos para exibi-los.

>[!NOTE]
>
> Verifique se o arquivo é chamado de **license.key**, caso contrário, o aplicativo não poderá encontrá-lo.

### Variável de ambiente

Você pode substituir o local que o Sampler verifica para o arquivo **license.key** por uma [Variável de ambiente](../pipeline-and-integrations/environment-variables.md).
