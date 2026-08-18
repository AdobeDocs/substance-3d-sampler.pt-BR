---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/gravel.html"
breadcrumb-title: ''
description: Use o gerador de cascalho no Substance 3D Sampler para criar texturas de granulado de cascalho e pedra realistas para materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Gravel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Cascalho
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '457'
ht-degree: 0%

---


# Cascalho

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-gravel-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Cascalho cria camadas de cascalho sobre o material de uma forma natural, preenchendo fendas.

Estas imagens mostram o **Filtro de cascalho** sendo usado para preencher as fendas de um material de lama com cascalho.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0029-gravel-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0028-gravel-out.jpg)

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Quantidade**: 0-1\
  Altere a quantidade de cascalho espalhado pelo material.
* **Cor primária**: seleção de cor\
  Selecionar a cor base das pedras de cascalho
* **Cor secundária**: seleção de cor\
  Selecionar a cor secundária das pedras de cascalho
* **Correspondência de Cores de Material Inferior**: 0-1\
  Ajustar quanto a cor de cascalho é afetada pela cor do material subjacente
* **Habilitar Máscara de Cavidade**: alternar\
  Quando ativado, o cascalho preencherá as cavidades e não será espalhado em partes mais altas do material. Isso pode resultar em uma dispersão de cascalho mais realista.
* **Limite de Volume de Dispersão**: 0-50\
  Ajustar o volume de dispersão com base nos valores de height
* **Mascaramento aleatório**: 0-1\
  Definir a porcentagem de cascalho para mascarar aleatoriamente
* **Tamanho da Pedra**: 1-10\
  Controle o tamanho das pedras
* **Variação de Tamanho de Pedra**: 0-1\
  Controlar a aleatoriedade do tamanho da pedra
* **Arredondamento da Pedra**: 0-1\
  Arredondar pedras ou mais angular
* **Aspereza de pedra**: 0-1\
  Modifique o valor de aspereza das pedras
* **Height de Pedra**: 0-1\
  Modifique o height das pedras. Isso afeta a forma como as pedras se misturam com o material subjacente.
* **Elevação da Pedra**: 0-1Modifique a elevação da base das pedras. A elevação define o piso de onde as pedras se encontram, enquanto o height define o height das pedras fora do piso.
* **Altitude aleatória da pedra**: 0-1\
  Adicione um valor aleatório à elevação de cada pedra.
* **Smoothness de superfície**: 0-1\
  Suavizar os topos das pedras
* **Usar Máscara Personalizada**: alternar\
  Ative ou desative o uso de uma máscara personalizada para pintar locais de pedra. Os parâmetros a seguir só estarão visíveis se **Usar Máscara Personalizada** estiver habilitado.
  * **Desfoque de Máscara**: 0-1\
    Desfocar as bordas da máscara pintada
  * **Máscara personalizada**: imagem/pincel\
    Clique no pincel para pintar uma máscara personalizada na qual as pedras aparecerão. Clique no quadrado para importar uma imagem para usar como máscara.

**Parâmetros avançados**

* **Tamanho da superfície (cm)**: 0-1000\
  Modifique o tamanho da superfície que está sendo representada por seu material. Aumentar o tamanho da superfície significa que o tamanho físico de pedras de cascalho é maior, e elas serão modificadas em conformidade.
* **Profundidade de Height** **(cm)**: 0-100\
  Modifique a profundidade física representada pelo mapa de heights do material. Uma profundidade de height aumentada significa que o tamanho físico de pedras é mais alto do que seria de outra forma, portanto a intensidade normal das pedras é aumentada.
