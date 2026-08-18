---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/brightness-contrast.html"
breadcrumb-title: ''
description: Use o filtro Brilho/Contraste no Substance 3D Sampler para ajustar os níveis de brilho e contraste em texturas e camadas de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > BrightnessContrast
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: ContrasteDeBrilho
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---


# Brilho/contraste

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-brightnesscontrast-18-n-d.png)

**Entrada:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Como o nome sugere, o filtro Brilho/Contraste permite ajustar o brilho e o contraste do material. É importante observar que você pode usar o filtro Brilho/Contraste para definir canais específicos. Por exemplo, é possível aumentar o contraste do canal de aspereza ou o brilho do canal emissivo.

Nas imagens abaixo, o **filtro Brilho/Contraste** foi usado para aumentar o brilho e o contraste de um material ladrilhado.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0051-brightness-contrast-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/brightness-contrast-example.jpg.img.jpg)

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Seleção de Canal**:\
  Selecione o canal que o filtro afeta. Observação: não é possível usar o filtro Brilho/Contraste para modificar o canal Normal, pois ele se comporta de maneira diferente da maioria dos canais.
* **Brilho**: -1 a 1\
  Modificar o brilho do canal selecionado
* **Contraste**: -1 a 1\
  Modificar o contraste do canal selecionado

**Máscara**

* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara
  * **Máscara personalizada - Inverter**: alternar\
    Inverter a máscara
