---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/paint.html"
breadcrumb-title: ''
description: Use o filtro Tinta no Substance 3D Sampler para adicionar camadas de tinta, revestimentos e efeitos de superfície pintados aos materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Paint
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pintura
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '500'
ht-degree: 0%

---


# Pintura

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-paint-18-n-d.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O **filtro de Tinta** permite cobrir o material em uma camada de tinta de thickness variável.

*Um material metálico com tinta gasta adicionado em cima dele.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0017-paint-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0016-paint-out.jpg){width="200px"}

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
* **Cor**: seleção de cor\
  Defina a cor da tinta.
* **Aspereza**: 0-1\
  Defina a aspereza das áreas cobertas pela tinta.
* **Thickness**: 0-1\
  Ajuste a viscosidade e o thickness da tinta. Isso afeta o quanto do height subjacente e das informações normais são visíveis através da tinta.
* **Descascar**: 0-1\
  Adicione patches onde a tinta tenha se afastado do material subjacente.
* **Granulado**: 0-1\
  Altere a granulação da superfície da tinta.
* **Tamanho da granulação**: 1-5\
  Ajuste a escala da textura usada para criar os grãos.

**Máscara**

* **Máscara de cavidade**: alternar\
  Crie uma máscara com base nas cavidades encontradas no mapa de altura. Se ativado, os seguintes parâmetros serão exibidos:
  * **Tamanho da Cavidade**: 0-1\
    Ajuste o intervalo de heights usado para criar a máscara de cavidade.
  * **Intensidade da cavidade**: 0-1\
    Ajuste a opacidade da máscara com base na profundidade da cavidade.
  * **Máscara de inversão de cavidade**: alternar\
    Inverta a máscara de cavidade para mudar se ela afeta os pontos altos ou baixos.
* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para tinta uma máscara personalizada diretamente na Visualização 2D.
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara.
  * **Máscara personalizada - Inverter**: alternar\
    Inverta a máscara.

**Parâmetros Avançados**

* **Cor de base**: alternar\
  Define se o canal de cor de base é afetado pelo filtro.
* **Metálico**: alternar\
  Define se o canal metálico é afetado pelo filtro.
  * **Valor Metálico**: 0-1\
    Ajuste o valor metálico das áreas pintadas.
* **Aspereza**: alternar\
  Defina se o canal de aspereza é afetado pelo filtro.
* **Normal**: alternar\
  Define se o canal normal é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Normal - Intensidade**: -1 a 1\
    Ajuste a intensidade dos normais.
* **Height**: alternar\
  Define se o canal de height é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Height - Intensidade**: 0-1\
    Ajuste o contraste do mapa de altura.
* **Opacidade**: alternar\
  Define se o canal de opacidade é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Opacidade - Valor**: 0-1\
    Altere a opacidade do material.
* **Emissivo**: alternar\
  Define se o canal de emissivo é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Emissivo - Cor**: seleção de cor\
    Defina a cor do canal do emissivo.
* **Oclusão de ambiente**: alternar\
  Define se o canal de oclusão de ambiente é afetado pelo filtro. Se ativado, os seguintes controles adicionais serão exibidos:
  * **Oclusão de ambiente - Intensidade**: 0-1\
    Ajuste a intensidade do AO gerado.
  * **Oclusão de ambiente** **- Raio**: 0-1\
    Ajuste o raio do efeito AO.
