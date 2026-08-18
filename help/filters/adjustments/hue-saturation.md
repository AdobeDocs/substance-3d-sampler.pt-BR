---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/adjustments/hue-saturation.html"
breadcrumb-title: ''
description: Use o filtro Matiz/saturação no Substance 3D Sampler para ajustar os valores de matiz, saturação e luminosidade em texturas e materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > HueSaturation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: HueSaturation
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---


# Matiz/saturação

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hueandsat-18-n-d.png)

**Entrada:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Matiz/Saturação permite ajustar a cor da cor de base e dos canais difusos. Também é possível usar uma máscara para modificar especificamente as cores somente de partes da imagem.

As imagens abaixo mostram o **filtro de Matiz/Saturação** usado para ajustar a Matiz de um material ladrilhado.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0027-hue-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0026-hue-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Matiz**: -1 a 1\
  Ajuste a matiz da imagem - isso é útil para corrigir cores no fluxo de trabalho Imagem para material.
* **Saturação**: -1 a 1\
  Ajuste a saturação para destacar as cores ou diminua a intensidade da cor.
* **Luminosidade**: -1 a 1\
  Modifique a luminosidade de suas cores.
* **Colorir**: alternar\
  Quando desativado, o filtro ajusta as cores que já estão presentes. Quando ativado, o filtro substituirá as cores com base nos controles deslizantes de Matiz, Saturação e Luminosidade, mantendo os detalhes.

**Máscara**

* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara
  * **Máscara personalizada - Inverter**: alternar\
    Inverter a máscara
