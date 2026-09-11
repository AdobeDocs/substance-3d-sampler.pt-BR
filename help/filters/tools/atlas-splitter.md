---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/atlas-splitter.html"
breadcrumb-title: ''
description: Use a ferramenta Atlas splitter no Substance 3D Sampler para dividir atlas de textura em mapas de textura individuais para edição de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Splitter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas splitter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---


# Atlas splitter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlassplitter-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O **Atlas splitter** é uma ferramenta útil para organizar e exibir os elementos de um atlas.

As imagens abaixo mostram o **Atlas splitter** em ação.

![](../../assets/3d-2d-filters-cropped-0039-atlas-splittter-in.jpg)

A imagem acima mostra um material de atlas adicionado à pilha de camadas. use o **Atlas splitter** para selecionar elementos específicos do atlas.

![](../../assets/3d-2d-filters-cropped-0038-atlas-splitter-out.jpg)

Com o **Atlas splitter** adicionado à pilha de camadas, é possível focar em uma única folha ou em qualquer outro elemento do material do atlas.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Exibição de grade**: alternar\
  Alternar entre a exibição de grade e a exibição individual de elementos. Se ativado, os seguintes parâmetros adicionais serão exibidos:
  * **Opacidade da grade**: 0-1\
    Modificar a opacidade da grade
  * **Opacidade da Seleção de Grade**: 0-1\
    Modificar a opacidade da borda ao redor do elemento selecionado
  * **Escala automática**: alternar\
    Alterne se os elementos do atlas serão dimensionados para preencher cada quadrado da grade ou não.
* **Corte automático**: alternar\
  Selecione se deseja ajustar o corte da forma selecionada. Se habilitada, uma opção adicional aparecerá:
  * **Modo de corte automático**:\
    Escolha como o elemento selecionado é cortado para preencher o espaço do material.
* **Seleção de forma**: 1-10\
  Alterar o elemento do atlas selecionado. Para atlas com mais de 10 elementos, você pode digitar um número no valor de **Seleção de forma** para alterar o intervalo do controle deslizante.
* **Rotação**: 0-1\
  Girar elementos

**Parâmetros Avançados**

* **Tolerância de forma pequena**: 0-1\
  Ajuste o tamanho mínimo das formas a serem selecionadas pelo **Atlas splitter**. Isso é útil para filtrar artefatos
* **Rotação automática**: alternar\
  Se habilitada, os elementos serão girados automaticamente para terem orientações semelhantes.
* **Reduzir Máscara De Opacidade**: 0-4\
  Ajuste a escala da máscara de opacidade. Observe que aumentar esse valor pode diminuir a qualidade da máscara de opacidade.
* **Precisão de Detecção de Forma**:\
  Selecione o algoritmo de detecção de forma a ser usado.
* **Largura de Dilatação**: 0-32\
  Modificar a dilatação: extrai as cores das bordas do elemento na área mascarada para ajudar a evitar problemas de transparência na borda de elementos do atlas. Exiba o canal de cor base na **exibição 2D** para ver os resultados.
* **Cor de fundo personalizada**: alternar\
  Se ativado, um controle aparece para modificar a cor de fundo do canal normal:
  * **Cor de fundo normal**: seleção de cor\
    Selecione a cor de fundo personalizada do canal normal em partes transparentes do material.
* **Cor do Blog de Height**: 0-1\
  Ajuste a cor de fundo do canal de height. Geralmente, é uma boa ideia fazer com que o fundo do height corresponda ao height médio das bordas dos elementos do atlas para evitar artefatos nas bordas dos elementos.
