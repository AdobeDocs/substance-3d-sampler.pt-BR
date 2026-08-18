---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/hdri-tools/hdr-merge.html"
breadcrumb-title: ''
description: Use a ferramenta Mesclar HDR no Substance 3D Sampler para mesclar várias imagens de exposição em uma única imagem de intervalo dinâmico.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > HDR Merge
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mesclar HDR
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# Mesclar HDR

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_HDRMerge_18_N_D.png)

**Entradas:** Ferramentas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O **filtro** Mesclar HDR **&#x200B;**&#x200B;permite mesclar uma coleção de imagens SDR (Intervalo Dinâmico Padrão) para criar uma imagem HDR.

As imagens abaixo mostram os resultados da **Mesclagem HDR**.

![](../../assets/3d-2d-filters-cropped-0027-hdr-merge-in.jpg)

Antes da **Mesclagem HDR** ser concluída, a esfera na **exibição 3D** reflete a luz de ambiente padrão. A **exibição 2D** exibe os dados da imagem importada para a primeira imagem de digitalização por padrão, que nesse caso é a imagem exposta mais baixa.

![](../../assets/3d-2d-filters-cropped-0026-hdr-merge-out.jpg)

Depois que o **filtro** do **Mesclar HDR** é adicionado, a esfera reflete uma nova luz de ambiente - a imagem HDR gerada a partir das imagens de entrada.

</td>
</tr>
</table>

## ParâmetrosTP

**Parâmetros básicos**

* **Delta de Exposição de Entrada (EV)**: 0-2\
  Defina a diferença de exposição entre as exposições de entrada mais alta e mais baixa. Um delta de alta exposição aumentará o contraste resultante da operação de mesclagem.
* **Exposição Automática de Saída**: alternar\
  Ative ou desative o ajuste de exposição automático.
* **Deslocamento da Exposição de Saída (EV)**: -5 a 5\
  Compensar a exposição.

## Guia de Uso

Assista a este vídeo para descobrir como usar o **filtro de Mesclagem HDR**, bem como outros filtros que podem ajudar na conversão de imagens SDR em uma luz de ambiente HDR.

As etapas básicas para usar o **filtro** Mesclagem HDR **são as seguintes:**

1. Importe o conjunto de imagens a serem mescladas para a pilha de camadas.
1. Adicione o **filtro de Mesclagem HDR** à pilha de camadas.
1. Modifique os parâmetros para garantir que os valores de exposição estejam corretos.
