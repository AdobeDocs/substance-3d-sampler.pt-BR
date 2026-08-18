---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/image-to-material.html"
breadcrumb-title: ''
description: Use a ferramenta Imagem para material no Substance 3D Sampler para converter imagens individuais em materiais totalmente PBR usando o processamento viabilizado por IA.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Image To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Imagem para material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 1%

---


# Imagem para material

![](../../assets/sat-icon-image-to-material.png)

O modelo **Imagem para material** permite gerar um material PBR de alta qualidade a partir de uma única imagem de entrada.

Este modelo tem dois algoritmos principais:

* **Com IA**
* **B2M**

Veja abaixo uma explicação detalhada de cada algoritmo.

## Exemplo

Veja um exemplo de canais de material gerados a partir de uma única imagem de entrada:

![](../../assets/sat-image-to-material.jpg){width="500px"}

## Algoritmos

Para alterar o algoritmo do modelo **Imagem para material**, clique na lista suspensa abaixo do nome do modelo:

![](../../assets/image-to-material-algo-setting.png)

### Com tecnologia de IA

O algoritmo <b>Powered</b> em IA usa o aprendizado de máquina para reconhecer formas e objetos e gerar com precisão mapas de Normal, Height e Aspereza, bem como para se livrar do albedo de sombras ou realces.

A rede neural foi treinada em uma ampla gama de materiais como tecidos, orgânicos, interiores e superfícies ao ar livre.

>[!NOTE]
>
> O Image to Material (alimentado por IA) levará mais tempo para ser computado em imagens de alta resolução. Recomendamos usar o sistema de [Resolução de camada](../../interface/preferences/layer-resolution.md) para otimizar o fluxo de trabalho enquanto trabalhamos.

### B2M

O algoritmo **B2M** usa o método Bitmap to Material baseado em Substance para gerar vários canais, como cor base, normal, metálico, aspereza e oclusão ambiente usando técnicas de procedimento.

Esse algoritmo pode produzir resultados menos precisos, mas funcionará em uma variedade maior de imagens de entrada.

## Adobe Capture

Essa funcionalidade também está disponível no aplicativo Adobe Capture para dispositivos móveis (Android e iOS). Você pode tirar uma foto em qualquer lugar e obter uma visualização do resultado diretamente no seu telefone.

Envie facilmente os resultados para a Substance 3D Sampler para outras edições.

![](../../assets/capture-qr-code.gif)

>[!NOTE]
>
> Essa funcionalidade só está disponível com uma assinatura do Adobe Substance 3D Collection.
