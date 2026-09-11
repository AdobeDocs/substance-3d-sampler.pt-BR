---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-5-0-substance-3d-sampler.html"
breadcrumb-title: ''
description: Revise as notas de versão do Substance 3D Sampler versão 5.0 para saber mais sobre novas ferramentas de digitalização, recursos e melhorias no fluxo de trabalho.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 5.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '647'
ht-degree: 0%

---


# Versão 5.0

![](../assets/welcome_digitization_tool.jpg)

O <b>Substance 3D Sampler 5.0</b> apresenta maneiras mais fáceis de obter gêmeo digital de material com digitalizações e renderizações de alta qualidade.

Os principais novos recursos incluem:

## Ações rápidas

Inicie todos os fluxos de trabalho principais do Sampler com um clique e prepare a pilha de camadas para você.

Mais informações *[aqui](../interface/panels/quick-actions-panel.md)*.

![](../assets/quick_actions_1440x810.png)

## Novo layout da tela inicial

Encontre todos os seus projetos e tutoriais e comece seu trabalho diretamente na página inicial.

Mais informações *[aqui](../interface/the-home-screen.md)*.

![](../assets/new_home_screen_layout_1440x810.png)

## Novo renderizador

Escolha entre tempo real e rastreamento de caminho, melhorando a consistência visual e oferecendo suporte a novas propriedades de material. Salve instantâneos do seu trabalho diretamente da visualização 3D.

Mais informações *[aqui](../interface/2d-and-3d-viewport.md)*.

![](../assets/eclair_support_1440x810.png)

## Integração com o HP Z Captis

Com o HP Z Captis e o Substance 3D Sampler, coloque materiais do mundo real em formato digital em minutos.

Recursos disponíveis para contas corporativas, de equipes e de instituições de ensino.

Mais informações *[aqui](../pipeline-and-integrations/hp-z-captis-support/hp-z-captis-support.md)*.

![](../assets/hp_z_captis_1440x810.png)

## Notas de versão da V5.0

*(Lançado em: 20 de fevereiro de 2025)*

<b>Adicionado</b>:



* [Integração] Nova página inicial com acesso rápido a conteúdo de aprendizagem, projeto de amostra, ações rápidas e projetos recentes.
* [Integração] Comece rapidamente com as novas Ações rápidas, acessíveis na página inicial e no painel dedicado
* [Integração] [Conteúdo] Ações rápidas são fluxos de trabalho predefinidos que preenchem a pilha de camadas com as camadas mais usadas
* [Integração] Possibilidade de criar um novo projeto por meio de um novo menu Início rápido, por meio de ações rápidas ou Projeto personalizado
* [Integração] Possibilidade de criar um projeto vazio diretamente da página inicial através do botão dedicado
* [Visualização 3D] Novo rasterizador e pathtracer avançados que trazem novos recursos de renderização (propriedades como revestimento, brilho, translucidez, dispersão de subsuperfície) e consistência visual no ecossistema de Substance
* [Visualização 3D] As configurações do visualizador agora podem ser acessadas diretamente na visualização 3D
* [Visualização 3D] Possibilidade de salvar um instantâneo de renderização na área de transferência ou em arquivos
* [Visualização 3D] Exibir uma grade para visualizar a origem da cena
* [Visualização 3D] Permitir que o plano do solo capture sombras e reflexos
* [Visualização 3D] Controlar o quão reflexivo e opaco é o seu plano terrestre
* [captura 3D] Malha de posição no solo
* [Aplicativo] Verificar a compatibilidade de hardware na inicialização do aplicativo
* [Aplicativo] A janela de relatório de falhas agora é aberta logo após a ocorrência de uma falha
* [Conteúdo] Abrir um projeto de amostra para começar facilmente
* [Exportar] Exportar sombreador de Adobe Standard Material em arquivos USD
* [Generative AI] Marque a tag “Não inferir” ao usar uma imagem como entrada em fluxos de trabalho de Imagem para Textura
* [Project] As miniaturas são armazenadas no arquivo de projeto para agilizar a abertura dos projetos
* [Projeto] Configuração nas preferências para armazenar dados do cache no arquivo de projeto, com modos diferentes (sem cache, cache leve, cache cheio)
* [Scripting] [Quebrando mudança] Migração Qt para Qt6.15 - impacto compatibilidade de plug-ins existentes
* [Script] Os plug-ins padrão e a pasta de scripts agora estão na pasta Documentos
* [Script] Nova interface para plug-ins, para consistência visual com os painéis principais do Sampler
* [Scripting] Exemplos de plug-in do Access 2 para descobrir os recursos de plug-in do Sampler
* [Scripting] Nova função open\_3d\_catpure()
* [Script] Ao inserir uma camada, controle se ela é inserida acima ou abaixo da posição de destino

<b>Corrigido:</b>

* [captura 3D] Falha se a Captura de objeto não puder ser iniciada no macOS
* [Application] Falha ao sair
* [Aplicativo] Travamento ao sair ao adicionar ativos ao painel do projeto
* [Aplicativo] Renomear um ativo de projeto não funciona a menos que você pressione enter
* [Aplicativo] As entradas de menu Desfazer e Refazer não são desativadas quando deveriam ser
* [Ativos] Não é possível excluir ativos da seção Todas as bibliotecas do painel Ativos
* [Content] Criador de atlas - Usar mapa de opacidade existente, se presente
* [Content] Combinar de ID de cor - Corrigir a escolha de cores na cor base
* [Camadas] Evite cálculos inúteis ao usar geradores
* [Camadas] Ajustar um gerador pode levar ao acionamento de muitos computadores
* [Desempenho] Melhorar o gerenciamento de memória da GPU
* [Desempenho] O cache de renderização não pode ser usado ao reiniciar o aplicativo
* [Recursos] Os arquivos somente leitura não são visíveis no painel Ativos
* [Script] Permitir a reutilização de uma camada após adicionar outra camada
* [Script] A alteração da estrutura da pilha de camadas várias vezes em um script pode falhar

<b>Removido:</b>

* [Aplicativo] Remova o suporte para arquivos de imagem .dng e .nef
