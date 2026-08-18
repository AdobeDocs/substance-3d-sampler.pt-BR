---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/adjustments/colorize.html"
breadcrumb-title: ''
description: Use o filtro Colorir no Substance 3D Sampler para aplicar tons de cores e efeitos de colorização monocromática a texturas e materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Colorize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Colorir
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 1%

---


# Colorir

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_ColorFill_18_N_D.png)

**Entrada:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Colorir permite adicionar cor a uma seleção de canais sem perder os detalhes.

>[!NOTE]
>
> Embora o filtro Colorir permita que você modifique o canal normal, não é uma boa ideia fazê-lo, a menos que você tenha um bom entendimento de como o canal normal funciona e qual será o impacto no material. Esta é uma função avançada que geralmente só deve ser necessária em circunstâncias específicas.

Nessas imagens, o **filtro Colorir** foi usado para ajustar a cor de base para produzir um material de madeira muito mais rico.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0045-colorize-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0044-colorize-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

Os parâmetros disponíveis nesta seção são alterados com base na **Seleção de Canal**.

* **Seleção de Canal**:\
  Selecione o canal que o filtro afetará. Convém visualizar o canal selecionado na visualização 2D para visualizar diretamente os resultados do filtro.
  * ***Opções de Cores Básicas/Emissivas***
    * ***Nome do Canal*** **- Cor**: seleção de cores\
      Selecione a cor usada para colorir o canal
    * ***Nome do Canal*** **- Manter Luminosidade**: alternar\
      Se estiver ativo, os valores de Luminosidade das cores originais serão mantidos
    * ***Nome do Canal*** **- Intensidade**: 0-1\
      Ajuste a intensidade do efeito Colorir.
  * ***Opções de canal normal***
    * **Normal - Ângulo de Inclinação**: 0-90\
      Modificar o gradiente do normal
    * **Normal - Direção**: 0-360\
      Ajustar a direção das faces normais
    * **Normal - Manter Luminosidade**: alternar\
      Se ativada, a luminosidade dos normais originais será mantida
    * **Normal - Intensidade**: 0-1\
      Ajuste a intensidade do efeito Colorir.
* **Máscara personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara
  * **Máscara personalizada - Inverter**: alternar\
    Inverter a máscara
