---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/color-variation.html"
breadcrumb-title: ''
description: Use o filtro Variação de cor no Substance 3D Sampler para adicionar diversidade e variação de cores às texturas para obter materiais mais naturais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Color Variation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Variação de cor
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '534'
ht-degree: 1%

---


# Variação de cor

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-colorpalette-18-n-d.png)

**Entrada:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Variação de cor permite substituir várias cores na cor base ou no canal difuso de uma só vez. Isso é semelhante ao **filtro de Substituição de Cor**, mas enquanto a **Variação de Cor** permite ajustar várias cores em um filtro, a **Substituição de Cor** fornece a você mais controle sobre a máscara usada para substituir cores e pode ser usada em vários canais.

Nas imagens abaixo, o **filtro de Variação de Cor** foi usado para ajustar não apenas a cor branca subjacente para torná-la uma cor turquesa pálida, mas também para aumentar o contraste de muitas das manchas menores.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0047-color-variation-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0046-color-variation-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Contagem de cores**: 1-10\
  Modificar o número de cores que substituirão as cores do canal
* **Variação de luminosidade**: 0-1\
  Ajuste quanto os valores de luminosidade são afetados pela cor substituída
* **Segmentação**:\
  Baseie a máscara usada para aplicar cores em um canal diferente.
* **Modo de Seleção de Cores**:\
  Escolha se deseja selecionar as cores de origem manual ou automaticamente. Se o modo de seleção **Manual** for escolhido, use as alças da **exibição 2D** para selecionar as cores.
  * **Mostrar auxiliar de texto**: alternar\
    Este controle só será visível se o **Modo de Seleção de Cores** estiver definido como **Manual**. Quando habilitado, o **Mostrar auxiliar de texto** adicionará rótulos de texto às alças na **exibição 2D** para distinguir mais facilmente as alças de seleção de cores
* **Cor X**: seleção de cor\
  O número de controles de cor disponíveis depende do valor selecionado com **Contagem de cores**. Para cada cor, selecione a nova cor para substituir a cor do material original.

## Guia de Uso

O **filtro de Variação de Cor** permite modificar rapidamente várias cores do canal de cor base de uma só vez. Para alguns materiais, isso pode ser útil para fazer pequenos ajustes, mas o **filtro de Variação de cor** é melhor para reformular completamente as cores do material com um único filtro.

Para usar o **filtro de Variação de Cor**:

1. Adicionar o **filtro de Variação de Cor** à pilha de camadas
1. Ajuste o número de cores que deseja substituir por **Contagem de cores**. O filtro substituirá toda a cor do canal - o controle **Contagem de cores** permite definir quantas cores novas as cores existentes substituirão.
1. Opcionalmente, selecione uma **Segmentação** ou um canal diferente no qual basear as cores. Por exemplo, você pode selecionar o canal metálico e usar o **Modo de seleção de cores > Manual** para colocar uma alça em um valor metálico preto e outra em um valor metálico branco. Com essa configuração, você pode controlar a cor das partes metálicas e não metálicas do material individualmente.
1. Selecione um **Modo de Seleção de Cores**. Com o modo manual selecionado, as alças aparecem na **exibição 2D**, permitindo selecionar a cor base original que a nova cor substituirá. Habilite o **Assistente para Mostrar Texto** para controlar qual identificador está vinculado a qual cor.
1. Modifique os valores de cor com os controles de **Cor 1 - 10**.
1. Ajuste a **Variação de luminosidade** para ajustar quanto a luminosidade é afetada pela substituição da cor. Com uma baixa **Variação de luminosidade**, você pode nivelar completamente as cores do material ou usar uma alta **Variação de luminosidade** para manter os detalhes das cores originais.
