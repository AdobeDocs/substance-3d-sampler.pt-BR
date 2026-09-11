---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/wear-and-finish/water.html"
breadcrumb-title: ''
description: Use o filtro Água no Substance 3D Sampler para adicionar efeitos de água, umidade e umidade aos materiais e texturas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Water
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Água
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Água

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-water-18-n-d.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o **Filtro de erosão** para se desgastar em pontos altos do seu material.

![](../../assets/water-compare.png)

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Nível da Água**: 0-1\
  Ajuste o height da água.
* **Escuridão Hídrica**: 0-1\
  Deixe a água mais clara ou mais escura.
* **Umidade das Bordas**: 0-1\
  Ajuste o quanto acima da linha da água o material parece molhado.
* **Habilitar Dirt na Água**: alternar\
  Adicione dirt à parte superior da água modificando ligeiramente o mapa de aspereza. A **seção de Dirt** só aparecerá se esse parâmetro estiver habilitado.
* **Máscara personalizada**: alternar\
  Quando ativado, o seguinte controle adicional é exibido:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara personalizada ou use o pincel para tinta uma máscara diretamente no **Visualização 2D**.

**Dirt**

Esta seção só será exibida se **Parâmetros básicos > Habilitar Dirt na Água** estiver habilitado

* **Quantidade de Dirt**: 0-1\
  Ajuste a quantidade de dirt flutuando na superfície das águas.
* **Intensidade de Distorção**: 0-1\
  Controle a quantidade de distorção do dirt de superfície com base na interseção entre a água e o restante do material.
* **Intensidade da borda do Dirt**: 0-1\
  Gerencie a intensidade do dirt de superfície próximo às bordas da máscara de dirt.
* **Distância da Borda do Dirt**: 0-1\
  Controla a distância da borda do dirt a partir da interseção entre as áreas úmidas e secas do material.
* **Precisão da Borda**: 0-1\
  Ajuste a precisão da borda do dirt.
* **Distorção de borda**: 0-1\
  Distorça a borda para quebrar a uniformidade da superfície do dirt.

**Parâmetros Avançados**

* **Distância de Umidade das Bordas**: 0-1\
  Controla a extensão da umidade das bordas em áreas secas.
* **Quantidade de Desfoque de Profundidade**: 0-1\
  Ajuste quanto a cor de base fica desfocada nas áreas subaquáticas.
* **Opacidade do Desfoque de Profundidade**: 0-1\
  Ajuste a transparência da água.
* **Cor do lodo**: seleção de cor\
  Mude a cor do dirt que fica em cima da superfície da água.
* **Opacidade do lodo**: 0-1\
  Ajuste a transparência do lodo.
