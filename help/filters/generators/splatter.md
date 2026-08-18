---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/generators/splatter.html"
breadcrumb-title: ''
description: Use o gerador de respingos no Substance 3D Sampler para criar efeitos de respingos de tinta e padrões aleatórios para texturas de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Splatter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Respingo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '736'
ht-degree: 0%

---


# Respingo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-splatter-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Divida instâncias de outros materiais no seu material.

>[!NOTE]
>
> Para materiais do atlas, use o filtro Atlas scatter.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Entrada de material**:\
  Selecione o número de materiais a serem usados como entradas. Nota: uma camada Splatter com 3 slots de entrada, mas apenas um slot preenchido com uma entrada, aparecerá de forma diferente para uma camada Splatter com 1 slot de entrada e esse slot preenchido com a mesma entrada. Por esse motivo, é recomendável usar somente as entradas necessárias.
* **Tamanho da grade**: 1-64\
  O tamanho da grade determina o número de instâncias criadas pelo filtro Respingo.
* **Profundidade DE Height DO AO**: 0-1\
  Ajuste a intensidade do AO para ocorrências criadas pelo filtro.

**Forma**

* **Escala**: 0-5\
  Ajustar o tamanho base de todas as instâncias
* **Escala aleatória**: 0-1\
  Ajustar a aleatoriedade do valor de escala para cada instância
* **Escala sem sobreposição**: 0-1\
  Modifique o tamanho das instâncias para evitar sobreposição
* **Posição Aleatória**: 0-2\
  Controlar a aleatoriedade da dispersão de ocorrências
* **Rotação aleatória**: 0-1\
  Controla a aleatoriedade da rotação das ocorrências
* **Rotação da Inclinação de Plano de Fundo**: 0-1\
  Modifique quanto de um impacto os normais do material subjacente têm na rotação das ocorrências.

**Cor base**

* **Correspondência de Albedo**: 0-1\
  Corresponder a cor das ocorrências à cor do material subjacente
* **Ajuste HSL**: 0-1\
  Ajuste de Matiz, Saturação e Luminosidade das ocorrências
* **HSL aleatório**: 0-1\
  Controle a aleatoriedade de matiz, saturação e luminosidade de cada ocorrência

**Normal**

* **Normal de** **Fundo**: 0-1\
  Ajuste quanto o normal do material em cada instância afeta o normal da instância.
* **Ângulo Normal Aleatório**: 0-1\
  Inclinar os normais de cada ocorrência em um ângulo aleatório.

**Aspereza**

* **Ajuste de aspereza**: -1 a 1\
  Adicionar ou subtrair do valor de aspereza uniformemente em todas as instâncias
* **Aspereza aleatória**: -1 a 1\
  Adicionar ou subtrair aleatoriamente do valor de aspereza de cada instância
* **Aspereza de plano de fundo**: 0-1\
  Ajuste quanto o valor de aspereza do material subjacente afeta o valor de aspereza de cada instância

**Height**

* **Deslocamento de Height**: -1 para 1\
  Deslocar o height de instâncias. Isso pode afetar a forma como as instâncias se misturam com o material subjacente.
* **Deslocamento de Height Aleatório**: 0-1\
  Adicione um valor aleatório ao deslocamento de height de cada instância
* **Escala do Height**: 0-2\
  Ajuste o height de todas as instâncias.
* **Escala de Height Aleatória**: 0-1\
  Adicione um valor aleatório ao height de cada instância
* **Inclinar da Inclinação de erros**: 0-1\
  Adicione uma inclinação a cada instância para corresponder à inclinação do material subjacente
* **Smoothness de Inclinação de plano de fundo**: 0-2\
  Ajuste a inclinação do plano de fundo para as finalidades do parâmetro **Inclinar da Inclinação de erros**
* **Em conformidade com o plano de fundo**: 0-1\
  Controle quanto o mapa de heights em segundo plano afeta o mapa de heights de instâncias. Isso permite encolher e quebrar instâncias ao redor dos detalhes do plano de fundo
* **Plano de fundo suave**: 0-1\
  Ajustar quantos detalhes estão visíveis devido à **Conformidade com o Plano de Fundo**

**Metálico**

* **Ajuste Metálico**: -1 a 1\
  Controle os valores metálicos das ocorrências
* **Aleatório Metálico**: -1 a 1\
  Adicione ou subtraia valores aleatórios do elemento metálico de cada ocorrência
* **Metálico do plano de fundo**: 0-1\
  Ajustar quanto impacto os valores metálicos de fundo têm em cada instância

**Máscara**

* **Usar Máscara Personalizada**: alternar\
  Ative essa opção para usar uma máscara personalizada e acessar os controles de máscara personalizada:
  * **Máscara personalizada**: imagem/pincel\
    Importar uma imagem para usar como máscara personalizada ou pintar diretamente na **exibição 2D**
  * **Desfoque de máscara personalizado**: 0-1\
    Desfocar as bordas da máscara personalizada
  * **Inversão de máscara personalizada**: alternar
  * **Opacidade da máscara personalizada**: 0-1\
    Ajustar a força da máscara personalizada

Guia de Uso

O filtro Respingo é uma maneira útil de dispersão ativos em seu material, como folhas, pedras ou lixo.

Para usar o filtro Respingo:

1. Adicionar o filtro Respingo à pilha de camadas
1. Na camada Splatter (Respingo), os slots de entrada aparecerão
1. Opcionalmente, altere o número de slots de entrada disponíveis com **Parâmetros básicos > Entrada de material**
1. Arraste materiais para os slots de entrada do Splatter

Você pode ajustar os parâmetros de dispersão no **painel Propriedades** selecionando a camada Splatter.

Você pode ajustar os parâmetros dos materiais de entrada no **painel Propriedades** selecionando o material no slot de entrada.
