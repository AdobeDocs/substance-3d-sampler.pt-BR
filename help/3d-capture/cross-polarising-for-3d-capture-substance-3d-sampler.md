---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/cross-polarising-for-3d-capturesubstance-3d-sampler.html"
breadcrumb-title: ''
description: Saiba como usar técnicas de polarização cruzada no Substance 3D Sampler para reduzir reflexos e melhorar a Captura 3D.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Polarização cruzada para captura 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---


# Polarização cruzada para captura 3D

>[!WARNING]
>
> O suporte para captura 3D foi removido a partir da versão 5.1 do Sampler.

## Polarização cruzada

Neste guia do usuário, abordaremos como lidar com objetos reflexivos e os problemas que causam e como usar a polarização da luz para resolver isso.

Você prefere aprender sobre esse tópico em um tutorial em vídeo? Encontre [aqui](https://youtu.be/VWsbP56MDk0?si=Hdp7vblJB6L1RPxK "Tutorial de polarização cruzada").

![](../assets/polarized-lens-3d-capture.png)

Quando a luz atinge uma superfície, ela geralmente reflete de forma difusa, rebatendo uniformemente, dando à superfície sua aparência de cor. Mas dependendo da aspereza da superfície, alguma luz pode ser refletida diretamente em direção ao seu olho ou câmera. Este <b>reflexo de specular</b> muda dependendo do seu ângulo de visualização.

A fotogrametria funciona alinhando padrões visuais e elementos entre fotografias. Ela presume que a aparência de um objeto não será alterada em cada fotografia consecutiva. Portanto, o reflexo do specular é um efeito indesejado aqui. Um objeto de gabinete leve pode ter apenas uma camada reflexiva, mas objetos que são metálicos podem ser muito mais complicados e exigem mais esforço para serem resolvidos. Vamos resolver o caso leve neste guia do usuário. Só precisamos capturar uma cor de base perfeita, intacta pelos destaques do specular. É fácil adicionar a refletividade novamente em 3D depois de capturada.

Para resolver isso, podemos filtrar nossos reflexos de specular usando um método chamado <b>polarização cruzada</b>. Quando a luz é polarizada, todas as ondas são orientadas na mesma direção. Se você polarizá-lo novamente, em direção perpendicular, ele fica completamente bloqueado, tornando-o invisível.

A polarização afeta principalmente a luz do specular, pois esses são raios de luz focalizados, viajando em uma direção específica, em oposição à luz difusa dispersa que queremos manter.

Você polariza a luz com um filtro polarizador, uma folha transparente especial que filtra as ondas. Elas vêm de várias formas, usaremos filtros de vidro rosqueados para suas lentes, bem como folhas de filme polarizador estilo “faça você mesmo”

A ideia básica é <b>adicionar um filtro à sua luz</b> e <b>à sua lente</b>, e ajustá-los para que sejam <b>perpendiculares entre si</b>. Isso significa que você precisará ajustar a orientação do filtro girando-o. Uma vez instalados, os reflexos do specular daquela luz se tornam invisíveis. É muito especial ver que torcer seus filtros pode eliminar completamente o brilho de uma luz polarizada de repente.

![](../assets/polarizing-before-after-3d-capture.png)

Um filtro polarizador para a lente deve ser comprado, pois você quer uma ótica ideal, ainda permitindo fotos nítidas claras. Lentes diferentes têm fios de tamanhos diferentes para parafusar os filtros, então certifique-se de obter o correto para a lente de sua escolha, ou alguns tamanhos para várias lentes se você estiver experimentando.

Polarizar suas luzes é mais barato e simples:<b> folhas de filme polarizantes</b> são relativamente baratas. Você pode usar uma folha inteira ou recortar pedaços. É uma boa ideia cortar pedaços circulares que cobrem toda a luz, pois facilita girá-los. Algumas luzes são melhores para isso, eles podem ter um pequeno suporte de filtro, ou ímãs para segurar folhas no lugar. Se não, a fita adesiva sempre funciona!

<b>adicione o polarizador após qualquer difusor</b>, pois a difusão da luz cancela qualquer polarização.

O anel mais barato pisca o parafuso no slot de filtro e pode não permitir mais que você fixe um filtro de lente. Eles também não têm nenhuma maneira de anexar filtros polarizantes à própria luz do flash, então você terá que criar os seus próprios. Somente os modelos topo de linha suportam isso adequadamente.

<b>Polarizadores giratórios e correspondentes em sua configuração precisam ser feitos constantemente</b>. Seu filtro de lente precisa ser totalmente perpendicular a todas as luzes. A única maneira de fazer isso é observar a tela da câmera e ajustar as coisas. Gosto de começar colando uma única folha no meu flash e, em seguida, ajustar o filtro da lente para bloquear os reflexos do flash. Você só pode fazer isso tirando uma foto ou disparando o flash a seco. Está um pouco envolvido, você pode marcar a orientação correta no filtro de lente com um marcador e tentar não tocar mais na lente e no filtro de flash.

Ajustar a polarização nas luzes de vídeo é diferente, mas mais fácil. Você terá que ajustar constantemente as luzes conforme as move ou ao ajustar o height da câmera. Basta <b>girar a planilha até que fique à direita na tela da câmera</b>.

<b>Cada fonte de luz que aparece em reflexos precisa ser polarizada</b>, portanto, pode ser necessário fechar janelas ou desligar telas.

Quando configurado corretamente, você deve ser capaz de capturar um objeto como se ele fosse completamente fosco, sem reflexos e até mesmo iluminação. Assim como ver sua malha apenas com a textura basecolor aplicada, ele permite capturar objetos reflexivos difíceis.

Agora saiba mais sobre [como processar sua Captura 3D usando o Substance 3D Sampler](processing-advanced-3d-captures.md)!
