---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/wear-and-finish/stylization.html"
breadcrumb-title: ''
description: Use o filtro Estilização no Substance 3D Sampler para aplicar efeitos artísticos e aparências estilizadas aos seus materiais e texturas.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Estilização
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '740'
ht-degree: 1%

---


# Estilização

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/stylization-filter-icon-transp.png)

<b>Entrada:</b> Desgaste Concluído

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o <b>filtro de Estilização</b> para modificar a aparência do material para simplificar os detalhes com diferentes efeitos.

As imagens abaixo mostram o material da casca antes e depois da aplicação do filtro de estilização.

![](../../assets/stylization-regular-bark.png)

![](../../assets/stylization-contrasted-stylization-bark.png)

</td>
</tr>
</table>

## Predefinições

<b>Estilização</b>

    A predefinição padrão aplica um efeito de estilização suave desfocando pequenos detalhes e aumentando o contraste

<b>Estilização Contrastada</b>

    Esta predefinição aplica um efeito semelhante a pinceladas ao material

<b>Pintura</b>

    Esta predefinição aplica um efeito semelhante a pinceladas suaves e desfocadas ao material

<b>Pintado à Mão</b>

    Esta predefinição aplica mais contraste do que as anteriores, ela imita pinceladas manuais de guache ou tinta a óleo

## Parâmetros básicos

* <b>Distribuição aleatória </b>\
  A semente aleatória na qual todos os outros parâmetros aleatórios neste filtro se baseiam.

* <b>Intensidade de filtro global</b>: 0-1 \
  Ajuste quanto os efeitos deste filtro serão aplicados em seu material original. Defina como 1 para aplicar o efeito completo.

* <b>Contraste</b>: 0-1 \
  Modifique o nível de contraste que se aplica ao seu material

* <b>Intensidade de estilização de cores</b>: 0-1 \
  Ajuste quanto o efeito de estilização do filtro afetará a cor do material

* <b>Intensidade de estilização da aspereza</b>: 0-1 \
  Ajuste quanto o efeito de estilização do filtro afetará a aspereza do material

* <b>Intensidade de estilização metálica</b>: 0-1 \
  Ajuste quanto o efeito de estilização do filtro afetará a metalidade do material

* <b>Intensidade de estilização do Height</b>: 0-1 \
  Ajuste quanto o efeito de estilização do filtro afetará o height do material

* <b>Intensidade de estilização normal</b>: 0-1 \
  Ajuste quanto o efeito de estilização do filtro afetará o normal do material

## Cor de base

* <b>Intensidade da colorização</b>: 0-1 \
  Cores mais vivas

* <b>Colorir Cor</b>: Cor \
  Permite escolher a cor para a qual os parâmetros de “Intensidade da coloração” tendem.

* <b>Intensidade de variação de cor</b>: 0-1 \
  Ajuste quanto a intensidade da cor é afetada pela cor definida em “Variação de cor”

* <b>Variação de cor</b>: cor \
  Escolha a cor que orientará o controle deslizante “Intensidade de variação de cor”

* <b>Contraste da Variação de Cores</b>: 0-1 \
  Ajuste o contraste na cor definida em “Variação de cor”

* <b>Intensidade da cor da cavidade</b>: 0-1 \
  Ajuste a intensidade da cor que aparece nas áreas afundadas do material, cor que foi definida em “Cor de cavidade”

* <b>Cor da cavidade</b>: cor \
  Define a cor que será aplicada nas áreas submersas do material

* <b>Intervalo de Cavidade</b>: 0-1 \
  Define a largura das áreas afundadas no material.

* <b>Desfoque de Cavidade</b>: 0-1\
  Ajuste o nível de desfoque nas áreas na borda das cavidades do material

* <b>Intensidade da curvatura</b>: 0-1 \
  Modifique a visibilidade do ponto mais alto dos materiais, colorido com a cor definida no parâmetro “Cor da curvatura”

* <b>Intensidade da colorização da curvatura</b>: 0-1 \
  Ajuste a opacidade da cor definida no parâmetro “Cor da curvatura”

* <b>Cor da curvatura</b>: cor \
  Definir a cor que será aplicada nos pontos mais altos do material

* <b>Desfoque de Curvatura</b>: 0-1 \
  Ajuste o nível de desfoque ao redor das áreas coloridas pelo parâmetro “Cor de curvatura”

## Grunge

* <b>Intensidade de Desgaste</b>: 0-1 \
  Adiciona um mapa de desgaste sobre o material. O mapa do desgaste pode ser escolhido abaixo.

* <b>Cor do Desgaste</b>: cor \
  Escolha a cor que será usada para aplicar o mapa de desgaste escolhido

* <b>Aspereza de Desgaste</b>: 0-1 \
  Ajustar o nível ou a aspereza que será aplicado ao mapa de desgaste adicionado

* <b>Desgaste metálico</b>: 0-1 \
  Ajustar o nível de metalidade que será aplicado ao mapa de desgaste adicionado

* <b>Variação de aspereza de Desgaste</b>: 0-1 \
  Escolher o nível de variação na aspereza aplicada ao mapa de desgaste adicionado

* <b>Intensidade de Variação da Aspereza do Desgaste</b>: 0-1 \
  Escolha o nível de variação da intensidade da variação aplicada ao mapa de desgaste adicionado

* <b>Desgaste</b>: imagem \
  Escolha uma imagem ou um Gerador de textura disponível na biblioteca de ativos do Sampler para ser usado como um mapa de desgaste

## Parâmetros técnicos

* <b>Intensidade de nitidez</b>: 0-1 \
  Ajustar a intensidade do efeito de nitidez global

* <b>Raio da nitidez</b>: 0-1 \
  Ajustar o raio do efeito de nitidez global

* <b>Recalcular normal</b>: alternar \
  Permitir que o Sampler recalcule o normal seguindo as alterações que foram aplicadas ao material

* <b>Intensidade Normal</b>: 0-1 \
  Ajustar a intensidade do mapa normal

* <b>Suavização Normal</b>: 0-1\
  Suavize o normal para obter uma aparência mais suave para o material

* <b>Intensidade de Oclusão do ambiente</b>: 0-1\
  Ajustar o nível de contraste no mapa do AO
