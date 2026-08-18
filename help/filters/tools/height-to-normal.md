---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/tools/height-to-normal.html"
breadcrumb-title: ''
description: Use a ferramenta Height para normal no Substance 3D Sampler para converter mapas de height em mapas normais para fluxos de trabalho de criação de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to Normal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Height para normal
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# Height para normal

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-heighttonormal-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Gere dados de canal Normal com base no canal do height.

Nas imagens abaixo, você pode ver o **filtro Height para Normal** em ação.

![](../../assets/h2n-in.jpg)

Na imagem acima, não há dados normais do material. Somente o mapa de heights está disponível e é mostrado no **modo de exibição 2D**.

![](../../assets/h2n-out.jpg)

Com o **filtro Height para Normal**, os dados normais são gerados a partir do mapa de height mostrado na imagem superior. A luz reflete de forma mais realista no material na segunda imagem, graças ao mapa normal gerado.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Usar unidades mundiais**: alternar\
  Altere se os parâmetros são medidos usando unidades reais ou não. Isso modifica quais parâmetros estão disponíveis.
  * **Se a opção Usar unidades mundiais estiver habilitada:**
    * **Tamanho da superfície (cm)**: 0-500\
      Definir o tamanho do espaço UV em unidades mundiais
    * **Profundidade do Height (cm)**: 0-10\
      Defina a distância representada pelo mapa de height. Se o mapa de height representar uma pequena distância, uma grande diferença nos valores do mapa de height pode ter um pequeno impacto no ângulo normal. Se o mapa de heights representar uma grande distância, uma pequena diferença nos valores do mapa de heights pode representar um grande ângulo no mapa normal.
  * **Se Usar unidades mundiais estiver desabilitado:**
    * **Intensidade**: 0-3\
      Ajustar a inclinação dos ângulos normais
* **Combinar abaixo normal**: 0-1\
  Adicione o mapa normal existente aos resultados deste filtro.

**Máscara**

* **Máscara personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara
  * **Máscara personalizada - Inverter**: alternar\
    Inverter a máscara
