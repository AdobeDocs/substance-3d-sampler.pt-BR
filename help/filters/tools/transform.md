---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/tools/transform.html"
breadcrumb-title: ''
description: Use a ferramenta Transformar no Substance 3D Sampler para dimensionar, girar, traduzir e manipular texturas e camadas de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Transform
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Transformação
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '553'
ht-degree: 1%

---


# Transformação

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-transformgeneric-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use a **ferramenta Transformar** para mover, dimensionar ou girar sua imagem ou material.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Modo de controle**:\
  Escolha se deseja exibir parâmetros para controlar a transformação com controles deslizantes além das alças de **exibição 2D**.

  Com **Widget e Parâmetros** selecionados, os seguintes controles adicionais serão exibidos:

  * **Transformo seguro**: alternar\
    Habilite ou desabilite transformações seguras. Quando ativado, o nó de transformação manterá a divisão em blocos gráficos e evitará a perda de detalhes de pixels devido a pequenos deslocamentos e rotações. Isso reduz a liberdade que você tem para controlar a transformação e habilitar o **Transformo seguro** ocultará alguns parâmetros.
  * **Manter proporção**: alternar\
    Quando habilitado, somente um parâmetro de **Escala** ficará visível, o que controla o dimensionamento nos dois eixos simultaneamente. Quando desativados, os controles estarão disponíveis para modificar a escala nos eixos horizontal e vertical separadamente.

    * **Escala**: 0-1\
      Dependendo se a **Taxa de retenção** estiver habilitada ou desabilitada, os controles deslizantes de 1 ou 2 estarão disponíveis para ajustar a escala.
  * **Rotação**; 0-360\
    Gire a entrada dentro das alças.
  * **Inclinar**: -1 para 1\
    Inclinar a entrada dentro das alças nos eixos horizontal e vertical.
* **Deslocamento de Posição**: -1 para 1\
  Deslocar o transformo da posição inicial nos eixos horizontal e vertical.
* **Virar horizontalmente**: alternar\
  Espelhar a entrada horizontalmente
* **Virar verticalmente**: alternar\
  Espelhar a entrada verticalmente

**Parâmetros avançados**

* **Transformação**:\
  Ajuste a transformação das alças com controles deslizantes em vez de no **Visualização 2D**.
  * **Escala em X**: 0-2
  * **Inclinar verticalmente**: -7,44 para 2
  * **Inclinar horizontalmente**: 0-1
  * **Escala em Y**: 0 - 13,15
* **Desativar Transformo por Canal**: alternar\
  Quando ativado, serão exibidos controles adicionais que permitem desativar esse transformo para cada canal.

## Guia de Uso

Clique na **ferramenta Transformar** para adicionar uma nova camada de filtro de Transformo ao topo da pilha de camadas.

Criar ou selecionar uma camada de filtro de Transformo abre automaticamente o **Visualização 2D**. Com a camada Transformar selecionada, uma **Barra de ferramentas** aparece na parte superior de **Visualização 2D**.

## Funcionalidade

![](../../assets/alchemist-2020-2-transform-1.gif){width="300px"}

### Mover

Para mover a camada:

1. Passe o mouse dentro da caixa de transformo
1. Seu cursor mudará para quatro setas
1. Clique e arraste para mover a caixa do transformo.

### Dimensionar

Para dimensionar a camada:

1. Passe o mouse sobre uma das alças na borda ou no canto da caixa do transformo
1. Seu cursor mudará para quatro setas.
1. Clique e arraste para dimensionar a caixa de transformo.

>[!NOTE]
>
> As alças no canto da caixa de transformo permitirão dimensionar em duas dimensões de uma só vez, enquanto as alças na borda da caixa de transformo limitarão o dimensionamento em uma dimensão.

### Girar

Para girar a camada:

1. Passe o mouse fora da caixa de transformo, mas dentro do **Visualização 2D**.
1. Uma pequena seta horizontal aparecerá ao lado do cursor.
1. Clique e arraste para girar a caixa do transformo.

>[!NOTE]
>
> É possível alterar o centro da rotação arrastando o pequeno círculo no centro da caixa do transformo. A caixa de transformo sempre gira em torno desse círculo.

## Barra de ferramentas

![](../../assets/transform-toolbar.png){width="200px"}

A barra de ferramentas contém os seguintes atalhos:

* Tornar quadrado: ajuste o dimensionamento da transformação atual para torná-la quadrada.
* Rotação +90° (para a direita): rotação de 90° no sentido horário.
* Rotação -90° (para a esquerda): rotação de 90° no sentido anti-horário.
* Redefinir centro de rotação: redefina o centro de rotação para o centro da caixa do Transformo.
* Redefinir transformação: redefine a ferramenta Transformar para a posição padrão.
