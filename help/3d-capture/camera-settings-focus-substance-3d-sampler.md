---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/camera-settingsfocussubstance-3d-sampler.html"
breadcrumb-title: ''
description: Saiba como definir as configurações de foco da câmera no Substance 3D Sampler para obter a qualidade e a nitidez de imagem ideais.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Foco das configurações da câmera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '759'
ht-degree: 0%

---


# Foco das configurações da câmera

>[!WARNING]
>
> O suporte para captura 3D foi removido a partir da versão 5.1 do Sampler.

## Configurações da câmera - Foco

A <b>Abertura</b> é a configuração de câmera mais complexa, portanto, explicaremos isso na profundidade deste guia do usuário.

Você prefere assistir a este guia como um tutorial em vídeo? Você pode encontrar [aqui](https://youtu.be/kFZ71ZWuap0?si=MDuvyO9w96rFpsQ9 "abertura e foco para o tutorial em vídeo do Captura 3D").

![](../assets/focus-manually-3d-capture.png)

## Foco na lente

Por padrão, o sistema de foco automático da câmera controla isso, definindo o foco automaticamente. Isso faz sentido ao fotografar pessoas, grandes ambientes ou qualquer coisa dinâmica, mas para nosso objeto controlado e estático, isso pode até causar problemas. A focagem automática pode cometer erros e arruinar uma foto, mesmo entre duas fotos.

Cada DSLR pode alternar do foco automático para um <b>foco manual</b> completo. Isso significa que você está completamente no controle do foco, girando o anel de foco na lente. Dessa forma, você tem certeza de que o foco não alternará entre as tomadas. Se você ler o manual da câmera, provavelmente haverá configurações para ajudá-lo, como “pico de foco”, em que um efeito colorido é desenhado sobre a tela da câmera. Isso ajuda a ver qual parte da imagem está em foco. Pode haver até mesmo um ampliador de zoom, no qual a tela mostra uma pequena parte aumentada da vista atual, ajudando a obter um foco de pixels perfeitos. Especialmente este ampliador de zoom é crucial para ajudar a pregar o seu foco.

O uso do foco manual ajudará você a ver e entender melhor o que está acontecendo com sua <b> abertura</b> e seu <b>foco</b>. A desvantagem é que você precisa <b>reajustar seu foco sempre que sua câmera ou objeto se mover</b>. É fácil esquecer e arruinar uma foto, então é melhor deixar que ela seja um hábito de verificação.

## Escolher o valor de abertura

A <b>abertura</b> é complicada porque afeta o <b>foco</b> e a <b>nitidez</b>. Não queremos que partes do nosso objeto não estejam em foco, o que causa problemas no processo de fotogrametria. Isso significa que uma grande abertura, geralmente entre f1.8 e f3.5 para lentes padrão, será um problema. Por outro lado, indo para a menor abertura possível, f/32 também não é grande, as coisas também ficam menos nítidas neste final, e a quantidade de luz que vem é pequena, levando a problemas de sublinhado.

Enquanto a profundidade de campo fica mais ampla com aberturas menores, ela também é dimensionada com a distância de foco. Isso significa que você terá mais profundidade de campo de perto e muito menos até a nitidez total, mais longe. Isso pode ser problemático para objetos pequenos, se você quiser que eles tirem a maior parte da foto.

Então, qual é o valor de abertura correto? Como regra geral, descubra qual é a faixa de abertura mais nítida para a lente e comece com esse valor. Isto é provavelmente<b> F8 ou f11, até f16</b>.  Verifique se <b>tudo está em foco</b>. Caso contrário, reduza passo a passo até f20 ou mais. Se o objeto ainda não estiver totalmente em foco, tente se afastar um pouco mais dele. Mesmo uma distância de 10 a 15 cm pode fazer a diferença para objetos pequenos.

Lembre-se também de que sua escolha de lente pode fazer a diferença. As lentes de kit padrão que vêm com uma câmera geralmente não são as mais nítidas ou de alta qualidade, e pode valer a pena investir em uma lente de alta qualidade. Especialmente para close-ups, lentes macro podem ser úteis, pois permitem que seu foco fique muito mais perto da lente.

## Colchete de foco

Há um truque especial que você pode fazer para obter a nitidez perfeita quando todo o resto falhar. <b>Colchete de foco</b> significa que você tira <b>várias fotos</b>, a <b>diferentes distâncias de foco</b>, e as combina no Photoshop. Requer <b>muito trabalho extra</b>, especialmente com séries de loop completas, portanto, deve ser usado apenas como último recurso.

Se você tiver 2 ou mais fotografias com foco diferente, carregue-as em camadas diferentes.

![](../assets/focus-differences-3d-capture.png)

Selecione todas as camadas e vá para <b>Editar</b> > <b>Alinhar camadas automaticamente</b>. Toque em OK com as configurações padrão. O Photoshop tentará fazer um alinhamento perfeito de pixels de todas as camadas selecionadas

Em seguida, vá para <b>Editar</b> > <b>Mesclar camadas automaticamente</b>. Novamente, escolha ok com todas as configurações padrão. O Photoshop mesclará as partes mais nítidas das camadas.

Se tudo correu bem, agora você tem uma fotografia perfeita. Vale a pena transformar pelo menos algumas dessas etapas em uma ação gravada, para poupar seu tempo.

Agora que você aprendeu tudo o que há para saber sobre Abertura e Foco para o processo de Captura 3D, saiba mais sobre [como criar uma configuração de iluminação ideal](3d-capture-lighting-substance-3d-sampler.md).
