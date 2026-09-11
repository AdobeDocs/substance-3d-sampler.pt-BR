---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/release-notes/all-changes.html'
breadcrumb-title: ''
description: Revise todas as alterações e atualizações nas versões do Substance 3D Sampler para acompanhar a evolução e as melhorias de recursos ao longo do tempo.
helpx_description: Sampler > Release Notes > All Changes
title: Todas as alterações
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0484ed7ae81bd16687abe23ac0ce8f5ad84d1888
workflow-type: tm+mt
source-wordcount: '24940'
ht-degree: 0%

---


# Todas as alterações

Esta página agrupa todas as alterações que aconteceram no Substance 3D Sampler, desde novos recursos até correções de erros.

## Versão 6

### **6.0.3**

*(Lançado em: 24 de agosto de 2026)*

**Corrigido:**

[Renderização] Reverta a solução temporária para drivers NVIDIA com falha

### **6.0.2**

*(Lançado em: 25 de junho de 2026)*

**Adicionado:**

* &lbrack;Assets&rbrack; Verifique a versão do sbsar e avise os usuários se o mecanismo é muito antigo para lê-lo
* &lbrack;Captis&rbrack; Adicionar opção de volta para salvar a fotometria das legendas nas preferências

**Corrigido:**

* &lbrack;Visualização 2D&rbrack; Não “exibir com proporção física” se o tamanho físico estiver desativado
* &lbrack;Analytics&rbrack; Eventos de análise ausentes
* &lbrack;Analytics&rbrack; Impedir que o bloco de anotações reporte uma falha no vk devicelost
* &lbrack;Aplicativo&rbrack; Não destrua dispositivos vkna saída para evitar uma falha no driver nvidia
* &lbrack;Aplicativo&rbrack; Corrigir saída do inspetor de coleções vinculadas + gerenciador de canais
* &lbrack;Aplicativo&rbrack; Evitar falhas ao sair
* O filtro &lbrack;Content&brack; “metal finish” não afeta a metalidade
* &lbrack;Content&brack; Adicionar tamanho físico a filtros dinâmicos nos quais está faltando
* &lbrack;Filtros&rbrack; Remover preenchimento sensível a conteúdo da lista de ativos ocultos
* &lbrack;Camadas&rbrack; Clicar em &#39;redefinir todas as configurações&#39; não redefine o menu suspenso &#39;aplica a&#39;
* &lbrack;Camadas&rbrack; Corrigir ajuste mínimo &amp; máximo para o widget de posição
* &lbrack;Camadas&rbrack; Atualizar filtro corretamente
* &lbrack;Tamanho físico&rbrack; Certificar-se de que a escala física está funcionando em todos os lugares + deixar o tamanho físico ok com filtros dinâmicos
* &lbrack;Projeto&rbrack; Certifique-se de que a resolução do ativo é a padrão (2k x 2k) ao criar um novo ativo
* &lbrack;Projeto&rbrack; Reabrindo o projeto atual usado para abrir a versão anterior
* &lbrack;Projeto&rbrack; O Sampler não oferece mais a opção de restaurar um backup de projetos corrompidos
* &lbrack;Renderização&rbrack; Renderizar a miniatura do material em no máximo 2k de resolução
* &lbrack;UI&rbrack; Código defensivo para evitar falhas se o usuário for mais rápido que a interface

### **6.0.1**

*(Lançado em: 21 de maio de 2026)*

**Adicionado:**

* &lbrack;Aplicativo&rbrack; Avisar o usuário ao abrir um projeto com objetos ou iluminações do ambiente 3D
* &preto;Captis&rbrack; Faz com que a interface se adapte a telas pequenas
* &preto;Captis&rbrack; Atualizar interface do usuário do Captis
* &lbrack;Configurações do Canal&rbrack; Ativar o SSS automaticamente ao usar o canal SSS no ASM
* &lbrack;Engine&rbrack; Atualização Substance Engine para a versão 9.4.3
* &lbrack;Predefinição&rbrack; Ativar &#39;aplicar valores de miniatura predefinidos&#39; por padrão
* &lbrack;Recursos&rbrack; Exibir &#39;todas as bibliotecas&#39; por padrão em vez de &#39;ativos iniciais&#39; no painel de recursos
* &lbrack;Scripting&brack; Adicionar funções Python para gerenciar &#39;Aplicado a&#39; de uma camada
* &lbrack;UI&rbrack; A lista de ativos agora responde: o tamanho do ativo se adapta ao contêiner
* &lbrack;UI&rbrack; Exibir 3D/Visualização 2D por padrão
* &lbrack;UI&rbrack; Exibir pop-up de otimização de material ao soltar um material do explorador
* &lbrack;UI&rbrack; Ativar inversão da dica de ferramenta dos botões da barra de dispositivos

**Corrigido:**

* &lbrack;Aplicativo&rbrack; Corrigir problemas de espaço de cores
* &lbrack;Aplicativo&rbrack; Corrigir configurações atualizador
* &lbrack;Aplicativo&rbrack; Torna os canais de digitalização ativos quando estiverem definidos como automáticos
* &lbrack;Aplicativo&rbrack; O botão Novo projeto da tela inicial não apaga mais o projeto anterior com o mesmo nome
* &lbrack;Aplicativo&rbrack; Evitar falhas ao sair no macOS
* &lbrack;Aplicativo&rbrack; Impedir o acesso a ativos de referências de ativos inválidos
* &lbrack;Aplicativo&rbrack; Impedir falha ao acessar a superfície a partir da ImagemVersionada em um ajuste
* &lbrack;Aplicativo&rbrack; Evitar falha ao excluir um estágio quando não houver nenhum
* &lbrack;Captis&rbrack; Certifique-se de que a Captis está desconectada antes de fechar o Sampler
* &lbrack;Captis&rbrack; Impedir que o aviso USB-2 seja exibido duas vezes
* &lbrack;Configurações do canal&rbrack; Corrigir nomes dos canais de OpenPBR
* &lbrack;Configurações do canal&rbrack; Atualizar etiquetas longas para canais de OpenPBR
* &lbrack;Content&brack; Atualizar todas as unidades de malha de metros a centímetros para valores SSS
* &lbrack;Export&brack; Garantir que os valores padrão estejam conectados a filtros dinâmicos
* &lbrack;Export&brack; As imagens agora são salvas em um thread de trabalho para melhorar o desempenho
* &lbrack;Filtros&rbrack; O Preenchimento sensível ao conteúdo falha ao ativar a escala
* &lbrack;Filtros&rbrack; Não foi possível abrir o local de um filtro dinâmico no painel de ativos
* &lbrack;Filtros&rbrack; Corrigir redefine tudo na etapa de ajuste de AutoLado a Lado
* &lbrack;Filtros&rbrack; Restaurar desabilitar processamento de uso na criação de estruturas em árvore
* &lbrack;Filtros&rbrack; Define o valor padrão correto para o parâmetro upscale
* &lbrack;Filtros&rbrack; Atualiza os geradores mesmo se estiverem em uma camada de preenchimento
* &lbrack;Camadas&rbrack; Proibir renomeação de camadas de cabeçalho de camada de entrada ou camadas de espaço reservado
* &lbrack;Camadas&rbrack; Evitar falha durante a inserção da camada devido a um ponteiro oscilante
* &lbrack;Camadas&rbrack; Número incorreto de imagens no nome da camada achatada
* &lbrack;Localization&brack; Certifique-se de que os nomes predefinidos sejam atualizados ao alternar idiomas
* &lbrack;Localização&rbrack; Vários problemas de tradução no painel de recursos
* &lbrack;Localização&rbrack; Ações rápidas categorias problemas de localização
* &lbrack;Performance&rbrack; Ajustes de carregamento somente na seção aberta
* &lbrack;Preferências&rbrack; Limpar caminho do cache de preferências redefine para o valor anterior
* &lbrack;Renderizando&brack; Vazamento de memória ao usar o Rastreador de caminho
* &lbrack;Renderização&rbrack; Impedir a exclusão de texturas enquanto ainda podem ser acessadas pelo Vulkan
* &lbrack;Renderização&rbrack; a rotação de Textura não foi convertida de 0-1 para 0-360
* &lbrack;Scripting&brack; Remover classes não existentes da documentação do Python
* &lbrack;Scripting&rbrack; seletedAsset retorna Nenhum se não houver nenhum ativo selecionado
* &lbrack;Ferramentas&rbrack; Redefinir um valor de textura agora para de pintar e limpa a visualização de correção
* &lbrack;UI&rbrack; Não feche as seções no painel de propriedades sempre que algo for ajustado
* &lbrack;UI&rbrack; Rótulo de ajuste de cor exposto invisível ao passar o mouse
* &lbrack;UI&rbrack; Corrigir comportamento responsivo da lista de ativos
* &lbrack;UI&rbrack; Corrigir loop de ligação na dica de ferramenta do AssetItem
* &lbrack;UI&rbrack; Corrigir duplo clique no grupo de predefinições selecionado
* &lbrack;UI&rbrack; Corrigir área de soltar no apresentador de imagens
* &lbrack;UI&rbrack; Corrigir rótulo com um botão para todos os idiomas
* &lbrack;UI&rbrack; Corrigir height de linha para japonês no pop-up de lista de canais
* &lbrack;UI&rbrack; Corrigir sinal onAccepted do campo de comprimento
* &lbrack;UI&rbrack; Corrigir largura pop-up com item de controle esquerdo longo
* &lbrack;UI&rbrack; Corrigir pop-up de visualização em itens de ativo
* &lbrack;UI&rbrack; Corrigir seletor áspero/reflexivo
* &lbrack;UI&rbrack; Corrigir reticências de string
* &lbrack;UI&rbrack; Corrigir problema de truncamento de string
* &lbrack;UI&rbrack; Botão de reinicialização de ajuste do interruptor de correção
* &lbrack;UI&rbrack; Oculta a lista suspensa de Modelos de material quando uma predefinição de exportação personalizada é selecionada
* &lbrack;UI&rbrack; Remover resolução na lista de canais do pop-up de exportação
* &lbrack;UI&rbrack; Redefinir para layout padrão mantém as configurações do visualizador de projeção
* &lbrack;UI&rbrack; Restaurar itens de menu “Editar no Photoshop” e “Editar no Illustrator”

**Removido:**

* &lbrack;UI&rbrack; Remover seção &#39;Aplicado a&#39; para camadas de importação de imagem
* &lbrack;UI&rbrack; Remover dica de ferramenta de ação rápida de abertura automática na primeira inicialização

## Versão 5

### **5.1.3 ÎLE FLOTTANTE**

*(Lançado: 6 De Janeiro De 2026)*

**Adicionado:**

* &lbrack;Captis&rbrack; Exibir um aviso se o protocolo FTP estiver desativado pelo firewall

**Corrigido:**

* &lbrack;Captis&rbrack; A interrupção durante uma captura pode levar a erros
* &lbrack;Captis&rbrack; O download dos resultados no final de uma captura usa muita memória RAM
* &lbrack;Captis&rbrack; Executar um foco automático imediatamente após uma intensidade automática pode levar a erros
* &lbrack;Captis&rbrack; A exibição de resultados de HDR no painel Resumo
* &lbrack;UI&rbrack; Em alguns casos, a caixa de diálogo de pasta no MacOS não seleciona a pasta correta

### **5.1.2 ÎLE FLOTTANTE**

*(Lançado em: 20 de novembro de 2025)*

**Adicionado:**

* &lbrack;Aplicativo&rbrack; Detectar perda de dispositivo gráfico, avisar o usuário e sair normalmente
* &lbrack;Camadas&rbrack; Mensagens aprimoradas ao nivelar camadas
* &preto;Camadas&rbrack; Miniaturas aprimoradas para importação de imagem e camadas achatadas
* &lbrack;Integração&rbrack; Conteúdo de aprendizado atualizado na tela inicial
* &lbrack;Projeto&rbrack; Recupera o último estado salvo da sessão antes do erro fatal
* &lbrack;UI&rbrack; Atualização do ícone do aplicativo

**Corrigido:**

* &lbrack;Aplicativo&rbrack; Inserir um material na pilha de camadas pode levar a uma falha no macOS
* &lbrack;Aplicativo&rbrack; Possível falha em carga pesada no macOS
* &lbrack;Application&brack; Possível falha ao adicionar camadas quando a memória de vídeo estiver cheia
* &lbrack;Aplicativo&rbrack; Possível falha ao abrir um projeto
* &lbrack;Captis&rbrack; Falha se o foco automático for executado logo após a calibração automática de intensidade
* &lbrack;Captis&rbrack; Problemas de confiabilidade e desempenho após a primeira captura
* &lbrack;Captis&rbrack; Acelerações e erros ao copiar arquivos no final de uma captura
* &lbrack;Captis&rbrack; Vazamento de memória pequeno ao consultar informações do dispositivo Captis
* &lbrack;Exportar&rbrack; Os parâmetros expostos de vários controles deslizantes produzem arquivos .sbsar corrompidos
* &lbrack;Camadas&rbrack; O padrão de divisão automática é redefinido para os valores padrão ao alternar os ativos
* &lbrack;Camadas&rbrack; A cor de base personalizada padrão é exibida em vermelho
* &lbrack;Camadas&rbrack; O nivelamento parcial de camadas filho de Clonar Stamp é possível e causa problemas de renderização
* &lbrack;Camadas&rbrack; Possível falha ao ajustar uma pilha de camadas enquanto a renderização está em andamento
* &lbrack;Camadas&rbrack; Erro inesperado na etapa de região de interesse de divisão automática ao alterar canais de origem
* &lbrack;Projeto&rbrack; Miniatura incorreta às vezes ao criar um novo material
* &lbrack;Ações rápidas&rbrack; Algumas ações rápidas têm uma contagem de entrada incorreta
* &lbrack;UI&rbrack; O botão Grupo de ação tem larguras diferentes
* &lbrack;UI&rbrack; O botão Limpar nos campos de texto às vezes dispara a perda de foco
* &lbrack;UI&rbrack; Caixas de combinação e campos de texto são muito grandes
* &lbrack;UI&rbrack; Os ícones e rótulos estão desalinhados
* &lbrack;UI&rbrack; O rótulo do campo Nome está posicionado incorretamente
* &lbrack;UI&rbrack; Os rótulos do botão Ações rápidas estão desalinhados
* &lbrack;UI&rbrack; Os controles deslizantes mostram muitos 0s à direita

**Removido:**

* &preto;Geração de AI&rbrack; Recursos de IA generativa remoção. *Este recurso foi removido do aplicativo e o serviço deixará de funcionar nas versões anteriores do Sampler em 5 de março.*

### **5.1.1 ÎLE FLOTTANTE**

*(Lançado em: 18 de setembro de 2025)*

**Adicionado:**

* &lbrack;Exibição 2D&rbrack; Consegue reduzir mais na exibição 2D para texturas de alta resolução
* &lbrack;Captis&rbrack; Avisa os usuários sobre problemas ao copiar arquivos
* &lbrack;Camadas&rbrack; Ao duplicar uma camada, use um número incremental no nome da nova camada

**Corrigido:**

* &lbrack;Exibição 2D&rbrack; Ao pintar traçados após redefinir todas as propriedades do Carimbo, os traçados criados anteriormente reaparecerão
* &lbrack;Aplicativo&rbrack; “Salvar projeto atual?” o pop-up usa um nome de projeto incorreto
* &lbrack;O aplicativo &rbrack; falha ao sair
* &lbrack;Aplicativo&rbrack; Possível falha
* &lbrack;Application&brack; Às vezes, uma miniatura é gerada com um material incorreto
* &lbrack;Captis&rbrack; Em alguns dispositivos, ao executar uma varredura em alta resolução, o mapa de height fica preto
* &lbrack;Captis&rbrack; O botão “Iniciar captura” não é mais desativado quando nenhum nome de captura está definido e quando uma calibragem está em execução
* &lbrack;Export&rbrack; Ao exportar um arquivo .sbsar, a exportação pode falhar sem que o usuário seja notificado
* &lbrack;Filtros&rbrack; Tela de parâmetros avançados para o filtro de divisão em blocos automáticos às vezes pisca ao ajustar parâmetros
* &lbrack;Filtros&rbrack; Os parâmetros padrão para o filtro de divisão em blocos gráficos produzem artefatos cinzas na saída
* &lbrack;Filtros&rbrack; Às vezes, com entradas de alta resolução, as configurações avançadas do Filtro de divisão em blocos gráficos automático não mostram os pontos de padrão individuais
* &lbrack;Filtros&rbrack; O tamanho do padrão para o parâmetro de divisão em blocos gráficos de tamanho personalizado tem um valor padrão incorreto
* &lbrack;Camadas&rbrack; Problema ocasional de cor com o filtro Divisão em blocos gráficos automático visível principalmente em materiais vermelhos
* &lbrack;Camadas&rbrack; Às vezes, adicionar camadas redefinirá alguns ajustes para o valor padrão
* &lbrack;Tamanho físico&rbrack; A miniatura de ativos com um tamanho físico tem uma escala de height incorreta
* &lbrack;UI&rbrack; Não é possível renomear parâmetros expostos
* O botão de ativação do canal do &lbrack;UI&rbrack; não é quadrado
* &lbrack;UI&rbrack; Se o rótulo de um controle deslizante for muito longo, o botão de redefinição não estará acessível
* &lbrack;UI&rbrack; Pressionar a tecla return ou clicar para não remove o foco dos campos de texto
* &lbrack;UI&rbrack; Às vezes, uma dica de ferramenta indesejada aparece no painel Tamanho físico
* &lbrack;UI&rbrack; A visualização 3D exibe uma malha incorreta ao criar um projeto vazio
* &lbrack;UI&rbrack; Ao expor uma entrada do seletor de cores, seu rótulo desaparece ao passar o mouse
* &lbrack;UI&rbrack; Ao expor parâmetros, o ponto de cor às vezes é posicionado incorretamente

### **5.1.0 ÎLE FLOTTANTE**

*(Lançado em: 7 de agosto de 2025)*

**Adicionado:**

* O tamanho do pincel do &lbrack;Visualização 2D&rbrack; agora se adapta à resolução de textura atual
* &lbrack;Visualização 3D&rbrack; Alternar a escala de exibição nativa para renderização 3D nas preferências
* &lbrack;Atualização do mecanismo de renderização do Application&brack;
* &lbrack;Captis&rbrack; Adicionar a possibilidade de “criar quadrado” durante a visualização
* &lbrack;Captis&rbrack; Detecção automática de tamanho físico
* &preto;Capta&rbrack; Capturar um novo material criará um novo ativo
* &lbrack;Captis&rbrack; Alterar seleção de resolução em menu suspenso para pixel por polegada ou centímetro em vez de resolução de pixel da área máxima
* &lbrack;Captis&rbrack; Ajuda contextual sobre calibração de alinhamento
* &lbrack;Captis&rbrack; Gerar mapa de aspereza
* &lbrack;Captis&rbrack; Avisa o usuário se os arquivos de calibração padrão estiverem ausentes
* &lbrack;Filtros&rbrack; Filtro de divisão automática em blocos gráficos para materiais estruturados e digitalizações
* &lbrack;Filtros&rbrack; Novo filtro Removedor de Dobra
* &lbrack;Filtros&rbrack; Novos recursos dentro do filtro Carimbo de Clonar
* &lbrack;Filtros&rbrack; Novos recursos dentro do filtro Equalizar
* &preto;Camadas&rbrack; Capacidade de nivelar camadas
* &lbrack;Camadas&rbrack; Menu de contexto ao clicar com o botão direito do mouse em uma camada para renomear, duplicar, excluir ou nivelar a camada
* &lbrack;Integração&rbrack; Atualizar conteúdo de telas de Boas-vindas e Novidades
* &lbrack;Desempenho&rbrack; Melhor desempenho ao usar o filtro Corte demarcado
* &lbrack;Desempenho&rbrack; Melhorar o uso de memória para a Visualização 3D
* &lbrack;Desempenho&rbrack; A atualização da visualização 3D é mais rápida
* &lbrack;Tamanho físico&rbrack; Habilitar “exibição com proporção física” ao trabalhar em filtros de Substance quando o Tamanho físico estiver habilitado
* &lbrack;Tamanho físico&rbrack; Ao importar imagens em uma pilha vazia, proponha uma resolução mais coerente com a proporção da imagem
* &lbrack;Ações rápidas&rbrack; 3 novas ações rápidas para processamento de digitalização
* &preto;Script&rbrack; API para nivelar camadas
* &lbrack;Scripting&brack; Obtém o nome de arquivo de cada imagem de uma camada de importação de imagem
* &lbrack;Scripting&brack; Nova função para ativar/desativar um determinado canal de um ativo
* &lbrack;UI&rbrack; Retrabalhe os ícones e botões no painel Camadas para acomodar os novos recursos
* &lbrack;UI&rbrack; Avisar sobre a obsolescência da criação de luz ambiente

**Corrigido:**

* &lbrack;2D View&rbrack; Selecionar &#39;display with physical ratio&#39; pode não funcionar ao usar filtros de Substance
* &lbrack;captura 3D&rbrack; Os arquivos SVG estão listados no seletor de arquivos, mas não são suportados
* O parâmetro de intensidade de emissão do &brack;Visualização 3D&rbrack; nas Configurações do sombreador não funciona
* &lbrack;Visualização 3D&rbrack; Às vezes, a posição da malha está incorreta ao criar um novo ativo
* &lbrack;Visualização 3D&rbrack; Alternar para o traçado de caminho renderiza falhas em hardware não suportado
* &lbrack;O aplicativo &rbrack; trava ao fechar o pop-up de medida manual sem definir um tamanho
* &lbrack;Falha do aplicativo&rbrack;
* &lbrack;Aplicativo&rbrack; Congela no Windows ao exibir a área de trabalho (tecla Windows + D atalho de teclado)
* &lbrack;Aplicativo&rbrack; Possível falha ao alternar o idioma
* &lbrack;Captis&rbrack; Falha quando os dados de visualização não são válidos
* &lbrack;Captis&rbrack; Impossível reduzir totalmente após aumentar o zoom
* &lbrack;Captis&rbrack; Localização ausente em algumas etapas do assistente
* &lbrack;Captis&rbrack; Possível falha ao sair ao usar Captis
* &lbrack;Captis&rbrack; A digitalização não funciona se o dispositivo não tiver arquivos de calibração
* &brack;Filtros&rbrack; A visualização do pincel ao usar o filtro Carimbo de Clonar pode estar incorreta, dependendo da textura e dos tamanhos do pincel
* &lbrack;Filtros&rbrack; Tamanho de saída incorreto após o uso do filtro Escala superior
* &lbrack;Filtros&rbrack; Ícones ausentes para os filtros de Rotação e Estilização do Ambiente
* &lbrack;Filtros&rbrack; A atualização de alguns filtros pode levar à renderização incorreta
* &lbrack;Camadas&rbrack; Primeira renderização incorreta ao mesclar dois materiais
* &lbrack;Camadas&rbrack; O botão para atualizar as camadas mostra “Atualizar tudo” mesmo quando há apenas uma atualização
* &lbrack;Camadas&rbrack; Cálculos desnecessários ao importar imagens na pilha de camadas
* &lbrack;Desempenho&rbrack; Melhorar a manipulação de formatos de mapa normais para reduzir os tempos de renderização
* &lbrack;Tamanho físico&rbrack; A mensagem de medida manual só funciona depois de fazer uma medida automática
* &lbrack;Tamanho físico&rbrack; Resolução de exportação incorreta no pop-up Exportar quando o Tamanho físico está habilitado
* &lbrack;Ações rápidas&rbrack; Localização ausente nos nomes dos ativos gerados
* &lbrack;UI&rbrack; A visualização do ativo ao passar o mouse pode não mostrar
* &lbrack;UI&rbrack; Clicar no botão Redefinir para o valor padrão pode quebrar alguns dos controles
* &lbrack;UI&rbrack; As mensagens de erro não são apagadas ao alternar projetos
* &lbrack;UI&rbrack; Certifique-se de que o nome do material no visor e no painel de propriedades esteja vazio quando não houver nenhum ativo
* &lbrack;UI&rbrack; O botão Redefinir para o valor padrão do parâmetro Ponto de Vista não funciona
* &lbrack;UI&rbrack; Sobreposição do botão Redefinir para valor padrão
* &lbrack;UI&rbrack; Alguns botões não são clicáveis quando um painel é desencaixado
* &lbrack;UI&rbrack; Textura inclinando o parâmetro V parcialmente oculto nas Configurações do visualizador e Visualização 3D

**Removido:**

* &lbrack;captura 3D&rbrack; Remover suporte ao captura 3D
* &lbrack;Aplicativo&rbrack; Remover suporte ao macOS x86

### **AVELÃ 5.0.3**

*(Lançado em: 3 de junho de 2025)*

**Adicionado:**

* &lbrack;Captis&rbrack; Permite dar a um material o mesmo nome de um já existente
* &lbrack;Captis&rbrack; Move mensagens de erro para pop-ups em vez de notificações do sistema
* &lbrack;Filtros&rbrack; Atualizar bordado
* &lbrack;Preferências&rbrack; Adicionar redefinição nas configurações do visualizador e sombreadores
* &lbrack;UI&rbrack; Não apresentar o item de menu “Mostrar localização” nos ativos do projeto

**Corrigido:**

* &lbrack;captura 3D&rbrack; O filtro de pós-processamento de malha não gera os mapas esperados
* A visualização 3D do &lbrack;Visualização 3D&rbrack; não funciona devido à corrupção do cache de sombreador
* &lbrack;Visualização 3D&rbrack; O plano horizontal e a grade ficam verticais quando a cena é Z-up
* &lbrack;Visualização 3D; A malha às vezes desaparece
* &lbrack;Aplicativo&rbrack; Fechar a janela de login na inicialização sem efetuar login às vezes trava o aplicativo
* &lbrack;Application&brack; Falha quando o acesso ao arquivo de configuração de plug-ins é negado
* &lbrack;Aplicativo&rbrack; O material atual não está selecionado quando o projeto é salvo
* &lbrack;Aplicativo&rbrack; Redefinir para o layout padrão define a resolução para 64x64
* &lbrack;O Application&brack; Sampler às vezes trava ao renderizar uma pilha de camadas
* A resolução da exportação do &brack;Export&brack; às vezes é redefinida para 64x64
* &lbrack;Export&rbrack; Às vezes, não é possível exportar arquivos .sbs/.sbsar
* &lbrack;Camadas&rbrack; O botão Adicionar material de base não faz nada quando o material está vazio
* &lbrack;Camadas&rbrack; A divisão em blocos gráficos de Textura é alterada ao duplicar um material
* &lbrack;Tamanho físico&rbrack; A medida automática não funciona se o painel de Tamanho físico foi encaixado antes da importação da imagem
* O plug-in de salvamento automático do &brack;Scripting&brack; está com falha
* &lbrack;UI&rbrack; Espaçamento incorreto na caixa de diálogo Exportar
* &lbrack;UI&rbrack; A animação dos ajustes no controle deslizante não funciona mais
* &lbrack;UI&rbrack; Os controles deslizantes não se encaixam em valores inteiros quando necessário
* &lbrack;UI&rbrack; Alguns menus suspensos são cortados

### **5.0.2 AVELÃ**

*(Lançado em: 22 de abril de 2025)*

**Corrigido:**

* &lbrack;O botão Voltar da página inicial do &amp;aplicativo está quebrado
* &lbrack;Aplicativo&rbrack; O Sampler às vezes não inicia se dados corrompidos de versões anteriores estiverem presentes no disco
* &lbrack;Aplicativo&rbrack; A imagem importada não aparece no visor ou na pilha de camadas
* &lbrack;Captis&rbrack; o campo Endereço IP da Captis permanece vazio mesmo depois de reiniciar o Sampler
* A visualização da câmera do &preto;Captis&rbrack; Live funciona somente quando o idioma do aplicativo está definido como inglês
* &lbrack;Export&brack; Falha durante a exportação &lbrack;Camadas&rbrack; A pintura às vezes não funciona em projetos salvos anteriormente
* &lbrack;Camadas&rbrack; O Sampler às vezes atualiza todas as texturas quando apenas um canal é atualizado
* &lbrack;Camadas&rbrack; Não é possível usar misturas de materiais na pilha de camadas após atualizar para 5.0.x
* &lbrack;Camadas&rbrack; Atualizar um projeto com uma versão anterior do Image to Material (AI) torna o material todo preto
* &lbrack;Camadas&rbrack; Ao tentar importar uma imagem não suportada, o Sampler cria uma camada quebrada
* &lbrack;Scripting&brack; Parte da API Python não funciona com um projeto vazio
* Os itens de menu do &lbrack;UI&rbrack; às vezes transbordam no menu Arquivo

### **5.0.1 AVELÃ**

*(Lançado em: 20 de março de 2025)*

**Adicionado**

* &lbrack;Aplicativo&rbrack; Lista de compatibilidade de driver gráfico atualizada
* &lbrack;Captis&rbrack; Mostra um pop-up quando o uso do HP Z Captis for bloqueado pelas políticas do sistema operacional
* &lbrack;Ações rápidas&rbrack; Explicar por que uma Ação rápida é desativada em uma dica de ferramenta
* &lbrack;UI&rbrack; Estilo da interface da janela do relatório de falhas
* &lbrack;UI&rbrack; Ao copiar para a área de transferência, mostrar uma caixa de informações para dizer que está feito

**Corrigido:**

* &lbrack;O controle deslizante de Exposição do &amp;Visualização 2D; não tem efeito quando a projeção esférica está desativada
* &lbrack;Visualização 2D; Pintar fora da textura cria um traçado descontinuado
* &lbrack;Exibição 2D&rbrack; O botão de exposição não tem dica de ferramenta.
* &lbrack;Visualização 2D; O zoom na lateral de uma imagem não quadrada não segue o mouse
* O &lbrack;captura 3D&rbrack; captura 3D não funciona no Windows 11 24H2
* &lbrack;captura 3D&rbrack; Falha se sairmos do Sampler durante a etapa de reconstrução de malha
* &lbrack;Visualização 3D&rbrack; O tempo de computação às vezes é mostrado como 0ms
* &lbrack;Visualização 3D&rbrack; Ao alterar a projeção de ortográfico para perspectiva, o visor se torna cinza
* &lbrack;Aplicativo&rbrack; Falha na inicialização ao verificar os recursos da GPU
* &lbrack;O aplicativo &rbrack; falha durante a instalação
* &lbrack;Aplicativo&rbrack; Falha ao sair após clicar com o botão direito do mouse em um campo de metadados
* &lbrack;Application&brack; Iluminação do ambiente ausente ao abrir um SBSAR a partir do explorador de arquivos do sistema operacional
* &lbrack;Aplicativo&rbrack; Abrir um .sbsar enquanto o Sampler está em execução altera a configuração de Divisão em Texturas Lado a Lado
* &lbrack;Captis&rbrack; Alguns metadados podem não ser transferidos entre as etapas de captura
* &lbrack;Captis&rbrack; O nome do ativo criado não é o inserido no campo de metadados
* &lbrack;Content&brack; Exemplo de projeto solicita uma atualização de filtro, mas já está atualizado
* &lbrack;Filtros&rbrack; O filtro de ajuste Normal/height não tem ícone
* &lbrack;Camadas&rbrack; Não é possível alterar imagens em uma camada de importação de imagem
* &lbrack;Camadas&rbrack; Falha ao usar o filtro Aumento
* &lbrack;Camadas&rbrack; Atualizar um projeto com uma Imagem antiga para Material torna o material todo preto
* &lbrack;Renderização&rbrack; Ajustar uma pilha de camadas imediatamente após criar um ativo interrompe a renderização
* &lbrack;Scripting&brack; O plug-in de salvamento automático falha quando não há ativo no projeto
* &brack;Ferramentas&rbrack; O valor do tamanho do pincel está ausente na barra de ferramentas Pincel
* &lbrack;UI&rbrack; Alterar o idioma do aplicativo não atualiza alguns dos rótulos na tela inicial
* &lbrack;UI&rbrack; Pressionar Escape ou Enter nos campos de texto do controle deslizante não perderá o foco
* &lbrack;UI&rbrack; No painel Propriedades, o botão Redefinir tudo e o rótulo do nome do ativo se sobrepõem
* &lbrack;UI&rbrack; Problemas ao encaixar e desencaixar painéis
* &lbrack;UI&rbrack; A rolagem em um painel de sobreposição também rolará na janela subjacente
* &lbrack;UI&rbrack; Alternar para a exibição de Lista na seção Projetos Recentes da Tela Inicial não funciona
* &lbrack;UI&rbrack; Ícone do botão do modo de exibição do Visor sempre mostra 2D/3D

### **5.0.0 AVELÃ**

*(Lançado em: 20 de fevereiro de 2025)*

**Adicionado**

* &lbrack;Integração&rbrack; Nova Página Inicial com acesso rápido a conteúdo de aprendizagem, projeto de amostra, ações rápidas e projetos recentes.
* &brack;Integração&rbrack; Comece rapidamente com as novas Ações rápidas, acessíveis na página inicial e no painel dedicado
* &lbrack;Integração&rbrack; &lbrack;Conteúdo&rbrack; Ações rápidas são fluxos de trabalho predefinidos que preenchem a pilha de camadas com as camadas mais usadas
* &lbrack;Integração&rbrack; Possibilidade de criar um novo projeto por meio de um novo menu Início rápido, por meio de ações rápidas ou Projeto personalizado
* &lbrack;Integração&rbrack; Possibilidade de criar um projeto vazio diretamente da página inicial através de um botão dedicado
* &lbrack;Visualização 3D&rbrack; Novo rasterizador e rastreador de caminho avançados que trazem novos recursos de renderização (propriedades como revestimento, brilho, translucidez, dispersão de subsuperfície) e consistência visual entre o ecossistema de Substance
* As configurações do visualizador do &brack;Visualização 3D&rbrack; agora podem ser acessadas diretamente na visualização 3D
* &lbrack;Visualização 3D&rbrack; Possibilidade de salvar um instantâneo de renderização na área de transferência ou em arquivos
* &lbrack;Visualização 3D; Exibir uma grade para visualizar a origem da cena
* &lbrack;Visualização 3D; Habilita o plano do solo a capturar sombras e reflexos
* &lbrack;Visualização 3D; Controla o quão reflexivo e opaco é o seu plano terrestre
* &preto;captura 3D; Malha de posição no chão
* &lbrack;Aplicativo&rbrack; Verificar compatibilidade de hardware na inicialização do aplicativo
* A janela Relatório de falhas do &lbrack;Application&brack; agora abre logo após ocorrer uma falha
* &lbrack;Content&brack; Abrir um projeto de amostra para começar facilmente
* &lbrack;Export&rbrack; Exportar sombreador de Adobe Standard Material em arquivos USD
* &lbrack;Generative AI&rbrack; Marque a marca “Não inferir” ao usar uma imagem como entrada em fluxos de trabalho de Imagem para Textura
* &lbrack;Projeto&rbrack; As miniaturas são armazenadas no arquivo de projeto para uma abertura mais rápida dos projetos
* &lbrack;Projeto&rbrack; Configuração nas preferências para armazenar dados do cache dentro do arquivo de projeto, com modos diferentes (sem cache, cache leve, cache cheio)
* &lbrack;Scripting&rbrack; &lbrack;Breaking change&rbrack; Migração do Qt para o Qt6.15 - afeta a compatibilidade dos plug-ins existentes
* &lbrack;Scripting&brack; Os plug-ins padrão e a pasta de scripts agora estão na pasta Documentos
* &lbrack;Scripting&brack; Nova interface para plug-ins, visando a consistência visual com os painéis principais do Sampler
* Exemplos de plug-in do &brack;Scripting&rbrack; Access 2 para descobrir os recursos do plug-in do Sampler
* &lbrack;Scripting&brack; Nova função open_3d_catpure()
* &lbrack;Scripting&brack; Ao inserir uma camada, controle se ela é inserida acima ou abaixo da posição de destino

**Corrigido:**

* &lbrack;captura 3D&rbrack; Falha se a Captura de Objeto não puder ser iniciada no macOS
* &lbrack;O aplicativo &rbrack; falha ao sair
* &lbrack;Aplicativo&rbrack; trava ao sair ao adicionar ativos ao painel do projeto
* &lbrack;Aplicativo&rbrack; Renomear um ativo do projeto não funciona a menos que você pressione enter
* &lbrack;Aplicativo&rbrack; As entradas de menu Desfazer e Refazer não estão desativadas quando deveriam estar
* &lbrack;Ativos&rbrack; Não é possível excluir ativos da seção Todas as Bibliotecas do painel Ativos
* &lbrack;Content&brack; Criador de atlas - Usar mapa de opacidade existente, se presente
* &lbrack;Content&brack; Combinar de ID de Cor - Corrigir a escolha de cores na cor base
* &lbrack;Camadas&rbrack; Evitar cálculos inúteis ao usar geradores
* &lbrack;Camadas&rbrack; Ajustar um gerador pode levar ao acionamento de muitos computadores
* &lbrack;Desempenho&rbrack; Melhorar o gerenciamento de memória da GPU
* &lbrack;Performance&rbrack; O cache de renderização não pode ser usado ao reiniciar o aplicativo
* &lbrack;Recursos&rbrack; Os arquivos somente leitura não estão visíveis no painel Ativos
* &lbrack;Scripting&brack; Permitir a reutilização de uma camada após adicionar outra camada
* &lbrack;Scripting&brack; Alterar a estrutura de pilha de camadas várias vezes em um script pode falhar

**Removido:**

* &lbrack;Aplicativo&rbrack; Remove o suporte para arquivos de imagem .dng e .nef

## Versão 4

### **4.5.2 GRUYERE**

*(Lançado Em: 07 De novembro De 2024)*

**Corrigido:**

* &lbrack;Content&brack; Filtros de mesclagem de Corte, Bordado e Height

### **4.5.1 GRUYERE**

*(Lançado Em 30 De julho De 2024)*

**Corrigido:**

* &preto;Camadas&rbrack; Pintar máscaras em tons de cinza não funciona, afetando ferramentas como Carimbo de Clonar, Distorção de Tinta, Preenchimento sensível ao conteúdo

### **4.5.0 GRUYERE**

*(Lançado Em 18 De julho De 2024)*

**Adicionado**

* &lbrack;Interoperabilidade&rbrack; Enviar materiais para UE5, Blender, Maya, 3DsMax Unity
* &lbrack;Content&brack; Nova categoria de gerador de textura - Gradientes
* &lbrack;Content&brack; Ferramenta HDRI - novo filtro de rotação Ambiente

**Corrigido:**

* &lbrack;Parâmetros expostos&rbrack; A exposição de valores de entrada .sbsar não funciona
* &lbrack;Camadas&rbrack; a Cor de base fica vermelha com imagens em tons de cinza
* &lbrack;Renderização&rbrack; as imagens em Tons de Cinza usadas em canais de cor têm espaço de cor incorreto
* &lbrack;Scripting&brack; Usar uma predefinição de exportação às vezes não exporta os canais esperados
* &lbrack;Content&brack; Dirt - Aplicar um filtro de Dirt sobre a Imagem para o Material gera um normal preto
* &lbrack;Content&rbrack; Relevo - A escala de um padrão no filtro de relevo não é linear entre 0 e 1
* &lbrack;Content&brack; Torne-o lado a lado - Consistência normal e de height aprimorada

### **4.4.1 FONDUE**

*(Lançado Em: 6 De junho De 2024)*

**Corrigido:**

* O filtro de Dirt &lbrack;Content&brack; está ausente
* &lbrack;O erro de rede do AI&rbrack; generativo às vezes ocorre ao usar Imagem para Textura

### **4.4.0 FONDUE**

*(Lançado Em 23 De maio De 2024)*

**Adicionado:**

* O cache do &brack;Application&brack; agora está armazenado em uma subpasta separada
* &preto;Geração de AI&rbrack; Imagem para Textura (Beta)
* &Preta;Geração de AI&rbrack; Texto com Padrão (Beta)
* &Preenchimento;Geração de AI&rbrack; Texto para Textura (Beta)
* &lbrack;Scripting&brack; Os ativos agora têm uma propriedade &#39;resource&#39;
* As camadas do &brack;Scripting&brack; agora têm uma propriedade &#39;output_usages&#39;

**Corrigido:**

* &lbrack;Aplicativo&rbrack; Falha ao abrir arquivo de projeto corrompido
* &lbrack;Aplicativo&rbrack; Falha quando o projeto contém ativos corrompidos
* &lbrack;Aplicativo&rbrack; Falha ao desconectar um monitor no Windows
* &lbrack;Aplicativo&rbrack; Ícone de aplicativo incorreto na barra de tarefas do Windows
* &lbrack;Aplicativo&rbrack; A corrupção do arquivo de configuração principal pode levar à exclusão de arquivos
* Os Painéis do &Preenchimento;Aplicativo&Rbrack; aparecem na frente dos pop-ups
* &lbrack;Os geradores de Textura do Content&brack; possuem miniaturas desfocadas
* &lbrack;Export&brack; O canal de Opacidade gerado a partir de uma imagem importada é interrompido ao exportar um arquivo .sbs/.sbsar
* &lbrack;Filtros&rbrack; A ampliação pode falhar dependendo de suas camadas de entrada
* &lbrack;Generative AI&rbrack; Possíveis falhas ao receber resultados inesperados do serviço
* &lbrack;Scripting&rbrack; Falha ao carregar automaticamente um plug-in a partir de uma variável de ambiente
* &lbrack;Scripting&rbrack; Possível falha ao atribuir Uso de Saída com a API

### **4.3.3 EMPANADA**

*(Lançado Em 26 De março De 2024)*

**Adicionado:**

* &lbrack;captura 3D&rbrack; Novos parâmetros UV automáticos avançados durante o processo de postagem
* &lbrack;Filtros&rbrack; Filtro perfurado: capacidade de inverter e alterar o tamanho do padrão personalizado

**Corrigido:**

* A Cor de base do &lbrack;captura 3D&rbrack; pode estar incorreta no macOS
* &lbrack;captura 3D; Falha ao processar uma nova versão
* &lbrack;captura 3D; A etapa de Pós-processo pode falhar no macOS
* &lbrack;captura 3D; A camada de Transformo Mesh pode levar à renderização incorreta
* &lbrack;Aplicativo&rbrack; Falha ao iniciar o Sampler enquanto uma instância anterior ainda está exportando
* &lbrack;Aplicativo&rbrack; o Sampler não responde por um momento quando iniciado pela primeira vez
* O mapa de Ângulos de anisotropia do &brack;Export&brack; não é exportado
* &lbrack;Filtros&rbrack; Adicionar um tecido à pilha de camadas pode causar um travamento
* &lbrack;Filtros&rbrack; Adicionar um Relevo à pilha de camadas pode causar um travamento
* &lbrack;Filtros&rbrack; O Preenchimento sensível ao conteúdo falha ao usar imagens de 32 bits
* &lbrack;Filtros&rbrack; Relevo: a opacidade das camadas abaixo não é totalmente substituída
* &lbrack;Filtros&rbrack; Preenchimento: o modo Combinar não funciona no Designer e no Painter
* &lbrack;Filtros&brack; Bordado: a seleção automática de cores está corrompida
* &lbrack;Preferências&rbrack; Impedir a definição de um caminho não compatível para o captura 3D Cache
* &lbrack;Preferências&rbrack; A preferência Formato normal não funciona
* &lbrack;Scripting&brack; Os parâmetros de canais de Asset.export_material diferenciam maiúsculas de minúsculas

### **4.3.2 EMPANADA**

*(Lançado Em 22 De fevereiro De 2024)*

**Corrigido:**

* &lbrack;Aplicativo&rbrack; Salvar um projeto em um compartilhamento de rede no Windows corrompe o arquivo de projeto

### **4.3.1 EMPANADA**

*(Lançado Em 15 De fevereiro De 2024)*

**Corrigido:**

* &lbrack;captura 3D&rbrack; Falha quando arquivos de imagem se tornam inacessíveis durante a geração de máscaras em lote
* &lbrack;Export&brack; Exportar um material com Cortar ou relativo à camada de política de entrada fornece resultados inválidos
* &lbrack;Camadas&rbrack; Falha rara ao renderizar uma pilha de camadas
* &lbrack;Filtros&brack; Bordado - Corrigir problema ao usar entrada de material no MacOS
* &lbrack;Filtros&rbrack; Estilização - Suporte a Geradores de Textura
* &lbrack;Filtros&rbrack; Padrão - Corrigir a nomeação de parâmetros
* &lbrack;Localization&rbrack; “Salvar como...” na janela informações de hardware, no menu ajuda, está aparecendo deslocalizado

### **4.3.0 EMPANADA**

*(Lançado Em 25 De Janeiro De 2024)*

**Adicionado**

* &lbrack;Assets&rbrack; Novo tipo de ativo: Geradores de textura
* &lbrack;Ativos&rbrack; Novos materiais incluídos nos Ativos iniciais
* &lbrack;Ativos&rbrack; Novo seletor de ativos para parâmetros de imagem no painel Propriedades
* &lbrack;Ativos&rbrack; Arraste e solte Geradores de textura do painel Ativos para os seletores de imagem no painel Propriedades
* &lbrack;Assets&rbrack; Arrastar e soltar Geradores de Textura do explorador de arquivos do sistema operacional
* &lbrack;Ativos&rbrack; Os filtros podem sugerir o ajuste de geradores por meio de uma tag de usuário na entrada da imagem
* &lbrack;Assets&rbrack; Os Geradores de Textura podem definir qual filtro deve sugerir através de uma tag de usuário
* &lbrack;Content&brack; Novo filtro de Corte de Perspectiva
* &lbrack;Content&brack; Novo filtro de estilização
* &preto;Content&brack; Modo de mesclagem no Filtro de preenchimento
* &lbrack;Content&brack; Filtro de bordado atualizado
* &lbrack;Content&brack; Filtro de quebra de pintura atualizado
* &lbrack;Content&brack; Atualizado todos os filtros para suportar Geradores de Textura
* &lbrack;Camadas&rbrack; Capacidade de escolher um canal de saída do Gerador de Textura ao adicioná-lo à pilha de camadas
* &lbrack;Camadas&rbrack; Capacidade de listar e aplicar facilmente predefinições em Geradores de textura
* &lbrack;Camadas&rbrack; Exibir uma visualização do Gerador de Textura nos seletores de imagem
* Os parâmetros do Gerador de textura do &brack;Layers&brack; podem ser expostos e exportados
* &lbrack;Camadas&rbrack; Atribui o uso de Cor Base ao importar uma única imagem com o Modelo de Criação de Importação de Textura
* &lbrack;Camadas&rbrack; Feedback ao tentar arrastar e soltar arquivos incompatíveis em seletores de imagem no painel Propriedades
* &lbrack;Camadas&rbrack; Gerar um canal de opacidade a partir do canal alfa de uma imagem importada
* &lbrack;Camadas&rbrack; A imagem para material (AI) é mais rápida de calcular ao alterar sua categoria
* &lbrack;Camadas&rbrack; Selecione a camada mais relevante depois que um Modelo de criação for usado
* &lbrack;Camadas&rbrack; Os widgets de posição agora podem ser ajustados com um controle deslizante no grupo Parâmetros avançados
* &preto;Exportar&rbrack; Exibir uma porcentagem na fila em vez de números brutos
* &lbrack;Interoperabilidade&rbrack; O canal de Opacidade agora é reconhecido como canal alfa ao enviar para o Painter
* &lbrack;Aplicativo&rbrack; Novo diálogo para exibir e salvar informações de hardware
* &lbrack;Aplicativo&rbrack; Nova preferência para alterar a escala de height padrão para cada projeto
* &Preenchimento;Aplicativo&Rbrack; Melhorar a exibição de ativos desatualizados
* &brack;Scripting&brack; Novas funções asset.documentResolution() e asset.setDocumentResolution()
* &lbrack;Scripting&brack; Nova função select_asset()
* &lbrack;Scripting&brack; API Python para Geradores de Textura
* &brack;Scripting&brack; get_project_assets() agora retorna objetos 3D
* &lbrack;UI&rbrack; O tamanho da miniatura do ativo pode ser alterado no painel Ativos
* &lbrack;UI&rbrack; Ícones de exibição do visor atualizados

**Corrigido:**

* &lbrack;O zoom com a roda do mouse está bloqueado em 244%
* &lbrack;Application&brack; Falha no início ao inicializar a API gráfica
* &lbrack;Aplicativo&rbrack; Falha se o nome do projeto contiver o caractere #
* &lbrack;Aplicativo&rbrack; Possível falha ao abrir um projeto antigo
* &lbrack;Aplicativo&rbrack; A reabertura do projeto atual pode levar a uma falha
* &lbrack;Aplicativo&rbrack; Algumas alterações do projeto não são registradas e são perdidas sem aviso ao fechar o projeto, se não forem salvas
* &lbrack;Export&brack; .sbs/.sbsar problemas de exportação ao usar vários arquivos com o mesmo nome
* &lbrack;Export&brack; Espaço de cor incorreto para imagens em tons de cinza exportadas no arquivo .sbs/.sbsar
* &lbrack;Filtros&rbrack; Problemas de comportamento de mesclagem de opacidade
* &lbrack;Camadas&rbrack; arquivos .svg às vezes não são renderizados na resolução correta
* &lbrack;Desempenho&rbrack; Alguns salvamentos de projeto em disco são desnecessários
* &lbrack;Projeto&rbrack; Importar um projeto antigo não carrega predefinições associadas
* &lbrack;Scripting&brack; Não é possível obter os parâmetros da primeira camada inserida
* &lbrack;UI&rbrack; O pop-up de visualização ao passar o mouse sobre um ativo pode aparecer no local ou na tela errada
* &lbrack;UI&rbrack; Os painéis desencaixados ficam visíveis e podem ser usados na tela de boas-vindas

### **4.2.2 DORAYAKI**

*(Lançado Em: 5 De dezembro De 2023)*

**Adicionado:**

* O &lbrack;captura 3D&rbrack; captura 3D agora está 5% a 10% mais rápido no Windows
* &lbrack;captura 3D&rbrack; Melhorar limpeza de malha antes da dizimação
* &lbrack;Engine&rbrack; Atualize o Substance Engine para a versão 9.0.3
* &lbrack;Camadas&rbrack; Preenchimento sensível ao conteúdo: atualização upstream, várias correções de caso de uso e suporte a Linux

**Corrigido:**

* &lbrack;captura 3D&rbrack; Clicar em “Voltar” após o alinhamento e “Avançar” não atualiza a nuvem de pontos
* &lbrack;captura 3D&rbrack; Malha exibida com furos após ser adicionada ao projeto
* &lbrack;Aplicativo&rbrack; Falha ao sair do modo de tela cheia após uma Captura 3D
* &lbrack;Application&brack; Falha com arquivos de imagem criados
* &lbrack;Aplicativo&rbrack; Se estiver em “Todas as bibliotecas” ao sair do Sampler, o painel Ativos ficará vazio na reinicialização
* &lbrack;Aplicativo&rbrack; Vazamento de memória ao exportar material
* &lbrack;Aplicativo&rbrack; Abrir um projeto salvo com versões anteriores do Sampler pode levar a uma falha
* O &brack;Aplicativo&rbrack; pode travar ao falhar na conversão de malhas 3D
* &lbrack;Aplicativo&rbrack; Falha silenciosa ao abrir um .sbsar enquanto o Sampler está em execução
* &lbrack;Export&rbrack; Falha ao exportar um arquivo .sbs/.sbsar com um uso personalizado
* &lbrack;Export&brack; Mapas normais exportados são sempre DirectXs, independentemente da configuração do usuário
* &lbrack;Exportar&rbrack; exportar um objeto 3D para um arquivo FBX no macos não funciona
* Inconsistências do &brack;Export&brack; ao exportar uma Pilha de camadas com um filtro de Bordado como um arquivo .sbs/.sbsar
* &lbrack;Export&rbrack; Às vezes, exportar arquivos .sbs/.sbsar não funciona
* &lbrack;Export&brack; Às vezes, ao exportar um arquivo .sbs/.sbsar, as imagens não têm a profundidade de bits correta
* &lbrack;Camadas&rbrack; Tornar uma camada de respingo invisível renderiza seu primeiro filho
* &lbrack;Camadas&rbrack; Falha ao carregar a máscara na camada Brilho/Contraste
* &lbrack;Camadas&rbrack; Mensagens de erro enganosas são exibidas após a exclusão da camada
* &lbrack;Camadas&rbrack; Possível falha ao fazer downgrade de um ativo
* &lbrack;Camadas&rbrack; Algumas saídas não são conectadas a entradas, a menos que o uso seja forçado no painel Configurações do canal
* O menu suspenso da camada de referência do &lbrack;Tamanho físico&rbrack; pode ser redefinido por engano
* &lbrack;UI&rbrack; Os ícones de importação de informações de modelos precisam de atualização
* &lbrack;UI&rbrack; A dica de atalho do visor aparece sempre que o layout do visor é alterado

### **4.2.1 DORAYAKI**

*(Lançado Em 21 De setembro De 2023)*

**Adicionado:**

* &lbrack;Content&brack; Imagem para Material - Melhorar a geração de microdetalhes em mapas normais
* &lbrack;Content&brack; Imagem para material - Novo parâmetro de intensidade de deleite
* &lbrack;Camadas&rbrack; As imagens podem ser adicionadas nas camadas de importação de imagem
* &lbrack;Camadas&rbrack; As imagens podem ser removidas nas camadas de importação de imagem
* &lbrack;Camadas&rbrack; Camadas inválidas agora podem ser excluídas
* &lbrack;2D View&rbrack; Shift+C atalho para voltar os canais
* &lbrack;captura 3D; Exibir uma caixa de informações de aviso quando o usuário importar menos de 20 imagens
* &lbrack;Aplicativo&rbrack; Novas preferências para definir o valor padrão da divisão em blocos gráficos da textura do material
* &lbrack;Integração&rbrack; Interface do usuário do tutorial atualizada para Imagem para material (IA) e Aumento
* &lbrack;Scripting&rbrack; API captura 3D: DatasetInfo tem mais dados quando Capture3dState está definido como alinhado
* &lbrack;Scripting&brack; Novo argumento select_asset para create_asset(). Novas funções: wait_for_computation() e clear_render_cache()

**Corrigido:**

* &lbrack;Camadas&rbrack; Falha quando a região de corte é muito pequena
* &lbrack;Camadas&rbrack; Falha ao adicionar ou ajustar o filtro Corte demarcado
* &lbrack;Camadas&rbrack; Criar um quadrado na região de corte leva a uma resolução de saída de material incorreta
* &lbrack;Camadas&rbrack; As saídas às vezes desaparecem quando várias camadas estão desativadas
* &lbrack;Camadas&rbrack; O cache de renderização pode não ser invalidado corretamente com os filtros Imagem para material (AI) e Aumento
* &lbrack;Camadas&rbrack; Não é possível adicionar o filtro de Ampliação ao selecionar “Não mostrar esta mensagem novamente” no pop-up de aviso
* &lbrack;Camadas&rbrack; Não é possível restaurar a imagem no filtro Bordado depois de modificada
* &lbrack;Export&brack; A resolução normal de mapas exportada muda ao alterar o formato normal
* &lbrack;Export&brack; Remover o sufixo de nome de arquivo “\_environment” ao exportar um ambiente
* &lbrack;Export&brack; Não é possível exportar um arquivo .sbsar quando há uma camada de Transformação de distorção na pilha de camadas
* &lbrack;O modo de exibição 2D&rbrack; “Ajustar à tela” não funciona quando a resolução é alterada
* &lbrack;Aplicativo&rbrack; Após fechar a janela do aplicativo durante a computação, o processo do aplicativo ainda poderia estar em execução
* &lbrack;O aplicativo &rbrack; falha ao sair
* &lbrack;Aplicativo&rbrack; Invalidar o cache de renderização ao alternar as redes neurais aceleradas por GPU
* &lbrack;Scripting&brack; nomear um plug-in como um nome de painel existente causa comportamentos inesperados
* &lbrack;UI&rbrack; Clicar em um item com uma dica fará com que a dica desapareça até reiniciar
* O valor da escala de Heights do &lbrack;UI&rbrack; pode mudar ao alternar ativos
* &lbrack;UI&rbrack; Margem incorreta em caixas de combinação

### **4.2 DORAYAKI**

*(Lançado Em: 05 De setembro De 2023)*

**Adicionado:**

* &lbrack;Content&rbrack; Filtros de imagem para material (IA) e Delighter extremamente aprimorados
* &lbrack;Content&brack; Novo filtro de Ampliação
* &lbrack;Content&brack; O filtro Cortar agora tem resolução de saída dinâmica.
* &preto;Modelo de criação de material&rbrack; Adicionar configuração de tamanho do documento.
* &preto;Modelo de criação de material&rbrack; Novo botão de alternância “Adicionar um corte”.
* &lbrack;Modelo de criação de material&rbrack; Novo alternador de “Aumentar material”
* &preto;Modelo de criação de material&rbrack; Exibir tamanho da imagem importada
* &preto;Modelo de criação de material&rbrack; Fornecer feedback quando algumas imagens importadas não puderem ser usadas
* &preto;Modelo de criação de material&rbrack; Avisar quando os tamanhos das imagens forem inconsistentes
* &lbrack;Modelo de criação de material&rbrack; Novos avisos e dicas de ferramentas
* &lbrack;Camadas&rbrack; Exibe a resolução das camadas na pilha de camadas
* &lbrack;Camadas&rbrack; A resolução de computação da camada agora pode ser definida como Tamanho do documento ou Tamanho de entrada
* &preto;Camadas&rbrack; Mostrar a resolução das camadas na pilha de camadas
* &lbrack;Camadas&rbrack; Alterne uma política de resolução de camada para Documento ou Entrada de camada quando aplicável
* &lbrack;Layers&brack; Avisa o usuário quando um filtro de Ampliação é adicionado manualmente e fornece alguma documentação
* &lbrack;Camadas&rbrack; Avisar o usuário ao fazer um upscale linear e se oferecer para usar o filtro Upscale
* &lbrack;Camadas&rbrack; Computar uma camada de Imagem para material (AI) agora pode ser cancelada mais rapidamente, para melhorar os tempos de renderização ao ajustar a pilha de camadas
* &lbrack;Camadas&rbrack; Computar uma camada em upscale agora pode ser cancelado mais rapidamente, para melhorar os tempos de renderização ao ajustar a pilha de camadas
* &lbrack;Export&brack; Permitir substituição de resolução de texturas exportadas
* &lbrack;Export&brack; Os canais para exportar a lista agora estão ordenados
* &lbrack;Export&brack; Exibir resolução do canal nos canais para exportar lista
* &lbrack;Application&brack; Nova preferência para ativar ou desativar redes neurais aceleradas por GPU
* &lbrack;UI&rbrack; Melhorias nas listas suspensas de resolução
* &lbrack;UI&rbrack; Novos ícones para os filtros Transformação em malha, Pós-processo em malha e Entrelinha
* &lbrack;UI&rbrack; Renomeie o painel “Compartilhar” para “Exportar”
* &lbrack;Scripting&brack; Adicionar suporte de resolução de saída de camada à API de exportação
* &lbrack;Scripting&rbrack; Adicionado Corte, Ampliação e Tamanho do documento à API de importação de imagem
* &lbrack;Integração&rbrack; Novos tutoriais
* &lbrack;Integração&rbrack; Atualizar conteúdo de telas de Boas-vindas e Novidades
* &lbrack;Engine&rbrack; Atualização Substance Engine para a versão 9.0.1

**Corrigido:**

* &lbrack;captura 3D&rbrack; Melhorar a nomenclatura das opções de Precisão nos parâmetros de configuração de Alinhamento
* &lbrack;Aplicativo&rbrack; Importar imagens com um não múltiplo de 16 dimensões pode levar a um travamento
* &lbrack;Aplicativo&rbrack; Falha ao duplicar um ativo no painel Projeto
* &lbrack;Aplicativo&rbrack; Falha ao alternar ativos no painel Projeto
* &lbrack;Content&brack; Pintar uma máscara personalizada para o filtro Snow não funciona corretamente
* &lbrack;Parâmetros expostos&rbrack; As alterações dos parâmetros expostos podem ser perdidas ao alternar os materiais
* &lbrack;Interoperabilidade&rbrack; Enviar um material do painel Exportar pode levar a um travamento
* &lbrack;Camadas&rbrack; O Preenchimento sensível ao conteúdo pára de ser computado ao alternar de uma única entrada de imagem para uma entrada de material
* &lbrack;Camadas&rbrack; Falha após duplicar uma Iluminação do ambiente que contém um material
* &lbrack;Camadas&rbrack; A camada de importação de imagem exibe um nome de imagem incorreto no painel Propriedades se o arquivo de imagem tiver sido renomeado
* &lbrack;Camadas&rbrack; Às vezes, um ícone giratório é exibido em uma camada inativa
* &lbrack;Camadas&rbrack; Às vezes, alterar o uso de saída de uma imagem em uma camada de importação de imagem não funciona
* &lbrack;Camadas&rbrack; Erros de digitação na janela Modelo de criação
* A dica de ferramenta de integração do visor 3D &brack;UI&rbrack; tem problemas de foco
* &lbrack;UI&rbrack; O nome da imagem poderá estourar se o nome do arquivo for muito longo
* &lbrack;UI&rbrack; Pequenos problemas de layout da barra de ferramentas do pincel ao usar a borracha
* &lbrack;UI&rbrack; As strings estão truncadas em alguns idiomas no painel Configurações do visualizador
* &lbrack;UI&rbrack; Enquanto o pop-up da dica de ferramenta do visor é exibido, pressionar “space” cria um novo projeto

### **4.1.2 CANNOLI**

*(Lançado: 20 de junho de 2023)*

**Corrigido:**

* &lbrack;Camadas&rbrack; Vazamento de memória ao ajustar materiais e filtros de Substance, causando falhas

### **4.1.1 CANNOLI**

*(Lançado: 06 De junho De 2023)*

**Adicionado**

* &lbrack;Engine&rbrack; Atualização Substance Engine para a versão 9.0
* &lbrack;Interoperabilidade&rbrack; Enviar objetos 3D para o Stager e Painter

**Corrigido:**

* &lbrack;Os aplicativos do captura 3D&rbrack; travam quando o captura 3D falha
* &lbrack;captura 3D; Falha quando uma imagem não pode ser carregada
* &lbrack;captura 3D&rbrack; Falha ao atingir a etapa de Reconstrução de malha
* &lbrack;captura 3D&rbrack; Falha ao redimensionar a caixa delimitadora
* &lbrack;captura 3D&rbrack; A importação de máscaras seguindo a convenção não atribui a máscara corretamente
* &lbrack;captura 3D; A renderização falha ao ajustar a caixa delimitadora
* &lbrack;captura 3D&rbrack; Alternar entre a versão e alternar as opções de renderização durante o processo de Captura 3D é lento
* &lbrack;captura 3D&rbrack; Alternar entre versões durante a etapa de Pós-processamento às vezes é interrompido
* &lbrack;Application&brack; Falha na inicialização
* &lbrack;Aplicativo&rbrack; Falha ao duplicar um material renomeado
* &lbrack;Aplicativo&rbrack; Falha ao abrir um projeto .alch legado sem sua pasta de dependência
* &lbrack;Aplicativo&rbrack; Falha ao conectar/desconectar uma tela, o computador entra em suspensão ou é acessado remotamente
* &lbrack;Aplicativo&rbrack; Falha e vazamentos de memória relacionados ao gerenciamento de ativos não persistentes
* &lbrack;Export&brack; A escolha do formato de material para tipos de arquivo de objeto 3D que incorporam ou fazem referência a texturas deve ser desativada
* &lbrack;Export&brack; Falha se algo der errado durante a exportação de Objeto 3D
* &lbrack;Export&brack; Falha ao exportar um arquivo .sbs/.sbsar
* &lbrack;Export&brack; Falha ao importar predefinição personalizada que tem o mesmo Rótulo, mas não o mesmo nome de arquivo
* &lbrack;Export&brack; Exportar uma iluminação do ambiente para um arquivo .sbs/.sbsar às vezes não funciona
* &lbrack;Export&rbrack; A exportação Gltf/Glb codifica as texturas na base64
* &lbrack;O campo de texto Nome do Export&brack; não funciona ao focar novamente
* &lbrack;Export&brack; Preservar divisão em blocos gráficos não funciona ao exportar uma camada de Imagem para material (alimentada por IA) para um arquivo .sbs/.sbsar
* &lbrack;Export&brack; Ao exportar arquivos gltf e substituir, a lista de arquivos a serem substituídos não está correta
* &lbrack;Parâmetros expostos&rbrack; A propagação aleatória não funciona em arquivos .sbs/.sbsar exportados
* &lbrack;Camadas&rbrack; O Preenchimento sensível ao conteúdo às vezes trava quando adicionado pela segunda vez
* &lbrack;Camadas&rbrack; Falha ao calcular uma pilha de camadas
* &lbrack;Camadas&rbrack; O cache de disco de Imagem para material (AI) não funciona
* &lbrack;Camadas&rbrack; Possível falha ao ajustar uma camada
* &lbrack;Desempenho&rbrack; Vazamentos de memória
* &lbrack;Projeto&rbrack; Falha ao salvar um projeto
* &lbrack;Projeto&rbrack; Importar o mesmo projeto duas vezes seguidas duplica os ativos
* &lbrack;UI&rbrack; Botões arredondados com apenas um ícone não são renderizados corretamente

### 4.1.0 Cannoli

*(Lançado: 28 De março De 2023)*

**Adicionado:**

* &lbrack;Content&brack; Novo filtro de Bordado
* &lbrack;Content&brack; Novo filtro de Distorção de Tinta
* &lbrack;UI&rbrack; Adicionar opção de exportação no menu Arquivo
* O botão Voltar do &lbrack;captura 3D&rbrack; agora está disponível na etapa de alinhamento
* &lbrack;captura 3D&rbrack; Imagens Manipular orientação EXIF do JPEG
* &lbrack;captura 3D&rbrack; Script - Nova propriedade dataset_info.camera
* &lbrack;captura 3D&rbrack; Adicionar suporte a Linux (consulte a documentação)
* &lbrack;captura 3D&rbrack; Verificar o acesso de leitura das imagens importadas
* &lbrack;Integração&rbrack; Aprender - 2 novos tutoriais (Bordado e Distorção de Tinta)
* &lbrack;Integração&rbrack; Atualizado conteúdo Novidades

**Corrigido:**

* &lbrack;captura 3D; Manter posição da câmera ao alterar a versão
* &lbrack;captura 3D&rbrack; Mescla todos os grupos de um objeto em um
* &lbrack;captura 3D&rbrack; Malhas geradas renomeadas para Original
* &lbrack;Aplicativo&rbrack; Falha ao tentar gerar miniatura de uma imagem não existente
* &lbrack;Ativos&rbrack; Ícone da lixeira não faz nada no painel Ativos
* &lbrack;Content&rbrack; Atualizar filtros com slots de material não funciona como esperado
* &lbrack;Export&brack; Possível falha ao exportar um ativo com filtros específicos
* &brack;Export&brack; SBS/SBSAR Export - as camadas de importação de imagem têm prioridade sobre os parâmetros de imagem
* &lbrack;Export&brack; UE4 A predefinição de exportação não funciona com o PNG
* &lbrack;Camadas&rbrack; Falha ao soltar um material e um filtro ao mesmo tempo do explorador do sistema operacional
* &lbrack;Camadas&rbrack; Falha ao arrastar qualquer arquivo SBSAR com qualquer arquivo de imagem
* &lbrack;Camadas&rbrack; O canal de opacidade do bordado pode ser completamente branco
* &lbrack;Localization&rbrack; O idioma chinês pode ser exibido por padrão no Linux
* &lbrack;Desempenho&rbrack; Corrigido um problema de memória ao remover uma camada de um ativo
* &lbrack;Projeto&rbrack; Possível falha ao salvar
* &lbrack;UI&rbrack; Adicionar espaçamento ausente no botão de menu da Versão
* &lbrack;UI&rbrack; O botão Cancelar não é exibido corretamente
* &lbrack;UI&rbrack; Desativar a animação dos controles deslizantes para os parâmetros de pós-processamento do captura 3D
* &lbrack;UI&rbrack; A janela Modelo de Criação de Material não se fecha ao clicar fora
* &lbrack;UI&rbrack; O acessador rápido do filtro fecha-se ao clicar fora

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 4.0.2 Banana

*(Lançado: 09 de março de 2023)*

**Adicionado:**

* &lbrack;captura 3D&rbrack; A utilização do disco mostra a quantidade usada
* &lbrack;captura 3D&rbrack; A importação de fotos é assíncrona e rápida
* &lbrack;Scripting&rbrack; Novas classes e funções para gerar script do recurso captura 3D
* &lbrack;Scripting&brack; Nova classe ExportController para executar ações quando a exportação for concluída, falha ou cancelada
* &lbrack;Scripting&brack; Passar argumentos scripts python executados com —run-script
* Feedback de IU&rbrack;UI&rbrack; ao arrastar um ativo sobre o painel Camadas
* O filtro de Temperatura de Cor do &lbrack;Content&brack; agora está funcionando nos materiais
* &lbrack;Content&brack; Normal para filtros de Height tem uma nova opção para preservar a divisão em blocos gráficos

**Corrigido:**

* &lbrack;captura 3D; Tamanho da imagem corrigido na etapa de alinhamento do conjunto de dados
* &lbrack;captura 3D&rbrack; Remover vértices duplicados após o desempacotamento UV
* &lbrack;captura 3D&rbrack; MacOS - Detecção aprimorada se o captura 3D estiver disponível
* &lbrack;captura 3D&rbrack; Falha ao fechar a janela do Captura 3D durante a importação de imagens
* &lbrack;captura 3D; Falha ao gerar uma nova versão
* &lbrack;captura 3D; Falha ao tentar carregar o objeto 3D no visualizador
* &lbrack;captura 3D&rbrack; Falha ao usar um caminho com caracteres não UTF8
* &lbrack;captura 3D&rbrack; Acertos &amp; Dicas erro
* &lbrack;captura 3D&rbrack; As malhas não são mais dimensionadas para caber no cubo da unidade
* &lbrack;captura 3D&rbrack; Evitar falhas ao fechar o Captura 3D durante a renderização
* &lbrack;captura 3D; Remover uma máscara faz a imagem desaparecer
* &lbrack;Aplicativo&rbrack; Falha ao importar duas vezes um ativo simultaneamente
* &lbrack;Aplicativo&rbrack; Fazer backup da versão anterior dos ativos ao abrir um projeto, se eles nunca tiverem feito backup
* &lbrack;Aplicativo&rbrack; Armazena corretamente em cache os mapas baked quando nem todos os mapas estão armazenados
* &lbrack;O aplicativo&rbrack; trava quando um objeto 3D é exibido.
* &lbrack;Aplicativo&rbrack; O último material é duplicado ao salvar o projeto
* &lbrack;Aplicativo&rbrack; Evitar falhas ao cancelar o computador de Pós-processamento de Malha durante a etapa de cozimento
* &lbrack;Aplicativo&rbrack; A reabertura do projeto atual não descarta as alterações
* &lbrack;Aplicativo&rbrack; Parar de gerar miniaturas para objetos 3D
* &lbrack;Visualização 2D&rbrack; Falha ao usar a ferramenta pincel
* &lbrack;Content&rbrack; Preenchimento sensível ao conteúdo - a computação pode travar
* &lbrack;Content&brack; O filtro Criador de Atlas está reduzindo o canal Opacidade
* &lbrack;Export&rbrack; Corrigir falha ao limpar fila de exportações
* &lbrack;Exportar&rbrack; exportação OBJ cria objeto 100 vezes menor do que o esperado
* &preto;Camadas&rbrack; As imagens coloridas importadas como canais em tons de cinza agora são consideradas tons de cinza
* &lbrack;Os arquivos FBX do Export&brack; não podem ser importados em aplicativos de terceiros
* &lbrack;Export&rbrack; os nomes de saída do Sombreador nos arquivos USD não estão corretos
* &lbrack;Camadas&rbrack; O nome da imagem não é atualizado ao alterar seu nome no explorador do sistema operacional
* &lbrack;Scripting&brack; Exibir uma mensagem de erro ao recarregar um script inválido
* &lbrack;UI&rbrack; botão de Material de base desativado quando não disponível
* &lbrack;UI&rbrack; Falha ao acessar a caixa de diálogo de arquivo na janela Modelo de criação de material
* &lbrack;UI&rbrack; O acessador Rápido está acessível mesmo quando o painel Camadas é fechado
* &lbrack;UI&rbrack; Os ícones Enviar para estão desalinhados
* &lbrack;UI&rbrack; O ícone da camada muda ao clicar no ícone de Combinar

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 4.0.1 Banana

*(Lançado em: 07 de fevereiro de 2023)*

**Corrigido:**

* &lbrack;captura 3D&rbrack; Ao usar máscaras, a projeção de textura pode estar quebrada
* &lbrack;captura 3D&rbrack; Artefatos podem aparecer em seu objeto
* &lbrack;captura 3D; A malha exportada pode ser realmente pequena

**Problemas Conhecidos:**

* &lbrack;captura 3D&rbrack; as exportações de OBJ e FBX diminuem o resultado
* O &lbrack;captura 3D&rbrack; captura 3D está disponível no MacOS mesmo se o hardware não for compatível. Verifique a documentação.
* &lbrack;captura 3D&rbrack; Falha quando a reconstrução da malha é feita.
* &lbrack;Camadas&rbrack; O Preenchimento sensível ao conteúdo pode ficar travado se você ajustar as camadas abaixo
* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 4.0.0 Banana

*(Lançado: 31 De Janeiro De 2023)*

**Adicionado:**

* &lbrack;captura 3D&rbrack; Criar objetos 3D a partir de imagens
* &lbrack;captura 3D&rbrack; Assistente de captura 3D Dedicado
* &lbrack;captura 3D&rbrack; Importar ou gerar máscaras em preto e branco no conjunto de dados
* &lbrack;captura 3D&rbrack; Resultado do alinhamento - visualizar todos os recursos correspondentes como uma nuvem de pontos
* &lbrack;captura 3D&rbrack; Resultado do alinhamento - visualize e interaja com câmeras associadas a cada foto alinhada
* &lbrack;captura 3D; Define a área de reconstrução com um widget de caixa delimitadora
* &lbrack;captura 3D; Dimensionar, traduzir e girar em todos os eixos do widget da caixa delimitadora
* &lbrack;captura 3D; Define a precisão da geometria para a malha reconstruída
* &lbrack;captura 3D&rbrack; Otimize sua malha e texturas criando uma nova versão
* &lbrack;captura 3D; Cada uma das versões é automaticamente dizimada para o conjunto de números de faces de destino
* &lbrack;captura 3D&rbrack; A etapa de pós-processamento automaticamente desembrulha, reprojeta texturas e, em seguida, faz bake as informações normais de height e AO da malha de alto polígono
* &lbrack;captura 3D&rbrack; Adicionar o resultado original ou uma versão ao projeto do Sampler
* &lbrack;captura 3D&rbrack; Nova camada de Pós-processamento de Malha para dizimar, quebrar, reprojetar texturas automaticamente e fazer bake detalhes da camada de malha subjacente
* &lbrack;captura 3D&rbrack; Nova camada de Transformo de Malha para dimensionar, girar ou traduzir a camada de malha subjacente
* &brack;Exportar&rbrack; Nova janela de Exportação
* &lbrack;Export&brack; Configurações dedicadas e interface dependendo do tipo de ativo (material, iluminação do ambiente, malha)
* &lbrack;Export&brack; Exportar a malha como USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &lbrack;Export&brack; Define o tipo de material ao exportar arquivos de Substance (SBSAR, SBS)
* &lbrack;UI&rbrack; Move as configurações de cache para uma nova aba no pop-up Preferências
* &lbrack;Aplicativo&rbrack; As viewports 2D e 3D agora podem ser redimensionadas, trocadas e empilhadas verticalmente
* &lbrack;Aplicativo&rbrack; Nova variável de ambiente SAMPLER_RESOURCES_PATH para adicionar ativos iniciais extras
* &lbrack;Scripting&rbrack; Adicionadas variáveis de ambiente SAMPLER_PLUGIN_PATH e SAMPLER_SCRIPT_PATH para importar plug-ins e scripts na inicialização
* &lbrack;Scripting&brack; Funções de exportação adicionadas para materiais, luzes de ambiente e objetos 3D
* &lbrack;Scripting&rbrack; Identificador adicionado, valor padrão, valores mínimos e máximos, rótulos e valores de enumeração para parâmetros
* &lbrack;Scripting&rbrack; Adicionada a função import_textures para inserir um uso personalizado ao importar imagens

**Corrigido:**

* &lbrack;Aplicativo&rbrack; Falha ao abrir um projeto recente e salvar na caixa de diálogo de confirmação
* A caixa de diálogo Arquivo &brack;Application&brack; impede a abertura de arquivos .ssa
* &lbrack;Aplicativo&rbrack; As caixas de diálogo de arquivos podem aparecer em uma janela em segundo plano no macOS
* &lbrack;Aplicativo&rbrack; Possível falha ao abrir projetos 3.2
* &lbrack;Aplicativo&rbrack; Selecionar um arquivo fecha a caixa de diálogo Arquivo antes de exibir avisos
* &lbrack;Parâmetros expostos&rbrack; Exportar luzes de ambiente paramétricas não funciona
* &lbrack;Camadas&rbrack; O link “Clique aqui para procurar” na pilha de camadas não funciona mais
* &lbrack;Camadas&rbrack; Pintar várias imagens dentro da mesma camada às vezes não funciona
* &lbrack;Camadas&rbrack; Configurar uma imagem nas propriedades da camada não atualiza a miniatura do seletor de imagens
* &lbrack;Camadas&rbrack; Ajustar um ativo do Sampler adicionado como uma camada não funciona
* &lbrack;Projeto&rbrack; Atualização de ativo indesejado ao abrir um projeto
* &lbrack;Scripting&brack; A navegação para a pasta de plug-ins às vezes falha no Windows
* &lbrack;Scripting&rbrack; Falha ao usar &#39;open_project()&#39; em um script Python
* &lbrack;Scripting&rbrack; a exportação de JPEG está ausente da API
* &lbrack;Scripting&brack; O painel de registro não é somente leitura
* &lbrack;Scripting&brack; o valor do parâmetro image_picker não funciona
* &lbrack;UI&rbrack; Ícone de ativo ausente para luzes ambiente no painel Projeto
* &lbrack;UI&rbrack; A lista suspensa Enviar para o formato do Designer no pop-up Preferências pode estar vazia
* &lbrack;UI&rbrack; Alguns botões têm um estilo incorreto
* &lbrack;UI&rbrack; O rótulo se sobrepõe aos botões nos widgets Grupo de Botões
* &lbrack;UI&rbrack; A posição da dica de ferramenta está incorreta para “Ferramentas” no menu Definir o tamanho físico
* &lbrack;UI&rbrack; Ao alterar o idioma, o menu Arquivo fica desalinhado

**Problemas Conhecidos:**

* &lbrack;captura 3D&rbrack; Ao usar máscaras, a projeção de textura pode estar quebrada
* &lbrack;captura 3D&rbrack; Pequenos artefatos poderão aparecer em seu objeto se sua escala na transformação de malha for muito pequena
* &lbrack;captura 3D&rbrack; A malha exportada pode ser realmente pequena. Redefinir o dimensionamento da transformação e da reexportação da malha
* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

## Versão 3

### 3.4.1 Arancini

*(Lançado: 06 De outubro De 2022)*

**Adicionado:**

* &lbrack;Integração&rbrack; Novas telas de Boas-vindas e Novidades
* &lbrack;Integração&rbrack; Interface do Usuário de Tela Inicial Atualizada
* &lbrack;Integração&rbrack; Novo conteúdo de aprendizado na tela inicial
* &lbrack;Scripting&rbrack; Registra um erro no painel Registro quando um método não é reconhecido
* &lbrack;Scripting&brack; Novo módulo ssa.helpers para permitir a impressão no painel Log
* &lbrack;Aplicativo&rbrack; Suporte para o novo widget de botões lado a lado do Substance 3D Designer

**Corrigido:**

* &lbrack;Export&brack; Falha ao exportar um arquivo .sbsar fazendo referência a uma imagem ausente
* &lbrack;Export&brack; Falha ao exportar um ativo que faz referência a um arquivo de imagem corrompido
* &lbrack;Export&brack; Exportar um arquivo .sbsar com uma camada de Bordado resulta em um material cinza
* &lbrack;Export&brack; Exportar um material para um arquivo .sbs/sbsar pode gerar um material totalmente transparente
* O parâmetro Formato Normal do &brack;Export&brack; não é exposto corretamente em arquivos .sbs/.sbsar
* &lbrack;Export&rbrack; A exportação de Sbs/sbsar de uma pilha de camadas que faz referência a um arquivo .svg está quebrada
* &lbrack;Exportar&rbrack; a camada de transformação não é exportada corretamente / Enscape atualizado - Revit export preset
* &lbrack;Parâmetros expostos&rbrack; Falha ao excluir uma camada contendo um parâmetro exposto
* &lbrack;Parâmetros expostos&rbrack; Atualizar uma camada desatualizada na pilha de camadas pode levar a uma lista corrompida de parâmetros expostos
* &lbrack;Parâmetros Expostos&rbrack; Os parâmetros que não devem ser exportados são exportados mesmo assim
* &lbrack;Parâmetros expostos&rbrack; Remover um filtro de mesclagem ao excluir uma camada não deixa de expor seus parâmetros
* &lbrack;Parâmetros expostos&rbrack; Parâmetros de texto quebram as exportações .sbs/.sbsar
* &lbrack;Camadas&rbrack; Falha ao soltar uma pilha de camadas em outra pilha de camadas
* &lbrack;Camadas&rbrack; Falha ao carregar um filtro
* &lbrack;Camadas&rbrack; Não é possível recarregar a imagem anterior ao redefinir o campo de Imagem
* &lbrack;Camadas&rbrack; Não é possível desfazer/refazer alterações na ferramenta transformar
* &lbrack;Camadas&rbrack; A camada de Carimbo fica parada após clicar em “Redefinir todas as configurações”
* &lbrack;Camadas&rbrack; Usar qualquer um dos botões de redefinição impede o desenho no campo de Imagem
* &lbrack;Camadas&rbrack; O botão Redefinir não limpa a máscara de desenho no campo Imagem
* &lbrack;Camadas&rbrack; O botão Redefinir no campo de Imagem não faz nada se o usuário tiver pintado algo
* &lbrack;Camadas&rbrack; O cache de renderização não funciona ao usar a ferramenta Pincel
* &lbrack;Camadas&rbrack; A camada excluída ainda pode aparecer no painel Propriedades
* &lbrack;Camadas&rbrack; O cálculo da camada pode parar ao alternar entre ativos de projeto
* &lbrack;Projeto&rbrack; Às vezes, o Sampler não consegue abrir um projeto do disco
* &lbrack;Exibição 2D&rbrack; A exibição 2D sempre retorna como padrão para Saída de material

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.4.0 Arancini

*(Lançado: 06 De setembro De 2022)*

**Adicionado:**

* &preto;Parâmetros Expostos&rbrack; Novo Painel de parâmetros expostos
* &lbrack;Parâmetros expostos&rbrack; O novo botão nos parâmetros passa o mouse para expor e não expor os parâmetros do painel Propriedades
* &lbrack;Parâmetros expostos&rbrack; Novo menu de contexto de clique com o botão direito do mouse nos parâmetros para expor e não expor parâmetros do painel Propriedades
* &lbrack;Parâmetros expostos&rbrack; Os parâmetros expostos são listados no Painel de parâmetros expostos
* &lbrack;Parâmetros expostos&rbrack; Os pontos de cor e os discos de cor são adicionados em vários locais para identificar facilmente os parâmetros expostos
* &lbrack;Parâmetros expostos&rbrack; Os rótulos dos parâmetros podem ser editados no Painel de parâmetros expostos
* &lbrack;Parâmetros expostos&rbrack; Exibir um aviso para parâmetros não exportáveis
* &lbrack;Parâmetros expostos&rbrack; Exibir aviso se mover uma camada com parâmetros de mesclagem expostos em algum lugar onde eles se tornam ocultos
* &preto;Parâmetros expostos&rbrack; Os parâmetros expostos são exportados nos formatos SBS e SBSAR
* &lbrack;Metadados&rbrack; Suporte a modelos de metadados personalizados
* &lbrack;Metadados&rbrack; Novo modelo de metadados de propriedades físicas do CLO
* &lbrack;Metadados&rbrack; Adiciona ícones ao passar o mouse para adicionar/remover metadados personalizados
* &lbrack;API Python&rbrack; Nova API Python
* &lbrack;API Python&rbrack; API para a criação de ativos
* &lbrack;API Python&rbrack; API para gerenciamento de camadas
* API&rbrack; Python API&rbrack; para gerenciamento de Parâmetros
* API&rbrack; Python API&rbrack; para gerenciamento de projetos
* &lbrack;Python API&rbrack; Um plug-in pode ser ativado e desativado
* Documentação da API do &amp;Python&rbrack; Python acessível no menu Ajuda
* &lbrack;Scripting&brack; seção Novos plug-ins e scripts no pop-up Preferências
* &lbrack;Scripting&brack; Crie e importe plug-ins para personalizar a interface do Sampler com seus próprios painéis
* &brack;Scripting&rbrack; Os plug-ins se tornam parte da interface do Sampler e podem ser encaixados e movidos como painéis padrão do Sampler
* &lbrack;Scripting&brack; Barra de botões dedicada para os plug-ins na barra de ferramentas direita do Sampler
* &lbrack;Scripting&rbrack; Cria e importa scripts para executar uma lista de tarefas fornecidas
* &lbrack;Scripting&brack; Inicia scripts Python através do menu Scripts
* &lbrack;Scripting&rbrack; Os plug-ins e scripts podem ser excluídos, reordenados e recarregados na janela Preferências
* &lbrack;Scripting&rbrack; Adicionado — run-script parâmetros da linha de comando
* &lbrack;Logs&rbrack; Novo painel de Logs
* &lbrack;Logs&rbrack; Ativar painel Logs na janela Preferências
* &lbrack;Logs&rbrack; Nova barra de ações para limpar, copiar/colar, exportar logs
* &lbrack;Propriedades&rbrack; Novo botão nos parâmetros passe o mouse para redefinir o valor do parâmetro
* &lbrack;Propriedades&rbrack; Novo menu de contexto acessado com o botão direito do mouse nos parâmetros para redefinir o valor do parâmetro
* &brack;Content&brack; A imagem para material (viabilizada por IA) agora funciona no MacOS
* &lbrack;Engine&rbrack; Atualiza mecanismo de Substance para v8.6.0

**Corrigido:**

* &lbrack;Aplicativo&rbrack; O aplicativo podia falhar ao sair quando uma geração de miniatura estava em andamento
* &lbrack;Aplicativo&rbrack; O aplicativo pode falhar ao usar &#39;Salvar como&#39; ao sair
* &lbrack;O aplicativo&rbrack; pode travar durante o desligamento no MacOS
* &lbrack;Aplicativo&rbrack; Salvar com a caixa de diálogo de cor aberta não salva suas alterações
* &lbrack;Export&brack; A convenção de nomenclatura de uso não está correta ao exportar
* &lbrack;Camadas&rbrack; Soltar um material sobre um filtro pode falhar
* &lbrack;Camadas&rbrack; Atualizar uma pilha de camadas desatualizada poderia atualizar pilhas de camadas não relacionadas
* &lbrack;Metadados&rbrack; Os campos vazios são exportados
* &lbrack;Metadados&rbrack; Quando há apenas um item de metadados, a interface do usuário permite que você tente reordená-lo
* &lbrack;Projeto&rbrack; A computação nunca termina após a duplicação de um material
* &lbrack;Projeto&rbrack; O ativo do projeto é duplicado após o salvamento inicial do projeto
* &lbrack;Projeto&rbrack; Cálculos desnecessários ao alternar ativo
* &lbrack;Renderização&rbrack; Algumas pilhas de camadas não são renderizadas corretamente após a exclusão de uma camada
* &lbrack;Segurança&rbrack; Corrigir CVE-2015-20107
* &lbrack;UI&rbrack; As saídas 2D podem ficar desfocadas dependendo do tamanho da janela
* &lbrack;UI&rbrack; A visualização do ativo pode permanecer aberta na parte superior quando o aplicativo perde o foco
* &lbrack;UI&rbrack; Os cantos arredondados da tela inicial têm um fundo quadrado opaco

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.3.2. Abobrinha

*(Lançado: 28 de junho de 2022)*

**Corrigido:**

* &lbrack;Aplicativo&rbrack; Corrigir falha potencial ao abrir um projeto
* &lbrack;Export&rbrack; Reiniciar o Sampler interrompe a lista de predefinições de exportação personalizadas importadas
* &lbrack;Interoperabilidade&rbrack; Corrigir falha quando um material enviado do Designer é excluído e reenviado do Designer
* &lbrack;Projeto&rbrack; Impossível excluir o último material ou luz ambiente se for o último ativo no projeto
* &lbrack;Projeto&rbrack; Clicar com o botão direito do mouse em uma luz ambiente faz com que o asterisco “modificações não salvas” apareça

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.3.1. Abobrinha

*(Lançado em: 07 de junho de 2022)*

**Adicionado:**

* &lbrack;Suporte nativo ao Apple Silicon (M1)
* &lbrack;UI&rbrack; Novo atalho, tecla “C”, para percorrer os canais no Visualização 2D
* &preto;Ferramentas&rbrack; Campo numérico para editar o valor da cor em tons de cinza na barra de ferramentas Pincel

**Corrigido:**

* &lbrack;Ferramentas&rbrack; Usar a ferramenta Pincel no Windows com uma escala de interface fracionada (150%) desloca os traçados
* &lbrack;Desempenho&rbrack; Melhorar o consumo de memória
* &lbrack;Tamanho físico&rbrack; as informações do Tamanho físico podem estar ausentes ao ativar o recurso
* &lbrack;UI&rbrack; A rolagem do mouse às vezes não funciona conforme o esperado ao pressionar a tecla Alt
* &lbrack;O aplicativo&rbrack; pode falhar ao abrir um projeto salvo
* &lbrack;Aplicativo&rbrack; Falha ao arrastar e soltar várias imagens e usar Importação de Textura na janela Modelo de criação de material
* &lbrack;Aplicativo&rbrack; Possível falha ao salvar um projeto contendo um filtro personalizado
* &lbrack;Aplicativo&rbrack; Às vezes, o estado da tecla Control é perdido ao alternar o aplicativo
* &lbrack;Assets&rbrack; Falha ao renomear uma pasta local

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.3.0 Abobrinha

*(Lançado: 17 de maio de 2022)*

**Adicionado:**

* &lbrack;Content&brack; Novo filtro de Preenchimento sensível ao conteúdo (Windows e Mac)
* &lbrack;Content&rbrack; O Preenchimento sensível ao conteúdo está funcionando em imagens, materiais PBR e iluminações do ambiente
* &lbrack;Content&brack; Adicionar o parâmetro “Preservar divisão em blocos gráficos” à Imagem para Material (Ativado por IA)
* &lbrack;Content&brack; O filtro Transformo de Perspectiva pode exibir uma grade entre seus quatro pontos
* &lbrack;Interoperabilidade&rbrack; Enviar materiais para o Adobe Substance 3D Stager
* &lbrack;Ferramentas&rbrack; Centralize a transformação pressionando Ctrl ao redimensionar a ferramenta Transformar ou Cortar
* &lbrack;Ferramentas&rbrack; Bloqueie a proporção para o quadrado pressionando Shift ao redimensionar a ferramenta Transformar ou Cortar
* &lbrack;Ferramentas&rbrack; o cursor do carimbo de Clonar oferece uma previsão do que será carimbado
* &lbrack;Ferramentas&rbrack; Visualize o conteúdo original no cursor Borracha ao usar o Carimbo
* &lbrack;Tools&brack; Ctrl+Clique cria um novo carimbo na camada Clonar Carimbo
* &lbrack;Ferramentas&rbrack; Carimbos de clonagem sucessivos agora são agrupados em uma única camada
* &lbrack;Ferramentas&rbrack; Pincel barra de ferramentas IU Renovar
* &lbrack;Ferramentas&rbrack; A posição da barra de ferramentas Pincel é persistente durante uma sessão
* &lbrack;Ferramentas&rbrack; Novas opções de divisão em blocos gráficos por eixo
* &lbrack;Ferramentas&rbrack; Ocultar/exibir a sobreposição sobre a Visualização 2D ao pintar
* &lbrack;Ferramentas&rbrack; Novo atalho, tecla “X”, para alternar entre Pincel e Borracha
* &lbrack;Ferramentas&rbrack; Novo atalho, “&lbrack;” “&rbrack;” para alterar o tamanho do pincel
* &lbrack;Ferramentas&rbrack; Novo atalho, tecla “E”, para alternar a Borracha
* &lbrack;Exibição 2D&rbrack; Novo modo de Projeção esférica ao criar luz ambiente
* A ferramenta Pincel do &lbrack;Visualização 2D&rbrack; é suportada com o modo de projeção esférica
* &lbrack;A ferramenta de Posição do &amp;2D View&rbrack; é suportada com o modo de projeção esférica
* &lbrack;Visualização 2D; Desfazer/refazer é suportado com o modo de projeção esférica
* &lbrack;Visualização 2D; Na Projeção esférica, defina a posição padrão para olhar para o centro do ambiente
* &lbrack;Visualização 2D&rbrack; Novo controle de exposição
* &lbrack;UI&rbrack; No painel Propriedades, o ajuste da imagem exibe a origem do conteúdo (imagem ou de uma camada)
* &lbrack;UI&rbrack; Melhoria no plano de fundo do menu suspenso de saídas de camada/material
* &lbrack;UI&rbrack; Nova posição das informações de resolução na Visualização 2D
* &lbrack;UI&rbrack; Nova dica de ferramenta com atalhos de controles de navegação de exibição 3D
* &lbrack;UI&rbrack; Nova dica de ferramenta com controles de pincel
* &lbrack;UI&rbrack; Nova dica de ferramenta com atalhos de controles de navegação de projeção
* &preto;Filtros compostos&rbrack; Os filtros compostos manipulam variações para trabalhar em imagens, materiais PBR e luzes ambiente
* &preto;Filtros compostos&rbrack; A ordem dos ajustes corresponde à ordem da lista de nós no filtro composto
* &preto;Filtros compostos&rbrack; Os ajustes de nós diferentes com o mesmo grupo serão mesclados em um único grupo no painel Propriedades
* &lbrack;Aplicativo&rbrack; Possui configurações de visualizador dedicadas por tipo de ativo

**Corrigido:**

* &lbrack;O aplicativo&rbrack; pode falhar ao alternar para a exibição 2D
* &lbrack;Aplicativo&rbrack; Corrigir um possível deadlock ou falha ao exportar várias vezes
* &lbrack;Aplicativo&rbrack; Tornar os valores padrão para canais consistentes com o Substance 3D Designer
* &lbrack;Aplicativo&rbrack; Carregar um projeto não aciona o recálculo do material
* &lbrack;Aplicativo&rbrack; Atualizou o URL para a documentação de importação de textura
* &lbrack;Content&brack; Ao usar um filtro composto, ele pede para ser atualizado quando não deveria, ao recarregar
* &lbrack;Content&brack; Os detalhes no mapa de height desaparecem ao usar a Mesclagem de opacidade
* &lbrack;UI&rbrack; Na caixa de diálogo Cor, é possível sair do intervalo usando os campos de texto do controle deslizante
* &lbrack;UI&rbrack; A lista de Uso tem uma barra de rolagem vertical inútil

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &lbrack;O widget de luz do Content&brack; Shape não está funcionando no modo de projeção esférica
* &lbrack;Interoperabilidade&rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.2.1 Iakitori

*(Lançado Em: 08 De março De 2022)*

**Adicionado:**

* &lbrack;Export&brack; Exportar metadados de dpi em arquivos de imagem
* &lbrack;Tamanho físico&rbrack; Mantém a proporção com texturas não quadradas ao editar dimensões físicas
* &lbrack;Tamanho físico&rbrack; os metadados do Tamanho físico são aplicados imediatamente quando o tamanho físico é alterado
* &lbrack;UI&rbrack; Ajusta o controle deslizante máximo da escala de Height para que possa influenciar qualquer tipo de material quando o Tamanho físico estiver ativado
* &lbrack;UI&rbrack; Novas dicas de ferramentas em filtros de pesquisa no Painel de ativos
* &lbrack;UI&rbrack; Use dicas de ferramentas para explicar quando os botões estão desativados no painel Ativos
* &lbrack;Content&brack; Atualização do filtro de contraste de brilho

**Corrigido:**

* &lbrack;Visualização 2D&rbrack; o botão de rotação de 90 graus nas ferramentas Cortar e Transformar não funciona como esperado
* &lbrack;Visualização 2D&rbrack; O widget Cortar às vezes fica ausente
* &lbrack;Aplicativo&rbrack; Limpar um parâmetro de imagem não reconecta a camada subjacente
* &lbrack;Aplicativo&rbrack; Falha ao sair após salvar um projeto
* &lbrack;Aplicativo&rbrack; Falha ao arrastar e soltar o material atual em uma coleção do painel Ativos
* &lbrack;Aplicativo&rbrack; Arrastar e soltar um ativo no visor pode travar
* &lbrack;Content&brack; A mesclagem normal tem um ajuste de semente aleatório
* O filtro de Snow do &lbrack;Content&brack; tem saída normal incorreta dependendo dos valores dos parâmetros neve fresca e derretida
* &lbrack;Content&brack; Filtro de assoalho: costuras inesperadas fixas
* &lbrack;Content&brack; Filtro de bordados: remover thread em mapa metálico
* &lbrack;Content&brack; filtro de blocos do Número inteiro: corrigir contagem de blocos x e y
* &lbrack;Content&rbrack; Filtro de parede de tijolos: saída normal e height para 16 bits
* &lbrack;Export&brack; O nome de arquivo padrão no pop-up de exportação não é o nome do material atual
* &lbrack;Export&brack; Exportar com proporção física com uma predefinição de exportação fornece dimensões incorretas
* &lbrack;Export&brack; Metálico está ausente na predefinição de exportação CLO
* &lbrack;Export&brack; Ao substituir uma predefinição personalizada de exportação, o nome para exibição não é atualizado
* &lbrack;Camadas&rbrack; Os canais personalizados da primeira camada inserida não são descobertos
* &lbrack;Camadas&rbrack; O material é reavaliado ao alterar ajustes de uma camada oculta
* &lbrack;Dicas de ferramenta do Localization&brack; não estão localizadas no painel Exportar
* &lbrack;Tamanho físico&rbrack; Desativar o Tamanho físico de um ativo não remove a escala física
* O valor da Escala de Height do &lbrack;Tamanho físico&rbrack; não pode ser definido fora dos limites do controle deslizante na primeira vez
* &lbrack;Tamanho físico&rbrack; Importar uma imagem sem tamanho físico impede a abertura do projeto
* O Tamanho físico do &lbrack;Tamanho físico&rbrack; está definido como zero por engano quando está ausente
* &lbrack;Tamanho físico&rbrack; O status da caixa de seleção da escala física do Tamanho físico não é atualizado quando exibido pela primeira vez
* &lbrack;UI&rbrack; Material de base &amp; Normal para Height não tem uma categoria
* &lbrack;UI&rbrack; O cursor às vezes fica invisível ao pintar uma imagem
* &lbrack;UI&rbrack; Desativar as opções “Copiar tudo” e “Recortar tudo” no menu de edição de um campo de texto se estiver vazio
* &lbrack;UI&rbrack; Os nomes dos filtros possuem caracteres incorretos
* O botão de bloqueio de Tamanho físico do &lbrack;UI&rbrack; não tem o estilo correto
* &lbrack;UI&rbrack; O botão Fechar na barra de pesquisa do Painel de Ativos não limpa a string de pesquisa

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.2.0 Yakitori

*(Lançado: 25 De Janeiro De 2022)*

**Adicionado:**

* &lbrack;Tamanho físico&rbrack; Novo painel Tamanho físico
* &lbrack;Tamanho físico&rbrack; Adicionar opções de Tamanho físico à janela Modelo de criação de material
* &lbrack;Tamanho físico&rbrack; Adicionar ferramenta de medida de Tamanho físico
* &lbrack;Tamanho físico&rbrack; Adicionar ferramenta de medição automática de Tamanho físico
* &lbrack;Tamanho físico&rbrack; Adicionar ferramenta de diagnóstico de Tamanho físico
* &lbrack;Tamanho físico&rbrack; Permitir a definição do valor z do Tamanho físico
* &lbrack;Tamanho físico&rbrack; Widget de lista suspensa para definir o nível de zoom no Visualização 2D
* &lbrack;Tamanho físico&rbrack; Nova opção “Exibir com proporção física” no nível do menu suspenso de zoom
* &lbrack;Tamanho físico&rbrack; Nova opção “Ajustar ao tamanho físico” no menu suspenso de nível de zoom
* &lbrack;Tamanho físico&rbrack; Exibir o Tamanho físico na exibição 2D
* &lbrack;Tamanho físico&rbrack; Exibir a Tamanho físico no visor 3D
* &lbrack;Tamanho físico&rbrack; Na caixa de diálogo de importação de imagem, mostrar profundidade de tamanho físico se houver um mapa de altura importado
* &lbrack;Tamanho físico&rbrack; Mostrar o Tamanho físico no menu contextual do ativo
* &lbrack;Tamanho físico&rbrack; Define a unidade de comprimento nas Preferências
* &lbrack;Tamanho físico&rbrack; Exportar texturas respeitando a proporção física
* &lbrack;Metadados&rbrack; Capacidade de adicionar metadados personalizados a um ativo criado pelo usuário
* &lbrack;Exportar&rbrack; Exportar metadados personalizados para arquivos .sbs(ar)
* &lbrack;Export&brack; Exportar metadados de descrição, categoria, autor e marcas para arquivos .sbs(ar)
* &lbrack;Export&brack; Exporta o Tamanho físico para arquivos .sbs(ar)
* &lbrack;Export&brack; Definir configuração de compactação do arquivo .sbsar
* &lbrack;Export&brack; Exporta a miniatura do ativo para arquivos .sbs(ar)
* &lbrack;Export&brack; Define o tipo de gráfico ao exportar um arquivo .sbs(ar)
* O &lbrack;Application&brack; Realtime Engine 2021 não está mais disponível
* &lbrack;O aplicativo&rbrack; Desfazer/Refazer agora suporta mudanças de controle deslizante Lado a lado (U, V) e escala de height
* &lbrack;Renderização&rbrack; Gerar cache de disco quando o ativo criado for salvo
* &lbrack;Ativos&rbrack; Use Ctrl+clique para ativar vários filtros de tipo de ativo no painel Recursos
* &lbrack;UI&rbrack; Capacidade de bloquear os controles deslizantes de divisão em blocos gráficos (U,V)
* &lbrack;UI&rbrack; Adicionar um menu contextual com “Copiar”, “Recortar”, “Colar”, “Copiar tudo” e “Recortar tudo” nos campos de texto
* &lbrack;UI&rbrack; Unidade de comprimento (metros, polegadas, parsecs, ...) suporte em rótulos e campos de texto
* &lbrack;UI&rbrack; O usuário pode definir a precisão decimal usada para exibir números
* &lbrack;UI&rbrack; Usar unidades nos pop-ups de medidas sempre que for relevante
* &lbrack;Localização&rbrack; O novo nome padrão do ativo agora está localizado
* &lbrack;Content&brack; Novo gerador de tecelagem
* &lbrack;Content&brack; Novo filtro de Comutador de Canal
* &lbrack;Content&brack; Todos os filtros relevantes agora estão cientes do Tamanho físico
* &lbrack;Content&brack; Novos ícones para Acabamento em madeira
* &lbrack;Content&rbrack; Todos os filtros agora são compatíveis com canais de Materiais Padrão de Adobe (ASM)
* Os Filtros do &amp;predefinição;Content&brack; agora podem ter uma variação de “ambiente”

**Corrigido:**

* &lbrack;Visualização 2D&rbrack; O canal permanece na lista quando removido
* &lbrack;Aplicativo&rbrack; Não é possível duplicar um ativo carregado do explorador de arquivos do sistema operacional
* &lbrack;O aplicativo &rbrack; falha ao sair
* &lbrack;Aplicativo&rbrack; Falha às vezes ao clicar em “Ativos iniciais” no painel Ativos
* &lbrack;Aplicativo&rbrack; Falha ao excluir um material
* &lbrack;Application&brack; A variável de ambiente “SUBSTANCE_DISABLE_SPECIFIC_FEATURES” ainda está ativa quando definida como “0” ou “”.
* &lbrack;Aplicativo&rbrack; Congela ao salvar um projeto com vários materiais
* &lbrack;Aplicativo&rbrack; Importar uma imagem pode levar a um travamento
* &lbrack;Application&brack; Alguns ativos iniciais estão ausentes na primeira inicialização
* &lbrack;Export&brack; Exportar um ativo às vezes leva a um travamento
* &lbrack;Camadas&rbrack; Não é possível importar imagens quando o painel de camadas está fechado ou invisível
* &lbrack;Camadas&rbrack; Alterar o idioma faz com que o ativo atual seja recalculado
* &lbrack;Camadas&rbrack; Alterar o uso de uma imagem importada não atualiza qual variação de filtro usar
* &lbrack;Camadas&rbrack; A Imagem para Material (AI) às vezes não é calculada ao ajustar as camadas abaixo dela
* &lbrack;Camadas&rbrack; Imagem para Material (AI) às vezes recalcula quando não é necessário
* &lbrack;Camadas&rbrack; Nenhuma atualização é sugerida quando um filtro personalizado é atualizado no disco
* &lbrack;Camadas&rbrack; O canal Normal às vezes tem o formato de pixel incorreto
* &lbrack;Camadas&rbrack; Algumas camadas ainda são computadas mesmo quando não visíveis
* &lbrack;Camadas&rbrack; As ferramentas de exibição 2D podem ser interrompidas ao alternar a visibilidade de uma camada
* &lbrack;Camadas&rbrack; A interface congela ao usar a Imagem para material (AI)
* &lbrack;Camadas&rbrack; Alternar a visibilidade da camada de filtro de Transformo interrompe a ferramenta de Visualização 2D e pode levar a um travamento
* &lbrack;Camadas&rbrack; Muitos recálculos ao remover uma camada da pilha de camadas
* &lbrack;Camadas&rbrack; Quando um filtro composto contém uma entrada/saída incomum ou personalizada, o Sampler não o calcula
* &lbrack;Desempenho&rbrack; O painel Ativos é lento ao abrir
* &lbrack;Performance&rbrack; Evitar alguns recálculos desnecessários da pilha de camadas
* &lbrack;Desempenho&rbrack; Carregar ativos do projeto leva muito tempo
* &lbrack;Performance&rbrack; O cache de renderização em disco não pode ser usado
* &lbrack;Desempenho&rbrack; Alternar entre camadas é lento
* &lbrack;Desempenho&rbrack; Ajustar um material ou filtro é lento
* &lbrack;Projeto&rbrack; Salvar um projeto ao sair pode levar a um travamento
* &lbrack;Renderizando&rbrack; Remover uma imagem pode remover todas as saídas
* &lbrack;Renderização&rbrack; O tempo de renderização exibido no visor está incorreto ao ajustar
* &lbrack;UI&rbrack; Não é possível rolar verticalmente no pop-up de exportação quando necessário
* &lbrack;UI&rbrack; É possível abrir o pop-up de exportação quando não há nada para exportar
* &lbrack;UI&rbrack; Alguns pop-ups não rolam se seu conteúdo transbordar
* &lbrack;UI&rbrack; Os campos de texto não são selecionados ao clicar neles ou ao abrir um menu
* &lbrack;UI&rbrack; O nome do modo de mesclagem no painel de propriedades às vezes não está correto
* &lbrack;UI&rbrack; A opção Salvar no menu Arquivo às vezes fica esmaecida
* &lbrack;UI&rbrack; O campo de texto não desaparece após renomear dois materiais
* &lbrack;UI&rbrack; Erro de ortografia no pop-up de preferência

**Problemas Conhecidos:**

* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.1.2 Xocoatl

*(Lançado: 14 De dezembro De 2021)*

**Corrigido:**

* &lbrack;Interoperabilidade&rbrack; Abrir arquivo .sbsar com o Substance 3D Sampler a partir do Bridge pode falhar no Windows
* &lbrack;Camadas&rbrack; Se você mover a única camada abaixo dela, o desempenho irá falhar
* &lbrack;UI&rbrack; O botão de configurações do canal desaparece ao alterar o idioma
* &lbrack;UI&rbrack; O nome do material no painel Propriedades desaparece após salvar o projeto
* &lbrack;Assets&rbrack; Clicar em “Todas as bibliotecas” pode levar a uma falha

**Problemas Conhecidos:**

* &lbrack;Realtime Engine 2021&rbrack; Computação pesada pode travar o aplicativo
* &lbrack;O Mecanismo em Tempo Real 2021&rbrack; O Mecanismo em Tempo Real 2021 falhará em uma máquina Windows com a CPU AMD e a GPU Nvidia instaladas
* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.1.1 Xocoatl

*(Lançado: 24 De novembro De 2021)*

**Adicionado:**

* &lbrack;Interoperabilidade&rbrack; Enviar ativos (SBS ou SBSAR) para o Substance 3D Designer
* &lbrack;Interoperabilidade&rbrack; Defina nas preferências o formato padrão para interoperabilidade com o Substance 3D Designer
* &lbrack;Interoperabilidade&rbrack; Receber vários ativos do Adobe Bridge
* &lbrack;UI&rbrack; Novo widget de Distribuição Aleatória
* &lbrack;UI&rbrack; Atualização do menu de contexto
* &lbrack;Ativos&rbrack; Arraste e solte imagens do painel Ativos para o painel Propriedades
* &lbrack;Projeto&rbrack; Os nomes dos ativos são limpos para evitar alguns caracteres específicos
* &brack;Marca&rbrack; Atualizar ícone do arquivo para arquivos SBSAR
* &lbrack;Engine&rbrack; Atualização Substance Engine versão 8.3.0

**Corrigido:**

* &lbrack;Content&brack; Cortar - Preservar proporção ao cortar imagens não quadradas
* &lbrack;Transformo do Content&brack; - A transformação horizontal não é invertida ao usar o widget
* &lbrack;Content&brack; Gravel - corrigir pintura de máscara personalizada em todos os canais
* &lbrack;Content&brack; Ladrilhos do piso - corrigir problemas com divisão em blocos gráficos e repetição de padrão
* &lbrack;Assets&rbrack; opção Gray out Adobe Bridge se não estiver instalada
* &preto;Seletor de cores&rbrack; A tecla Escape fecha o Seletor de cores
* &lbrack;Renderização&rbrack; Corrigir a Escala de Distância de Dispersão ao usar entrada em tons de cinza
* &lbrack;Share&brack; As opções Enviar para estão disponíveis somente com licenças Adobe
* &lbrack;Projeto&rbrack; Corrigir um problema de desempenho de memória

**Problemas Conhecidos:**

* &lbrack;Realtime Engine 2021&rbrack; Computação pesada pode travar o aplicativo
* &lbrack;O Mecanismo em Tempo Real 2021&rbrack; O Mecanismo em Tempo Real 2021 falhará em uma máquina Windows com a CPU AMD e a GPU Nvidia instaladas
* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.1.0 Xocoatl

*(Lançado: 28 De setembro De 2021)*

**Adicionado:**

* &preto;Seletor de cores&rbrack; Nova interface do Seletor de cores
* &preto;Seletor de cores&rbrack; Visualizar as cores atuais e anteriores lado a lado
* &preto;Seletor de cores&rbrack; Insira sua cor em Hexadecimal
* &preto;Seletor de cores&rbrack; Novo conta-gotas com visualização de cores
* &preto;Seletor de cores&rbrack; O conta-gotas pode selecionar uma cor fora do Sampler
* &lbrack;Seletor de cores&rbrack; Ajuste sua cor em espaços de cores RGB ou HSV
* &preto;Seletor de cores&rbrack; Salvar e gerenciar amostras
* &lbrack;Interoperabilidade&rbrack; Edite imagens no Illustrator a partir da camada de importação de imagem ou dos parâmetros de imagem
* &lbrack;Interoperabilidade&rbrack; Edite imagens no Photoshop a partir da camada de importação de imagem ou dos parâmetros de imagem
* &lbrack;Widget&rbrack; Novo widget de corte
* &lbrack;Widget&rbrack; Pressione Enter para validar seu corte
* &lbrack;Widget&rbrack; O widget Cortar lê o tamanho da imagem para se ajustar ao widget e manter a proporção ao redimensionar
* &lbrack;UI&rbrack; Nova interface deslizante de escala de cinza
* &lbrack;Aplicativo&rbrack; Adicionar seleção de formato normal nas preferências
* &lbrack;Aplicativo&rbrack; O formato normal nas camadas de importação de imagem segue o formato normal padrão definido nas preferências
* &lbrack;Aplicativo&rbrack; Na exibição 2D, o normal é exibido seguindo o formato normal definido nas preferências
* &lbrack;Aplicativo&rbrack; O normal é exportado no formato normal definido nas preferências
* &lbrack;Export&brack; Adicionar parâmetro de formato normal às exportações de arquivos SBS e SBSAR
* &preto;Exportar&rbrack; Adicionar configurações de sombreador às exportações de arquivos SBS e SBSAR
* &lbrack;Export&brack; Define a resolução padrão dos gráficos SBS exportados
* &lbrack;Filtros Compostos&rbrack; Encapsulamento filtros SSA com 7z
* &preto;Filtros compostos&rbrack; Adicionar metadados de categoria em filtros compostos
* &preto;Filtros compostos&rbrack; Os filtros compostos podem ter uma miniatura incorporada
* &lbrack;Filtros compostos&rbrack; Extensão de Filtros compostos adicionada (.ssafilter) à caixa de diálogo Obter arquivo de conteúdo
* &preto;Filtros compostos&rbrack; Importar filtros compostos (.ssafilter) no painel Ativos
* &lbrack;Mecanismo&rbrack; Atualizar mecanismo do substance para v8.2.0

**Corrigido:**

* &lbrack;Aplicativo&rbrack; As pastas locais conectadas podem travar
* &lbrack;O aplicativo &rbrack; falha ao sair
* &lbrack;Aplicativo&rbrack; Falha ao iniciar duas instâncias do Sampler
* &lbrack;Content&brack; O filtro de corte tem um ajuste de semente aleatório
* &lbrack;Content&rbrack; Alguns materiais de Substance às vezes não são atualizados
* &lbrack;Export&brack; Falha ao exportar com uma predefinição personalizada recém-adicionada
* &lbrack;Export&brack; O tamanho estimado do pacote está ausente no pop-up de exportação
* &lbrack;Export&brack; Corrigir vazamento de memória ao exportar arquivos SBS e SBSAR
* &preto;Filtros compostos&rbrack; Os filtros compostos podem ter entradas duplicadas
* &preto;Filtros compostos&rbrack; Falha se um filtro tiver referências não atendidas
* &preto;Filtros compostos&rbrack; Falha ao reordenar uma pilha de camadas com um filtro composto
* &preto;Filtros compostos&rbrack; A renderização às vezes trava
* &preto;Importação de imagem&rbrack; Importar uma imagem dispara várias renderizações
* &preto;Camadas &rbrack; Falha ao desfazer/refazer
* &lbrack;Camadas&rbrack; Falha ao adicionar um Material de base
* &lbrack;Camadas&rbrack; Falha ao usar uma imagem inválida como iluminação do ambiente
* &lbrack;Camadas&rbrack; Corrigir importação duplicada ao inserir um filtro com vários gráficos
* &lbrack;Camadas&rbrack; A reordenação de camadas nem sempre funciona
* &lbrack;Projeto&rbrack; Falha ao carregar um arquivo de projeto incompleto
* &lbrack;Projeto&rbrack; Falha ao abrir um projeto corrompido
* &lbrack;Projeto&rbrack; Alguns ativos podem desaparecer de um projeto
* &lbrack;Propriedades&rbrack; Corrigir predefinições de filtro ausentes
* Os parâmetros de Ângulo do &lbrack;UI&rbrack; não podem ser definidos
* &lbrack;UI&rbrack; Filtros exibição de metadados no painel Ativos
* &lbrack;UI&rbrack; Agrupar por categoria oculta filtros
* &lbrack;UI&rbrack; Problema de rolagem no Painel de ativos
* &lbrack;UI&rbrack; O painel de exportação agora tem uma barra de rolagem
* &lbrack;UI&rbrack; A miniatura não é exibida para alguns formatos de imagem no seletor de imagens

**Problemas Conhecidos:**

* &lbrack;Realtime Engine 2021&rbrack; Computação pesada pode travar o aplicativo
* &lbrack;O Mecanismo em Tempo Real 2021&rbrack; O Mecanismo em Tempo Real 2021 falhará em uma máquina Windows com a CPU AMD e a GPU Nvidia instaladas
* &lbrack;Seletor de Cores&rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.0.1 Waffle

*(Lançado: 27 de julho de 2021)*

**Adicionado:**

* &lbrack;Pincel&rbrack; Ativar cores na ferramenta pincel se a entrada da imagem suportá-lo
* &lbrack;Pincel&rbrack; manter a tecla Shift pressionada na ferramenta pincel desenha linhas retas
* &lbrack;Pincel&rbrack; Mostra uma visualização de linha ao manter a tecla Shift pressionada na ferramenta Pincel
* A ferramenta Pincel &preto;Pincel&rbrack; agora suporta desfazer e refazer
* &lbrack;Visualização 2D&rbrack; A cor padrão de entrada da imagem é usada ao pintar
* &lbrack;Camadas&rbrack; Leitura do valor padrão de entrada de Substance em arquivos SBSAR
* &lbrack;Renderização&rbrack; Permitir combinar height com normal
* &lbrack;Renderização&rbrack; Suporte à dispersão de subsuperfícies (não disponível no MacOS)
* &lbrack;Ativos&rbrack; Use o tipo de gráfico SBSAR para determinar o tipo de ativo
* &lbrack;Assets&rbrack; Melhor desempenho para pesquisa e descoberta de ativos no painel Ativos
* &Brack;Ativos&rbrack; Adicionada a entrada “Todas as bibliotecas” no painel Ativos, que exibe todos os ativos de todas as suas bibliotecas
* &lbrack;Ativos&rbrack; Agora o usuário pode optar por agrupar ativos por categoria ou tipo
* &lbrack;Import&brack; Detectar automaticamente texturas de anisotropia, capa, brilho e specular edge color na importação
* &lbrack;UI&rbrack; Substitui o título do painel com cabeçalho por um ícone
* &lbrack;UI&rbrack; Atualização do estilo de campos de texto
* &lbrack;UI&rbrack; Novo texto de descrição na janela de Criação do Modelo de Luz do Ambiente
* &preto;Aplicativo&rbrack; Exportar ativos com a resolução atual ao enviar para um aplicativo externo
* &lbrack;A resolução padrão do material agora é 2048\*2048 (1024\*1024 no macos)
* &lbrack;Content&brack; Novos padrões no filtro Ladrilhos
* &lbrack;Content&brack; Novo modo de Cor Dupla no filtro Substituição de cor

**Corrigido:**

* &lbrack;Visualização 2D&rbrack; O primeiro traçado na ferramenta pincel às vezes é quebrado
* &lbrack;Visualização 2D&rbrack; Recursos livres quando a ferramenta pincel não está visível
* &lbrack;Exibição 2D&rbrack; Usar o cursor de redimensionamento direito no widget de transformação
* &lbrack;Visualização 2D&rbrack; Os widgets não são exibidos se o usuário já tiver feito panorâmica na visualização 2D antes
* &lbrack;Aplicativo&rbrack; Falha ao abrir um projeto com fluxo de trabalho quebrado
* &lbrack;Aplicativo&rbrack; Corrigir o desligamento do aplicativo para evitar inundar o log com erros inúteis
* &lbrack;Aplicativo&rbrack; Refazer, excluir e salvar atalhos de teclado não funcionam em alguns sistemas operacionais
* &lbrack;Aplicativo&rbrack; Desfazer/refazer alteração do uso da imagem na camada de importação está danificado
* &lbrack;Exportar&brack; A cor de emissão das imagens exportadas possui um nome incorreto
* &lbrack;Export&brack; O ambiente é de 8 bits ao usar a exportação SBSAR
* &lbrack;Export&brack; Remove espaços extras em nomes de arquivos de imagem exportados
* &preset;Export&brack; A substituição ou exclusão de uma predefinição de exportação personalizada trava
* &lbrack;Camadas&rbrack; Evitar falha quando houver uma incompatibilidade de contagem de entrada
* &lbrack;Camadas&rbrack; Falha ao inserir uma camada de Material de base
* &lbrack;Camadas&rbrack; A contagem de entrada do filtro está limitada ao valor padrão
* &lbrack;Camadas&rbrack; Refazer altera erroneamente o tipo de Combinar para mesclagem de Height
* &lbrack;Camadas&rbrack; Remover zona de destino acima dos cabeçalhos de entrada
* &preto;Camadas&rbrack; As camadas são inseridas no local errado ao redor dos cabeçalhos de entrada
* &lbrack;Camadas&rbrack; O botão Redefinir todas as configurações não redefine os valores dos widgets suspensos
* &lbrack;Camadas&rbrack; Desfazer/refazer ao alterar uma imagem na camada de importação de imagem marca o projeto como modificado e assim para salvar
* &lbrack;Camadas&rbrack; Os usos podem ser interrompidos pela mesclagem de camadas
* &lbrack;Projeto&rbrack; Falha ao carregar um projeto legado com pasta de dependências ausentes
* &lbrack;Projeto&rbrack; Falha ao usar Desfazer/Refazer após salvar
* &lbrack;Projeto&rbrack; Abrir um arquivo SBSAR contendo uma luz ambiente cria um ativo material
* &lbrack;Projeto&rbrack; Renomear um material pode acionar uma geração de miniatura
* &lbrack;Projeto&rbrack; Salvar após renomear um material marca o projeto como não modificado
* &lbrack;Project&brack; Algumas alterações após renomear um material não são salvas
* &lbrack;Renderização&rbrack; Pontos brilhantes são visíveis no ambiente com o mecanismo em tempo real 2020
* &lbrack;Renderização&rbrack; Falha ao redimensionar usando o Mecanismo em tempo real 2021
* &lbrack;Renderização&rbrack; Recalcular sombras na alteração do nível de height
* &lbrack;Ativos&rbrack; As pastas conectadas param de indexar novos ativos ao adicionar um arquivo inválido
* &lbrack;Assets&rbrack; Falha ao conectar uma pasta local com muitos materiais
* &lbrack;UI&rbrack; botões de visualização 2D/3D sem dicas de ferramentas
* &lbrack;UI&rbrack; Todos os ativos no painel Ativos são destacados na inicialização
* O &lbrack;UI&rbrack; Trilhas às vezes desaparece no painel Ativos ao importar materiais
* &lbrack;UI&rbrack; A alteração do idioma não afeta o painel Projeto
* &lbrack;UI&rbrack; O painel de Configurações do Canal mostra informações de fluxo de trabalho herdadas
* &lbrack;UI&rbrack; Alinha corretamente o texto “Nenhuma configuração para este item” para os filtros sem ajustes no painel de propriedades
* &lbrack;UI&rbrack; Os elementos estão desalinhados na tela de boas-vindas e no pop-up de preferências
* &lbrack;UI&rbrack; A largura dos títulos do painel está incorreta
* &lbrack;UI&rbrack; A rolagem às vezes é interrompida no painel Propriedades
* &lbrack;UI&rbrack; A tela inicial possui uma proporção incorreta e está desfocada
* &lbrack;UI&rbrack; O modo de tela cheia não é de tela cheia
* &lbrack;UI&rbrack; Os painéis desencaixados estão sempre na parte superior, mesmo quando o aplicativo não estiver ativo no MacOS
* &lbrack;UI&rbrack; Atualizar imagem do banner da tela de boas-vindas
* &lbrack;Content&rbrack; O filtro de divisão em blocos gráficos não processa o canal de oclusão de ambiente
* &lbrack;Content&brack; Quilt Stitch problema com a seleção de costura de montagem e padrão de diamante
* &lbrack;Content&rbrack; O filtro Entalhe funciona em 256px por 256px
* &lbrack;Content&rbrack; Corrigir problema de divisão em blocos gráficos com os blocos de piso quando o deslocamento for maior que 0

**Problemas Conhecidos:**

* &lbrack;Realtime Engine 2021&rbrack; Computação pesada, falha o aplicativo
* &lbrack;O Mecanismo em Tempo Real 2021&rbrack; O Mecanismo em Tempo Real 2021 falhará na máquina Windows com a CPU AMD e a GPU Nvidia

### 3.0.0 Waffle

*(Lançado: 23 de junho de 2021)*

**Adicionado:**

* &lbrack;Branding&rbrack; Substance Alchemist se torna Adobe Substance 3D Sampler
* &brack;Marca&rbrack; Ícones de Novo aplicativo
* &lbrack;UI&rbrack; Nova Experiência do Usuário e Interface do Usuário
* &lbrack;UI&rbrack; Nova Tela de Apresentação
* &lbrack;UI&rbrack; Os painéis são desencaixáveis e encaixáveis na interface
* &lbrack;UI&rbrack; Encaixar até 3 painéis na mesma coluna
* &lbrack;UI&rbrack; Encaixar até 3 painéis no mesmo painel (Tabulações)
* &lbrack;UI&rbrack; Desencaixar painéis para criar uma janela separada na mesma tela ou em uma tela diferente
* &lbrack;UI&rbrack; Painéis fechados pop-over ao clicar em seus ícones
* &lbrack;UI&rbrack; Reorganize as barras esquerda e direita movendo os ícones dos painéis
* &lbrack;UI&rbrack; Nova barra de ferramentas para acessar diretamente filtros específicos (Cortar, Transformar, Transformação de perspectiva, Carimbo)
* &lbrack;UI&rbrack; Novo botão “Obter conteúdo” na barra esquerda
* &lbrack;UI&rbrack; Importe arquivos diretamente em seus ativos com o botão Obter conteúdo
* &lbrack;UI&rbrack; Importe arquivos diretamente para suas Camadas com o botão Obter Conteúdo
* &lbrack;UI&rbrack; Acesse diretamente o site do Adobe Substance 3D Assets com o botão Obter Conteúdo
* O widget de resolução do &lbrack;UI&rbrack; agora pode ser acessado diretamente no visor
* &lbrack;UI&rbrack; Todos os elementos da interface agora são carregados dinamicamente
* &lbrack;UI&rbrack; Atalho - Use “2” para alternar a visibilidade da exibição 2D
* &lbrack;UI&rbrack; Atalho - Use “3” para alternar a visibilidade da visualização 3D
* &Preenchimento;Tela de boas-vindas&Preenchimento; Crie um projeto com um clique usando o botão Novo
* &preto;Tela de boas-vindas&rbrack; Novo banner de arte
* &lbrack;Projeto&rbrack; Todos os projetos agora estão associados a um arquivo exclusivo
* &lbrack;Projeto&rbrack; Nova extensão de arquivo de projeto .ssa
* &lbrack;Projeto&rbrack; Salvar como um projeto solicitará que você selecione onde salvar seu projeto
* &lbrack;Projeto&rbrack; Ao fechar o Sampler, você será solicitado a salvar o projeto, caso ele não tenha sido salvo
* &lbrack;Projeto&rbrack; Fechar o Sampler solicitará que você salve seu projeto se houver modificações desde o último salvamento
* &lbrack;Projeto&rbrack; O nome do seu projeto é exibido acima do visor
* &lbrack;Projeto&rbrack; O nome do projeto está em itálico com uma estrela se não for salvo ou se contiver modificações desde o último salvamento
* &lbrack;Projeto&rbrack; Abre um arquivo de projeto .ssa diretamente do explorador do SO
* &lbrack;Projeto&rbrack; Abrir um .sbsar a partir do explorador do sistema operacional iniciará o Sampler com um novo projeto com este arquivo .sbsar pronto para uso
* &lbrack;Projeto&rbrack; Abra um .alch (arquivo de Substance Alchemist legado) do explorador do sistema operacional
* &lbrack;Painel do projeto&rbrack; Novo painel que conterá todos os ativos criados em um projeto
* &preto;Painel do projeto&rbrack; Criar um ativo (material ou luz ambiente) usando o ícone +
* &preto;Painel do projeto&rbrack; Clicar com o botão direito do mouse no ativo abre um menu de contexto
* &lbrack;Painel do Projeto&rbrack; No menu de contexto acessado ao clicar com o botão direito do mouse, é possível excluir um ativo
* &lbrack;Painel do projeto&rbrack; No menu de contexto do botão direito do mouse, você pode duplicar um ativo
* &lbrack;Painel do projeto&rbrack; No menu de contexto do botão direito do mouse, você pode renomear um ativo
* &lbrack;Painel do projeto&rbrack; Alternar entre ativos não perderá as modificações
* &lbrack;Resolução&rbrack; Agora você pode definir uma resolução não quadrada para todos os seus ativos
* &lbrack;Resolution&rbrack; O valor de resolução é salvo por um ativo dentro de um projeto
* &preto;Luz ambiente&rbrack; Criar luz ambiente no Substance 3D Sampler
* &preto;Luz ambiente&rbrack; Ao criar uma luz ambiente, arrastar e soltar imagens exibirá a janela Modelo de criação de luz ambiente
* &preto;Luz do ambiente&rbrack; No Modelo de criação da Luz do ambiente, selecione Importação do ambiente para atribuir sua imagem ao ambiente na visualização 3D
* &lbrack;Luz do ambiente&rbrack; No Modelo de criação da luz ambiente, selecione Mesclar HDR para criar uma luz ambiente de várias imagens de 360 graus com diferentes exposições
* &lbrack;Luz do ambiente&rbrack; No Modelo de criação da Luz do ambiente, selecione “Usar como bitmap” para editar a(s) imagem(ns) antes de criar uma luz do ambiente
* &preto;Luz do ambiente&rbrack; Atribui o uso do ambiente na camada de importação de imagem para atribuir diretamente a imagem ao ambiente na visualização 3D
* &preto;Luz do ambiente&rbrack; Na exibição 2D do canal de ambiente, há uma correção de cores automática para que a renderização apareça da mesma forma que na exibição 3D
* &preto;Luz do ambiente&rbrack; Novo conteúdo dedicado para criação de luz ambiente
* &preto;Painel de ativos&rbrack; Os painéis Recursos e Filtros são mesclados em um novo painel Ativos
* &lbrack;Painel Ativos&rbrack; O painel Ativos agora suporta os seguintes tipos de ativos: materiais, filtros e imagens
* &lbrack;Painel de ativos&rbrack; Todos os ativos iniciais podem ser acessados na seção Ativos iniciais
* &lbrack;Painel Ativos&rbrack; A seção Ativos iniciais é somente leitura
* &lbrack;Painel Ativos&rbrack; Nova seção “Seus ativos”
* &lbrack;Painel de Ativos&rbrack; A seção “Seus ativos” é o local onde você pode importar todos os seus recursos
* &lbrack;Painel de ativos&rbrack; Todos os ativos em “Seus ativos” são adicionados a uma pasta específica em seus Documentos
* &preto;Painel de ativos&rbrack; Conecte as pastas locais no painel Ativos para adicionar novas seções
* &lbrack;Painel de Ativos&rbrack; A pesquisa pesquisará na pasta atual e em suas subpastas
* &preto;Painel de ativos&rbrack; Navegar entre pastas e subpastas com navegação estrutural
* &lbrack;Painel de Ativos&rbrack; Filtrar a pasta atual por material, filtro ou imagem
* &preto;Painel de ativos&rbrack; Combine vários filtros para obter apenas materiais e imagens
* &lbrack;Painel de Ativos&rbrack; Altera a exibição alternando entre uma grade ou uma lista
* &preto;Painel de ativos&rbrack; Os filtros são representados com seus ícones
* &lbrack;Painel de Ativos&rbrack; As imagens são representadas com sua visualização
* &lbrack;Painel de ativos&rbrack; O aumento da largura alterará o layout do painel com uma exibição específica para navegar entre as pastas
* &lbrack;Painel Ativos&rbrack; Em seções não somente leitura, exclua um ativo arrastando-o e soltando-o no ícone de compartimento
* &lbrack;Painel Ativos&rbrack; Clicar com o botão direito do mouse no ativo abre um menu de contexto
* &lbrack;Painel de ativos&rbrack; No menu de contexto do botão direito do mouse, acesse os metadados do ativo (nome, categoria, local)
* &lbrack;Painel de ativos&rbrack; No menu de contexto do botão direito do mouse, exclua o ativo (disponível somente em seções não somente leitura)
* &lbrack;Painel de ativos&rbrack; No menu de contexto do botão direito do mouse, procure seu ativo no Adobe Bridge
* &lbrack;Painel de Camadas&rbrack; Novo ícone para adicionar diretamente uma material de base sobre as camadas
* &preto;Painel de camadas&rbrack; Atalho - Shift + B adicionará um material de base sobre as camadas
* &preto;Painel de camadas&rbrack; As camadas agora têm uma visualização em miniatura (miniatura do material, ícone do filtro ou visualização da imagem)
* &lbrack;Painel Propriedades&rbrack; Novo design do título do painel Propriedades com o nome e a miniatura do ativo
* &lbrack;Painel de Propriedades&rbrack; As camadas de filtro agora suportam predefinições
* &lbrack;Painel de Propriedades&rbrack; Na Camada de Importação de Imagem, clique com o botão direito do mouse na visualização da imagem para editar a imagem no Photoshop
* &lbrack;Adobe Bridge&rbrack; Procure seu ativo no Adobe Bridge e iniciará o Bridge no local do ativo
* &lbrack;O Adobe Photoshop&rbrack; Editar no Adobe Photoshop abrirá a imagem no Photoshop pronta para ser editada
* &lbrack;Adobe Photoshop&rbrack; A cada salvamento no Adobe Photoshop, a imagem editada será recarregada no Sampler
* &lbrack;Os ativos do Substance 3D Designer&rbrack; enviados do Adobe Substance 3D Designer chegarão diretamente na seção “Seus ativos” do painel Ativos
* &lbrack;Exportar&rbrack; Envia ativos diretamente para o Adobe Substance 3D Painter e Adobe Substance 3D Stager
* &lbrack;Export&brack; Enviar materiais e iluminações do ambiente para o Adobe Substance 3D Painter
* &preto;Exportar&rbrack; Enviar iluminações do ambiente para o Adobe Substance 3D Stager
* &lbrack;Renderização&rbrack; Novas propriedades de material agora são suportadas e renderizadas em 3D
* &lbrack;Renderização&rbrack; Adição de suporte a Brilho (Cor do brilho, opacidade de Brilho e aspereza de Brilho)
* &lbrack;Renderização&rbrack; Adição de suporte a Revestimento (Cor do revestimento, Aspereza do revestimento, Normal do revestimento, Nível especular do revestimento e Revestimento IOR)
* &lbrack;Renderização&rbrack; Adicionando suporte a Anisotropia (Nível de anisotropia e Ângulo de anisotropia)
* &lbrack;Renderização&rbrack; Adicionando suporte a Speculares edge colores
* &lbrack;Renderização&rbrack; Ativar estas novas propriedades no painel Configurações do canal
* &lbrack;Renderização&rbrack; Introdução de um novo renderizador de Mecanismo em Tempo Real (2021) na versão Beta
* &lbrack;Renderização&rbrack; Alternar entre as duas versões do Renderizador no painel Configurações do Visualizador
* &lbrack;Renderização&rbrack; O renderizador do Realtime Engine (2021) oferece suporte às propriedades de translucidez, absorção e material de dispersão
* &lbrack;Renderização&rbrack; O renderizador Realtime Engine (2021) apresenta uma nova maneira de calcular sombras a partir da iluminação do ambiente
* &lbrack;Renderização&rbrack; O renderizador Realtime Engine (2021) calcula em tempo real a irradiância da iluminação do ambiente
* &lbrack;Painel de configurações do Sombreador&rbrack; Novo painel de configurações do Sombreador para ajustar parâmetros específicos de sombreador do material
* &lbrack;Painel de configurações do Sombreador&rbrack; Novos parâmetros (escala normal, escala do height, nível do height, intensidade da emissão, IOR, intensidade do Normal do revestimento e Coat IOR)
* &lbrack;Painel de Configurações do Sombreador&rbrack; Parâmetros específicos para o Mecanismo em Tempo Real 2021 (Dispersão da Subsuperfície, Distância de Dispersão, Red Shift e Dispersão de Rayleigh)
* &lbrack;Painel de configurações do Sombreador&rbrack; Os valores das configurações são salvos por ativo
* &preto;Painel de configurações do visualizador&rbrack; Adicionada uma visualização das iluminações do ambiente padrão
* &preto;Painel de configurações do visualizador&rbrack; Adicionada uma visualização das malhas padrão
* &preto;Painel de configurações do visualizador&rbrack; Novo parâmetro de opacidade do ambiente
* &lbrack;Painel de configurações do visualizador&rbrack; Novo parâmetro de desfoque de ambiente (específico para o renderizador Realtime Engine 2021)
* &lbrack;Localização&rbrack; Novas traduções para alemão e francês
* &lbrack;Content&brack; Novos materiais iniciais padrão
* &lbrack;Content&brack; Novas iluminações do ambiente padrão
* &lbrack;Content&rbrack; Todos os filtros foram atualizados, limpos e otimizados
* &lbrack;Content&brack; O filtro Ajuste foi dividido em vários filtros
* &preto;Content&brack; Novo filtro de Brilho/Contraste
* &lbrack;Content&brack; Novo filtro de Matiz/Saturação
* &lbrack;Content&brack; Novo filtro de Vibratilidade
* &lbrack;Content&brack; Novo filtro de nitidez
* &lbrack;Content&brack; Novo ajuste Normal/Height
* &lbrack;Content&brack; Novo painel filtro
* &lbrack;Content&brack; Novo filtro Borrar
* &brack;Content&brack; New Weaves filter
* &lbrack;Content&brack; Novo filtro de transformo de distorção
* &lbrack;Content&brack; Novo Height para filtro AO
* &lbrack;Content&brack; Novo Height para filtro Normal
* &lbrack;Content&brack; Substituição de cor - Substituir em novos canais suportados (Brilho, Revestimento, Anisotropia,...)
* &lbrack;Content&brack; Variação de cor - Modo manual para selecionar exatamente as cores a serem alteradas
* &lbrack;Content&brack; Tiling - opção para visualizar o corte de costuras
* &lbrack;Content&rbrack; Tiling - opção para tinta as costuras cortadas para uma divisão perfeita
* &lbrack;Content&brack; Match - opção para adicionar um material que corresponda à sua cor e aspereza
* &lbrack;Content&brack; Match - agora funciona em imagens para corresponder à cor de outra imagem
* &lbrack;Content&brack; Luz ambiente - Novo filtro de temperatura de cor
* &lbrack;Content&brack; Luz do ambiente - Novo filtro de exposição
* &lbrack;Content&brack; Luz do ambiente - Novo filtro de visualização de exposição
* &lbrack;Content&brack; Luz do ambiente - Novo filtro de Nadir patch
* &lbrack;Content&brack; Luz do ambiente - Novo filtro de Nadir extract
* &lbrack;Content&brack; Luz ambiente - Novos filtros de Luzes (Esfera, Linha, Forma, Plano)
* &lbrack;Content&brack; Luz ambiente - Novo filtro de correção de panorama
* &lbrack;Content&brack; Luz do ambiente - Novo filtro Endireitar horizonte
* &lbrack;Content&brack; Luz do ambiente - Novo filtro de mesclagem HDR

**Problemas Conhecidos:**

* &lbrack;Realtime Engine 2021&rbrack; Alterar o layout, falha o aplicativo
* &lbrack;Realtime Engine 2021&rbrack; Computação pesada, falha o aplicativo
* &brack;Painéis&rbrack; MacOS - Os painéis desencaixados estão na frente de todos os aplicativos
* &lbrack;Widgets&rbrack; Os widgets de Transformação e Posições podem desaparecer. Oculte e reexiba a camada para fazê-las aparecer.
* &lbrack;Export&rbrack; A exportação de SBSAR de uma luz de ambiente perde a precisão 32profundidade de bits
* &lbrack;Painel de Ativos&rbrack; Os ativos podem ser destacados ao abrir uma pasta
* &lbrack;Painel de Propriedades&rbrack; A redefinição dos parâmetros não redefine a interface do usuário da caixa de combinação
* &lbrack;Localização&rbrack; A alteração do idioma não afeta o painel do projeto até que ele seja recriado

## Versão 2

### 2.3.2 (2020.3.2) Vermicelli

*(Lançado: 23 De fevereiro De 2021)*

**Adicionado:**

* &lbrack;Suporte para localizaçãp&rbrack; japonês

**Corrigido:**

* &lbrack;Camadas&rbrack; Ajustar um material no filtro de bordados perde a imagem do bordado

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.3.1 (2020.3.1) Vermicelli

*(Lançado: 17 de dezembro de 2020)*

**Adicionado:**

* &lbrack;Atualização do Substance Engine do motor&rbrack;
* &lbrack;Aplicativo&rbrack; Variável de ambiente para desativar recursos específicos
* &lbrack;Content&brack; Substituir cor - Nova opção de segmentação avançada
* &lbrack;Content&brack; Floor Tiles - novos padrões e opções disponíveis
* &lbrack;Content&brack; Bordado - Renovação completa do filtro
* &lbrack;Content&brack; Adjustment - Novo parâmetro metálico + correção de transformação segura de opacidade

**Corrigido:**

* &lbrack;Camadas&rbrack; Não é possível importar duas vezes o mesmo filtro personalizado
* &lbrack;Camadas&rbrack; Não é possível usar a entrada de imagem com a ferramenta pincel
* &preto;Exportar&rbrack; Exportar .jpg em vez de .jpeg
* &lbrack;UI&rbrack; Atualizar créditos da imagem de boas-vindas
* &lbrack;UI&rbrack; Corrigir separador invisível nos menus
* &lbrack;UI&rbrack; Os botões de opção exibem uma dica de ferramenta quando estão truncados
* &lbrack;UI&rbrack; Erro de Digitação: Materiais Iniciais
* &lbrack;O aplicativo&rbrack; com caracteres UTF-8 em nomes de ativos não funciona
* &preto;Localização&rbrack; Desativar estilo de fonte em itálico para o idioma chinês
* &lbrack;Localizaçãp&rbrack; Cadeia localizada dividida em 2 linhas
* &lbrack;Localization&brack; Ajusta o nome da pasta e substitui com reticências se for muito longo
* &lbrack;Localização&rbrack; Formatar números com separador de milhar
* &preto;Localização&rbrack; Localizar exibição de data e hora
* &lbrack;Localizaçãp&rbrack; Localizar seletor de cores no Windows
* &lbrack;Content&brack; Transform - Com a transformação segura ativada, o normal gira corretamente a cada 45°
* &lbrack;Content&brack; relevo de Superfície - Corrigir problema de divisão em blocos gráficos com ruído fractal de perlin (ruído avançado)
* &lbrack;Content&rbrack; Brickwall Pattern - Height de entrada em 16 bits
* &lbrack;Content&brack; Ícone de Material Renderizar - problema de reflexos de Specular
* Variação de Cor do &lbrack;Content&brack; - Nenhuma mudança de cor entre as entradas de cor e o resultado
* Variação de cor do &presilha;Content&brack; - Atualização de desempenho

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.3.0 (2020.3.0) Vermicelli

*(Lançado: 26 De outubro De 2020)*

**Adicionado:**

* &lbrack;Imagem para material&rbrack; Suporte da série NVIDIA RTX 3000
* &lbrack;Imagem para material&rbrack; Novos parâmetros para controlar os detalhes da geometria
* &lbrack;Imagem para material&rbrack; Novos parâmetros para controlar a aspereza
* &lbrack;Imagem para material&rbrack; Novos parâmetros para controlar a intensidade da delícia
* &lbrack;Miniaturas&rbrack; Novo gerador de miniaturas baseado no renderizador Substance Designer PBR
* &preto;Miniaturas&rbrack; Atualiza materiais de base e atlas para incorporar a miniatura
* &lbrack;Miniaturas&rbrack; Recupera a miniatura do arquivo .sbsar, se existir
* &lbrack;Miniaturas&rbrack; Alterar a qualidade da miniatura nas Preferências
* &lbrack;Engine&rbrack; Atualizado para a versão 8 do Substance Engine
* &lbrack;Localização&rbrack; Localização em chinês
* &preto;UI&rbrack; Seletor de Cores Especiais Experimentais
* &lbrack;Content&rbrack; Novo Mapa de Ambiente - Studio 06
* &preto;Content&brack; Adicionar filtro Gerador de Atlas
* &preto;Content&brack; Adicionar filtro de Atlas splitter
* &preto;Content&brack; Adicionar filtro de gengivas descartadas
* &lbrack;Content&brack; Adicionar filtro de impressões digitais
* &preto;Content&brack; Adicionar filtro Scratches
* &lbrack;Content&brack; Adicionar filtro de Relevo de Superfície (substituir filtro de modulação do height)
* &preto;Content&brack; Adicionar filtro de distorção
* &preto;Content&brack; Adicionar filtro Inverter
* &preto;Content&brack; Adicionar filtro Colorir
* &preto;Content&brack; Adicionar filtro Substituir cor
* &lbrack;Content&brack; Transform - Adiciona a possibilidade de desativar a transformação em um canal específico
* &lbrack;Content&brack; Transform - Adicionar rotação quando a transformação segura estiver ativada
* Variação de cor do &brack;Content&brack; - Adicione uma opção de segmentação para escolher como distribuir as cores

**Corrigido:**

* &lbrack;Camadas&rbrack; Atualizar UI corretamente ao fazer várias ações de desfazer/refazer
* &preto;Camadas&rbrack; Impedir falhas ao fazer várias ações de desfazer/refazer
* &lbrack;Camadas&rbrack; Falha ao usar Imagem para Material (Ativado por IA), com log: ordinal de dispositivo inválido
* &lbrack;Filtros&rbrack; Melhorar a detecção de placa gráfica NVIDIA para recursos específicos do NVIDIA
* &lbrack;Aplicativo&rbrack; Falha ao fechar o aplicativo
* &lbrack;Aplicativo&rbrack; Corrigir detecção de quantidade de VRAM no MacOS
* &lbrack;Export&brack; Algumas predefinições de exportação às vezes estão ausentes
* &lbrack;Content&brack; Efeito de pintura a óleo - Corrigir o intervalo do height com amplitude de deslocamento alta
* &lbrack;Content&brack; Tornar bloco avançado - Sem cor base desbotada na exportação
* &lbrack;Content&brack; Tornar bloco avançado - Máscara branca na cor base quando o AO for muito forte
* &lbrack;Ajuste de &amp;Content&brack; - Agora funciona em imagens (scan1, ...)

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.2.1 (2020.2.1) Udon

*(Lançado: 21 de julho de 2020)*

**Adicionado:**

* &lbrack;Camadas&rbrack; Mensagem de erro no aplicativo quando a imagem para material (alimentada por IA) está sem memória

**Corrigido:**

* &lbrack;Camadas&rbrack; A imagem para material (viabilizada por IA) não funciona com fluxos de trabalho de Specular/Textura reluzente
* &lbrack;Camadas&rbrack; Falha quando está fora da memória de vídeo ao usar Imagem para material (alimentado por IA)
* &lbrack;Camadas&rbrack; O cache de disco não é usado para exibição ao abrir uma pilha
* &lbrack;Camadas&rbrack; Detecção de Nvidia RTX 8000
* &lbrack;Camadas&rbrack; Às vezes, é impossível mover uma camada para fora de uma entrada Splatter
* &lbrack;Camadas&rbrack; O cache de disco não é usado ao inserir uma pilha em uma pilha
* &lbrack;Camadas&rbrack; Alguns usos de canal são computados embora não sejam usados
* &lbrack;Camadas&rbrack; Saídas em branco são criadas às vezes ao importar imagens
* &lbrack;Exibição 2D&rbrack; Alternando para outra camada com o modo de Desenho ativa bloqueia a panorâmica e o zoom
* &lbrack;Content&brack; Snow - Problema de 8 bits no mapa normal
* &lbrack;Content&brack; Padrão de pavimento - problema de 8 bits no mapa normal
* &lbrack;Content&brack; Equalizador - Problema de 8 bits no mapa normal
* &lbrack;Content&brack; Gravel Generator - problema de 8 bits no mapa normal
* &lbrack;Content&brack; Floor Tiles - Manipular opacidade e specular level
* &lbrack;Content&rbrack; O mesclador reinicia a predefinição de exportação - inverter mapa normal
* &lbrack;Content&brack; Corrigir problema com imagens enormes com Imagem para material (alimentado por IA)
* &lbrack;Application&brack; Falha ao escolher “Fazer Backup e Reiniciar” em erro de banco de dados
* &lbrack;Aplicativo&rbrack; Falha ao clicar rapidamente no mesmo ativo
* &lbrack;Aplicativo&rbrack; Falha rara ao sair
* &lbrack;Aplicativo&rbrack; Falha ao soltar arquivos na tela de boas-vindas
* &lbrack;Aplicativo&rbrack; Falha quando um arquivo de ambiente corrompido é carregado
* &lbrack;Aplicativo&rbrack; Falha rara ao alternar rapidamente ativo renderizado
* &lbrack;Aplicativo&rbrack; Congela ao sair enquanto um ativo está sendo calculado
* &lbrack;Aplicativo&rbrack; Falha rara na inicialização no macos
* &lbrack;Aplicativo&rbrack; Bloqueio ao fechar o aplicativo logo após a inicialização
* &lbrack;Renderizando&brack; a visualização 3D às vezes pisca
* &lbrack;UI&rbrack; O seletor de cores e os widgets de semente aleatórios não estão alinhados com o restante dos ajustes
* &lbrack;Renderização&rbrack; Tempo de computação incorreto exibido
* &lbrack;Export&brack; Algumas predefinições de exportação às vezes estão ausentes

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.2.0 (2020.2.0) Udon

*(Lançado: 15 de junho de 2020)*

**Adicionado:**

* &lbrack;Criar&brack; Novo filtro de Imagem para Material (alimentado por IA) disponível no Windows e no Linux
* &lbrack;Criar&rbrack; Renomear Bitmap como Material para Imagem como Material (B2M)
* &preto;Importação de imagem&rbrack; Pop-up Modelo de criação de novo material
* &lbrack;Importação de imagem&rbrack; Nova opção “Adicionar um material de base”
* &lbrack;Importação de imagem&rbrack; Ser capaz de arrastar e soltar imagens adicionais no Modelo de criação de material
* &lbrack;Importação de imagem&rbrack; Ser capaz de remover imagens no Modelo de criação de material
* &preto;Importação de imagem&rbrack; Atribui canal aos bitmaps importados automaticamente com base no nome do arquivo
* &preto;Importação de imagem&rbrack; Ser capaz de inverter mapas normais
* &lbrack;Visualização 2D&rbrack; Introdução de um modo de pintura
* &lbrack;Exibição 2D&rbrack; Os blocos de pintura
* &lbrack;Visualização 2D; Define um valor em tons de cinza para a cor do pincel
* &lbrack;Exibição 2D&rbrack; Panorâmica e zoom ao pintar
* &lbrack;Visualização 2D&rbrack; X atalho para inverter o valor do pincel em escala de cinza
* &lbrack;Exibição 2D&rbrack; &lbrack; e &rbrack; atalhos para alterar o tamanho do pincel
* &lbrack;Exibição 2D&rbrack; Ctrl (ou Cmd) + Roda do mouse alteram o tamanho do pincel
* &lbrack;Exibição 2D&rbrack; Agora é possível modificar a posição do código-fonte ao usar Clonar correção
* &preto;Camadas&rbrack; Shift + arrastar e soltar para atlas de dispersão automática
* &lbrack;Camadas&rbrack; Alt + arrastar e soltar insere um material como um decalque
* &lbrack;Camadas&rbrack; Expor facilmente as matriz de transformação do Substance Designer
* &lbrack;Camadas&rbrack; Soltar texturas em uma pilha não vazia automaticamente atribui aos canais corretos
* &lbrack;Camadas&rbrack; Novo tipo de camada: Filtros compostos
* &lbrack;Parâmetros&rbrack; Suporte a entradas de cadeia de caracteres de Substance
* &lbrack;UI&rbrack; Sombras projetadas adicionadas para pop-ups e menus
* &lbrack;UI&rbrack; Novo Widget de Cor com opções do botão direito (limpar, copiar, colar)
* &lbrack;UI&rbrack; Novo widget de imagem com a opção de ferramenta Pintura
* &lbrack;UI&rbrack; Ser capaz de pintar sobre uma imagem importada em um widget de imagem
* &lbrack;Renderização&rbrack; Nova posição padrão da câmera
* &lbrack;Exportar&rbrack; os arquivos de Substance são exportados para o Substance Designer 2020.1.2 (10.1.2)
* &lbrack;Desempenho&rbrack; Melhor tempo de inicialização do aplicativo
* &lbrack;Desempenho&rbrack; Melhorar a manipulação de tarefas assíncronas
* &lbrack;Desempenho&rbrack; Melhorar o desempenho da pilha de camadas ao adicionar, remover ou mover camadas
* &lbrack;Desempenho&rbrack; Imagem para material (com IA) é executada mais rapidamente em GPUs RTX
* &lbrack;Content&brack; Novas malhas: Camiseta Feminina, Camiseta Masculina, Sapato
* &lbrack;Content&rbrack; Novo Modo de Mesclagem - Mesclagem por Canal
* &lbrack;Conteúdo&rbrack; Opacidade mesclar correção de height com 2 novos parâmetros (posição do height e escala do height)
* &lbrack;Content&brack; Adicionar ajustes de Height no modo de mesclagem Height
* &lbrack;Content&rbrack; Usar a opção de informações do Height na Mesclagem de máscaras personalizadas
* &lbrack;Content&rbrack; Nova ferramenta de correção de perspectiva
* &lbrack;Gerador de padrões do Content&brack; - Adicionar um parâmetro para inverter o padrão
* &lbrack;Content&brack; Gerador de padrões - Adicionar um novo parâmetro Sobrescrever detalhes do material
* &brack;Content&brack; Novo filtro de decalques
* &lbrack;Content&brack; Novo filtro de musgo
* &lbrack;Content&brack; Novo filtro do Rachadura
* &lbrack;Content&brack; Novo filtro de Validações do PBR
* &lbrack;Content&brack; Novo Blocos de Piso, filtro
* &lbrack;Content&brack; Novo Filtro Colar Comichão
* &lbrack;Content&brack; Atlas scatter - Adicionar entrada de Máscara personalizada para ativar a opção de pintura
* &lbrack;Content&brack; Dirt - Adicionar entrada de Máscara personalizada para ativar a opção de pintura
* &amp;predefinição de exportação de CLO do &brack;Content&brack;
* &amp;predefinição de exportação do VStitcher; Content&brack;
* &lbrack;Content&brack; Unity HDRP presets exportar um detailMap

**Corrigido:**

* &lbrack;Camadas&rbrack; As imagens importadas são carregadas muitas vezes
* &lbrack;Camadas&rbrack; Falha ao criar uma correção de clone na parte inferior da pilha
* &lbrack;Camadas&rbrack; Adicionar um material na parte inferior da pilha o torna instável
* &lbrack;Camadas&rbrack; Filtro após importação de imagem funciona incorretamente
* &lbrack;Layers&brack; o valor workflow_type não é atualizado ao alternar o fluxo de trabalho entre projetos com um filtro personalizado
* &lbrack;Camadas&rbrack; Desativar o botão “remover camada” quando nenhuma camada estiver selecionada
* &lbrack;Camadas&rbrack; Falha ao carregar um ativo contendo uma correção de clone
* &lbrack;Camadas&rbrack; O filtro Normal para Height trava no MacOs
* &lbrack;Application&brack; Falha ao carregar mapas de ambiente para frente e para trás
* &lbrack;Aplicativo&rbrack; Problemas de desempenho quando algum driver de tablet gráfico está instalado
* &lbrack;Application&brack; os arquivos de 32 bits EXR importados são pretos
* &lbrack;O aplicativo &rbrack; trava ao carregar e descarregar ativos
* &lbrack;Aplicativo&rbrack; Falha ao alternar de explorar para criar
* &lbrack;Aplicativo&rbrack; A coleção de destino ao salvar um material não é do projeto atual
* &lbrack;Aplicativo&rbrack; Corrigir backup e reiniciar
* &preto;Importação de imagem&rbrack; Importar imagens em tons de cinza corretamente
* &lbrack;Content&brack; Novos filtros para nova manipulação de matriz
* &lbrack;Conteúdo&rbrack; Os filtros personalizados importados são visíveis na barra de acesso rápido
* &lbrack;Content&brack; Corrigir mudança de cor com o filtro avançado Tornar bloco
* &lbrack;Desempenho&rbrack; Abrir uma caixa de diálogo de cores é lento e recalcula a camada atual
* Atalhos de teclado do &brack;UI&rbrack; às vezes não funcionam
* &lbrack;2D Visualizar&rbrack; Preenchimento sensível a conteúdo precisa de um primeiro clique inútil para funcionar
* &lbrack;Recursos&rbrack; As pastas em discos locais ainda são monitoradas por atualizações após sua remoção
* &lbrack;Resources&rbrack; Excluir uma pasta vinculada do sistema de arquivos não a remove
* &preto;Exportar&rbrack; Os usos personalizados em predefinições de exportação personalizadas não são exportados
* &lbrack;Export&brack; Falha ao exportar arquivo .sbsar com caracteres especiais no caminho

**Problemas Conhecidos:**

* Recálculos repetitivos de imagem para material (com IA) podem acionar um travamento (memória insuficiente)
* Recálculos repetitivos do Delighter podem disparar uma falha (memória insuficiente)
* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* O uso de imagem para material (alimentado por IA) em GPU com baixo VRAM pode acionar uma falha (memória insuficiente)
* A imagem para material (alimentada por IA) não está disponível em Specular/textura reluzente de PBR
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.1.1 (2020.1.1) Tiramisu

*(Lançado em: 01 de abril de 2020)*

**Adicionado:**

* &lbrack;Projeto&rbrack; Exportar e importar metadados
* &lbrack;Application&brack; Ctrl+S agora salva uma predefinição em Explorar
* &lbrack;Desempenho&rbrack; Usar cache de renderização em vez de recalcular materiais salvos para resoluções de até 2k

**Corrigido:**

* &lbrack;UI&rbrack; Indicador de computação fixa no visor
* &lbrack;UI&rbrack; A inserção de valores negativos nos controles deslizantes é fixa
* &lbrack;UI&rbrack; Caixas de combinação: setas do teclado e barra de rolagem agora funcionam
* &lbrack;UI&rbrack; Mantenha o canal selecionado ao alternar entre “Saídas de material” e “Entradas de camada” na exibição 2D
* &lbrack;Camadas&rbrack; Corrigido um erro fatal ao adicionar canais personalizados no Material de base
* &lbrack;Camadas&rbrack; Falha ao manipular camadas
* &lbrack;Camadas&rbrack; Os canais personalizados não são exibidos com um material salvo
* &lbrack;Aplicativo&rbrack; Corrigido uma falha rara ao importar um ativo
* &lbrack;O aplicativo &rbrack; falha ao sair
* As caixas de combinação do &brack;Application&brack; agora mostram os valores corretos ao alternar as predefinições
* &lbrack;Export&rbrack; Predefinição de paisagem renomeada para Enscape Revit
* &amp;predefinição;Exportar&amp;predefinição; Importar uma predefinição de exportação após removê-la funciona
* &lbrack;Export&brack; Falha na exportação
* &lbrack;Renderização&rbrack; Renderização fixa quando a cor base está no formato half float de 16 bits
* &lbrack;Projeto&rbrack; Não falhar ao importar pacote corrompido
* &lbrack;Project&rbrack; Manipular a migração 2019.1.4 para 2.x.x quando Criar nunca tiver sido aberto
* &lbrack;Projeto&rbrack; Corrigir uma falha ao importar o mesmo projeto duas vezes
* &lbrack;Projeto&rbrack; Corrigir uma falha ao importar projetos
* &lbrack;Recursos&rbrack; Os filtros personalizados importados em versões anteriores funcionam
* &lbrack;Recursos&rbrack; Os materiais com o mesmo nome não se apagam mais
* &lbrack;Resources&rbrack; Falha ao vincular uma pasta local
* &lbrack;Resources&rbrack; As pastas criadas pelo usuário dos materiais de início não são mais removidas após uma reinicialização
* &lbrack;Inspire&brack; Corrija a área de soltar material/coleção e adicione uma mensagem de aviso se estiver usando um material não salvo

**Problemas Conhecidos:**

* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante

### 2.1.0 (2020.1.0) Tiramisu

*(Lançado: 12 De março De 2020)*

**Adicionado:**

* &lbrack;Export&brack; Exportar seleção predefinida para empacotar suas texturas para renderizadores e mecanismos de jogo
* &lbrack;Export&brack; Exportar predefinição para Unreal Engine 4
* &amp;predefinição de Exportação do &brack; para o Padrão de Unidade
* &amp;predefinição Exportar; &amp;predefinição Exportar para Unity HDRP
* &amp;predefinição de Exportar para Ciclos de Mesclagem/Evee
* &preset;Exportar predefinição para Arnold 5
* &preto;Exportar &rbrack; Exportar predefinição para Renderizador Corona
* &amp;predefinição;Exportar &amp;predefinição para o Enscape
* &preto;Exportar &rbrack; Exportar predefinição para Keyshot 9
* &amp;predefinição;Exportar &amp;predefinição para Redshift
* &preset;Exportar predefinição para Vray Next
* &preset;Exportar predefinição para o Lens Studio
* &amp;predefinição de Exportação do Adobe Spark; para Spark AR Studio
* &lbrack;Export&brack; Exportar predefinição para Specular PBR Brilho da Aspereza metálica PBR
* &lbrack;Export&brack; Nova interface de exportação
* &preto;Exportar&rbrack; Lembrar configurações de exportação
* &amp;predefinição;Exportar&amp;predefinição; Importar e gerenciar suas predefinições de exportação personalizadas
* &amp;predefinição;Exportar&amp;predefinição; Excluir e substituir suas predefinições de exportação personalizadas
* &preto;Exportar&rbrack; Renomeia suas predefinições de exportação personalizadas
* &preto;Export&brack; Define a resolução de exportação padrão para a resolução atual
* &lbrack;Export&brack; Adicionar a opção de criar uma subpasta para o local de exportação
* &lbrack;Exportar&rbrack; Mensagem de aviso antes de substituir arquivos existentes
* &lbrack;Aplicativo&rbrack; Novo esquema de numeração de versão
* &lbrack;Aplicativo&rbrack; Abrir Criar na inicialização e alterar ordem dos laboratórios
* &preto;Tela de boas-vindas&rbrack; Novo banner de boas-vindas
* &lbrack;Projeto&rbrack; Abrir último projeto na inicialização
* &lbrack;UI&rbrack; Novo estilo de caixa de combinação
* &lbrack;exibição 2D&rbrack; F atalho para focalizar na exibição 2d
* &lbrack;Filtros&rbrack; Adicionado suporte para a tag alchemist::parameterVisibility em gráficos de Substance
* &lbrack;Filtros&rbrack; Tenha um ajuste global para gerenciar a visibilidade de parâmetros com base no seu fluxo de trabalho
* &lbrack;Resources&rbrack; Nova opção de linha de comando para configurar recursos e pastas vinculadas com um arquivo de configuração
* &lbrack;Verificador de versão&rbrack; Configuração da verificação de versão
* &lbrack;Content&brack; Novos materiais iniciais
* &lbrack;Content&brack; Bitmap para Material - Adiciona a possibilidade de definir o canal metálico (uniforme, importação de imagem personalizada, escolha de cores)
* &lbrack;Content&brack; Adjustment - Adicionar o suporte do fluxo de trabalho de specular/brilho PBR
* &lbrack;Content&brack; Atlas scatter - Novos parâmetros

**Corrigido:**

* &lbrack;Projeto&rbrack; Falha ao importar o mesmo projeto duas vezes
* &lbrack;Projeto&rbrack; Corrigido um erro fatal ao importar e abrir projetos várias vezes
* &lbrack;Aplicativo&rbrack; Falha ao carregar um material sem nome
* &lbrack;Aplicativo&rbrack; Reconhecer arquivos ausentes ao importá-los novamente
* &lbrack;Aplicativo&rbrack; Corrigir falha aleatória ao desligar
* &lbrack;Aplicativo&rbrack; Corrigido uma falha rara ao descarregar um material em Criar
* &lbrack;Aplicativo&rbrack; Corrigido um erro fatal aleatório ao usar controles da interface do usuário
* &lbrack;Aplicativo&rbrack; Corrigida a exportação de arquivos de log para a área de trabalho no Windows 10
* O painel de Exportação do &lbrack;UI&rbrack; tem o tamanho incorreto quando você o abre em Criar
* &lbrack;UI&rbrack; Abrir projeto com um único clique
* &lbrack;UI&rbrack; Define corretamente os valores mínimos e máximos da barra deslizante
* &lbrack;UI&rbrack; Mostrar rótulo dos usos do canal em vez de ids
* &lbrack;UI&rbrack; Clicar em um material sempre abre/fecha o painel de ajuste
* &lbrack;UI&rbrack; Corrigir cores de camadas ocultas
* &lbrack;UI&rbrack; Melhorias nos botões da Tela de Boas-vindas
* &lbrack;Camadas&rbrack; Recomputações menos desnecessárias
* &lbrack;Camadas&rbrack; Falha ao usar o Clonar Patch
* &lbrack;Camadas&rbrack; Selecionar uma camada de importação de imagem não dispara mais um computador
* &lbrack;Camadas&rbrack; Clonar As camadas de Correção e Preenchimento sensível a conteúdo não são mais recalculadas quando selecionadas
* &lbrack;Configurações do canal&rbrack; Ativar ou desativar os usos agora aciona uma renderização
* &lbrack;Resources&rbrack; Impedir o congelamento ao clicar em massa em uma pilha da biblioteca
* &lbrack;Recursos&rbrack; Acerto de desempenho ao readicionar uma pasta vinculada adicionada anteriormente
* &lbrack;Recursos&rbrack; Corrigido um erro fatal ao tentar abrir um arquivo .sbsar excluído
* &lbrack;Performance&rbrack; Evite carregar materiais para acessar seus parâmetros
* &lbrack;Desempenho&rbrack; Fazer backup de ativos somente quando usado em um projeto ou em um material criado
* &lbrack;Export&brack; Materiais fixos na fila de exportação às vezes ignorados ou exportados com parâmetros errados
* &lbrack;Visualização 2D; Panorâmica e zoom restaurados
* &lbrack;Content&brack; Parquet Pattern leva em consideração o canal de Oclusão de ambiente
* &lbrack;Content&brack; Tinta - Exibe a entrada da máscara ao ativar a máscara personalizada
* &lbrack;Content&brack; Stonewall Pattern - Remover possíveis efeitos de bandas no mapa normal
* &lbrack;Content&rbrack; Height Modulation - Corrigir entradas de cor de base dupla na exibição 2d

**Problemas Conhecidos:**

* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante

## Versão 1

### 1.1.4 (2019.1.4) Sésamo

*(Lançado: 30 De Janeiro De 2020)*

**Adicionado:**

* &lbrack;Resources&rbrack; Prompt de confirmação ao limpar uma pasta de recursos

**Corrigido:**

* &preto;Camadas&rbrack; Mover camadas para duas e mais camadas abaixo ou acima
* &lbrack;Criar&rbrack; Alocação de orçamento VRAM suficiente para ter bons desempenhos

**Problemas Conhecidos:**

* Importar muitos recursos pode realmente tornar o Substance Alchemist mais lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para Height pode falhar no MacOS

### 1.1.3 (2019.1.3) Sésamo

*(Lançado: 28 De Janeiro De 2020)*

**Adicionado:**

* &lbrack;Workflow&rbrack; Suporte a vários fluxos de trabalho
* &lbrack;Fluxo de trabalho&rbrack; Suporte ao fluxo de trabalho de Brilho de Specular PBR
* &lbrack;Fluxo de trabalho&rbrack; Novo painel de Configurações do canal
* &lbrack;Fluxo de trabalho&rbrack; Seleção de fluxo de trabalho na criação do projeto
* &lbrack;Configurações do canal&rbrack; Ativar/desativar o cálculo específico do canal
* &lbrack;Configurações do canal&rbrack; Exibe a lista de canais personalizados disponíveis no material atual
* &lbrack;Configurações do canal&rbrack; Cálculo automático de canais personalizados quando necessário
* &preto;Configurações do canal&rbrack; Forçar/Bloquear computação de canais personalizados
* &lbrack;Camadas&rbrack; Nova interface do usuário do espaço reservado de entrada de material nos filtros de Atlas scatter e Respingo
* &lbrack;Camadas&rbrack; O parâmetro de Entrada de Imagem de um filtro pode ser alimentado por camadas inferiores
* &lbrack;Camadas&rbrack; Exibir uma notificação quando algumas camadas estiverem desatualizadas
* &lbrack;Camadas&rbrack; Possibilidade de atualizar para a versão mais recente de camadas desatualizadas por meio da notificação
* &lbrack;Projeto&rbrack; Novos campos de metadados na criação do projeto
* &lbrack;Inspire&brack; As variações geradas são específicas de um projeto
* &lbrack;Visualização 2D&rbrack; Alternar entre as entradas da camada, as saídas da camada e as saídas de material
* &lbrack;Tela de boas-vindas&rbrack; Adicionar opção de importar projeto (.alch)
* &lbrack;Preferências&rbrack; Nova janela de Preferências para definir a localização do cache e as configurações de privacidade analítica
* &lbrack;UI&rbrack; Novos botões de interface
* &lbrack;Desempenho&rbrack; Melhoria geral do sistema de paralelização
* &lbrack;Desempenho&rbrack; Otimização do número de computadores de material
* &lbrack;Atualização do Substance Engine do motor&rbrack;
* &lbrack;Framework&rbrack; Atualize para o Qt 5.13
* &lbrack;MacOS&rbrack; Melhorias globais do suporte ao macOS Catalina
* &lbrack;Content&brack; Filtro de ajuste - Intensidade normal e parâmetros invertidos

**Corrigido:**

* &lbrack;Camadas&rbrack; Parâmetro Cancelar definição da entrada de imagem ao excluir a camada
* &lbrack;Camadas&rbrack; Corrigir uma falha ao adicionar uma camada de correção de clone
* &lbrack;Camadas&rbrack; Corrigir algumas falhas ao mesclar camadas para empilhar materiais em outros materiais de pilha de camadas
* A seleção de canais para exportação do &brack;Export&brack; agora é respeitada
* &lbrack;Recursos&rbrack; Não trave ao navegar no painel Recursos
* &lbrack;Resources&rbrack; Corrigir falha ao importar arquivos de Substance corrompidos
* &lbrack;Resources&rbrack; Reduz o número de falhas ao carregar pastas grandes
* &lbrack;Miniatura&rbrack; O cálculo da miniatura não congela a interface
* &lbrack;Importação de imagem&rbrack; Uniformização de tipo de imagem suportada pelo aplicativo
* &amp;Preset&brack; Salve a descrição ao criar uma predefinição a partir de um SBSAR
* &lbrack;Inspire&brack; Corrigir arrastar e soltar imagem
* &lbrack;O aplicativo &rbrack; corrige falhas ao sair
* &lbrack;Correção do aplicativo&rbrack; falha ao sair ao exportar materiais
* &lbrack;UI&rbrack; Correções e melhorias
* &lbrack;UI&rbrack; Renomeia o ativo temporário para “material não salvo”
* &lbrack;Content&brack; Atualização global e limpeza de todos os filtros

**Problemas Conhecidos:**

* Importar muitos recursos pode realmente tornar o Substance Alchemist mais lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para Height pode falhar no MacOS

### 1.1.2 (2019.1.2) Sésamo

*(Lançado: 11 de dezembro de 2019)*

**Adicionado:**

* &preto;Camadas&rbrack; As opções Salvar e Salvar como podem ser acessadas pela interface na barra de ferramentas da pilha de camadas
* &lbrack;Recursos&rbrack; Trilha de navegação mais nítida no painel Recursos para navegar pelas pastas
* &lbrack;Recursos&rbrack; botão Manter anterior pressionado para acessar todas as pastas superiores
* &lbrack;Resources&rbrack; Adicionar recarregamento de materiais importados opção para atualizá-los para a versão mais recente
* &lbrack;Camadas&rbrack; Possibilidade de alterar a imagem na camada de importação da imagem
* &lbrack;Camadas&rbrack; Possibilidade de definir uma imagem como um canal (cor de base, normal, height,...) na camada de importação de imagem
* &lbrack;Content&brack; Novo filtro de Atlas scatter para dispersão novos elementos atlas de Substance Source
* &lbrack;Content&brack; Novo filtro Efeito de Tinta a óleo
* &lbrack;Content&brack; Novo filtro de Geração de Canais para gerar height, oclusão de ambiente e aspereza a partir de cor de base e mapas normais

**Corrigido:**

* &lbrack;UI&rbrack; Reativar dicas de ferramentas na barra de ferramentas da pilha de camadas
* &lbrack;UI&rbrack; Corrigir problema ao digitar duas casas decimais em um valor de controle deslizante
* &lbrack;Performance&rbrack; Corrigir falha ao alternar rapidamente entre materiais
* &lbrack;Export&brack; Alternar para outro material antes do final de uma exportação não trava mais
* &lbrack;Recursos&rbrack; O menu de contexto é exibido na parte superior do material quando você clica com o botão direito nele
* &lbrack;Camadas&rbrack; O link “Clique aqui” está funcionando quando a pilha de camadas estiver vazia
* &lbrack;Predefinições&rbrack; Remove o botão Salvar no painel Ajustar quando for um material criado em Alchemist
* &lbrack;Tweak&rbrack; Mensagem de informações exibida quando é um material criado no Alchemist
* &lbrack;Viewport&rbrack; O valor padrão da textura de Specular level foi corrigido para 0,04
* &lbrack;Menu Arquivo&rbrack; Corrigir e renomear a opção Salvar e Salvar como
* &lbrack;Engine&rbrack; Atualize a versão do mecanismo de Substance para evitar a falha de alguns arquivos SBSAR durante a importação.
* &lbrack;Content&rbrack; O filtro de divisão em blocos está funcionando no canal de oclusão de ambiente
* &lbrack;Content&rbrack; O filtro Cortar está funcionando no canal de oclusão de ambiente
* &lbrack;Content&brack; O filtro Água modifica o mapa de alturas
* &lbrack;Content&brack; Corrigir divisão em blocos gráficos do material superior no modo de mesclagem de opacidade
* &lbrack;O Height de conteúdo&rbrack; do material superior é preservado no modo de mesclagem de opacidade
* &lbrack;Content&brack; Possível adicionar uma máscara personalizada, um padrão personalizado ou um mapa de escala no filtro de Perfuração
* O filtro de modulação de Height &lbrack;Content&rbrack; força o height e os mapas normais em 16 bits
* O filtro &lbrack;Content&rbrack; Ajuste força height e mapas normais em 16 bits

**Problemas Conhecidos:**

* Importar muitos recursos pode realmente tornar o Substance Alchemist mais lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para Height pode falhar no MacOS

### 1.1.1 (2019.1.1) Sésamo

*(Lançado: 26 De novembro De 2019)*

**Adicionado:**

* &lbrack;Mesclagem&rbrack; Novo modo de mesclagem de opacidade
* &lbrack;Engine&rbrack; Nova versão do Substance Engine

**Corrigido:**

* &lbrack;Camadas&rbrack; Corrigir falha ao excluir uma camada que ainda está em processamento
* &lbrack;Camadas&rbrack; Corrigir falha ao remover a camada inferior
* &lbrack;Camadas&rbrack; Corrigir falha enquanto o nome do material contém caracteres especiais
* &lbrack;Camadas&rbrack; Parar de computar todos os filtros que usam um widget
* &lbrack;Camadas&rbrack; Evite falhas ao usar os filtros Patch de Clone e Preenchimento sensível ao conteúdo
* &lbrack;Camadas&rbrack; Corrigir falha ao arrastar e soltar um filtro em slots de entrada de respingos
* &lbrack;Recursos&rbrack; Corrigir falha ao vincular pastas locais ou importar recursos no Substance Alchemist
* &lbrack;Collection&rbrack; Corrigir falha ao alternar rapidamente entre materiais
* &lbrack;UI&rbrack; Corrigir falha enquanto o valor é nulo ou inválido na divisão em blocos gráficos, controles deslizantes de deslocamento na viewport
* &lbrack;Inspire&rbrack; Corrigir falha ao acessar a guia Inspire
* &lbrack;Inspire&brack; Corrigir falha ao inspirar em um material de pilha de camadas recém-salvas
* &lbrack;Performance&rbrack; Computação de materiais e filtros de Substance pesados (Lado a lado) mais rápida
* &lbrack;Ajuda&rbrack; Corrigir arquivo de log de exportação
* &lbrack;Content&brack; O filtro Aleatório funciona em todos os canais
* &lbrack;Content&brack; O fluxo de trabalho de multiângulo leva todas as digitalizações em consideração
* &lbrack;Content&brack; AO Mesclar mistura correta
* &lbrack;Conteúdo&rbrack; Curvatura Mesclar mistura correta
* &lbrack;Content&brack; Mistura correta da ID de cor
* &lbrack;Content&brack; Mesclagem de máscara personalizada correta
* &lbrack;Content&rbrack; Corrigir filtro de ajuste para modificação de aspereza
* &lbrack;Content&rbrack; Corrigir filtro de Material de base para upload de canais normais personalizados
* &lbrack;Content&brack; Corrigir padrão de importação personalizada do filtro de entalhe

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para Height pode falhar no MacOS

### 1.1.0 (2019.1.0) Sésamo

*(Lançado em: 04 de novembro de 2019)*

**Adicionado:**

* &lbrack;Projeto&rbrack; Criação de um projeto
* &lbrack;Projeto&rbrack; Introdução do formato de arquivo .alch que contém dados do projeto
* &lbrack;Projeto&rbrack; Exportar um projeto .alch contendo as coleções e seus materiais
* &lbrack;Projeto&rbrack; Importar um projeto .alch
* &preto;Projeto&rbrack; Abrir projetos recentes
* &lbrack;Tela de boas-vindas&rbrack; Uma tela de boas-vindas é exibida na inicialização
* &Preenchimento;Tela de boas-vindas&Preenchimento; Criar um projeto a partir da tela de boas-vindas
* &prego;Tela de boas-vindas&rbrack; Acesse a lista de todos os seus projetos na tela de boas-vindas
* &lbrack;Tela de boas-vindas&rbrack; Links rápidos para acessar a documentação, o pop-up sobre e o gerenciamento de licenças
* &lbrack;Menu Arquivo&rbrack; Integração de um Menu de arquivos
* &lbrack;Menu Arquivo&rbrack; Acesse os comandos do projeto na guia Arquivo e salve a pilha de camadas
* &preto;Menu Arquivo&rbrack; Acesse os comandos Desfazer e Refazer na guia Editar
* &lbrack;Menu Arquivo&rbrack; O menu de ajuda anterior foi movido no menu Arquivo na guia Ajuda
* &lbrack;Camadas&rbrack; Nova arquitetura da pilha de camadas
* &lbrack;Camadas&rbrack; Nova interface do usuário da pilha de camadas
* &lbrack;Camadas&rbrack; Selecione o modo de mesclagem diretamente na barra de ferramentas
* &lbrack;Camadas&rbrack; Acessar separadamente os parâmetros de mesclagem e os parâmetros de material
* &lbrack;Camadas&rbrack; Adicionar materiais diretamente nas entradas dedicadas do filtro Respingo na pilha de camadas
* &lbrack;Camadas&rbrack; Altera a ordem de digitalização diretamente na camada de importação de imagem
* &lbrack;Visor&rbrack; Controle do campo de visão da câmera
* &lbrack;Visor&rbrack; Possibilidade de alternar entre a câmera ortográfica ou de perspectiva
* &lbrack;Visor&rbrack; Resolução de exibição e informações de profundidade de bits para cada canal
* &lbrack;Recursos&rbrack; Materiais de base é aberto por padrão
* &lbrack;Cache&rbrack; Localiza a pasta de cache em miniaturas
* &lbrack;Cache&rbrack; Localiza sua pasta de cache de renderização
* &lbrack;Painéis&rbrack; O painel Configurações de material está temporariamente oculto
* &lbrack;Fluxo de trabalho&rbrack; Specular/Textura reluzente temporariamente desativado
* &lbrack;MacOS&rbrack; Autenticação da versão do Catalina OS
* &lbrack;Content&brack; Nova versão do filtro Delighter
* &lbrack;Content&brack; Novo filtro de Preenchimento sensível ao conteúdo da imagem
* &lbrack;Content&brack; Novo filtro de Preenchimento sensível a conteúdo de material
* O filtro de Transformação do &Preenchimento; tem uma opção de transformação segura

**Corrigido:**

* Todos os erros anteriores relacionados ao Create são inválidos hoje com a nova interface do usuário e a versão da arquitetura
* As dicas de ferramenta não ocultam os ícones na barra superior (3D, 2D, 2D/3D)
* &lbrack;Content&rbrack; O filtro Respingo aceita Atlas com mapa de altura completo
* &lbrack;Content&brack; O filtro Transformar funciona em imagens (scan1, scan2,...)

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para Height pode falhar no MacOS

## Beta

### Quinoa 0. 8. 1- beta

*(Lançado em: 19 de agosto de 2019)*

**Adicionado:**

* Capacidade de enviar ativos de Substance Source do iniciador para o Substance Alchemist do projeto

**Corrigido:**

* &lbrack;Create&brack; Alguns filtros foram listados no acessador rápido, mas não no painel de filtros
* &lbrack;O MacOS&rbrack; corrigiu algumas falhas ao sair

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter não é recomendado
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para height pode falhar no MacOS
* Ainda pode travar aleatoriamente ao sair no MacOS

### Quinoa 0. 8. 0- beta

*(Lançado em: 08 de agosto de 2019)*

**Adicionado:**

* &lbrack;Resources&rbrack; Conectar e espelhar as pastas de materiais nos discos locais
* &lbrack;Resources&rbrack; Procure as pastas de materiais e suas subpastas
* &lbrack;Recursos&rbrack; Destacar o painel de recursos de material em uma janela separada para ver seus recursos em tela cheia
* &lbrack;Recursos&rbrack; Novo painel Recursos Layout para suportar a navegação em pastas e subpastas
* &lbrack;Recursos&rbrack; Use a estrutura para navegar pelas suas pastas
* &lbrack;Resources&rbrack; Forçar a sincronização da pasta local com a opção Sincronizar acessível com um clique com o botão direito do mouse
* &lbrack;Recursos&rbrack; Desconecte a pasta local com a opção Desconectar acessível clicando com o botão direito do mouse
* &lbrack;Gerenciar&rbrack; Exibir tags incorporadas de arquivos Substance
* &lbrack;Gerenciar&rbrack; Adicionar, editar e excluir tags de seus materiais
* &lbrack;Gerenciar&rbrack; Avaliar seus materiais
* &lbrack;Camadas&rbrack; Suporte Panorama saída
* &lbrack;Camadas&rbrack; Você pode excluir entradas de imagem na camada de importação de imagem
* &lbrack;Camadas&rbrack; Seleção automática da nova camada adicionada
* &lbrack;Camadas&rbrack; Seleção automática da camada abaixo após a exclusão de uma camada
* &lbrack;UX&rbrack; Mantém a visibilidade dos painéis à esquerda ao alternar para outro Lab
* &lbrack;UX&rbrack; Não crie uma camada base ou abra o pop-up Fluxo de trabalho de material ao importar imagens em uma pilha de camadas não vazias
* &lbrack;UI&rbrack; Novo estilo de campo de texto
* &lbrack;UI&rbrack; Novo estilo de SearchBox
* &lbrack;UI&rbrack; Novo estilo de cabeçalho do painel
* &lbrack;UI&rbrack; Novo estilo de indicador Ocupado
* &lbrack;UI&rbrack; As novas camadas empilham o estilo de fundo
* &lbrack;UI&rbrack; Usar fonte Adobe Clean
* &lbrack;UI&rbrack; Remover espaço reservado do ícone de conta-gotas do parâmetro de entrada de cores
* &lbrack;Desempenho&rbrack; Otimização do indicador de Ocupado
* &lbrack;Content&brack; Novo filtro Gerador de Padrão
* &lbrack;Content&brack; Novo filtro de desfoque

**Corrigido:**

* &lbrack;Inspire&rbrack; Corrigir falha ao usar mais de 10 cores
* &lbrack;Visualização 2D; Corrigir a barra de rolagem na lista de canais da Visualização 2D
* &lbrack;Viewer&rbrack; Corrigir falha ao importar um mapa de ambiente sem energia de 2
* &lbrack;Content&brack; Corrigir importação de PNG para o padrão personalizado de filtros de Gravação e Perfuração
* &lbrack;Export&rbrack; Corrigir normal e height de 16 bits por canal de exportação
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

### &#x200B;0. 7. 0- beta Pimenta

*(Lançado: 13 de junho de 2019)*

**Adicionado:**

* &lbrack;Filtros&rbrack; Acesse rapidamente seus filtros pressionando a barra de espaço
* &lbrack;Filtros&rbrack; Novo painel dedicado para gerenciar, procurar e importar seus filtros
* &lbrack;Metadados&rbrack; Clique com o botão direito do mouse em um material para ver seus metadados
* &lbrack;Metadata&rbrack; Clique com o botão direito do mouse em um material para ver sua localização no disco
* &lbrack;Controles deslizantes&rbrack; Animar controles deslizantes ao passá-los pressionando Ctrl
* &lbrack;Sliders&rbrack; Pare e reinicie a animação dos controles deslizantes pressionando P
* &lbrack;Export&brack; a exportação de SBSAR segue as diretrizes de Substance Source
* &lbrack;Licença&rbrack; Ativar Substance Alchemist usando uma variável de ambiente
* A caixa de diálogo Arquivo do &lbrack;UX&rbrack; lembra o último caminho de arquivo selecionado
* A caixa de diálogo da pasta &lbrack;UX&rbrack; lembra o caminho da última pasta selecionada
* &lbrack;UI&rbrack; Atualizar interface do painel Recursos
* &lbrack;UI&rbrack; Atualizar Interface do Usuário da barra de pesquisa
* &lbrack;UI&rbrack; O ícone Criar novo material foi atualizado
* &lbrack;Ajuda&rbrack; URLs são atualizados para o domínio substance3d.com
* &lbrack;Mesh&rbrack; Uma malha de pano agora está disponível
* &lbrack;Content&brack; Novo filtro de corrosão
* &lbrack;Content&brack; Novo Filtro de Oxidação
* &lbrack;Content&brack; Novo Filtro de Musgo
* &lbrack;Content&rbrack; Novo Filtro de Dust
* &lbrack;Content&rbrack; Novo filtro de padrão de Brickwall
* &lbrack;Content&brack; Novo filtro de padrão Stonewall
* &lbrack;Content&brack; Novo filtro de acabamento em madeira
* &lbrack;Content&brack; Novo filtro de acabamento metálico
* &lbrack;Content&rbrack; Novo Filtro de Snow
* &lbrack;Content&brack; Novo filtro aleatório
* &lbrack;Content&brack; Agora você pode importar suas texturas diretamente no filtro Material de base

**Corrigido:**

* Corrigir uma falha ao salvar a pilha de camadas
* É possível adicionar um valor acima de 1 no controle deslizante de rotação do ambiente
* Não perca os parâmetros de mesclagem quando uma camada de mesclagem for transformada para frente e para trás de uma camada de mesclagem para uma camada de material
* Corrigir duplicatas ao gerar variações da mesma pilha de camadas várias vezes
* Ao reabrir um material, o Alchemist se lembra dos intervalos modificados (mínimo e máximo) dos controles deslizantes

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter não é recomendado
* A importação de ambiente personalizado pode ficar preta
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para height pode falhar no MacOS

### 0.6.1-beta Laranja

*(Lançado: 13 de junho de 2019)*

**Adicionado:**

* &lbrack;Engine&rbrack; atualização de Substance Engine para ser compatível com a versão mais recente do Substance Designer
* &lbrack;Licença&rbrack; Atualizar pasta de licenças para as primeiras instalações
* &lbrack;Camadas&rbrack; Recarregue a qualquer momento a pilha de camadas para atualizar seus filtros personalizados

**Corrigido:**

* &lbrack;Compatibilidade de Dados&rbrack; Correção preventiva para limitar a corrupção de dados no momento da atualização

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter não é recomendado
* A importação de ambiente personalizado pode ficar preta
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante

### 0.6.0-beta Laranja

*(Lançado: 18 de abril de 2019)*

**Adicionado:**

* &lbrack;Metadados&rbrack; Veja e preencha os metadados dos materiais em uma guia dedicada
* &amp;predefinição;Coleta&amp;predefinição; Cria uma coleção diretamente dos resultados da pesquisa
* &Preenchimento;Publicação de mídia&Rbrack; Exportar um quadro de uma coleção
* &lbrack;UX&rbrack; Desfazer uma alteração de ajuste ou importação de imagem pressionando Ctrl+Z
* &lbrack;UX&rbrack; Refaz uma alteração de ajuste ou importação de imagem pressionando Ctrl+Shift+Z
* &lbrack;UI&rbrack; Novos ícones com um novo estilo
* &lbrack;Desempenho&rbrack; Novo gerenciador de sessão para manipular melhor a alternância de guias
* &lbrack;Desempenho&rbrack; Abertura mais rápida da camada de importação de imagem
* &lbrack;Content&brack; Material genérico New Metal
* &lbrack;Content&brack; Novo material de Ferrugem
* &lbrack;Content&brack; Novo material genérico do Stone
* &preto;Content&brack; Atualização do filtro de entalhe
* &lbrack;Content&brack; Atualização do filtro de bordados
* &lbrack;Content&brack; atualização do filtro de Tinta
* &lbrack;Content&brack; Atualização do filtro Delighter

**Corrigido:**

* &lbrack;Content&brack; O filtro Água está funcionando no fluxo de trabalho Specular/Textura reluzente
* Corrigir o botão de opção de tons de cinza no pop-up de ativação
* Aceitar arquivos que contenham caracteres em coma
* Corrigir pequenos problemas de fonte nas janelas pop-up
* Corrigir problema de interface de transparência devido a um conflito com o parâmetro FXAA de algumas placas NVIDIA
* Remover o foco do campo depois de inserir um valor em um controle deslizante
* Aloque a quantidade mínima de VRAM para o delicioso para reduzir travamentos
* Corrigir o congelamento da janela ao redimensionar a janela do aplicativo
* Correção de uma falha em que a pilha de camadas era excluída durante a avaliação

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter não é recomendado
* A importação de ambiente personalizado pode ficar preta
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante

### &#x200B;0. 5. 4- beta Nacho

*(Lançado: 26 De março De 2019)*

**Corrigido:**

* &lbrack;Stack&brack; Falha ao remover uma camada de respingo
* &lbrack;Data&brack; O banco de dados de ativos é corrompido quando o aplicativo trava
* &lbrack;O Substance Alchemist do &DataBrack; não pode iniciar quando o banco de dados de ativos estiver corrompido
* Falha aleatória ao importar materiais do Substance

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho
* A importação de ambiente personalizado pode ficar preta
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* A coleção padrão na qual salvar pode estar vazia

### &#x200B;0. 5. 3- beta Nacho

*(Lançado: 19 De março De 2019)*

**Adicionado:**

* Pesquisar por nome do material no painel Recursos
* &lbrack;UI&rbrack; Ferramenta Clonar nova interface com visualização do tamanho do pincel
* &lbrack;UI&rbrack; Selecionar e excluir estágios ocultos
* &lbrack;UI&rbrack; Nova IU de Campo de Texto
* &lbrack;Ajuda&rbrack; Acessar sites da academia de Substance Source, Substance share e Substance
* &lbrack;Content&brack; Novos materiais padrão com geradores e atlas
* &lbrack;Content&brack; Bitmap para Atualização de Material
* &lbrack;Atualização de Dirt do Content&brack;
* &lbrack;Atualização de Ferrugem do Content&brack;
* &preto;Content&brack; Novo filtro de entalhe
* &lbrack;Content&brack; Novo filtro de Bordado
* &lbrack;Content&brack; Novo Filtro de erosão
* &lbrack;Content&rbrack; Novo Gerador de cascalho
* &lbrack;Content&brack; Novo filtro de Tinta
* &lbrack;Content&brack; Novo filtro Padrão de Assoalho
* &lbrack;Content&brack; Novo filtro de padrão de pavimentação
* &lbrack;Content&brack; Novo filtro de perfuração
* &lbrack;Content&brack; Novo filtro de respingo
* &lbrack;Content&brack; Novo filtro de Desgaste de Têxteis
* &lbrack;Content&brack; Novo filtro de Transformo

**Corrigido:**

* &lbrack;Visor&rbrack; Malha da esfera com divisão em blocos gráficos x2 em X
* &lbrack;Viewport&rbrack; Falha ao carregar seu próprio ambiente
* &lbrack;Viewport&rbrack; O mapa de ambiente agora está usando o valor de exposição também
* O atalho &brack;Viewport&rbrack; F não redefine o ângulo da câmera
* &lbrack;Exportar&rbrack; a exportação de SBS funciona com o Substance Designer mais recente 2018.3.3
* &lbrack;Export&brack; A exportação SBSAR respeita as mesmas diretrizes dos materiais Substance Source
* &lbrack;UI&rbrack; Barras de rolagem podem ser arrastadas
* Caracteres especiais são aceitos em caminhos de pasta e arquivo
* A miniatura é gerada novamente quando você salva o material

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho
* A importação de ambiente personalizado pode ficar preta
* Imagens tif não são exibidas no painel Propriedades na camada de importação de imagem
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* A coleção padrão na qual salvar pode estar vazia

### &#x200B;0. 5. 2- beta Nacho

*(Lançado em: 07 de março de 2019)*

**Adicionado:**

* Detecção e uso da GPU de alto perfil

**Corrigido:**

* O parâmetro Rotação tem um widget de controle deslizante adequado
* Corrigir a visibilidade da linha de cor azul ao arrastar e soltar materiais
* Corrigir a mesclagem de materiais ao soltar um material abaixo da primeira camada
* Conecte as entradas de imagem apenas se um caminho de imagem personalizado não estiver definido

**Problemas Conhecidos:**

* Caracteres especiais no caminho de arquivo impedem o salvamento de um material
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho
* Falha ao carregar seu próprio ambiente

### &#x200B;0. 5. 1- beta Nacho

*(Lançado em: 04 de março de 2019)*

**Corrigido:**

* Corrigir relatórios de falhas, relatórios de erros e pop-ups de licenças

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho
* Falha ao carregar seu próprio ambiente

### &#x200B;0. 5. 0- beta Nacho

*(Lançado: 28 de fevereiro de 2019)*

**Adicionado:**

* &lbrack;Pilha de camadas&rbrack; Reordenação de camadas
* &lbrack;Pilha de camadas&rbrack; Excluir uma camada oculta
* &lbrack;Pilha de camadas&rbrack; Importar um material diretamente na posição de sua escolha
* &lbrack;Pilha de camadas&rbrack; Entrada de material como um novo tipo de parâmetro de filtro
* &lbrack;Desempenho&rbrack; Substance Engine orçamento é dinâmico para melhores desempenhos
* &lbrack;Desempenho&rbrack; Melhores desempenhos do OpenGL, especialmente no MacOS
* &lbrack;Data&brack; Atualização de dados mais rápida após o lançamento de uma nova versão
* &lbrack;Content&brack; AI Delighter disponível no Windows 7 e no Windows 8
* &lbrack;Content&brack; AI Delighter disponível na GPU RTX

**Corrigido:**

* Corrigir possíveis falhas ao sair do aplicativo
* Exportar pop-up abre mais rapidamente ao exportar grandes coleções

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho
* Falha ao carregar seu próprio ambiente

### &#x200B;0. 4. 0- beta Muffin

*(Lançado: 17 De Janeiro De 2019)*

**Adicionado:**

* &lbrack;Exportar&rbrack; Substance (sbsar) exportar sua coleção
* &lbrack;Exportar&rbrack; arquivo Substance (sbs) exportar sua coleção
* &preto;Exportar&rbrack; Fila de exportação visível no painel Exportar
* &lbrack;Export&rbrack; Nomeie sua coleção ou material antes da exportação
* &preto;Data&brack; Salvar como seu material pressionando Ctrl+Shift+S
* &lbrack;Data&brack; Salve seu material pressionando Ctrl+S
* &lbrack;Data&brack; Coleções e Materiais são compatíveis entre as versões
* &lbrack;Data&brack; Atualize sua pilha de camadas de material com filtros atualizados
* &lbrack;Data&brack; Recarga a quente de filtros personalizados importados
* &lbrack;UI&rbrack; Feedback visual no visor enquanto ele está em computação
* &lbrack;UI&rbrack; Novo estilo de botão
* &lbrack;UI&rbrack; Salvar pop-up exibe o nome da coleção ativa
* &lbrack;UI&rbrack; Modificar imagens de origem de uma Camada de Importação de Imagem(ns)
* &lbrack;Content&brack; Os usos personalizados agora são suportados
* &lbrack;Content&brack; Mais formatos de imagens são suportados em parâmetros de entrada de imagem
* &lbrack;Conteúdo&rbrack; Novo Filtro Lado a Lado chamado Torná-lo Lado a Lado Avançado
* &lbrack;Content&brack; Atualização do filtro Água

**Corrigido:**

* Bitmap para Material lida com o fluxo de trabalho Specular/Textura reluzente

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* O Delighter não é compatível com a placa GPU RTX
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho

### &#x200B;0. 3. 1- beta Lasanha

*(Lançado: 17 de dezembro de 2018)*

**Corrigido:**

* Gerar uma variação de cor com 10 travamentos extraídos
* Gerar uma variação de cor com falhas de pilha de camadas recém-salvas
* Links incorretos no pop-up de atualização da versão do Substance Alchemist

**Problemas Conhecidos:**

* O Bitmap para Material não manipula o fluxo de trabalho Specular/Aspereza
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho

### &#x200B;0. 3. 0- beta Lasanha

*(Lançado: 12 de dezembro de 2018)*

**Adicionado:**

* &preto;Exportar&rbrack; Novo pop-up de exportação
* &amp;predefinição;Exportar&amp;predefinição; Exporta uma coleção inteira
* &lbrack;Exportar&rbrack; Exportar bitmaps no formato de sua escolha
* &preto;Exportar&rbrack; Exportar bitmaps na resolução de sua escolha
* &lbrack;Export&brack; Exportar somente os canais de sua escolha
* &lbrack;Export&brack; Visualizar o tamanho da estimativa da exportação
* &lbrack;Export&brack; Visualizar o tamanho disponível no disco antes de exportar
* &lbrack;UX&rbrack; Ações na coleção acessíveis usando o botão direito
* &lbrack;UX&rbrack; Permite cancelar a definição de uma imagem ou de um ativo no Inspire
* &lbrack;UX&rbrack; Substance Alchemist é lançado maximizado
* &lbrack;Assets&rbrack; Nova maneira de salvar seus materiais para mantê-los persistentes com as próximas versões
* &lbrack;Ajuda&rbrack; Acesso à documentação online através do menu Ajuda
* &lbrack;Desempenho&rbrack; Variações de cores mais rápidas em materiais complexos criados com Substance Alchemist
* &lbrack;Performance&brack; Reduzir vazamentos de memória ao alternar Labs
* &lbrack;Content&brack; Verificador de escala para diagnosticar o tamanho físico do seu material
* &lbrack;Content&brack; Atualizar material ladrilho italiano de Veneza
* &lbrack;Content&rbrack; Atualizar respingos de musgo

**Corrigido:**

* Não há mais nome padrão ao salvar um material
* Os parâmetros dos filtros são perdidos após salvar um material e reabrir o Substance Alchemist
* &lbrack;Content&brack; Corrigir da parte inferior e da lógica superior para mesclagem de AO e curvatura

**Problemas Conhecidos:**

* Os materiais criados com uma versão anterior não estarão disponíveis na nova versão.
* O Bitmap para Material não manipula o fluxo de trabalho Specular/Aspereza
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho

### &#x200B;0. 2. 0- beta Kiwi

*(Lançado: 09 de novembro de 2018)*

**Adicionado:**

* As Configurações de visualização são salvas de uma sessão para outra
* As configurações de material são salvas de uma sessão para outra
* Carregamento rápido do painel Propriedades
* &lbrack;Log&brack; Exportar arquivo de log pelo menu Ajuda
* &preto;UI&rbrack;Novo estilo de controles deslizantes
* &lbrack;UI&rbrack;Os painéis Predefinições e Ajustar foram mesclados
* &preto;UI&rbrack;Novo estilo de miniaturas
* Configurações de deslocamento, divisão em blocos gráficos e sombras acessíveis diretamente na viewport
* &lbrack;Content&rbrack; Novos Materiais Padrão
* &lbrack;Content&brack; Atualização do Moss Splatter
* &lbrack;Framework&rbrack; Atualizar Substance Engine Framework

**Corrigido:**

* A exclusão da pilha de camadas por meio da alternância de laboratórios foi corrigida
* Os valores de tempo de carregamento exibidos na viewport estão corretos
* Os canais padrão do fluxo de trabalho de material foram inicializados corretamente
* Desativar importação de malha personalizada
* Exportação de bitmap
* &lbrack;O MacOS&rbrack; para fechar o Substance Alchemist pode precisar de um “Force to quit”

**Problemas Conhecidos:**

* Os materiais criados com uma versão anterior não estarão disponíveis na nova versão.
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho

### 0.1.1-Emperramento na versão beta

*(Lançado: 24 de outubro de 2018)*

**Adicionado:**

* BaseColor Delighter agora está disponível
* Acessar informações sobre o Substance Alchemist por meio do menu Ajuda
* Receber notificações quando uma nova versão do Substance Alchemist estiver disponível
* O console não está mais visível no Windows
* Novo estilo de miniaturas
* O Substance Alchemist do &lbrack;MacOS&rbrack; pode ser configurado em tela cheia
* &lbrack;Filter&rbrack; Importar máscara personalizada para gerenciar a mesclagem entre dois materiais
* &lbrack;Filter&brack; Control Moss scale
* &lbrack;Filter&rbrack; Atualização de correção de clone

**Corrigido:**

* Adicionar uma imagem em uma entrada de imagem na lista de parâmetros atualiza as saídas
* O filtro Importar Personalizado não adiciona uma Oclusão Ambiente preta e uma opacidade preta

**Problemas Conhecidos:**

* Os materiais criados com uma versão anterior não estarão disponíveis na nova versão.
* &lbrack;O MacOS&rbrack; para fechar o Substance Alchemist pode precisar de um “Force to quit”
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Alternar a visibilidade rápida de um estágio Delighter afetará o desempenho
* A exportação de material pode falhar

### &#x200B;0. 1. 0- beta IceCream

*(Lançado: 17 de outubro de 2018)*

**Adicionado:**

* Mistura de materiais com 4 tipos de mistura (Mistura de Heights, Mesclagem de amostras, Mesclagem de curvatura, Mesclagem de AO)
* Introduzir o mecanismo de cache para otimizar os novos cálculos de pilha de camadas
* Seleção automática de um material no Inspire se presente no visor
* Formato normal centralizado no painel Configurações de material
* Controles de widgets de corte e divisão em blocos gráficos (-90xB0,+90xB0, criar quadrado,...) limpeza
* Novo filtro de Snow

**Corrigido:**

* Limpeza da interface do painel
* Visualização de cintilação ao redimensionar janelas e painéis
* Pilha de camadas não recalculada quando salva
* A nomenclatura de ativos na interface usa rótulos em vez de nomes de gráficos

**Problemas Conhecidos:**

* Esticar a imagem alternando a visibilidade da camada rapidamente
* O foco redefine o ângulo da câmera
