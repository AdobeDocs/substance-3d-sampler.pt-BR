---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/features-and-workflows/flatten-layers.html"
breadcrumb-title: ''
description: Saiba como nivelar camadas no Substance 3D Sampler para melhorar o desempenho e simplificar sua pilha de camadas e, ao mesmo tempo, entender o impacto.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Achatar camadas
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 1%

---


# Achatar camadas

Nivelar camadas é uma maneira útil de melhorar o desempenho e simplificar a pilha de camadas, mas é importante estar ciente do impacto que o nivelamento de camadas pode ter em seu projeto.

## O que o botão Nivelar camadas faz?

Achatar camadas mescla todas as camadas abaixo da camada atualmente selecionada em uma única camada. A camada achatada resultante tem a mesma aparência das camadas originais, mas você não pode mais fazer ajustes nas camadas individuais originais.

### Por que nivelar camadas?

Sempre que uma camada é alterada na Pilha de camadas, o Sampler precisa recalcular a saída dessa camada e de todas as camadas acima dela. Cada camada adicional a ser calculada significa tempo de processamento adicional e uso de memória. Nivelar várias camadas reduz o tempo e a memória necessários para processar essas camadas. Por exemplo, em vez de recalcular 10 camadas, o Sampler só precisa processar uma única camada.

Além disso, o nivelamento de camadas resulta em uma pilha de camadas mais simples, que é mais fácil de navegar e entender.

### Quando não devo nivelar camadas?

As camadas achatadas não podem ser acessadas individualmente na pilha de camadas, portanto, você não poderá fazer alterações nos parâmetros no resultado achatado. Como resultado, você só deverá nivelar as camadas se não precisar mais fazer alterações no resultado dessas camadas.

## Parâmetros de camada achatada

Enquanto os parâmetros das camadas originais são perdidos, as camadas niveladas têm seu próprio conjunto de parâmetros que podem ser ajustados para controlar como cada canal resultante é usado.

Para cada canal, você pode:

* <b>Uso de saída</b>: altere para qual canal a saída é usada. Ao nivelar camadas, um TIFF é criado e nomeado para cada canal e atribuído automaticamente a esse canal.
* <b>Opacidade do canal alfa</b>: alterna se a opacidade é baseada no resultado do canal Alfa.
* <b>Remover</b>: remove o canal desta camada. Isso pode ser útil para canais que não contêm informações úteis. Por exemplo, é uma boa ideia remover um canal de opacidade totalmente branco, pois isso liberará memória sem afetar os resultados visuais.
