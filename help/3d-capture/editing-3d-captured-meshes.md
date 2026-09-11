---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/editing-3d-captured-meshes.html"
breadcrumb-title: ''
description: Saiba como editar malhas capturadas 3D no Substance 3D Sampler para refinar a geometria, corrigir problemas e otimizar a qualidade da malha.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Editar malhas capturadas em 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '806'
ht-degree: 0%

---


# Editar malhas capturadas em 3D

>[!WARNING]
>
> O suporte para captura 3D foi removido a partir da versão 5.1 do Sampler.

## Editar malhas capturadas em 3D

Neste guia do usuário, abordaremos algumas técnicas para editar e publicar objetos capturados em 3D processados no Substance 3D Sampler.

Você prefere assistir a isso como um tutorial em vídeo? Você pode encontrar [aqui.](https://youtu.be/6_EZEAR0Uy8?si=6AaCUHD6nnWZyKUE "Captura 3D avançado - Vídeo do tutorial de pós-processamento em malha")

![](../assets/post-processing-3d-capture.png)

Após concluir o processo e adicionar uma malha ao seu projeto do Sampler, você pode fazer modificações nele. Podem ser alterações na malha ou no material. Os filtros de malha são novos desde o Sampler 4.0. Os filtros Materiais usam todos os filtros conhecidos que estavam no Sampler antes.

Quando você está editando um objeto 3D capturado no Sampler, <b>é possível empilhar a Malha e os Filtros Materiais de maneira mista</b>, eles são aplicados automaticamente à parte correta dos dados. A lista de filtros rápidos não distingue entre os dois tipos.

## Filtros de malha

Vamos analisar os filtros de malha primeiro. Há dois no Sampler: <b>Transformo de malha</b> e <b>processo de postagem de malha</b>.

O <b>transformo de malha</b> é um filtro simples que permite <b>converter</b>, <b>girar</b> e <b>dimensionar</b> sua malha. Geralmente, é possível virar um objeto ou ajustar sua escala. Qualquer varredura vem com um transformo pré-aplicado.

<b>O </b> pós-processo de malha é o mesmo que a etapa de pós-processamento no final da caixa de diálogo de Captura 3D, mas em um filtro dinâmico. Com ele, você pode <b>alterar a malha</b>, <b>reutilizar</b> e <b>reaproveitar</b> suas texturas. O objetivo deste filtro é <b>otimizar as malhas reduzindo o tricount, melhorando os UVs e reduzindo a textura</b>. Um dos melhores resultados de usá-lo, é o layout UV melhorado. Por padrão, as Captura 3D originais têm UVs muito fragmentados, normalmente os novos UVs automáticos são uma melhoria.

Esse não é um filtro rápido, sempre que você alterar um parâmetro, a malha será processada. É melhor ser um pouco paciente com isso.

## Filtros de material

Os filtros Materiais são muito mais diversos, qualquer coisa que você possa usar em materiais comuns pode ser usada no material da captura 3D, mas lembre-se de que os resultados nem sempre podem funcionar, pois muitos filtros são destinados a materiais de revestimento uniformes.

Os filtros mais úteis tendem a ser ajustes como <b>contraste</b> claro, <b>saturação de matiz</b>, bem como alguns dos filtros mais avançados para edição de canais. Como não conseguimos capturar a aspereza do nosso objeto, usaremos alguns filtros para trazê-lo de volta.

Você pode usar um <b>filtro de Matiz/Saturação</b> para fazer com que as cores correspondam ainda mais às reais do seu objeto. Há maneiras melhores de obter precisão de cores, mas elas são muito mais envolvidas do que esse filtro rápido.

Em seguida, talvez você queira trazer de volta os reflexos que existiam em seu objeto. Podemos usar o <b>filtro Substituição de Cor</b> aqui. Substituição de cor permite extrair uma cor da textura e alterar todas as áreas com essa cor.

Por padrão, ela colore tudo na cor selecionada, mas se você ativar a <b>Segmentação avançada</b>, defina-a como <b>Máscara de basecolor</b> e <b>Substituir</b> em <b>Aspereza</b>, poderá tornar toda a aspereza da área da cor selecionada muito mais brilhante. Executar a variação de luminosidade e o intervalo da máscara pode ajudar no ajuste fino da máscara.

Por fim, talvez você queira trazer de volta um pouco de detalhe da cor de base para a aspereza. O <b>filtro de troca de canal</b> me permite misturar e mesclar detalhes entre canais diferentes. Você pode definir a <b>entrada para Basecolo</b>r, a <b>saída para Aspereza</b> e, em seguida, brincar com o modo de Combinar e a opacidade para obter algo interessante e próximo o suficiente da vida real.

Por fim, se quiser mais controle sobre a aspereza final, você pode usar um filtro de Contraste de brilho e defini-lo para afetar o canal de aspereza. Em seguida, ajuste os valores para tornar a aspereza um pouco mais texturizada.

Cada objeto é diferente e, dependendo do seu conjunto de dados, ajustes específicos podem ser necessários. Você pode até mesmo usar a <b>ferramenta Carimbo</b> para apagar partes da textura que deseja remover, como capturar marcadores de ajuda. Lembre-se de que qualquer filtro de material que usa locais específicos na textura dependerá do layout UV, assim como o processamento de malha antes de qualquer filtro de material.

Quando estiver satisfeito com seu objeto e texturas, você poderá <b>exportar </b>seu resultado usando a caixa de diálogo <b>Compartilhar > Exportar como</b>. As configurações gerais permitem escolher o nome e o caminho, as configurações de malha permitem escolher o formato de malha 3D e as configurações de material permitem configurar o material da malha. Você pode desativar a malha ou o material para exportar apenas um deles individualmente. Uma vez exportada, sua malha estará pronta para uso em outros aplicativos 3D.
