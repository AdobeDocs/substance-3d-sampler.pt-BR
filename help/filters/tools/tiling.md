---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/tiling.html"
breadcrumb-title: ''
description: Use a ferramenta Divisão em blocos gráficos no Substance 3D Sampler para criar padrões de divisão em blocos gráficos perfeitos a partir do textura para superfícies de materiais repetíveis.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Tiling
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Revestimento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---


# Revestimento

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o **Filtro de divisão em blocos gráficos** para tornar seu material legível. O **Filtro Torná-lo Bloco** também torna seu material legível, mas cada filtro funciona de maneira diferente. Se você descobrir que o **Filtro de divisão em blocos** não está funcionando, tente o **Filtro Torná-lo Bloco**.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Mostrar montagem**: alternar\
  Escolha se deseja exibir a junção
* **Usar máscara**: alternar\
  Se ativada, você pode criar uma máscara personalizada para controlar o local da costura
  * **Máscara**: imagem/pincel\
    Importe uma imagem para usar como máscara ou use o pincel para tinta uma máscara diretamente no **Visualização 2D**

**Borda**

* **Detectar bordas**: alternar\
  Se marcada, deve-se detectar bordas com base nos canais de material para criar uma transição mais orgânica entre as camadas de material. Se a opção estiver Ativada, os seguintes parâmetros adicionais serão exibidos:
  * **Usar Limite por Canal**: alternar\
    Se esta opção estiver ativada, serão exibidos parâmetros adicionais para ajustar o limite de cada canal individualmente.
    * **Cor de base de Limite**: 0-1
    * **Limite Normal**: 0-1
    * **Height de Limite**: 0-1
  * **Limite**: 0-1\
    Ajuste o valor de limiar a ser usado para localizar a costura.
  * **Desfoque**: 0-1\
    Desfocar a área ao redor da costura
  * **Smoothness**: 0-2\
    Ajuste o smoothness da costura. Isso pode ajudar a evitar artefatos
  * **Resolução da Grade**: 1-11\
    Ajuste a resolução da grade na qual a linha é desenhada. Resolução mais baixa pode melhorar o desempenho, mas diminuir a qualidade da costura
  * **Usar Cor de base**: alternar\
    Alternar se as informações de cor de base são consideradas na geração de costura
  * **Usar normal**: alternar\
    Alterne se as informações normais são consideradas na geração de costura
  * **Usar Height**: alternar\
    Alternar se as informações do height são consideradas na geração de costura
  * **Cortar deslocamento**: 0-0.5\
    Ajustar o deslocamento da costura nos eixos X e Y

**Parâmetros Avançados**

* **Transformo**: 0-2\
  Ajuste os valores do transformo de matriz. Aumente os valores de X e W para ajustar a quantidade de sobreposição entre o material subjacente e o material sobreposto.
* **Deslocamento**: 0-1\
  deslocar o material nos eixos X e Y
* **Filtragem**:\
  Selecione o método de filtragem a ser usado em pixels redimensionados. A filtragem bilinear desfoca os pixels, enquanto a filtragem mais próxima mantém a aresta rígida entre os pixels.
* **Tamanho de entrada**: 0-8192\
  Ajuste o tamanho da entrada em pixels nos eixos X e Y.

## Guia de Uso

O **filtro de divisão em blocos gráficos** funciona em duas etapas:

1. Ele dimensiona e desloca o material para gerar uma sobreposição.
1. Em seguida, varia a borda sobreposta para ocultar a costura.

Portanto, para usar o **Filtro de divisão em blocos gráficos**, ajustar essas duas partes do processo pode fornecer os melhores resultados.

1. Adicionar o **filtro de divisão em blocos gráficos** ao topo da pilha de camadas
1. Use as alças para transformar o material de modo que haja sobreposição suficiente para ocultar a costura.
   1. Dimensionar o material pode ser útil para criar uma sobreposição, mas também pode resultar em perda de detalhes.
1. Ajuste os parâmetros na seção **Borda** para ajustar a costura.

Para alguns materiais, o uso do **filtro de divisão em blocos gráficos** sozinho ainda resultará em artefatos ou problemas ao longo da linha de junção. Nesse caso, é recomendável usar outros filtros, como **Carimbo de Clonar**, para corrigir problemas de emenda e divisão em blocos gráficos.

É uma boa prática trabalhar na divisão em blocos gráficos do material no início do processo de criação do material. Assim que um elemento sem divisão em blocos gráficos for adicionado ao material, é uma boa ideia garantir que ele seja ladrilhado antes de trabalhar mais. Os filtros do Sampler foram projetados para não quebrar os materiais de revestimento. Isso significa que, depois que o material subjacente for ladrilhado, você poderá continuar trabalhando com filtros e os materiais incluídos no Sampler e seu material ainda será ladrilhado.
