---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/rust.html"
breadcrumb-title: ''
description: Use o filtro Ferrugem no Substance 3D Sampler para adicionar efeitos realistas de ferrugem e corrosão a materiais e superfícies metálicas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Rust
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ferrugem
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 0%

---


# Ferrugem

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-rust-18-n-d.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o **filtro de Ferrugem** para adicionar uma camada de metal oxidado ao material.

Nas imagens abaixo, você pode ver um material metálico antes e depois de adicionar o **filtro de Ferrugem**.

![](../../assets/3d-filters-cropped-0002-rust-out.jpg){width="200px"}

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Propagação de Ferrugem**: 0-1\
  Controle a distribuição ou a quantidade de ferrugem.
* **Influência de borda**: 0-1\
  Ajuste como a ferrugem interage com as bordas com base no mapa de curvatura.
* **Smoothness de páginas espelhadas**: 0-1\
  Aumente para tornar as áreas enferrujadas mais deslumbrantes ou diminua para torná-las mais detalhadas.
* **Afetar somente o Metal**: alternar\
  Quando habilitado, o **filtro de Ferrugem** afetará apenas áreas com um valor metálico maior que 0.

**Ferrugem**

* **Forma de Ferrugem**:\
  Altere o padrão no qual a ferrugem se baseia.
* **Intensidade de Ferrugem**: 0-1\
  Modifique a intensidade do efeito de ferrugem. Aumentar esse valor faz com que a ferrugem pareça mais antiga e mais forte.

**Descascar**

* **Escala de Cascas**: 0-1\
  Altere a escala da ferrugem descascada.
* **Intensidade Normal Da Casca**: 0-1\
  Ajuste a visibilidade dos normais da casca.
* **Intensidade de Height da casca**: 0-1\
  Ajuste o impacto das cascas no mapa de altura.

**Gotas**

* **Intensidade de gotas**: 0-1\
  Altere a intensidade do efeito de gotejamento.
* **Orientação das gotas**: 0-1\
  Posicione as gotas para que correspondam à gravidade ou ao vento.
* **Comprimento de Gota**: 0-1\
  Ajuste a distância em que as gotas se estendem da origem.

**Máscara**

* **Usar máscara**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para tinta uma máscara personalizada diretamente na Visualização 2D.
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara.
  * **Máscara personalizada - Inverter**: alternar\
    Inverta a máscara.
