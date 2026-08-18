---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/perforate.html"
breadcrumb-title: ''
description: Use o gerador de Perfuração no Substance 3D Sampler para criar padrões perfurados e matrizes de orifícios em materiais e texturas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Perforate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Perfurar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '453'
ht-degree: 0%

---


# Perfurar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-perforation-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o filtro Perfurar para adicionar furos ao material.

*Antes e depois de aplicar o **Filtro perfurado**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0007-perforate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0006-perforate-out.jpg){width="200px"}

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
* **Seleção de padrão**:\
  Selecione a forma dos furos ou escolha Padrão personalizado para criar o seu próprio.
* **Posição da perfuração**:\
  Selecione se os normais e o height recuam para o material ou se destacam do material
* **Tamanho do Chanfro de Perfuração**: 0-1\
  Alterar o tamanho do chanfro nas bordas dos furos
* **Tamanho do furo**: 0-1\
  Alterar o tamanho dos orifícios
* **Usar máscara**: alternar\
  Habilita a **seção de Máscara**, que pode ser usada para mascarar a perfuração com um pincel ou uma imagem.
* **Usar Mapa de Escala**: alternar\
  Permite o uso de um mapa de escala. Quando ativado, os seguintes parâmetros serão exibidos:
  * **Multiplicador de Mapa de Escala**: 0-1\
    Ajuste quanto de um impacto o mapa de escala tem na escala da perfuração
  * **Inverter Mapa de Escala**: alternar\
    Inverter os valores do mapa de escala
  * **Mapa de escala personalizado**: imagem/pincel\
    Importe uma imagem para usar como um mapa de escala ou use o pincel para pintar um mapa de escala diretamente na **exibição** **exibição**

**Máscara**

Esta seção só será visível se **Parâmetros básicos > Usar Máscara** estiver habilitado

* **Inverter máscara**:
* **Desfoque de Máscara**: 0-1\
  Ajustar o desfoque aplicado à máscara
* **Limite de Máscara**: 0-1\
  Modifique o limite da máscara. Use os valores de **Desfoque de máscara** e **Limite de máscara** juntos para ajustar as bordas da máscara.
* **Máscara personalizada**: imagem/pincel\
  Importar uma imagem para usar como máscara ou pintar sua própria máscara diretamente na **exibição 2D**

**Perfuração**

* **Tamanho da perfuração**: 0-1\
  Altere o tamanho de cada perfuração - isso inclui o orifício e o chanfro.
* **Valor Y de Perfuração**: 1-64\
  Ajustar o número de perfurações no eixo Y
* **Quantidade X de perfuração**: 1 a 64\
  Ajustar o número de perfurações no eixo X
* **Densidade de perfuração**: 0-1\
  Mascarar perfurações aleatoriamente
* **Deslocamento de Perfuração**: 0-1\
  Ajuste o deslocamento de cada segunda linha de perfurações
* **Opacidade da Cor de Perfuração**: 0-1\
  Ajuste a transparência da cor da área chanfrada de perfurações
* **Cor de perfuração**: seleção de cor\
  Selecione a cor da área chanfrada de cada perfuração
* **Aspereza da perfuração**: 0-1\
  Modificar o valor de aspereza das perfurações
* **Metálico de perfuração**: 0-1\
  Modificar o valor metálico das perfurações

**Parâmetros avançados**

* **Luminosidade**: 0-1
* **Contraste**: -1 a 1
* **Alteração de matiz**: 0-1
* **Saturação**: 0-1
* **Intensidade normal**: -1 a 1\
  Ajuste a intensidade de cada perfuração normal
* **Intensidade de Height**: 0-1\
  Ajustar a intensidade de cada mapa de height de perfurações
