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

Mais informações [*aqui*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode_br)

![](../assets/v6.1/6_1-Performance_Mode.png)

## Suporte aprimorado para máquinas de especificação mínima

Se o seu hardware estiver abaixo das [especificações mínimas](../getting-started/system-requirements.md), o Sampler agora se ajusta automaticamente para manter as coisas estáveis. Os recursos com maior probabilidade de desacelerar ou causar falhas são desativados automaticamente.

Mais informações [*aqui*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode_br)

![](../assets/v6.1/6_1-Checked.png)

## Notas de versão V6.1

*(Lançado em: 19 de novembro de 2026)*

## Adicionado

* &lbrack;Aplicativo&rbrack; Nova maneira de relatar avisos de requisitos mínimos de hardware
* &lbrack;Captis&rbrack; Adicionar uma opção para escolher entre 4 e 8 ângulos de polarização
* &lbrack;Captis&rbrack; Ação rápida Nova legenda
* &lbrack;Export&rbrack; Relatar falhas de exportação corretamente ao usuário
* &lbrack;Export&rbrack; Atualizar predefinição de exportação do Unreal Engine 4 (renomeado para Unreal Engine 5)
* &lbrack;Desempenho&rbrack; A criação de ativos a partir do arquivo agora é assíncrona
* &lbrack;Desempenho&rbrack; Mover carga de trabalho do thread principal para os threads de trabalho
* &lbrack;Desempenho&rbrack; Novo modo de desempenho
* &lbrack;Projeto&rbrack; Avisar o usuário se o salvamento do projeto falhar
* &lbrack;Scripting&rbrack; Novo método generate_thumbnail para ativos e nova propriedade de tipo para recursos
* &lbrack;Scripting&brack; Renderiza um instantâneo de visualização 3D para um arquivo a partir do módulo Python
* &lbrack;UI&rbrack; Clicar em qualquer lugar de uma zona para soltar abre a caixa de diálogo do arquivo
* &lbrack;UI&rbrack; Barra de navegação esquerda atalhos para ferramentas (equalizar, cortar, divisão em blocos gráficos, transformar, reparar, cor, ...)
* &lbrack;UI&rbrack; Atualize o espectro qt para obter os ícones mais recentes

## Fixa

* &lbrack;Visualização 3D; Corrigir Deslocamento UV e rotação imediatos, remover escala normal para OpenPBR
* &lbrack;Visualização 3D&rbrack; Evitar falhas assegurando que nenhuma edição de estágio ocorra enquanto o visor for excluído
* &lbrack;Visualização 3D&rbrack; Remover corretamente as informações do deslocamento (height) ao alterar o ativo exibido
* &lbrack;Visualização 3D&rbrack; Atualizar documento corretamente ao excluir a malha
* &lbrack;Aplicativo&rbrack; Garante que a superfície permaneça ativa ao computar informações de depuração de filtro dinâmico
* &lbrack;Aplicativo&rbrack; Corrigir falha ao sair na Cena
* &lbrack;Aplicativo&rbrack; Corrigir falha potencial ao excluir um ativo enquanto o serviço de banco de dados de ativos está sendo desligado
* &lbrack;Aplicativo&rbrack; Tornar o thread de informações de depuração do cache seguro para evitar uma falha
* &lbrack;Aplicativo&rbrack; Evitar falhas por nó de teste não é nulo antes de acessá-lo
* &lbrack;Aplicativo&rbrack; Evitar falhas causadas pelo acesso ao primeiro elemento de um vetor vazio
* &lbrack;Aplicativo&rbrack; Evitar falhas em invalidateVisibleIfs
* &lbrack;Aplicativo&rbrack; Evita falhas ao criar ativos enquanto o serviço de banco de dados é desligado
* &lbrack;Aplicativo&rbrack; Impedir a condição de corrida ao sair
* &lbrack;Assets&rbrack; Garanta que os recursos estejam adequadamente protegidos atrás do bloqueio correto
* &lbrack;Captis&rbrack; Erro com valor de intensidade no modo manual
* &lbrack;Captis&rbrack; Impede que o usuário selecione uma zona maior do que o backend permite
* &lbrack;Configurações do canal&rbrack; Ocorrência dupla de SpecularColor no ASM
* &lbrack;Configurações do canal&rbrack; Corrigir a id de um uso criado a partir de uma string
* &lbrack;Problema de opacidade de Atlas scatter do Content&brack;
* &lbrack;Content&brack; O filtro de bordados não tem recurso metálico
* &lbrack;Content&brack; Corrigir filtro de perfuração
* &lbrack;Content&brack; Corrigir a categoria do filtro de Estilização e algumas correções no painel de recursos
* &preto;Content&brack; Atualizar filtro de Preenchimento
* &lbrack;Creative Cloud&rbrack; Corrigir caminho para os ativos 3D no Creative Cloud
* &lbrack;Engine&rbrack; Evitar falhas ao acessar dados do mecanismo enquanto o trabalho for cancelado
* &lbrack;Export&brack; Adicionar código defensivo para verificar se a árvore da estrutura não é nula
* &lbrack;Export&brack; Código defensivo para evitar falhas na geração de SBS
* &lbrack;Export&brack; Habilita usos personalizados de saída, mesmo que sejam conhecidos pelo mecanismo
* &preto;Exportar&rbrack; Corrigir predefinições de exportação
* &lbrack;Exportar&rbrack; os Mapas normais são exportados como raw no USD
* &preto;Exportar&rbrack; Usar rótulos de saída em vez de usos ao exportar com uma predefinição
* &preto;Parâmetros expostos&rbrack; Corrigir parâmetros expostos em filtros dinâmicos
* &lbrack;Parâmetros expostos&rbrack; Corrigir a atualização do parâmetro exposto quando seu nome mudar
* &lbrack;Filtros&rbrack; Garanta que os identificadores dos filtros dinâmicos sejam idênticos entre todas as execuções em todas as plataformas
* &lbrack;Filtros&rbrack; Ocultar usos não suportados na seleção do mapa de AutoLado a Lado
* &lbrack;Camadas&rbrack; Alterar a visibilidade da camada sempre recria estruturas
* &lbrack;Camadas&rbrack; Falha ao nivelar um Carimbo de Clonar sobre algo
* &lbrack;Camadas&rbrack; Inserir um gerador diretamente na pilha agora define corretamente ajustes e o nome do nó
* &lbrack;Camadas&rbrack; Inserir um gerador com Preenchimento exibe corretamente a textura no seletor
* &lbrack;Localização&rbrack; Corrigir conformidade de codificação chinesa para GB18030
* &lbrack;Projeto&rbrack; Falha ao salvar após pintar em um Clonar Stamp
* &lbrack;Project&rbrack; Certifique-se de que os nomes das sessões e dos projetos estejam realmente salvos
* &lbrack;Projeto&rbrack; Evitar falhas ao salvar uma árvore
* &lbrack;Projeto&rbrack; A restauração de um projeto corrompido a partir do banco de dados está novamente
* &lbrack;Ações rápidas&rbrack; Exibe o pop-up de seleção de imagem quando não há nenhuma imagem na pilha
* &preto;Ações rápidas&rbrack; Corrigir problemas de ações rápidas; cancelar uma ação rápida não fecha mais o início rápido
* &lbrack;Ações rápidas&rbrack; Importar texturas pede para ativar alguns canais e não deveria
* &lbrack;Ações rápidas&rbrack; Evitar falhas se uma ação rápida falhar ao carregar
* &preto;Ações rápidas&rbrack; Atualizar conteúdo de ações rápidas
* &lbrack;Renderização&rbrack; Corrigir combineNormalAndHeight para materiais ASM
* &lbrack;Renderização&rbrack; Corrigir usos de texturas exibíveis com Vulkan
* &lbrack;Renderização&rbrack; Marcar árvore como suja quando a saída de uso único for alterada
* &lbrack;Renderização&rbrack; Usar a estrutura de referência correta para calcular os nós de árvore a serem computados
* &lbrack;Scripting&brack; Não parar se algo der errado durante uma exportação
* &lbrack;Scripting&brack; Ensure import_images() retorna a camada importada
* &lbrack;Scripting&brack; A configuração de um ajuste de imagem para uma referência de ativo de imagem falha
* &brack;Scripting&brack; get_filters() não retorna filtros dinâmicos
* &lbrack;Miniatura&rbrack; Corrigir possíveis falhas ao gerar a miniatura
* &lbrack;Miniatura&rbrack; Recria o gerador de miniaturas quando o layout mudar
* &lbrack;UI&rbrack; Alterar ativo pode definir a escala do height para o valor máximo do controle deslizante
* &lbrack;UI&rbrack; Desenhar em uma textura atualiza o seletor de textura em tempo real
* &lbrack;UI&rbrack; Entrar no modo de tela cheia enquanto não estiver maximizado agora preenche toda a janela
* &lbrack;UI&rbrack; Corrigir link quebrado para Revista Substance
* &lbrack;UI&rbrack; Corrigir margens pop-up de exportação
* &lbrack;UI&rbrack; Corrigir tamanho do título da seção
* &lbrack;UI&rbrack; Corrigir erro de digitação em uma string
* A janela do arquivo do &lbrack;UI&rbrack; Linux agora usa o plug-in GTK
* &lbrack;UI&rbrack; Evitar falha ao exibir um emoji
* &lbrack;UI&rbrack; Renomear arquivos .ssa como &#39;arquivo Adobe Substance 3D Sampler&#39; (sem versão ou Beta)
* &lbrack;UI&rbrack; Restaurar desaceleração cintilável ao usar o mouse
* &lbrack;UI&rbrack; Pequenas correções no diálogo “Criar novo material”
