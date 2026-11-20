---
description: Revise as notas de versão do Substance 3D Sampler versão 6.1 para saber mais sobre novos recursos, melhorias e aprimoramentos de fluxo de trabalho.
title: Versão 6.1
hold: true
source-git-commit: 99bb504f8dd5c485bf0d208a85cc3825d186c55f
workflow-type: tm+mt
source-wordcount: '1167'
ht-degree: 0%
---

# Versão 6.1

**Kouign amann** (massa bretã em camadas)

![texto alternativo](../../help/assets/Sampler_splash_large.jpg)

Esta versão apresenta o modo Desempenho, que permite a qualquer pessoa desativar configurações que podem diminuir a velocidade do fluxo de trabalho, além de melhorias automáticas de estabilidade que protegem os usuários em hardwares mais leves.

Os principais novos recursos incluem:

## Modo de desempenho

Obtenha uma experiência mais rápida e mais responsiva com o Sampler. O novo **Modo de desempenho** reúne todas as configurações que podem retardar seu fluxo de trabalho: limites de resolução, sombras, qualidade do deslocamento e rastreamento de caminho. Desative os recursos de que você não precisa para melhorar o desempenho e a capacidade de resposta.

Mais informações [*aqui*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode)

![](../assets/v6.1/6_1-Performance_Mode.png)

## Suporte aprimorado para máquinas de especificação mínima

Se o seu hardware estiver abaixo das [especificações mínimas](../getting-started/system-requirements.md), o Sampler agora se ajusta automaticamente para manter as coisas estáveis. Os recursos com maior probabilidade de desacelerar ou causar falhas são desativados automaticamente.

Mais informações [*aqui*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode)

![](../assets/v6.1/6_1-Checked.png)

## Notas de versão V6.1

*(Lançado em: 19 de novembro de 2026)*

## Adicionado

* &amp;lbrack;Aplicativo&amp;rbrack; Nova maneira de relatar avisos de requisitos mínimos de hardware
* &amp;lbrack;Captis&amp;rbrack; Adicionar uma opção para escolher entre 4 e 8 ângulos de polarização
* &amp;lbrack;Captis&amp;rbrack; Ação rápida Nova legenda
* &amp;lbrack;Export&amp;rbrack; Relatar falhas de exportação corretamente ao usuário
* &amp;lbrack;Export&amp;rbrack; Atualizar predefinição de exportação do Unreal Engine 4 (renomeado para Unreal Engine 5)
* &amp;lbrack;Desempenho&amp;rbrack; A criação de ativos a partir do arquivo agora é assíncrona
* &amp;lbrack;Desempenho&amp;rbrack; Mover carga de trabalho do thread principal para os threads de trabalho
* &amp;lbrack;Desempenho&amp;rbrack; Novo modo de desempenho
* &amp;lbrack;Projeto&amp;rbrack; Avisar o usuário se o salvamento do projeto falhar
* &amp;lbrack;Scripting&amp;rbrack; Novo método generate_thumbnail para ativos e nova propriedade de tipo para recursos
* &amp;lbrack;Scripting&amp;brack; Renderiza um instantâneo de visualização 3D para um arquivo a partir do módulo Python
* &amp;lbrack;UI&amp;rbrack; Clicar em qualquer lugar de uma zona para soltar abre a caixa de diálogo do arquivo
* &amp;lbrack;UI&amp;rbrack; Barra de navegação esquerda atalhos para ferramentas (equalizar, cortar, divisão em blocos gráficos, transformar, reparar, cor, ...)
* &amp;lbrack;UI&amp;rbrack; Atualize o espectro qt para obter os ícones mais recentes

## Fixa

* &amp;lbrack;Visualização 3D; Corrigir Deslocamento UV e rotação imediatos, remover escala normal para OpenPBR
* &amp;lbrack;Visualização 3D&amp;rbrack; Evitar falhas assegurando que nenhuma edição de estágio ocorra enquanto o visor for excluído
* &amp;lbrack;Visualização 3D&amp;rbrack; Remover corretamente as informações do deslocamento (height) ao alterar o ativo exibido
* &amp;lbrack;Visualização 3D&amp;rbrack; Atualizar documento corretamente ao excluir a malha
* &amp;lbrack;Aplicativo&amp;rbrack; Garante que a superfície permaneça ativa ao computar informações de depuração de filtro dinâmico
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir falha ao sair na Cena
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir falha potencial ao excluir um ativo enquanto o serviço de banco de dados de ativos está sendo desligado
* &amp;lbrack;Aplicativo&amp;rbrack; Tornar o thread de informações de depuração do cache seguro para evitar uma falha
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falhas por nó de teste não é nulo antes de acessá-lo
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falhas causadas pelo acesso ao primeiro elemento de um vetor vazio
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falhas em invalidateVisibleIfs
* &amp;lbrack;Aplicativo&amp;rbrack; Evita falhas ao criar ativos enquanto o serviço de banco de dados é desligado
* &amp;lbrack;Aplicativo&amp;rbrack; Impedir a condição de corrida ao sair
* &amp;lbrack;Assets&amp;rbrack; Garanta que os recursos estejam adequadamente protegidos atrás do bloqueio correto
* &amp;lbrack;Captis&amp;rbrack; Erro com valor de intensidade no modo manual
* &amp;lbrack;Captis&amp;rbrack; Impede que o usuário selecione uma zona maior do que o backend permite
* &amp;lbrack;Configurações do canal&amp;rbrack; Ocorrência dupla de SpecularColor no ASM
* &amp;lbrack;Configurações do canal&amp;rbrack; Corrigir a id de um uso criado a partir de uma string
* &amp;lbrack;Problema de opacidade de Atlas scatter do Content&amp;brack;
* &amp;lbrack;Content&amp;brack; O filtro de bordados não tem recurso metálico
* &amp;lbrack;Content&amp;brack; Corrigir filtro de perfuração
* &amp;lbrack;Content&amp;brack; Corrigir a categoria do filtro de Estilização e algumas correções no painel de recursos
* &amp;preto;Content&amp;brack; Atualizar filtro de Preenchimento
* &amp;lbrack;Creative Cloud&amp;rbrack; Corrigir caminho para os ativos 3D no Creative Cloud
* &amp;lbrack;Engine&amp;rbrack; Evitar falhas ao acessar dados do mecanismo enquanto o trabalho for cancelado
* &amp;lbrack;Export&amp;brack; Adicionar código defensivo para verificar se a árvore da estrutura não é nula
* &amp;lbrack;Export&amp;brack; Código defensivo para evitar falhas na geração de SBS
* &amp;lbrack;Export&amp;brack; Habilita usos personalizados de saída, mesmo que sejam conhecidos pelo mecanismo
* &amp;preto;Exportar&amp;rbrack; Corrigir predefinições de exportação
* &amp;lbrack;Exportar&amp;rbrack; os Mapas normais são exportados como raw no USD
* &amp;preto;Exportar&amp;rbrack; Usar rótulos de saída em vez de usos ao exportar com uma predefinição
* &amp;preto;Parâmetros expostos&amp;rbrack; Corrigir parâmetros expostos em filtros dinâmicos
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Corrigir a atualização do parâmetro exposto quando seu nome mudar
* &amp;lbrack;Filtros&amp;rbrack; Garanta que os identificadores dos filtros dinâmicos sejam idênticos entre todas as execuções em todas as plataformas
* &amp;lbrack;Filtros&amp;rbrack; Ocultar usos não suportados na seleção do mapa de AutoLado a Lado
* &amp;lbrack;Camadas&amp;rbrack; Alterar a visibilidade da camada sempre recria estruturas
* &amp;lbrack;Camadas&amp;rbrack; Falha ao nivelar um Carimbo de Clonar sobre algo
* &amp;lbrack;Camadas&amp;rbrack; Inserir um gerador diretamente na pilha agora define corretamente ajustes e o nome do nó
* &amp;lbrack;Camadas&amp;rbrack; Inserir um gerador com Preenchimento exibe corretamente a textura no seletor
* &amp;lbrack;Localização&amp;rbrack; Corrigir conformidade de codificação chinesa para GB18030
* &amp;lbrack;Projeto&amp;rbrack; Falha ao salvar após pintar em um Clonar Stamp
* &amp;lbrack;Project&amp;rbrack; Certifique-se de que os nomes das sessões e dos projetos estejam realmente salvos
* &amp;lbrack;Projeto&amp;rbrack; Evitar falhas ao salvar uma árvore
* &amp;lbrack;Projeto&amp;rbrack; A restauração de um projeto corrompido a partir do banco de dados está novamente
* &amp;lbrack;Ações rápidas&amp;rbrack; Exibe o pop-up de seleção de imagem quando não há nenhuma imagem na pilha
* &amp;preto;Ações rápidas&amp;rbrack; Corrigir problemas de ações rápidas; cancelar uma ação rápida não fecha mais o início rápido
* &amp;lbrack;Ações rápidas&amp;rbrack; Importar texturas pede para ativar alguns canais e não deveria
* &amp;lbrack;Ações rápidas&amp;rbrack; Evitar falhas se uma ação rápida falhar ao carregar
* &amp;preto;Ações rápidas&amp;rbrack; Atualizar conteúdo de ações rápidas
* &amp;lbrack;Renderização&amp;rbrack; Corrigir combineNormalAndHeight para materiais ASM
* &amp;lbrack;Renderização&amp;rbrack; Corrigir usos de texturas exibíveis com Vulkan
* &amp;lbrack;Renderização&amp;rbrack; Marcar árvore como suja quando a saída de uso único for alterada
* &amp;lbrack;Renderização&amp;rbrack; Usar a estrutura de referência correta para calcular os nós de árvore a serem computados
* &amp;lbrack;Scripting&amp;brack; Não parar se algo der errado durante uma exportação
* &amp;lbrack;Scripting&amp;brack; Ensure import_images() retorna a camada importada
* &amp;lbrack;Scripting&amp;brack; A configuração de um ajuste de imagem para uma referência de ativo de imagem falha
* &amp;brack;Scripting&amp;brack; get_filters() não retorna filtros dinâmicos
* &amp;lbrack;Miniatura&amp;rbrack; Corrigir possíveis falhas ao gerar a miniatura
* &amp;lbrack;Miniatura&amp;rbrack; Recria o gerador de miniaturas quando o layout mudar
* &amp;lbrack;UI&amp;rbrack; Alterar ativo pode definir a escala do height para o valor máximo do controle deslizante
* &amp;lbrack;UI&amp;rbrack; Desenhar em uma textura atualiza o seletor de textura em tempo real
* &amp;lbrack;UI&amp;rbrack; Entrar no modo de tela cheia enquanto não estiver maximizado agora preenche toda a janela
* &amp;lbrack;UI&amp;rbrack; Corrigir link quebrado para Revista Substance
* &amp;lbrack;UI&amp;rbrack; Corrigir margens pop-up de exportação
* &amp;lbrack;UI&amp;rbrack; Corrigir tamanho do título da seção
* &amp;lbrack;UI&amp;rbrack; Corrigir erro de digitação em uma string
* A janela do arquivo do &amp;lbrack;UI&amp;rbrack; Linux agora usa o plug-in GTK
* &amp;lbrack;UI&amp;rbrack; Evitar falha ao exibir um emoji
* &amp;lbrack;UI&amp;rbrack; Renomear arquivos .ssa como &#39;arquivo Adobe Substance 3D Sampler&#39; (sem versão ou Beta)
* &amp;lbrack;UI&amp;rbrack; Restaurar desaceleração cintilável ao usar o mouse
* &amp;lbrack;UI&amp;rbrack; Pequenas correções no diálogo “Criar novo material”
