---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/pavement.html"
breadcrumb-title: ''
description: Use o gerador de pavimento no Substance 3D Sampler para criar texturas realistas de pavimento e superfície da estrada para materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Pavement
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pavimento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '384'
ht-degree: 1%

---


# Pavimento

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pavement-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Converta seu material em um padrão de pavimento. O filtro Pavimentação inclui várias opções para alterar o estilo de padrão de forma rápida e fácil.

*Um exemplo do **filtro de pavimento**.*

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Escala do Material de base**: 0-1\
  Controle a escala do material usado em cada tijolo
* **Espaçamento entre tijolos**: 0-1\
  Modificar a quantidade de espaço entre os tijolos
* **Arredondamento dos cantos**: 0-1\
  Torne os cantos dos tijolos mais ou menos arredondados.
* **Arredondamento de arestas**: 0-1\
  Suavize as bordas dos tijolos para torná-los mais desgastados do uso
* **Intensidade de inclinação**: 0-1\
  Alterar a intensidade da inclinação aleatória aplicada a cada tijolo
* **Intensidade de elevação aleatória**: 0-1\
  Modifique a variação de height dos tijolos em relação uns aos outros.

**Padrão**

Cada padrão tem um conjunto diferente de parâmetros disponíveis que aparecerão quando o padrão for selecionado em **Tipo de Padrão**. Experimente os parâmetros para ver o efeito.

* **Tipo de Padrão**:\
  Selecione o padrão para colocar os tijolos.

**Comum**

* **Conjunto** **Height**: 0-1\
  Modificar o height do material entre tijolos
* **Largura da junção**: 0-1\
  Ajustar até que ponto o material entre tijolos se sobrepõe às bordas dos tijolos
* **Variação de largura da junção**: 0-1\
  Ajustar a aleatoriedade da **Largura da junção**
* **Luminosidade da junção**: 0-1\
  Modifique a aparência do material entre tijolos. Isso pode ser útil para fins de máscara.

**Parâmetros avançados**

* **Intensidade da superfície**: 0-1\
  Controle a força dos normais em deformações na superfície, como rachaduras ou amassadas.
* **Tamanho da superfície (cm)**: 0-1000\
  Ajuste a tamanho físico representada pelo material
* **Escala do Height da superfície (cm)**: 0-1000\
  Alterar o espaço físico representado pelo mapa de altura
* **Smoothness de superfície**: 0-1\
  Controle a quantidade de variação e detalhes na superfície
* **Ponta de superfície**: 0-1\
  Adicione danos ou variações à superfície modificando o height e as normais aleatoriamente
* **Limite Da Máscara De Curva De Superfície**: 0-1\
  Modifique o limite da máscara usada para controlar o **Poke de Superfície**
* **Habilitar Scalemap**: alternar\
  Usar um mapa de escala para ajustar o tamanho dos tijolos com base em sua posição
* **Intensidade do Mapa de Escala**: 0-1\
  Ajuste quanto o mapa de escala afeta a escala de tijolos.
