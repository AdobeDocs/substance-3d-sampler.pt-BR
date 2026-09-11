---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-0-7-0.html"
breadcrumb-title: ''
description: Consulte as notas de versão do Substance 3D Sampler versão 0.7.0 para saber mais sobre atualizações, aprimoramentos e correções de erros.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.7.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 0.7.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Versão 0.7.0

Data de lançamento: **6/2019/13**

Adicionado:

* [Filters] Acesse rapidamente seus filtros pressionando a barra de espaço
* [Filtros] Novo painel dedicado para gerenciar, procurar e importar seus filtros
* [Metadados] Clique com o botão direito do mouse em um material para ver seus metadados
* [Metadados] Clique com o botão direito do mouse em um material para ver sua localização no disco
* [Controles deslizantes] Anime os controles deslizantes ao passar o mouse sobre eles pressionando Ctrl
* [Controles deslizantes] Pare e reinicie a animação dos controles deslizantes pressionando P
* [Exportar] A exportação SBSAR segue as diretrizes de Substance Source
* [License] Ativar Substance Alchemist usando uma variável de ambiente
* [UX] A caixa de diálogo Arquivo lembra o último caminho de arquivo selecionado
* [UX] A caixa de diálogo Pasta lembra o último caminho de pasta selecionado
* [UI] Atualizar interface do painel Recursos
* [UI] Atualizar interface do usuário da barra de pesquisa
* [UI] O ícone Criar novo material foi atualizado
* [Ajuda] URLs são atualizadas para o domínio [substance3d.com](http://substance3d.com)
* [Mesh] Uma malha de pano agora está disponível
* [Conteúdo] Novo filtro de corrosão
* [Content] Novo filtro de oxidação
* [Content] Novo Filtro De Moss
* [Conteúdo] Novo Filtro de Dust
* [Content] Novo filtro de padrão de tijolo
* [Content] Novo filtro de padrão Stonewall
* [Content] Novo filtro de acabamento em madeira
* [Content] Novo filtro de acabamento metálico
* [Content] Novo filtro de Snow
* [Content] Novo filtro aleatório
* [Conteúdo] Agora você pode importar suas texturas diretamente no filtro Material de base

Corrigido:

* Corrigir uma falha ao salvar a pilha de camadas
* É possível adicionar um valor acima de 1 no controle deslizante de rotação do ambiente
* Não perca os parâmetros de mesclagem quando uma camada de mesclagem for transformada para frente e para trás da camada de mesclagem para a camada de material
* Corrigir duplicatas ao gerar variações da mesma pilha de camadas várias vezes
* Ao reabrir um material, o Alchemist se lembra dos intervalos modificados (mínimo e máximo) dos controles deslizantes

Problemas conhecidos:

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter não é recomendado
* A importação de ambiente personalizado pode ficar preta
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para height pode falhar no MacOS
