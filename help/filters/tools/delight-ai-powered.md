---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/tools/delight-ai-powered.html"
breadcrumb-title: ''
description: Use o filtro Delícia com IA no Substance 3D Sampler para remover informações de iluminação das imagens e criar materiais de base neutros.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Delight (AI Powered)
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Delícia (viabilizado por IA)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---


# Delícia (viabilizado por IA)

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-lightgeneric-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O Delighter permite remover informações de iluminação do canal de cor base. Isso é importante ao converter imagens em materiais, pois geralmente os materiais não devem incluir informações de iluminação. Um material é uma coleção de informações que explica como a luz deve reagir com uma superfície, de modo que, se já houver informações sobre a luz inseridas em um canal que não deve ter informações sobre a luz, isso pode quebrar a capacidade do material de representar a superfície de forma realista.

*Um **n exemplo de uma imagem antes e depois de ser processada pelo**&#x200B;filtro de Alegria (IA)**. Observe que as sombras e os realces foram removidos, mas somente a cor base permanece.*

![](../../assets/120-0-comparison.png)

As imagens abaixo mostram um material antes e depois de ser processado por um **filtro de Alegria (alimentado por IA)**.

![](../../assets/3d-2d-filters-cropped-0043-delighter-in.jpg)

Na imagem acima, o material ainda inclui uma quantidade substancial de informações de iluminação no canal de cor base. As sombras escuras entre os tijolos não devem estar presentes no canal de cor base.

![](../../assets/3d-2d-filters-cropped-0042-delight-out.jpg)

Depois do passo delicioso, as sombras foram removidas para criar um canal de cor base mais fisicamente preciso. Embora os resultados neste exemplo possam não parecer perceptíveis, encantar imagens é uma etapa importante na conversão de imagens em materiais.

Em imagens de origem, a luz vem de fontes estáticas, mas os materiais precisam ser capazes de lidar com a luz vinda de qualquer ângulo. Por exemplo: se uma imagem de origem com luz brilhando de cima para baixo for convertida em um material sem passar por uma etapa de deleite, ela poderá ser exibida em um espaço 3D onde a luz brilha de baixo para cima. O material parecerá fora do lugar rapidamente porque, simultaneamente, parece estar projetando sombras de várias luzes quando há apenas uma única fonte de luz.

</td>
</tr>
</table>

## Parâmetros

O delighter não tem parâmetros - ele funciona automaticamente.

## Guia de Uso

Como usá-lo?

Adicione o **filtro Delighter** ao topo da pilha de camadas.

### Quando usá-lo?

Ao usar o **Image to Material (B2M)**, depois de extrair todos os canais de suas imagens e tornar o material legível, use o delighter para remover as informações de iluminação da cor base. **A Imagem para Material (desenvolvida por IA)** inclui uma passagem de delícia, portanto, você não precisa usar o **Filtro Delighter (desenvolvido por IA)** com ela.
