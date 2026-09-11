---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/export-parametric-assets.html"
breadcrumb-title: ''
description: Saiba como exportar ativos paramétricos do Substance 3D Sampler para permitir a modificação de parâmetros em outros aplicativos sem retornar ao Sampler.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Export parametric assets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Exportar ativos paramétricos
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 1%

---


# Exportar ativos paramétricos

Os parâmetros expostos podem ser modificados em outros aplicativos sem precisar voltar para o Sampler. Isso reduz o tempo de iteração para que você possa se concentrar em encontrar a melhor aparência sem precisar alternar entre os aplicativos.

## Expor e não expor parâmetros

Para expor parâmetros, abra o **painel Propriedades**. Passe o mouse ou clique com o botão direito sobre o parâmetro desejado e, em seguida, clique no ícone de fixar ou em “expor este parâmetro”.

![](../assets/ezgif-com-gif-maker-2.gif)

Há duas maneiras de cancelar a exposição de um parâmetro:

* No **Painel de parâmetros expostos**, clique com o botão direito do mouse no parâmetro e escolha “não expor”.

  ![](../assets/ezgif-com-gif-maker-3.gif)
* No **painel Propriedades**, clique no ícone de fixar cruzado ou clique com o botão direito do mouse no parâmetro e escolha “não expor este parâmetro”.

  ![](../assets/ezgif-com-gif-maker-4.gif)

Os parâmetros dos seguintes filtros não podem ser expostos:

* Imagem para material (com tecnologia IA)
* Preenchimento sensível ao conteúdo
* Normal para Height
* Aumentar

Se você adicionar um dos filtros acima das camadas que contêm parâmetros expostos, eles não serão expostos na exportação.\
Para evitar isso, remova o filtro ou coloque-o onde ele não afetará as camadas com parâmetros expostos.

Se você expôs parâmetros de uma mesclagem, eles serão perdidos se mover a camada de na parte inferior da pilha.

![](../assets/ezgif-com-gif-maker-10.gif)

## Editar seus parâmetros

Edite o rótulo do seu parâmetro clicando com o botão direito nele no **Painel de parâmetros expostos**, digite o novo nome e clique em “Aplicar”.

![](../assets/ezgif-com-gif-maker-5.gif)

![](../assets/ezgif-com-gif-maker-6.gif)

Você pode usar o parâmetro no **Painel de parâmetros expostos** como no **painel Propriedades**.

## Exportar seu material

Para exportar o material com os parâmetros expostos

1. Abra o <b>painel Exportar.</b>
1. Clique em Exportar.
1. Selecione SBSAR ou SBS.
1. Clique em “exportar”.

Agora você pode usar seu material com seus parâmetros expostos em qualquer software que suporte o formato de arquivo SBSAR.
