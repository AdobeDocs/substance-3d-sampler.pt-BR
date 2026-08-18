---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/warp.html"
breadcrumb-title: ''
description: Use a ferramenta Distorcer no Substance 3D Sampler para aplicar efeitos de distorção direcional e de distorção em texturas e camadas de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Warp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Distorcer
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---


# Distorcer

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-warp-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O **filtro de Distorção** permite distorcer o material com base em vários ruídos gerados.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Seleção de ruído**:\
  Selecione o ruído em que a distorção será baseada. Ruídos diferentes podem criar efeitos diferentes.
* **Escala de ruído**: 0-10\
  Ajuste a escala do ruído de origem. O ruído sempre será telha.
* **Tipo**:\
  Selecione o método usado para deformar o material. Se a **Distorção Direcional** ou a **Distorção Multidirecional** estiverem selecionadas, um parâmetro adicional será exibido:
  * **Ângulo de Distorção**: 0-1\
    Ajustar a direção ao longo da qual a distorção acontece
* **Intensidade**: 0-1\
  Ajuste a força da distorção.
* **Ruído personalizado**: alternar\
  Habilite para usar um ruído personalizado em vez da seleção em **Seleção de ruído**. Os parâmetros disponíveis serão alterados com base na habilitação ou desabilitação do **Ruído Personalizado**. Se ativado, os seguintes parâmetros serão exibidos:
  * **Desfoque de Ruído Personalizado**: 0-1\
    Desfocar o ruído personalizado
  * **Ruído personalizado**: imagem/pincel\
    Importe um mapa de ruído personalizado para usar como origem de distorção.
* **Distorcer por canal**: alternar\
  Quando ativadas, as seções adicionais aparecerão para controlar a distorção de cada canal independentemente. Para cada canal estão disponíveis os seguintes parâmetros:
  * ***Nome do canal***: alternar\
    Se marcada, este canal é afetado pelo **Filtro de distorção**.
  * **Modo de Mesclagem**:\
    Selecionar como os resultados da distorção deste canal são mesclados com a camada subjacente
  * **Opacidade**: 0-1\
    Altere a opacidade dos resultados do filtro para este canal.
