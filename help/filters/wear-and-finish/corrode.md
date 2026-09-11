---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/wear-and-finish/corrode.html"
breadcrumb-title: ''
description: Use o filtro Corrode no Substance 3D Sampler para adicionar efeitos de corrosão e degradação química aos materiais metálicos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Corrode
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Corroído
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 0%

---


# Corroído

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/corrode-filter-icon.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro de corrosão imita o efeito do ácido corroendo seu material, deixando buracos e danos à superfície.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Áreas afetadas**:\
  Selecione como a curvatura da superfície afeta o efeito do filtro.
* **Nível de Perfuração**: 0-1\
  Ajuste o número de orifícios criados.
* **Posição da Curvatura**: 0-1\
  Modifique o intervalo de curvatura a ser afetado.
* **Suavização da curvatura**: 0-1\
  Suavize o mapa de curvatura.
* **Distância do dano**: 0-1\
  Controle o raio do dano ao redor das áreas corroídas.
* **Intensidade de dano**: 0-1\
  Ajuste a quantidade de danos nas áreas afetadas.
* **Intensidade de Height**: 0-1\
  Controle o impacto dos danos no mapa de altura.
* **Posição de Extrusão**: alternar\
  Alterne a direção do dano no mapa de altura. Quando desativado, o dano se alimenta na superfície; quando ativado, o dano se acumula para fora da superfície.

**Máscara**

* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para tinta uma máscara personalizada diretamente na Visualização 2D.
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara.
  * **Máscara personalizada - Inverter**: alternar\
    Inverta a máscara.

**Parâmetros Avançados**

Alguns dos Parâmetros avançados afetam o material completo em vez de apenas as áreas modificadas por esse filtro.

* **Luminosidade**: 0-1\
  Ajuste a luminosidade ou a luminosidade do material completo.
* **Contraste**: -1 a 1\
  Ajuste o contraste do albedo para o material completo.
* **Alteração de matiz**: 0-1\
  Desloque o valor de matiz das cores no material completo.
* **Saturação**: 0-1\
  Ajuste a Saturação do material completo.
* **Intensidade Normal**: 0-1\
  Ajuste a intensidade do mapa normal onde ele foi afetado pelo **filtro de corrosão**.
* **Intervalo de Heights**: 0-1\
  Aumente o intervalo de valores no mapa de altura para o material completo.
* **Posição do Height**: 0-1\
  Desloque o height do material completo.
* **Intensidade de Oclusão de ambiente**: 0-1\
  Ajuste a intensidade do impacto do AO devido ao **filtro de corrosão**.
