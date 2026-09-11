---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/interface/2d-and-3d-viewport.html"
breadcrumb-title: ''
description: Saiba como usar as portas de visualização 2D e 3D no Substance 3D Sampler para visualizar materiais e navegar no seu espaço de trabalho com eficiência.
helpx_creative_field: ""
helpx_description: Sampler > Interface > 2D and 3D Viewport
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Janela de visualização 2D e 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '745'
ht-degree: 2%

---


# Janela de visualização 2D e 3D

![](../assets/main-3d-viewport-5.png)

O **Viewport** exibe o ativo atual. Na parte superior da **V**&#x200B;**viewport**, você pode ver o nome do ativo e as opções para alterar a aparência da **viewport**. Use estas opções para:

* Altere a largura e o height do ativo em pixels.
* Exibir <b>exibição </b>, <b>exibição 3D</b> ou exibir <b>exibições 2D </b> e <b>3D </b> juntas.
* Alterne a <b>exibição dividida</b> para exibição horizontal.
* Troque <b>exibições 3D e 2D</b>.
* Alterna entre o visor padrão e de tela cheia.

![](../assets/screenshot-2023-01-25-at-16-23-09.png)

## Visualização 3D

O <b>Viewport 3D</b> tem duas barras de ferramentas que permitem fazer alterações em como seu ativo aparece no <b>Viewport</b>. Por padrão, essas barras de ferramentas aparecem no canto superior direito e no centro inferior da <b>Janela de visualização 3D</b>.

![] ()

>[!NOTE]
>
> As barras de ferramentas do <b>Visor 3D</b> podem ser reposicionadas:
> 
> * Você pode mover as barras de ferramentas arrastando a alça na parte superior ou no lado esquerdo da barra.
> * Clique duas vezes na alça na parte superior ou no lado esquerdo da barra de ferramentas para alternar entre os layouts horizontal e vertical.
> * Clique nas divisas duplas na parte inferior ou no lado direito da barra de ferramentas para minimizá-la.

A barra de ferramentas no canto superior direito da <b>Janela de visualização 3D </b> tem controles focados na aparência da janela de visualização:

* <b>Exibição</b>: altere as configurações da câmera, como campo de exibição ou modo de projeção. Além disso, altere as cores da grade e do plano de fundo.
* <b>Malha</b>: selecione outra malha para mostrar seus ativos de material ou ver nuances de ativos de Iluminação do ambiente.
* <b>Material</b>: altere a posição e a divisão em blocos gráficos da textura na malha.
* <b>Deslocamento</b>: ajuste a qualidade e a intensidade do deslocamento.
* <b>Luz</b>: selecione e ajuste uma iluminação do ambiente, incluindo configurações como ativar sombras e o plano do solo.
* <b>Alternar traçado de caminho</b>: o traçado de caminho é uma técnica de renderização que fornece resultados fotorrealistas, melhorando a aparência dos seus ativos. No entanto, o traçado de caminho pode ser computacionalmente caro, aqui você pode ativar ou desativar o traçado de caminho, dependendo das suas necessidades.

>[!NOTE]
>
> Ative as sombras para melhorar os visuais do visor. Mantenha as sombras desativadas para melhorar o desempenho do Samplers.

![] ()

A barra de ferramentas no centro inferior do <b>Visor 3D</b> tem as seguintes informações e controles:

* <b>Tempo de Quadro/FPS</b>: esses valores mostram o desempenho do material.
* <b>Objeto de Quadro</b>: centralize a câmera na malha.
* <b>Alterar eixo para cima</b>: altere o eixo que é considerado para cima. Isso pode ajudar a corrigir problemas com malhas importadas.
* <b>Posicionamento</b>: altere como a malha é posicionada em relação ao plano do solo.
* <b>Copiar instantâneo</b>: copie rapidamente uma imagem do <b>Visor 3D</b> atual para a área de transferência.
* <b>Salvar instantâneo</b>: salve um instantâneo do <b>Visor 3D</b> em um arquivo de imagem.
* <b>Controles de Visualização 3D</b>: exiba uma referência rápida para controles de câmera no Visor 3D.

![] ()

## Mover a câmera

O visor usa uma câmera para renderizar a visualização 3D. Mova a câmera para alterar a visualização e ver suas criações de ângulos diferentes.

| Atalho | Movimento | Descrição |
| --- | --- | --- |
| Clique e arraste | Girar | Gire a câmera. Não é possível rolar a câmera. |
| Clique com o botão direito e arraste | Zoom | Mova a câmera para frente e para trás. |
| Clique com o botão do meio e arraste | Panorâmica | Mova a câmera para a esquerda, direita, cima e baixo. |

O <b>Visualização 2D</b> é bidimensional, portanto não há opção de órbita. Clicar com o botão direito + Alt + arrastar aumentará e diminuirá o zoom, enquanto que clicar com o botão do meio + Alt + arrastar aumentará.

Na <b>exibição 3D </b>e no <b>Visualização 2D</b>, use o <b>F</b> para focalizar no ativo. Isso é útil se você perder de vista o ativo 3D ou o espaço 2D.

## Visualização 2D

![] ()

Por padrão, somente a <b>exibição 3D</b> está visível, mas o <b>Visualização 2D</b> pode conter muitas informações úteis e controles para alguns filtros.

Para abrir o <b>Visualização 2D</b>, use o <b>botão Exibir seleção </b>no canto superior direito do visor. Você também pode usar o atalho <b>2</b> para alternar rapidamente para o <b>Visualização 2D</b>.

Com o <b>Visualização 2D </b>aberto, algumas novas opções aparecem:

* No canto superior direito do **Visualização 2D**, use o menu suspenso para alterar a origem dos canais disponíveis para exibição.

  * As Entradas de camada mostram os canais que estão sendo inseridos na camada selecionada
  * As saídas de camada mostram os canais sendo exportados pela camada selecionada
  * As saídas de material mostram os canais que estão sendo exportados pela camada superior e não são afetadas pela seleção de camada.
* Na parte inferior do **Visualização 2D**, você pode:

  * Veja a resolução do canal selecionado.
  * Selecione um canal para exibi-lo na visualização 2D.
  * Consulte canais de cores e profundidade de bits para o canal de material selecionado.

  ![](../assets/2dbottom.jpg)
