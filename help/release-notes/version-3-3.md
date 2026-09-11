---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-3-3.html"
breadcrumb-title: ''
description: Revise as notas de versão do Substance 3D Sampler versão 3.3 para saber mais sobre novas ferramentas, conteúdo e recursos de criação de material.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.3
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 3.3
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1108'
ht-degree: 0%

---


# Versão 3.3

O **Substance 3D Sampler 3.3.0** apresenta uma série de novas ferramentas, conteúdo e recursos para criar e editar materiais e iluminações do ambiente com mais facilidade.

*Data de lançamento: 17 de maio de 2022*

## Principais recursos

## Preenchimento sensível ao conteúdo

O Preenchimento sensível ao conteúdo é uma tecnologia popular encontrada no Adobe Photoshop, usada para remover detalhes em uma imagem enquanto mantém a integridade da área ao redor.

A Substance 3D Sampler agora usa essa mesma tecnologia, permitindo que você limpe materiais e iluminações do ambiente de PBR. Em materiais PBR, o Preenchimento com reconhecimento de conteúdo é aplicado em todos os canais. Não há necessidade de processar cada canal separadamente.

O Preenchimento sensível ao conteúdo pode ajudar a remover grandes elementos para evitar repetição ao colocar um material lado a lado ou remover pequenas imperfeições na tela digitalizada.

Ao capturar panoramas 360, você pode não ter controle de todos os elementos da cena e, portanto, precisa remover pequenos objetos no chão, pinturas em uma parede ou uma pessoa de pé no fundo. O Preenchimento sensível ao conteúdo agora torna isso mais fácil.

## Criação de IBL

### Projeção esférica

Editar iluminações do ambiente e imagens 360 pode ser um desafio quando elas são exibidas como imagens regulares. Todos os elementos são distorcidos, tornando quase impossível editá-los. Com a nova projeção esférica, você pode navegar em 360° e editar com ferramentas dedicadas, como Nadir patch, Preenchimento sensível ao conteúdo e todas as luzes processuais sem distorção. Agora é mais fácil, por exemplo, editar ou limpar linhas retas, remover o tripé da câmera e inserir as luzes de linha perfeitamente.

Confira o novo tutorial para [criar iluminações do ambiente](https://www.youtube.com/watch?v=cfW9IyoTXQ8) usando este novo modo.

### Controle deslizante de exposição

No Visualização 2D, você pode modificar temporariamente a exposição para ajudar a ver melhor os detalhes ou objetos em partes subexpostas ou superexpostas do ambiente que está editando.

### Configurações do visualizador dedicado

As configurações do visualizador são persistentes por tipo de ativo (material ou iluminação do ambiente). É possível definir a malha, as texturas padrão ou o campo de exibição da câmera para cada tipo de ativo, para facilitar a alternância entre elas e trabalhar no contexto certo.

## Widgets aprimorados

### Carimbo de Clonar

Com esta atualização de carimbo de Clonar, você pode tinta vários traçados de carimbo a várias fontes em uma única camada e acessar o histórico de carimbos na pilha de camadas. Além disso, agora você pode ver o resultado do carimbo diretamente na visualização do pincel antes de pintar. Isso facilita a limpeza do material e evita muitas oscilações entre as exibições.

### Cortar e Transformar

Esta atualização apresenta novos atalhos para a manipulação de widgets Cortar e Transformar.

### Barra de ferramentas Pincel

A nova interface, semelhante aos produtos de Adobe mais recentes, como o Fresco, permite mover a barra de ferramentas para qualquer lugar na Visualização 2D, exibido vertical ou horizontalmente. Ao pintar, alterne entre pincel e borracha com a tecla E e use as novas opções de divisão em blocos gráficos para controlar melhor o que você tinta.

## Imagem para material (viabilizado por IA)

### Preservar divisão em blocos gráficos

Image to Material (alimentado por IA) recebe uma nova opção: agora pode preservar a divisão em blocos gráficos da imagem lado a lado, reduzindo o tempo para dividir o material depois.

## Interoperabilidade

Enviar materiais para o Stager

Já era possível enviar iluminações do ambiente ao Stager. Agora você pode enviar seus materiais para o Stager em um clique, assim como com o Designer e o Painter. Graças a esse recurso, você não precisa mais publicar seus materiais e carregá-los no Stager como arquivos individuais (requer o Stager versão 1.2.0 com o novo gerenciador de materiais).

## Notas de versão

### 3.3.0 Abobrinha

*(Lançado Em 17 De maio De 2022)*

**Adicionado:**

* [Conteúdo] Novo filtro Preenchimento sensível ao conteúdo (Windows e Mac)
* [Content] O Preenchimento sensível ao conteúdo está funcionando em imagens, materiais PBR e iluminações do ambiente
* [Conteúdo] Adicionar o parâmetro “Preservar divisão em blocos gráficos” à Imagem para material (viabilizado por IA)
* [Conteúdo] O filtro Transformar Perspectiva pode exibir uma grade entre seus quatro pontos
* [Interoperabilidade] Enviar materiais para a Adobe Substance 3D Stager
* [Ferramentas] Centralize a transformação pressionando Ctrl ao redimensionar a ferramenta Transformar ou Cortar
* [Ferramentas] Bloqueie a proporção para o quadrado pressionando Shift ao redimensionar a ferramenta Transformar ou Cortar
* [Ferramentas] O cursor do carimbo de Clonar oferece uma visualização do que será carimbado
* [Ferramentas] Visualizar o conteúdo original no cursor de Borracha ao usar o carimbo de Clonar
* [Ferramentas] Ctrl+clique cria um novo carimbo na camada Clonar Carimbo
* [Ferramentas] Carimbos de clonagem sucessivos agora são agrupados em uma única camada
* [Ferramentas] Renovação da interface da barra de ferramentas Pincel
* [Tools] A posição da barra de ferramentas Pincel é persistente durante uma sessão
* [Ferramentas] Novas opções de divisão em blocos gráficos por eixo
* [Ferramentas] Ocultar/exibir a sobreposição sobre a Visualização 2D ao pintar
* [Ferramentas] Novo atalho, tecla “X”, para alternar entre Pincel e Borracha
* [Ferramentas] Novo atalho, “[” “]” para alterar o tamanho do Pincel
* [Ferramentas] Novo atalho, tecla “E”, para alternar a Borracha
* [Visualização 2D] Novo modo de Projeção esférica ao criar a iluminação do ambiente
* [Visualização 2D] A ferramenta Pincel é compatível com o modo de projeção esférica
* [Visualização 2D] A ferramenta Posição é compatível com o modo de projeção esférica
* [Visualização 2D] O recurso Desfazer/Refazer é compatível com o modo de projeção esférica
* [Visualização 2D] No Projeção esférica, defina a posição padrão para olhar para o centro do ambiente
* [Visualização 2D] Novo controle de exposição
* [IU] No painel Propriedades, o ajuste da imagem exibe a origem do conteúdo (imagem ou de uma camada)
* [IU] Aprimoramento do plano de fundo do menu suspenso de saídas de camada/material
* [IU] Nova posição das informações de resolução no Visualização 2D
* [UI] Nova dica de ferramenta com atalhos de controles de navegação de exibição 3D
* [UI] Nova dica de ferramenta com controles de pincel
* [IU] Nova dica de ferramenta com atalhos de controles de navegação de projeção
* [Filtros compostos] Eles manipulam variações para trabalhar em imagens, materiais PBR e iluminações do ambiente
* [Filtros compostos] A ordem de ajustes corresponde à ordem da lista de nós no filtro composto
* [Filtros compostos] Os ajustes de nós diferentes com o mesmo grupo serão mesclados em um único grupo no painel Propriedades
* [Aplicativo] Tem configurações de visualizador dedicado por tipo de ativo

**Corrigido:**

* [Application] O aplicativo pode falhar ao alternar para a exibição 2D
* [Aplicativo] Corrigir um possível deadlock ou falha ao exportar várias vezes
* [Aplicativo] Tornar os valores padrão para canais consistentes com o Substance 3D Designer
* [Aplicativo] Carregar um projeto não aciona o recálculo de material
* [Aplicativo] URL atualizada para importar documentação do textura
* [Conteúdo] Ao usar um filtro composto, ele pede para ser atualizado quando não deveria, ao recarregar
* [Content] Os detalhes no mapa de altura desaparecem ao usar o Combinar de opacidade
* [UI] Na caixa de diálogo Cor, é possível sair da faixa usando os campos de texto do controle deslizante
* [UI] A lista de uso tem uma barra de rolagem vertical inútil

**Problemas Conhecidos:**

* [Seletor de cores] Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* [Content] O widget de luz da forma não está funcionando no modo de projeção esférica
* [Interoperabilidade] O material com deslocamento enviado para o Stager perderá os controles do deslocamento
