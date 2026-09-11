---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/generators/floor-tiles.html"
breadcrumb-title: ''
description: Use o gerador de Números inteiros no Substance 3D Sampler para criar padrões realistas de ladrilhos e texturas de cerâmica para materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Floor Tiles
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Número inteiro lado a lado
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '787'
ht-degree: 0%

---


# Número inteiro lado a lado

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-floortiles-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Número inteiro Tiles quebra o material subjacente e o converte em um arranjo de Número inteiro Tiles.

As imagens abaixo mostram um material de concreto convertido em ladrilhos com padrão quadriculado.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0031-floor-tiles-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0030-floor-tiles-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

Parâmetros

<b>Parâmetros básicos</b>

* <b>Distribuição aleatória</b>: \
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* <b>Número de materiais</b>: \
  Altere o número de materiais a serem convertidos em ladrilhos para chão. O primeiro material é determinado por camadas sob a camada de filtro Número inteiro Tiles (Ladrilhos). Se selecionado, o segundo pode ser adicionado como uma entrada
* <b>Intensidade de materiais de entrada</b>: 0-1 \
  Quanto os detalhes dos materiais de entrada ficarão visíveis nos blocos
* <b>Inverter materiais</b>: alternar \
  Ao usar dois materiais, troque onde eles aparecem nos ladrilhos.
* <b>Variação de cores</b>: 0-1 \
  Quanto a cor varia entre cada ladrilho do mesmo material
* <b>Raio do chanfro</b>: 0-1 \
  Tamanho da telha versus o tamanho da argamassa
* <b>Profundidade de chanfro</b>: 0-1 \
  Profundidade da argamassa
* <b>Arredondamento do chanfro</b>: 0-1 \
  Determina os ângulos exteriores dos ladrilhos
* <b>Granulação Superficial</b>: 0-1 \
  Determina quanto os detalhes do material original aparecem nos mapas de normal e de altura dos ladrilhos
* <b>Máscara de padrão</b>: entrada.  \
  Cada máscara de padrão de blocos de Número inteiro tem um conjunto diferente de parâmetros disponíveis. Aqui só cobrimos os parâmetros disponíveis para <b>Bloco Quadrado</b>

  * <b>Distribuição aleatória </b>\
    A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
  * <b>X Valor </b>\
    Ajustar o número de colunas de blocos
  * <b>Valor Y</b> \
    Ajustar o número de linhas dos blocos
  * <b>Gradiente </b> \
    Ajusta a proporção do tamanho do ladrilho em comparação ao tamanho da argamassa.
  * <b>Luminância aleatória</b>\
    Como a luminância influencia o mapa de altura, esse parâmetro remove aleatoriamente alguns ladrilhos
  * <b>Rotação de Padrão</b>: 0-1 \
    Gira o ângulo dos ladrilhos, mantendo-os afastados uns dos outros para evitar a superposição
  * <b>Escala de Forma:</b> 0-1 \
    Ajusta a proporção do tamanho do ladrilho em comparação ao tamanho da argamassa.
  * <b>Escala de Forma Aleatória </b>\
    Adiciona aleatoriamente alguma diferença no tamanho dos blocos gráficos
  * <b>Tamanho da forma </b>\
    Ajustar o comprimento e a largura dos blocos
  * <b>Tamanho Aleatório da Forma </b>\
    Adicionar um pouco de aleatoriedade ao comprimento e largura dos blocos
  * <b>Modo de Deslocamento de Posição</b>: lista suspensa
  * <b>Deslocamento de Posição </b>\
    Desloca aleatoriamente as colunas dos ladrilhos para que eles não fiquem alinhados horizontalmente
  * <b>Posição Aleatória</b> \
    Posiciona os ladrilhos aleatoriamente na superfície, com alguma potencial sobreposição entre eles
  * <b>Rotação da forma </b>\
    Girar o ângulo dos ladrilhos na mesma direção, mantendo-os o mais próximo possível da potencial superposição
  * <b>Rotação de Forma Aleatória </b>\
    Girar aleatoriamente o ângulo dos ladrilhos, mantendo-os o mais próximo possível da potencial sobreposição

<b>Lacuna</b>

* <b>Cor do espaço</b>: seleção de cor \
  Alterar a cor entre os blocos gráficos
* <b>Aspereza de espaço</b>: 0-1 \
  Altere o valor de aspereza do material entre os ladrilhos.
* <b>Espaço Metálico</b>: 0-1 \
  Altere o valor metálico do material entre os ladrilhos.
* <b>Height de lacuna</b>: 0-1 \
  Altere o valor de height do material entre os blocos gráficos.
* <b>Irregularidade do Intervalo</b>: 0-1 \
  Ajuste o quão limpo a argamassa será aplicada entre os ladrilhos.

<b>Idade</b>

* <b>Inclinação do Número inteiro</b>: 0-1 \
  Adicionar um pouco de inclinação aos blocos aleatórios
* <b>Height aleatório</b> \
  Adicionar uma diferença de height entre os ladrilhos de maneira aleatória
* <b>Dirt</b>: 0-1 \
  Adicionar dirt aos blocos e espaço
* <b>Danos</b>: 0-1 \
  Remova aleatoriamente alguns fragmentos da borda do bisel de cada bloco
* <b>Imperfeições</b> \
  Adicionar pequenos orifícios e imperfeições aos ladrilhos

<b>Parâmetros Técnicos</b>

* <b>Escala de material</b>: 0-1 \
  Escala do material dentro dos ladrilhos
* <b>Intensidade Normal</b>: 0-1 \
  Ajuste a intensidade do normal do espaço, os ladrilhos e o material dentro

<b>Guia de Uso</b>

O filtro Número inteiro Lado a lado permite converter rapidamente o material em ladrilhos. A maioria dos blocos gráficos de Número inteiro é bastante simples de usar, exceto ao usar vários materiais. Para usar dois materiais:

1. Defina <b>Parâmetros básicos > Número de materiais</b> como 2.
1. Arraste o segundo material para o slot de entrada exibido sob o filtro Número inteiro Tiles (Blocos) na pilha de camadas.
1. Ajuste os parâmetros do material de entrada até ficar satisfeito com o resultado.

Embora seja possível adicionar vários materiais e filtros em um único slot de entrada, geralmente é uma boa ideia evitar fazer isso, pois adiciona complexidade e pode dificultar a leitura do material quando você voltar a ele mais tarde. Em vez disso, crie novos materiais em seu projeto e arraste uma instância do novo material para o slot de entrada. Ao atualizar o material no projeto, ele atualizará automaticamente o material no slot de entrada, oferecendo controle total e simplificando a pilha de camadas.
