---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/generators/surface-relief.html"
breadcrumb-title: ''
description: Use o gerador de Relevos de superfície no Substance 3D Sampler para criar padrões de superfície em alto-relevo e de relevo nos materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Surface Relief
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Relevo de superfície
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# Relevo de superfície

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-surfacerelief-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o filtro Relevo de superfície para adicionar ruído ao material. Isso pode ajudar a quebrar formas grandes ou adicionar interesse visual.

</td>
</tr>
</table>

## Parâmetros

<b>Parâmetros básicos</b>

* <b>Distribuição aleatória</b>:\
  A semente aleatória na qual todos os outros parâmetros aleatórios deste filtro se baseiam.
* <b>Intensidade</b>: 0-1\
  Alterar a amplitude do ruído
* <b>Intensidade de desfoque</b>: 0-1\
  A intensidade do desfoque aplicado ao ruído
* <b>Imperfeição De Superfície </b>: Gerador De Imagem/Pincel/Textura\
  Use uma imagem ou um Gerador de Textura para usar como a imperfeição de superfície.

<b>Parâmetros de Ruído</b>

* <b>Restrinjo</b>: 0-1\
  Restringir o ruído para um determinado intervalo
* <b>Contraste</b>: 0-1\
  Modifique o contraste do ruído
* <b>Inverter</b>: alternar\
  Inverter o mapa de altura do ruído

<b>Transformar</b>

* <b>Divisão em blocos gráficos</b>: 1-16\
  Diferentemente de <b>Parâmetros básicos > escala</b>, o <b>Enquadramento</b> gerencia o número de instâncias do ruído.
* <b>Espelho</b>:\
  Espelhe o ruído em um ou ambos os eixos
* <b>Deslocamento</b>:\
  Reposicionar o ruído nos eixos X e Y
* <b>Rotação</b>:\
  Gire o ruído. O ângulo de rotação se encaixa para garantir que a divisão em blocos gráficos ainda seja possível.

<b>Máscara</b>

* <b>Usar Máscara Personalizada</b>: alternar\
  Ative para ver os controles de Máscara personalizada:
  * <b>Máscara</b>: Gerador de imagem/pincel/Textura\
    Importe uma imagem para usar como máscara ou use o pincel para tinta diretamente no <b>Visualização 2D</b>
  * <b>Máscara Personalizada - Desfoque</b>: 0-1\
    Desfocar a máscara
  * <b>Máscara personalizada - Inverter</b>: alternar

<b>Parâmetros Avançados</b>

* <b>Intensidade de Height</b>: 0-1\
  Controle a mesclagem do mapa de altura de ruído com o mapa de altura dos materiais subjacentes
* <b>Height - Substituir base</b>: alternar\
  Alternar entre substituir ou não o height base
* <b>Intensidade Normal</b>: 0-1\
  Ajuste a intensidade do mapa normal de ruído
* <b>Normal - Substituir Base</b>: alternar\
  Alternar entre substituir ou não o mapa normal base
* <b>Direção-Normal</b>:\
  Modificar quais eixos usar para geração normal
* <b>Normal - Girar Direção</b>
* <b>Oclusão Ambiente - Intensidade</b>
* <b>Oclusão de ambiente - Raio</b>
