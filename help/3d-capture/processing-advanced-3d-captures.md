---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/3d-capture/processing-advanced-3d-captures.html"
breadcrumb-title: ''
description: Saiba como processar capturas 3D avançadas no Substance 3D Sampler para otimizar a geometria, as texturas e a qualidade do material.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Processamento de capturas 3D avançadas
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1339'
ht-degree: 0%

---


# Processamento de capturas 3D avançadas

>[!WARNING]
>
> O suporte para captura 3D foi removido a partir da versão 5.1 do Sampler.

## Processamento de capturas 3D avançadas no Substance 3D Sampler

Neste guia do usuário, estamos examinando em profundidade o processamento de seus conjuntos de dados captura 3D no Substance 3D Sampler.

Você prefere assistir a isso como um tutorial em vídeo? Você pode encontrar [aqui](https://youtu.be/vJQ756Up55Y?si=GiAnajXRGkb5gyTH "Captura 3D avançado - Tutorial de processamento de captura").

![](../assets/cloud-points-3d-capture.png)

Ao fazer fotogrametria de Captura 3D, a maior parte do esforço é para tirar boas fotografias, que etapas são abordadas nos artigos anteriores do guia do usuário. Lembre-se também de que projetamos e focamos a experiência de Captura 3D para objetos até o tamanho humano. Você pode ter problemas ao usar um conjunto de dados muito grande (isso significa acima de 6 pixels Giga, que são 500 fotos de 12 Megapixels).

## Iniciando o processo do captura 3D

Para começar a usar o Sampler, você precisará criar um <b>novo Projeto</b>. Você notará uma nova seção de Objetos 3D na janela Projetos. Clique no sinal de mais (+) próximo a ele e escolha “<b>Novo objeto 3D</b>” para começar o processo do captura 3D em uma nova janela dedicada.

![](../assets/new-capture-3d-capture.png)

Selecione todas as suas fotos no explorador e arraste-as para a janela da captura 3D. Depois de carregar por um tempo, suas fotos são apresentadas em uma lista e, como uma galeria, com propriedades para a seleção à direita.

A lista de grupos de fotos à esquerda é baseada na câmera e na lente usadas para as fotos. Se você misturar fotos de vários dispositivos, como celular, câmera dslr ou drone, você obterá <b>grupos separados</b> aqui.

Com o grupo selecionado, você obtém uma visão geral de suas propriedades. Às vezes, a <b>Distância focal</b> e o <b>tamanho do sensor</b> estão ausentes. É possível preenchê-los <b>manualmente</b> se soubermos os números. Essas informações podem ajudar a melhorar um pouco o processamento.

## Gerando máscaras

A opção mais importante está na seção <b>Máscara</b>. Como as fotos foram tiradas em uma mesa giratória, o fundo não mudou muito, mas o objeto mudou. Isso pode fazer com que o processo de alinhamento falhe completamente. Além disso, o fundo não contém nenhuma informação significativa. Para resolver isso, você vai querer mascarar o assunto de cada foto.

A maneira mais fácil é usar a geração automática de lote. Selecione <b>Gerar</b>, depois <b>Novo lote</b>, e aguarde até que o Sampler crie as máscaras. Ele usa a tecnologia “Selecionar objeto” do Adobe Sensei, assim como no Photoshop. Com 72 fotos, esse processo demora um pouco para ser concluído, então o melhor é ser paciente.

![](../assets/generate-mask-3d-capture.png)

Você pode verificar uma máscara individual <b>selecionando uma foto</b> e clicando no <b>ícone de olho</b> na parte inferior direita, próximo ao caminho da máscara. Isso mostra uma visualização em tons de cinza da máscara. Se o mascaramento automático cometer um erro e mantiver partes do plano de fundo, não se preocupe, algumas máscaras incorretas não serão um problema.

A maioria das máscaras deve ter apenas seu assunto. É por isso que é fundamental fotografar suas fotos em um <b>fundo uniforme e simples</b>. É muito mais fácil para o mascaramento automático funcionar bem. Se a maioria das suas máscaras não estiver correta, você poderá corrigir todas elas manualmente ou refotografar suas fotos com um plano de fundo mais adequado.

Você pode tentar novamente um conjunto de dados várias vezes e deseja evitar a geração de máscaras novamente toda vez, pois o Sampler as exclui depois que você fecha o aplicativo. As máscaras são armazenadas em cache em Documents\Adobe\Adobe Substance 3D Sampler\3DCapture\p1. Se você fizer vários ativos em uma sessão, obterá pastas chamadas p2, p3 etc. É uma boa ideia <b>copiar as máscaras em cache para um local seguro com seu conjunto de dados</b>, para que você possa economizar tempo se precisar revisitar esse conjunto de dados.

## Alinhamento

Com as máscaras corretas, você está pronto para prosseguir para o alinhamento. Pressione o <b>botão de envio azul</b> no canto superior direito. Você receberá duas opções, <b>Precisão</b> e <b>Pedidos de fotos</b>.

* A <b>Precisão</b> pode melhorar o alinhamento. É melhor começar em Baixo. Se você obter fotos com falha, tente novamente com Alto.
* <b>Pedido de fotos</b> está relacionado à ordem em que você tirou as fotos. Se você tiver caminhado ao redor de um objeto e fotografado em círculos em espiral, poderá usar a sequência para economizar tempo, mas normalmente o padrão é a opção mais segura, mesmo que leve mais tempo para alinhar.

Clique em <b>Processar</b> e aguarde a conclusão do alinhamento. Isso pode levar alguns minutos, então é melhor ter paciência novamente. Uma vez concluído, você verá uma representação em nuvem de pontos do seu objeto, com cada foto representada como uma câmera flutuando ao redor dele. Um triângulo laranja de aviso no canto superior esquerdo significa que algumas fotos <b>não foram alinhadas</b>. Volte e experimente com Precisão de alta qualidade e Pedido padrão, se ainda não tiver feito. Algumas fotos ainda podem não se alinhar, o que significa que não há sobreposição suficiente ou detalhes insuficientes nelas. Talvez você precise revisitar seu processo de fotografia para resolver isso ou basta ignorá-lo se forem apenas algumas fotos.

Olhando para seus dados de nuvem de ponto, você poderá ver <b>pontos isolados flutuando ao redor de seu objeto</b> que não devem fazer parte dele. Isso geralmente ocorre devido a um mascaramento ruim, neste caso, algumas máscaras ruins fizeram com que ele pegasse em algumas partículas de dust. Você pode cortá-los</b> usando o ícone de olho à direita, ao lado de Região de interesse. <b>Basta <b>mover as alças quadradas</b> que parecem obter um ajuste mais preciso ao redor do objeto. Nenhum ponto fora da caixa, exibido em cinza escuro, será incluído no modelo 3D final. Você também pode usar essa caixa delimitadora para <b>pré-girar e alinhar melhor o modelo.</b>

Às vezes, as nuvens de ponto têm pontos muito mais densos do que outras. Esse não é um problema, menos pontos significa que a superfície terá menos detalhes geométricos pequenos. Vem da falta de detalhes e contraste em algumas partes do objeto, enquanto outras têm mais detalhes.

## Detalhes da geometria

Há apenas uma configuração restante antes de criarmos nossa malha. Em detalhes da geometria, você pode selecionar o nível inicial de detalhes da geometria.

* O <b>Raw</b> é o <b>mes não decimados</b>h. Não é recomendável usá-lo, a menos que tenha certeza de que precisa dele.
* <b>Completo para rascunho</b> são <b>malhas dizimadas</b>. Você escolheria opções mais baixas para obter um resultado de teste mais rápido, opções mais altas para obter mais detalhes às custas de um processamento mais lento.

Pressione <b>Enviar para iniciar o processamento de malha</b>. Esse processo pode demorar um pouco mais do que qualquer uma das etapas anteriores.

## Visualizar e pós-processar

Quando sua malha estiver concluída, a janela final nos permite visualizar e pós-processar nossa malha antes de adicioná-la ao nosso projeto do Sampler. Este modo tem alguns botões na parte inferior para ver sua malha com <b>textura</b>, <b>sólido sombreado</b>, como <b>wireframe</b> e um <b>material de verificador UV</b>. As configurações de pós-processamento no lado permitem gerar uma nova versão da malha. Isso significa uma malha repetindo o mosaico, com novos UVs automáticos e textura feitos bake da malha original. Os controles principais permitem definir uma contagem de rosto de destino e alternar entre Normal, height e fça bake ao. Há muitas configurações avançadas para ajustar, mas os padrões geralmente funcionam bem.

Você também pode fazer essa etapa de processamento de malha depois, uma vez que a malha é adicionada ao Sampler. Depois de adicioná-lo ao Sampler, você pode dar um nome a ele. Agora ele aparece na lista de projetos.

Você pode editar a malha e as texturas, mas já pode exportar seu resultado usando o <b>Compartilhamento</b> > Caixa de diálogo <b>Exportar como</b>. As <b>configurações gerais</b> permitem escolher o nome e o caminho, as <b>configurações de malha</b> permitem escolher o formato de malha 3D e as <b>configurações de material</b> permitem definir o material da malha. Você pode desativar a malha ou o material para exportar apenas um deles individualmente. Uma vez exportada, sua malha estará pronta para uso em outros aplicativos 3D.

Agora saiba como [editar ainda mais suas malhas 3D capturadas no Sampler](editing-3d-captured-meshes.md).
