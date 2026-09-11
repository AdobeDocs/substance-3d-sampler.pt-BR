---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/adobe-standard-material.html"
breadcrumb-title: ''
description: Saiba como usar o Adobe Standard Material no Substance 3D Sampler para criar materiais compatíveis com o padrão de material Adobe.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Adobe Standard Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Material Padrão da Adobe
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 1%

---


# Material Padrão da Adobe

>[!NOTE]
>
> O Substance 3D Sampler agora usa como padrão o modelo de material [OpenPBR](openpbr.md) em vez do Adobe Standard Material.


## Propriedades padrão do material

## Propriedades da superfície de base

**Cor de base**

A cor da superfície.

**Aspereza**

Quão suave ou fosca é a superfície.

![](../assets/surface-roughness.jpg)

**Metálico**

O grau de brilho metálico que a superfície tem.

![](../assets/surface-metallic.jpg)

**Opacidade**

A visibilidade da superfície.

![](../assets/surface-opacity.jpg)

**Oclusão de ambiente**

Sombras de cavidades e vincos que impedem a luz de atingir a superfície.

**Specular level**

A força dos reflexos de luz na superfície.

![](../assets/surface-specularlevel.jpg)

**Specular edge color**

A cor dos reflexos de luz. Afeta os ângulos de brilho de materiais metálicos.

![](../assets/surface-specularedgecolor.jpg)

**Normal**

Simula detalhes da superfície como saliências e rachaduras.

**Escala normal**

A força do efeito normal.

**Combinar normal e height**

Aplica a textura normal sobre a textura do height.

**Height**

Cria detalhes da superfície usando o deslocamento de relevo ou de geometria.

**Escala de Height**

A escala de height em unidades de cena. Aplica-se ao relevo e ao deslocamento.

**nível de Height**

O valor da textura de height que representa deslocamento zero.

**Nível de anisotropia**

A quantidade na qual os reflexos se estendem em uma direção ao longo da superfície.

![](../assets/surface-anisotropy.jpg)

**Ângulo de Anisotropia**

A rotação no sentido anti-horário do efeito anisotrópico.

**Intensidade de emissão**

A intensidade da luz emitida pela superfície.

![](../assets/surface-emission.jpg)

**Cor de emissão**

A cor da luz emitida.

![](../assets/surface-emissioncolor.jpg)

**Opacidade do brilho**

Simula o efeito de fibras ou fuzz microscópico na superfície.

![](../assets/surface-sheen.jpg)

**Cor do brilho**

A cor do efeito de brilho.

![](../assets/surface-sheencolor.jpg)

**Aspereza de brilho**

Suavidade do efeito de brilho.

![](../assets/surface-sheenroughness.jpg)

## Propriedades internas

**Transparência**

A quantidade de luz capaz de transmitir através da superfície.

![](../assets/interior-translucency.jpg)

**Cor de absorção**

A luz da cor convergirá para à medida que for absorvida.

**Distância da Absorção**

Distância aproximada em unidades de cena em que a luz viajará antes de atingir a cor de absorção. Se definido como zero, o thickness não afetará a cor de absorção.

![](../assets/interior-absorptiondistance.jpg)

**Índice de refração**

A quantidade de luz se dobra à medida que passa pelo objeto.

![](../assets/interior-indexofrefraction.jpg)

**Dispersão**

A intensidade com que o espectro de cores se espalha quando refratado.

**Dispersão da subsuperfície**

As dispersões são iluminadas abaixo da superfície, em vez de passarem direto por ela.

**Dispersão de cores**

A cor abaixo da superfície em que a luz dispersa se tornará.

![](../assets/interior-scattercolor.jpg)

**Distância de dispersão**

A luz de distância aproximada deve se deslocar antes de atingir a dispersão total.

![](../assets/interior-scatterdistance.jpg)

**Escala de distância dispersa**

Um multiplicador da distância da dispersão. Pode ser diferente para cada canal de cor.

![](../assets/interior-scatterdistancescale.jpg)

**Turno vermelho**

Define a luz vermelha para viajar mais longe do que outras cores claras. Útil para pele.

![](../assets/interior-scatterredshift.jpg)

**Dispersão de Rayleigh**

Define a luz laranja para viajar mais abaixo da superfície e a luz azul para viajar menos.

![](../assets/interior-scatterraleigh.jpg)

**thickness de volume**

O thickness da superfície em relação à caixa delimitadora do objeto. Usado para efeitos internos quando o thickness real não é conhecido.

**Escala do thickness de volume**

Multiplicador do thickness de volume.

## Propriedades do revestimento

**Opacidade do revestimento**

Simula uma camada na parte superior do material. Usado para criar revestimentos, vernizes e vernizes transparentes.

![](../assets/coat-coatopacity.jpg)

**Cor do revestimento**

A cor da pelagem.

![](../assets/coat-coatcolor.jpg)

**Aspereza do revestimento**

Quão lisa ou fosca é a superfície da pelagem.

![](../assets/coat-coatroughness.jpg)

**Índice de refração do revestimento**

A quantidade de luz se dobra à medida que passa pela pelagem.

![](../assets/cooat-coatior.jpg)

**Nível especular do revestimento**

A força dos reflexos de luz na pelagem em ângulos de visão.

![](../assets/coat-coatspecular.jpg)

**Normal do revestimento**

Simule detalhes da superfície como saliências e rachaduras na superfície da pelagem.

![](../assets/coat-coatnormal.jpg)

**Escala de Normal do revestimento**

A intensidade do efeito normal do revestimento.
