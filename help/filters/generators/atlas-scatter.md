---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/atlas-scatter.html"
breadcrumb-title: ''
description: Use o gerador de Atlas scatter no Substance 3D Sampler para dispersão elementos de atlas de textura em superfícies de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Atlas Scatter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas scatter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '745'
ht-degree: 0%

---


# Atlas scatter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_AtlasScatter_18_N_D.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Atlas scatter dispersão instâncias dos elementos em um material atlas no material subjacente. O atlas scatter é útil para espalhar coisas como folhas, rochas ou lixo através de um material de uma forma natural.

As imagens abaixo mostram o **filtro de Atlas scatter** em ação.

![](../../assets/3d-2d-filters-cropped-0037-atlas-scatter-in.jpg)

Antes de usar o **filtro de Atlas scatter**, temos um material básico de lama - não muito emocionante.

![](../../assets/3d-2d-filters-cropped-0036-atlas-scatter-out.jpg)

Ao adicionar o **filtro de Atlas scatter** com um atlas de seixo, o material se torna mais interessante, pois os seixos são dispersos e se misturam realisticamente com a lama subjacente.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros Básicos**

* **Valor De X**: 1 A 64\
  Número de instâncias no eixo X
* **Valor Y**: 1-64\
  Número de instâncias no eixo Y
* **Modo Combinar**:\
  Método usado para mesclar com camadas subjacentes
* **Escala**: 0-5\
  Escala de instâncias
* **Posição Aleatória**: 0-2\
  Aumentar ou diminuir o deslocamento aleatório de instâncias das posições da grade
* **Escala do Height**: 0-1\
  Ajustar o height de instâncias
* **Em conformidade com o plano de fundo**: 0-1\
  Alterar quanto os valores de height subjacentes afetam instâncias dispersas
* **Cor de fundo**:
  * **Matiz:** 0-1\
    Ajustar o matiz das instâncias
  * **Saturação:** 0-1\
    Ajustar a saturação de instâncias
  * **Valor:** 0-1\
    Ajustar o valor das instâncias

**Máscara**

* **Máscara personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Quando ativados, os seguintes controles são exibidos:
  * **Máscara personalizada:**\
    Selecione um arquivo para usar como máscara ou use o modo pincel para mascarar manualmente.
  * **Alternar máscara de inversão:**\
    Inverter o valor da máscara
* **Máscara aleatória**: 0-1\
  Ocultar uma porcentagem de instâncias aleatoriamente

**Tamanho**

* **Escala aleatória**: 0-1\
  A quantidade de escala aleatória a ser aplicada a cada instância
* **Escala sem sobreposição**: 0-1\
  Ajuste a escala de cada instância para evitar a sobreposição de instâncias

**Height**

* **Deslocamento de Height**: -1 para 1\
  Deslocar o height de instâncias do nível base de 0
* **Deslocamento de Height Aleatório**: 0-1\
  Adicionar um valor aleatório ao deslocamento de height para cada instância
* **Inclinar da Inclinação de erros**: 0-1\
  Ajustar a inclinação dos normais com base na inclinação do plano de fundo
* **Smoothness do plano de fundo**: 0-2\
  Ajustar Smoothness do plano de fundo

**Rotação**

* **Rotação**: 0-1\
  Girar todas as instâncias por um valor definido
* **Rotação aleatória**: 0-1\
  Adicionar um valor aleatório à rotação de cada ocorrência
* **Rotação da Inclinação de erros**:\
  Girar instâncias com base na inclinação do material subjacente

**Ajustes de Material Atlas**

* **Ajuste de cor**:\
  Ajustar valores de HSV para o atlas
* **Cores aleatórias**:\
  Adicione aleatoriedade aos valores de HSV definidos em **Ajuste de cores**
* **Aspereza de plano de fundo**: 0-1\
  Use a aspereza do plano de fundo em vez da aspereza de cada instância.
* **Ajuste de aspereza**: -1 a 1\
  Adicione ou subtraia valores de aspereza de cada instância.
* **Aleatório Normal**: 0-1\
  Girar normais de cada ocorrência por um valor aleatório por ocorrência
* **Recalcular Oclusão de ambiente**: alternar\
  Se estiver ativado, os valores de Oclusão de ambiente serão recalculados com base nos valores de height modificados

**Detecção de forma de atlas**

* **Intervalo de padrões**:\
  Limitar os ativos disponíveis do atlas com base na posição. Deixe os valores X e Y em 0 para usar todos os ativos do atlas.
* **Reduzir a Opacidade do Atlas**: 0-4
* **Precisão de Detecção de Forma**:\
  Selecione o algoritmo a ser detectado nas formas. Diferentes atlas serão adequados para diferentes algoritmos de detecção. Nenhum modo de falha tem um custo computacional mais alto do que qualquer uma das outras opções.
* **Ignorar Forma Menor que**: 0-1\
  Use isso para evitar pegar formas muito pequenas como elementos individuais.

Guia de Uso

O filtro Atlas scatter é uma maneira útil de dispersão ativos em seu material, como folhas, pedras ou lixo. Para usar o filtro de Atlas scatter, você precisará de um material de atlas para que o filtro processe.

>[!NOTE]
>
> Um material de atlas é um material que mantém uma coleção (ou atlas) de ativos separados. Por exemplo, o Sampler inclui por padrão as Folhas de louro seco - este é um material de atlas porque contém uma coleção de folhas em um único material onde cada folha é separada uma da outra. O nó Atlas scatter usa um algoritmo para manipular cada folha do material do atlas como um elemento separado.

Para usar o filtro Atlas scatter:

1. Adicionar o filtro Atlas scatter à sua pilha de camadas
1. Na camada Atlas scatter, um slot de entrada aparecerá
1. Arraste o material do atlas para o slot de entrada do Atlas scatter

Você pode ajustar os parâmetros de dispersão no **painel Propriedades** selecionando a camada de Atlas scatter.

Você pode ajustar os parâmetros do material do atlas no **painel Propriedades** selecionando o material no slot de entrada.
