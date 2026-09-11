---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/generators/decal.html"
breadcrumb-title: ''
description: Use o gerador de decalques no Substance 3D Sampler para criar padrões de decalques e texturas de sobreposição para superfícies de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Decal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Adesivo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 1%

---


# Adesivo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-decal-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Decalque permite adicionar ocorrências de outro material em um local específico. Isso é útil para adicionar itens como adesivos ou detalhes específicos que podem não ser fáceis de gerar durante o procedimento.

As imagens abaixo mostram o **filtro de decalque** sendo usado para adicionar danos ao concreto.

![](../../assets/3d-2d-filters-cropped-0045-decal-in.jpg)

Antes que o decalque seja adicionado, a camada base de concreto é limpa e não danificada.

![](../../assets/3d-2d-filters-cropped-0044-decal-out.jpg)

Com o **filtro de decalque** aplicado, rachaduras e danos realistas são adicionados ao material.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros Básicos**

* **Modo lado a lado**:\
  Determina se o bloco deve ultrapassar as alças em **Visualização 2D**.\
  H significa Horizontal, enquanto V significa Vertical.
* **Correspondência de Cores de Material Inferior**: 0-1\
  Ajuste as cores do material de decalque para corresponder ao valor de cor das camadas abaixo dele.
* **Modo de mesclagem normal**:\
  Ajustar como os normais são mesclados entre o material de decalque e as camadas subjacentes
* **Combinar de Opacidade Normal**: 0-1\
  Alterar a opacidade dos normais do material de decalque
* **Posição do Height de decalque**: 0-1\
  Ajustar o height do decalque em relação ao height de camadas subjacentes
* **Escala de Height de decalques**: 0-1\
  Alterar o contraste do mapa de altura do material de decalque

**Parâmetros Avançados**

* **Transformação de decalque**:\
  Ajuste os valores do transformo de matrizes para o decalque. Em geral, é mais fácil usar apenas as alças no **Visualização 2D** para ajustar o transformo do decalque.
* **Decalque** **Deslocamento**: -1 para 1\
  Ajuste o deslocamento do decalque.

## Guia de Uso

Para usar o filtro Decalque:

1. Adicione o filtro Decalque à sua pilha de camadas
1. Na camada Decalque, um slot de entrada aparecerá
1. Arraste o material de decalque para o slot de entrada da camada Decalque

Você pode ajustar os parâmetros de filtro no **painel Propriedades** selecionando a camada Decalque.

Você pode ajustar os parâmetros do material de entrada de decalque no **painel Propriedades** selecionando o material no slot de entrada.
