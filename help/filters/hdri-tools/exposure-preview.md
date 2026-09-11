---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/exposure-preview.html"
breadcrumb-title: ''
description: Use a ferramenta Visualização de exposição no Substance 3D Sampler para visualizar ajustes de exposição em imagens HDRI antes de aplicar alterações.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Exposure Preview
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Visualização da exposição
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---


# Visualização da exposição

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-exposurepreview-18-n-d.png)

**Entradas:** Ferramentas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O **filtro** Visualização da Exposição **&#x200B;**&#x200B;permite visualizar rapidamente um espectro de valores de exposição.

Abaixo, você pode ver o que o **filtro Visualização de Exposição** faz.

![](../../assets/3d-2d-filters-cropped-0029-exposure-preview-in.jpg)

Na imagem acima, uma iluminação do ambiente foi criada e os dados da imagem HDR estão visíveis no **Visualização 2D**.

![](../../assets/filters-cropped-0028-exposure-preview-out.jpg)

Com o **Filtro** Visualização de Exposição **adicionado à pilha de camadas, um novo canal - Diagnóstico de Ambiente - é disponibilizado e mostra a iluminação do ambiente em várias exposições.**

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Exposição Mínima (VE)**: -8 a 8\
  Defina a exposição da imagem menos exposta.
* **Exposição Máxima (EV)**: -8 a 8\
  Defina a exposição da imagem mais exposta.

## Guia de Uso

O **filtro de Visualização de Exposição** funciona de maneira um pouco diferente de outros filtros do Sampler. É uma ferramenta destinada a ajudar a encontrar a exposição correta para sua iluminação do ambiente, mas na verdade não afeta o canal Ambiente. Em vez disso, quando você adiciona o **filtro de Visualização de Exposição** à pilha de camadas, um canal adicional fica disponível para exibição no **canal de Diagnóstico de Ambiente**.

Se você visualizar o canal de Diagnóstico do ambiente, poderá ver algumas ocorrências da imagem do ambiente 2D com valores de exposição variados. Ajuste os parâmetros do **Filtro de Visualização de Exposição** para alterar o intervalo de exposições visíveis no canal de Diagnóstico de Ambiente.
