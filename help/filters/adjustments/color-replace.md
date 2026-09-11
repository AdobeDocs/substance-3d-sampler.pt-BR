---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/color-replace.html"
breadcrumb-title: ''
description: Use o filtro Substituição de cor no Substance 3D Sampler para substituir cores específicas no textura por novos valores de cor.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Color Replace
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Substituição de cor
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '570'
ht-degree: 0%

---


# Substituição de cor

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-replacecolor-18-n-d.png)

**Entrada:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Substitua uma cor ou valor escolhido em um canal.

As imagens abaixo mostram **Substituição de cor** em ação. Observe como as áreas entre os ladrilhos permanecem com a mesma cor. Apenas os ladrilhos são alterados.

![](../../assets/3d-2d-filters-cropped-0051-color-replace-in.jpg)![](../../assets/3d-2d-filters-cropped-0050-color-replace-out.jpg)

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Segmentação avançada**: alternar\
  Quando ativado, o filtro pode usar um canal separado para gerar informações de máscara a partir do canal afetado pela Substituição de cor.
  * **Máscara** **De**:\
    Selecione um canal para agir como uma origem para a geração de máscara. Por exemplo, uma máscara do valor metálico substitui a cor de base de áreas metálicas do material
* **Substituir em**:\
  Selecione o canal afetado pela substituição de cor.
* **Cor de destino**: seleção de cor\
  Selecione a cor que substituirá as cores do canal atual.
* **Variação de luminosidade**: 0-1\
  Ajuste o quanto os valores de luminosidade originais são afetados pela luminosidade da nova cor.
* **Intervalo de máscaras**\
  A máscara é criada com base na combinação dos seguintes valores
  * **&#x200B;**&#x200B;**&#x200B; Da Luminosidade &#x200B;**: 0-1\
    O intervalo de luminosidade usado para criar a máscara **&#x200B;**
  * **De Cor**: 0-1\
    O intervalo de cores usado para criar a máscara
* **Smoothness de máscara**: 0-1\
  Ajustar a granularidade da máscara
* **Desfoque de Máscara**: 0-1\
  Desfocar a máscara

**Máscara**

Esta máscara é separada da máscara criada em **Parâmetros básicos** - você pode usar uma máscara personalizada para tinta ou usar uma imagem para especificar áreas a serem afetadas pelo filtro **Substituição de Cor** como um todo.

* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para tinta uma máscara personalizada diretamente na Visualização 2D
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara
  * **Máscara personalizada - Inverter**: alternar\
    Inverter a máscara

## Guia de Uso

O **filtro de Substituição de Cor** é uma maneira poderosa de modificar a aparência dos materiais, por exemplo, usá-lo para transformar ferrugem de ferro em cobre oxidado

O filtro funciona criando primeiro uma máscara com base nos valores de luminosidade e cor de um ponto escolhido e, em seguida, substituindo a cor da área definida por essa máscara. Para usar o filtro:

1. Adicionar o **filtro Substituição de Cor** à pilha de camadas
1. Determine qual canal você deseja usar para criar a máscara e qual canal deseja substituir a cor
   1. Se você deseja basear a máscara em um canal, mas substituir a cor de outro, habilite a **Segmentação avançada** e selecione os respectivos canais.
   1. Se você deseja basear a máscara em um canal e substituir a cor do mesmo canal, deixe a **Segmentação avançada** desabilitada.
1. Mova o controle no **modo de exibição 2D** sobre a cor que deseja substituir.
1. Ajuste quais áreas a máscara cobre usando os controles **Intervalo de máscara**, **Smoothness de máscara** e **Desfoque de máscara**.
1. Selecione uma **Cor de destino** e ajuste a **Variação de luminosidade** até ficar satisfeito com o efeito.
1. Ou adicione uma máscara personalizada para aplicar apenas os efeitos do filtro nas áreas escolhidas. A máscara personalizada não afeta a máscara criada na etapa 1. Em vez disso, é uma máscara adicional que você pode usar para ajustar mais onde o efeito é aplicado.

Às vezes, pode ser útil usar vários **filtros de Substituição de Cor** um sobre o outro para criar efeitos mais avançados.
