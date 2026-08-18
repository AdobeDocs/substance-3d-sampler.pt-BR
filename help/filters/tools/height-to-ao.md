---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/tools/height-to-ao.html"
breadcrumb-title: ''
description: Use a ferramenta Height para AO no Substance 3D Sampler para converter mapas de height em mapas de oclusão ambiente para criação de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to AO
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Height para AO
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 1%

---


# Height para AO

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hbao-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Gere um mapa de Oclusão ambiente a partir dos dados do height e normais.

Veja os resultados do **filtro de Height para AO** nas imagens abaixo.

![](../../assets/3d-2d-filters-cropped-0025-height-to-ao-in.jpg)

Na imagem acima, a **exibição 2D** exibe o mapa de heights. O material não inclui informações de Oclusão ambiente nesta imagem.

![](../../assets/3d-2d-filters-cropped-0024-height-to-ao-out.jpg)

Nesta imagem, o Mapa de Oclusão do Ambiente foi criado pelo **filtro Height para AO** e está visível na **exibição 2D**. Em geral, a Oclusão ambiente é um efeito sutil, por isso não é muito fácil vê-la neste material. Tente usar o **filtro Height para AO** em seus materiais para aumentar a intensidade do AO e ter uma ideia de como trabalhar com a Oclusão ambiente.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Modo**:\
  Selecione se os dados serão gerados a partir do canal de height, do canal normal ou de ambos os canais juntos.
* **Oclusão Ambiente - Intensidade**: 0-1\
  Ajustar a intensidade dos dados do AO gerados
* **Oclusão de ambiente - Distribuição**: 0-1\
  Ajustar o raio dos dados do AO gerados
