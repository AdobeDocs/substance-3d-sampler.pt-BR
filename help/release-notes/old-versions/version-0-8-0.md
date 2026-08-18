---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/release-notes/old-versions/version-0-8-0.html"
breadcrumb-title: ''
description: Revise as notas de versão do Substance 3D Sampler versão 0.8.0 para saber mais sobre novos recursos, atualizações e melhorias.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.8.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 0.8.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 0%

---


# Versão 0.8.0

**Adicionado:**

* [Recursos] Conecte e espelhe as pastas de materiais nos discos locais
* [Recursos] Procure suas pastas de materiais e suas subpastas
* [Recursos] Destaque o painel de recursos de material em uma janela separada para ver seus recursos em tela cheia
* [Recursos] Novo layout do painel Recursos para oferecer suporte à navegação de pastas e subpastas
* [Recursos] Use a estrutura para navegar pelas pastas
* [Recursos] Force a sincronização da pasta local com a opção Sincronizar acessível clicando com o botão direito do mouse
* [Recursos] Desconecte a pasta local com a opção Desconectar acessível clicando com o botão direito do mouse
* [Gerenciar] Exibir marcas incorporadas de arquivos Substance
* [Gerenciar] Adicione, edite e exclua marcas de seus materiais
* [Gerenciar] Avaliar seus materiais
* [Camadas] Saída do panorama de suporte
* [Camadas] Você pode excluir entradas de imagem na camada de importação de imagem
* [Camadas] Seleção automática da nova camada adicionada
* [Camadas] Seleção automática da camada abaixo após a exclusão de uma camada
* [UX] Manter a visibilidade dos painéis à esquerda ao alternar para outro laboratório
* [UX] Não crie uma camada base nem abra a pop-up Fluxo de trabalho de material ao importar imagens em uma pilha de camadas não vazias
* [UI] Novo estilo de campo de texto
* [UI] Novo estilo de SearchBox
* [UI] Novo estilo de cabeçalho do painel
* [UI] Novo estilo de indicador Ocupado
* [UI] Novo estilo de plano de fundo da pilha de camadas
* [UI] Usar fonte Adobe Clean
* [UI] Remover espaço reservado do ícone de conta-gotas do parâmetro de entrada de cores
* [Desempenho] Otimização do indicador de ocupado
* [Content] Novo filtro Gerador de Padrão
* [Conteúdo] Novo filtro de Desfoque

**Corrigido:**

* [Inspire] Corrigir falha ao usar mais de 10 cores
* [Visualização 2D] Corrigir a barra de rolagem na lista de canais da visualização 2D
* [Visualizador] Corrigir falha ao importar um mapa de ambiente sem alimentação de 2
* [Conteúdo] Corrigir a importação de PNG para um padrão personalizado de filtros de Gravação e Perfuração
* [Exportar] Corrigir normal e height de 16 bits por exportação de canal
* Corrija um loop infinito ao importar um material com duas predefinições que têm o mesmo nome
* Corrigir exibição de caminho de arquivo longo na Camada de Material de base

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter não é recomendado
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para height pode falhar no MacOS
* Pode travar aleatoriamente ao sair no MacOS
