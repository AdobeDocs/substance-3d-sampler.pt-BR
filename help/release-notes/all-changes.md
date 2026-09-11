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

* &amp;lbrack;Assets&amp;rbrack; Verifique a versão do sbsar e avise os usuários se o mecanismo é muito antigo para lê-lo
* &amp;lbrack;Captis&amp;rbrack; Adicionar opção de volta para salvar a fotometria das legendas nas preferências

**Corrigido:**

* &amp;lbrack;Visualização 2D&amp;rbrack; Não “exibir com proporção física” se o tamanho físico estiver desativado
* &amp;lbrack;Analytics&amp;rbrack; Eventos de análise ausentes
* &amp;lbrack;Analytics&amp;rbrack; Impedir que o bloco de anotações reporte uma falha no vk devicelost
* &amp;lbrack;Aplicativo&amp;rbrack; Não destrua dispositivos vkna saída para evitar uma falha no driver nvidia
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir saída do inspetor de coleções vinculadas + gerenciador de canais
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falhas ao sair
* O filtro &amp;lbrack;Content&amp;brack; “metal finish” não afeta a metalidade
* &amp;lbrack;Content&amp;brack; Adicionar tamanho físico a filtros dinâmicos nos quais está faltando
* &amp;lbrack;Filtros&amp;rbrack; Remover preenchimento sensível a conteúdo da lista de ativos ocultos
* &amp;lbrack;Camadas&amp;rbrack; Clicar em &#39;redefinir todas as configurações&#39; não redefine o menu suspenso &#39;aplica a&#39;
* &amp;lbrack;Camadas&amp;rbrack; Corrigir ajuste mínimo &amp; máximo para o widget de posição
* &amp;lbrack;Camadas&amp;rbrack; Atualizar filtro corretamente
* &amp;lbrack;Tamanho físico&amp;rbrack; Certificar-se de que a escala física está funcionando em todos os lugares + deixar o tamanho físico ok com filtros dinâmicos
* &amp;lbrack;Projeto&amp;rbrack; Certifique-se de que a resolução do ativo é a padrão (2k x 2k) ao criar um novo ativo
* &amp;lbrack;Projeto&amp;rbrack; Reabrindo o projeto atual usado para abrir a versão anterior
* &amp;lbrack;Projeto&amp;rbrack; O Sampler não oferece mais a opção de restaurar um backup de projetos corrompidos
* &amp;lbrack;Renderização&amp;rbrack; Renderizar a miniatura do material em no máximo 2k de resolução
* &amp;lbrack;UI&amp;rbrack; Código defensivo para evitar falhas se o usuário for mais rápido que a interface

### **6.0.1**

*(Lançado em: 21 de maio de 2026)*

**Adicionado:**

* &amp;lbrack;Aplicativo&amp;rbrack; Avisar o usuário ao abrir um projeto com objetos ou iluminações do ambiente 3D
* &amp;preto;Captis&amp;rbrack; Faz com que a interface se adapte a telas pequenas
* &amp;preto;Captis&amp;rbrack; Atualizar interface do usuário do Captis
* &amp;lbrack;Configurações do Canal&amp;rbrack; Ativar o SSS automaticamente ao usar o canal SSS no ASM
* &amp;lbrack;Engine&amp;rbrack; Atualização Substance Engine para a versão 9.4.3
* &amp;lbrack;Predefinição&amp;rbrack; Ativar &#39;aplicar valores de miniatura predefinidos&#39; por padrão
* &amp;lbrack;Recursos&amp;rbrack; Exibir &#39;todas as bibliotecas&#39; por padrão em vez de &#39;ativos iniciais&#39; no painel de recursos
* &amp;lbrack;Scripting&amp;brack; Adicionar funções Python para gerenciar &#39;Aplicado a&#39; de uma camada
* &amp;lbrack;UI&amp;rbrack; A lista de ativos agora responde: o tamanho do ativo se adapta ao contêiner
* &amp;lbrack;UI&amp;rbrack; Exibir 3D/Visualização 2D por padrão
* &amp;lbrack;UI&amp;rbrack; Exibir pop-up de otimização de material ao soltar um material do explorador
* &amp;lbrack;UI&amp;rbrack; Ativar inversão da dica de ferramenta dos botões da barra de dispositivos

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir problemas de espaço de cores
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir configurações atualizador
* &amp;lbrack;Aplicativo&amp;rbrack; Torna os canais de digitalização ativos quando estiverem definidos como automáticos
* &amp;lbrack;Aplicativo&amp;rbrack; O botão Novo projeto da tela inicial não apaga mais o projeto anterior com o mesmo nome
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falhas ao sair no macOS
* &amp;lbrack;Aplicativo&amp;rbrack; Impedir o acesso a ativos de referências de ativos inválidos
* &amp;lbrack;Aplicativo&amp;rbrack; Impedir falha ao acessar a superfície a partir da ImagemVersionada em um ajuste
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falha ao excluir um estágio quando não houver nenhum
* &amp;lbrack;Captis&amp;rbrack; Certifique-se de que a Captis está desconectada antes de fechar o Sampler
* &amp;lbrack;Captis&amp;rbrack; Impedir que o aviso USB-2 seja exibido duas vezes
* &amp;lbrack;Configurações do canal&amp;rbrack; Corrigir nomes dos canais de OpenPBR
* &amp;lbrack;Configurações do canal&amp;rbrack; Atualizar etiquetas longas para canais de OpenPBR
* &amp;lbrack;Content&amp;brack; Atualizar todas as unidades de malha de metros a centímetros para valores SSS
* &amp;lbrack;Export&amp;brack; Garantir que os valores padrão estejam conectados a filtros dinâmicos
* &amp;lbrack;Export&amp;brack; As imagens agora são salvas em um thread de trabalho para melhorar o desempenho
* &amp;lbrack;Filtros&amp;rbrack; O Preenchimento sensível ao conteúdo falha ao ativar a escala
* &amp;lbrack;Filtros&amp;rbrack; Não foi possível abrir o local de um filtro dinâmico no painel de ativos
* &amp;lbrack;Filtros&amp;rbrack; Corrigir redefine tudo na etapa de ajuste de AutoLado a Lado
* &amp;lbrack;Filtros&amp;rbrack; Restaurar desabilitar processamento de uso na criação de estruturas em árvore
* &amp;lbrack;Filtros&amp;rbrack; Define o valor padrão correto para o parâmetro upscale
* &amp;lbrack;Filtros&amp;rbrack; Atualiza os geradores mesmo se estiverem em uma camada de preenchimento
* &amp;lbrack;Camadas&amp;rbrack; Proibir renomeação de camadas de cabeçalho de camada de entrada ou camadas de espaço reservado
* &amp;lbrack;Camadas&amp;rbrack; Evitar falha durante a inserção da camada devido a um ponteiro oscilante
* &amp;lbrack;Camadas&amp;rbrack; Número incorreto de imagens no nome da camada achatada
* &amp;lbrack;Localization&amp;brack; Certifique-se de que os nomes predefinidos sejam atualizados ao alternar idiomas
* &amp;lbrack;Localização&amp;rbrack; Vários problemas de tradução no painel de recursos
* &amp;lbrack;Localização&amp;rbrack; Ações rápidas categorias problemas de localização
* &amp;lbrack;Performance&amp;rbrack; Ajustes de carregamento somente na seção aberta
* &amp;lbrack;Preferências&amp;rbrack; Limpar caminho do cache de preferências redefine para o valor anterior
* &amp;lbrack;Renderizando&amp;brack; Vazamento de memória ao usar o Rastreador de caminho
* &amp;lbrack;Renderização&amp;rbrack; Impedir a exclusão de texturas enquanto ainda podem ser acessadas pelo Vulkan
* &amp;lbrack;Renderização&amp;rbrack; a rotação de Textura não foi convertida de 0-1 para 0-360
* &amp;lbrack;Scripting&amp;brack; Remover classes não existentes da documentação do Python
* &amp;lbrack;Scripting&amp;rbrack; seletedAsset retorna Nenhum se não houver nenhum ativo selecionado
* &amp;lbrack;Ferramentas&amp;rbrack; Redefinir um valor de textura agora para de pintar e limpa a visualização de correção
* &amp;lbrack;UI&amp;rbrack; Não feche as seções no painel de propriedades sempre que algo for ajustado
* &amp;lbrack;UI&amp;rbrack; Rótulo de ajuste de cor exposto invisível ao passar o mouse
* &amp;lbrack;UI&amp;rbrack; Corrigir comportamento responsivo da lista de ativos
* &amp;lbrack;UI&amp;rbrack; Corrigir loop de ligação na dica de ferramenta do AssetItem
* &amp;lbrack;UI&amp;rbrack; Corrigir duplo clique no grupo de predefinições selecionado
* &amp;lbrack;UI&amp;rbrack; Corrigir área de soltar no apresentador de imagens
* &amp;lbrack;UI&amp;rbrack; Corrigir rótulo com um botão para todos os idiomas
* &amp;lbrack;UI&amp;rbrack; Corrigir height de linha para japonês no pop-up de lista de canais
* &amp;lbrack;UI&amp;rbrack; Corrigir sinal onAccepted do campo de comprimento
* &amp;lbrack;UI&amp;rbrack; Corrigir largura pop-up com item de controle esquerdo longo
* &amp;lbrack;UI&amp;rbrack; Corrigir pop-up de visualização em itens de ativo
* &amp;lbrack;UI&amp;rbrack; Corrigir seletor áspero/reflexivo
* &amp;lbrack;UI&amp;rbrack; Corrigir reticências de string
* &amp;lbrack;UI&amp;rbrack; Corrigir problema de truncamento de string
* &amp;lbrack;UI&amp;rbrack; Botão de reinicialização de ajuste do interruptor de correção
* &amp;lbrack;UI&amp;rbrack; Oculta a lista suspensa de Modelos de material quando uma predefinição de exportação personalizada é selecionada
* &amp;lbrack;UI&amp;rbrack; Remover resolução na lista de canais do pop-up de exportação
* &amp;lbrack;UI&amp;rbrack; Redefinir para layout padrão mantém as configurações do visualizador de projeção
* &amp;lbrack;UI&amp;rbrack; Restaurar itens de menu “Editar no Photoshop” e “Editar no Illustrator”

**Removido:**

* &amp;lbrack;UI&amp;rbrack; Remover seção &#39;Aplicado a&#39; para camadas de importação de imagem
* &amp;lbrack;UI&amp;rbrack; Remover dica de ferramenta de ação rápida de abertura automática na primeira inicialização

## Versão 5

### **5.1.3 ÎLE FLOTTANTE**

*(Lançado: 6 De Janeiro De 2026)*

**Adicionado:**

* &amp;lbrack;Captis&amp;rbrack; Exibir um aviso se o protocolo FTP estiver desativado pelo firewall

**Corrigido:**

* &amp;lbrack;Captis&amp;rbrack; A interrupção durante uma captura pode levar a erros
* &amp;lbrack;Captis&amp;rbrack; O download dos resultados no final de uma captura usa muita memória RAM
* &amp;lbrack;Captis&amp;rbrack; Executar um foco automático imediatamente após uma intensidade automática pode levar a erros
* &amp;lbrack;Captis&amp;rbrack; A exibição de resultados de HDR no painel Resumo
* &amp;lbrack;UI&amp;rbrack; Em alguns casos, a caixa de diálogo de pasta no MacOS não seleciona a pasta correta

### **5.1.2 ÎLE FLOTTANTE**

*(Lançado em: 20 de novembro de 2025)*

**Adicionado:**

* &amp;lbrack;Aplicativo&amp;rbrack; Detectar perda de dispositivo gráfico, avisar o usuário e sair normalmente
* &amp;lbrack;Camadas&amp;rbrack; Mensagens aprimoradas ao nivelar camadas
* &amp;preto;Camadas&amp;rbrack; Miniaturas aprimoradas para importação de imagem e camadas achatadas
* &amp;lbrack;Integração&amp;rbrack; Conteúdo de aprendizado atualizado na tela inicial
* &amp;lbrack;Projeto&amp;rbrack; Recupera o último estado salvo da sessão antes do erro fatal
* &amp;lbrack;UI&amp;rbrack; Atualização do ícone do aplicativo

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Inserir um material na pilha de camadas pode levar a uma falha no macOS
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha em carga pesada no macOS
* &amp;lbrack;Application&amp;brack; Possível falha ao adicionar camadas quando a memória de vídeo estiver cheia
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha ao abrir um projeto
* &amp;lbrack;Captis&amp;rbrack; Falha se o foco automático for executado logo após a calibração automática de intensidade
* &amp;lbrack;Captis&amp;rbrack; Problemas de confiabilidade e desempenho após a primeira captura
* &amp;lbrack;Captis&amp;rbrack; Acelerações e erros ao copiar arquivos no final de uma captura
* &amp;lbrack;Captis&amp;rbrack; Vazamento de memória pequeno ao consultar informações do dispositivo Captis
* &amp;lbrack;Exportar&amp;rbrack; Os parâmetros expostos de vários controles deslizantes produzem arquivos .sbsar corrompidos
* &amp;lbrack;Camadas&amp;rbrack; O padrão de divisão automática é redefinido para os valores padrão ao alternar os ativos
* &amp;lbrack;Camadas&amp;rbrack; A cor de base personalizada padrão é exibida em vermelho
* &amp;lbrack;Camadas&amp;rbrack; O nivelamento parcial de camadas filho de Clonar Stamp é possível e causa problemas de renderização
* &amp;lbrack;Camadas&amp;rbrack; Possível falha ao ajustar uma pilha de camadas enquanto a renderização está em andamento
* &amp;lbrack;Camadas&amp;rbrack; Erro inesperado na etapa de região de interesse de divisão automática ao alterar canais de origem
* &amp;lbrack;Projeto&amp;rbrack; Miniatura incorreta às vezes ao criar um novo material
* &amp;lbrack;Ações rápidas&amp;rbrack; Algumas ações rápidas têm uma contagem de entrada incorreta
* &amp;lbrack;UI&amp;rbrack; O botão Grupo de ação tem larguras diferentes
* &amp;lbrack;UI&amp;rbrack; O botão Limpar nos campos de texto às vezes dispara a perda de foco
* &amp;lbrack;UI&amp;rbrack; Caixas de combinação e campos de texto são muito grandes
* &amp;lbrack;UI&amp;rbrack; Os ícones e rótulos estão desalinhados
* &amp;lbrack;UI&amp;rbrack; O rótulo do campo Nome está posicionado incorretamente
* &amp;lbrack;UI&amp;rbrack; Os rótulos do botão Ações rápidas estão desalinhados
* &amp;lbrack;UI&amp;rbrack; Os controles deslizantes mostram muitos 0s à direita

**Removido:**

* &amp;preto;Geração de AI&amp;rbrack; Recursos de IA generativa remoção. *Este recurso foi removido do aplicativo e o serviço deixará de funcionar nas versões anteriores do Sampler em 5 de março.*

### **5.1.1 ÎLE FLOTTANTE**

*(Lançado em: 18 de setembro de 2025)*

**Adicionado:**

* &amp;lbrack;Exibição 2D&amp;rbrack; Consegue reduzir mais na exibição 2D para texturas de alta resolução
* &amp;lbrack;Captis&amp;rbrack; Avisa os usuários sobre problemas ao copiar arquivos
* &amp;lbrack;Camadas&amp;rbrack; Ao duplicar uma camada, use um número incremental no nome da nova camada

**Corrigido:**

* &amp;lbrack;Exibição 2D&amp;rbrack; Ao pintar traçados após redefinir todas as propriedades do Carimbo, os traçados criados anteriormente reaparecerão
* &amp;lbrack;Aplicativo&amp;rbrack; “Salvar projeto atual?” o pop-up usa um nome de projeto incorreto
* &amp;lbrack;O aplicativo &amp;rbrack; falha ao sair
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha
* &amp;lbrack;Application&amp;brack; Às vezes, uma miniatura é gerada com um material incorreto
* &amp;lbrack;Captis&amp;rbrack; Em alguns dispositivos, ao executar uma varredura em alta resolução, o mapa de height fica preto
* &amp;lbrack;Captis&amp;rbrack; O botão “Iniciar captura” não é mais desativado quando nenhum nome de captura está definido e quando uma calibragem está em execução
* &amp;lbrack;Export&amp;rbrack; Ao exportar um arquivo .sbsar, a exportação pode falhar sem que o usuário seja notificado
* &amp;lbrack;Filtros&amp;rbrack; Tela de parâmetros avançados para o filtro de divisão em blocos automáticos às vezes pisca ao ajustar parâmetros
* &amp;lbrack;Filtros&amp;rbrack; Os parâmetros padrão para o filtro de divisão em blocos gráficos produzem artefatos cinzas na saída
* &amp;lbrack;Filtros&amp;rbrack; Às vezes, com entradas de alta resolução, as configurações avançadas do Filtro de divisão em blocos gráficos automático não mostram os pontos de padrão individuais
* &amp;lbrack;Filtros&amp;rbrack; O tamanho do padrão para o parâmetro de divisão em blocos gráficos de tamanho personalizado tem um valor padrão incorreto
* &amp;lbrack;Camadas&amp;rbrack; Problema ocasional de cor com o filtro Divisão em blocos gráficos automático visível principalmente em materiais vermelhos
* &amp;lbrack;Camadas&amp;rbrack; Às vezes, adicionar camadas redefinirá alguns ajustes para o valor padrão
* &amp;lbrack;Tamanho físico&amp;rbrack; A miniatura de ativos com um tamanho físico tem uma escala de height incorreta
* &amp;lbrack;UI&amp;rbrack; Não é possível renomear parâmetros expostos
* O botão de ativação do canal do &amp;lbrack;UI&amp;rbrack; não é quadrado
* &amp;lbrack;UI&amp;rbrack; Se o rótulo de um controle deslizante for muito longo, o botão de redefinição não estará acessível
* &amp;lbrack;UI&amp;rbrack; Pressionar a tecla return ou clicar para não remove o foco dos campos de texto
* &amp;lbrack;UI&amp;rbrack; Às vezes, uma dica de ferramenta indesejada aparece no painel Tamanho físico
* &amp;lbrack;UI&amp;rbrack; A visualização 3D exibe uma malha incorreta ao criar um projeto vazio
* &amp;lbrack;UI&amp;rbrack; Ao expor uma entrada do seletor de cores, seu rótulo desaparece ao passar o mouse
* &amp;lbrack;UI&amp;rbrack; Ao expor parâmetros, o ponto de cor às vezes é posicionado incorretamente

### **5.1.0 ÎLE FLOTTANTE**

*(Lançado em: 7 de agosto de 2025)*

**Adicionado:**

* O tamanho do pincel do &amp;lbrack;Visualização 2D&amp;rbrack; agora se adapta à resolução de textura atual
* &amp;lbrack;Visualização 3D&amp;rbrack; Alternar a escala de exibição nativa para renderização 3D nas preferências
* &amp;lbrack;Atualização do mecanismo de renderização do Application&amp;brack;
* &amp;lbrack;Captis&amp;rbrack; Adicionar a possibilidade de “criar quadrado” durante a visualização
* &amp;lbrack;Captis&amp;rbrack; Detecção automática de tamanho físico
* &amp;preto;Capta&amp;rbrack; Capturar um novo material criará um novo ativo
* &amp;lbrack;Captis&amp;rbrack; Alterar seleção de resolução em menu suspenso para pixel por polegada ou centímetro em vez de resolução de pixel da área máxima
* &amp;lbrack;Captis&amp;rbrack; Ajuda contextual sobre calibração de alinhamento
* &amp;lbrack;Captis&amp;rbrack; Gerar mapa de aspereza
* &amp;lbrack;Captis&amp;rbrack; Avisa o usuário se os arquivos de calibração padrão estiverem ausentes
* &amp;lbrack;Filtros&amp;rbrack; Filtro de divisão automática em blocos gráficos para materiais estruturados e digitalizações
* &amp;lbrack;Filtros&amp;rbrack; Novo filtro Removedor de Dobra
* &amp;lbrack;Filtros&amp;rbrack; Novos recursos dentro do filtro Carimbo de Clonar
* &amp;lbrack;Filtros&amp;rbrack; Novos recursos dentro do filtro Equalizar
* &amp;preto;Camadas&amp;rbrack; Capacidade de nivelar camadas
* &amp;lbrack;Camadas&amp;rbrack; Menu de contexto ao clicar com o botão direito do mouse em uma camada para renomear, duplicar, excluir ou nivelar a camada
* &amp;lbrack;Integração&amp;rbrack; Atualizar conteúdo de telas de Boas-vindas e Novidades
* &amp;lbrack;Desempenho&amp;rbrack; Melhor desempenho ao usar o filtro Corte demarcado
* &amp;lbrack;Desempenho&amp;rbrack; Melhorar o uso de memória para a Visualização 3D
* &amp;lbrack;Desempenho&amp;rbrack; A atualização da visualização 3D é mais rápida
* &amp;lbrack;Tamanho físico&amp;rbrack; Habilitar “exibição com proporção física” ao trabalhar em filtros de Substance quando o Tamanho físico estiver habilitado
* &amp;lbrack;Tamanho físico&amp;rbrack; Ao importar imagens em uma pilha vazia, proponha uma resolução mais coerente com a proporção da imagem
* &amp;lbrack;Ações rápidas&amp;rbrack; 3 novas ações rápidas para processamento de digitalização
* &amp;preto;Script&amp;rbrack; API para nivelar camadas
* &amp;lbrack;Scripting&amp;brack; Obtém o nome de arquivo de cada imagem de uma camada de importação de imagem
* &amp;lbrack;Scripting&amp;brack; Nova função para ativar/desativar um determinado canal de um ativo
* &amp;lbrack;UI&amp;rbrack; Retrabalhe os ícones e botões no painel Camadas para acomodar os novos recursos
* &amp;lbrack;UI&amp;rbrack; Avisar sobre a obsolescência da criação de luz ambiente

**Corrigido:**

* &amp;lbrack;2D View&amp;rbrack; Selecionar &#39;display with physical ratio&#39; pode não funcionar ao usar filtros de Substance
* &amp;lbrack;captura 3D&amp;rbrack; Os arquivos SVG estão listados no seletor de arquivos, mas não são suportados
* O parâmetro de intensidade de emissão do &amp;brack;Visualização 3D&amp;rbrack; nas Configurações do sombreador não funciona
* &amp;lbrack;Visualização 3D&amp;rbrack; Às vezes, a posição da malha está incorreta ao criar um novo ativo
* &amp;lbrack;Visualização 3D&amp;rbrack; Alternar para o traçado de caminho renderiza falhas em hardware não suportado
* &amp;lbrack;O aplicativo &amp;rbrack; trava ao fechar o pop-up de medida manual sem definir um tamanho
* &amp;lbrack;Falha do aplicativo&amp;rbrack;
* &amp;lbrack;Aplicativo&amp;rbrack; Congela no Windows ao exibir a área de trabalho (tecla Windows + D atalho de teclado)
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha ao alternar o idioma
* &amp;lbrack;Captis&amp;rbrack; Falha quando os dados de visualização não são válidos
* &amp;lbrack;Captis&amp;rbrack; Impossível reduzir totalmente após aumentar o zoom
* &amp;lbrack;Captis&amp;rbrack; Localização ausente em algumas etapas do assistente
* &amp;lbrack;Captis&amp;rbrack; Possível falha ao sair ao usar Captis
* &amp;lbrack;Captis&amp;rbrack; A digitalização não funciona se o dispositivo não tiver arquivos de calibração
* &amp;brack;Filtros&amp;rbrack; A visualização do pincel ao usar o filtro Carimbo de Clonar pode estar incorreta, dependendo da textura e dos tamanhos do pincel
* &amp;lbrack;Filtros&amp;rbrack; Tamanho de saída incorreto após o uso do filtro Escala superior
* &amp;lbrack;Filtros&amp;rbrack; Ícones ausentes para os filtros de Rotação e Estilização do Ambiente
* &amp;lbrack;Filtros&amp;rbrack; A atualização de alguns filtros pode levar à renderização incorreta
* &amp;lbrack;Camadas&amp;rbrack; Primeira renderização incorreta ao mesclar dois materiais
* &amp;lbrack;Camadas&amp;rbrack; O botão para atualizar as camadas mostra “Atualizar tudo” mesmo quando há apenas uma atualização
* &amp;lbrack;Camadas&amp;rbrack; Cálculos desnecessários ao importar imagens na pilha de camadas
* &amp;lbrack;Desempenho&amp;rbrack; Melhorar a manipulação de formatos de mapa normais para reduzir os tempos de renderização
* &amp;lbrack;Tamanho físico&amp;rbrack; A mensagem de medida manual só funciona depois de fazer uma medida automática
* &amp;lbrack;Tamanho físico&amp;rbrack; Resolução de exportação incorreta no pop-up Exportar quando o Tamanho físico está habilitado
* &amp;lbrack;Ações rápidas&amp;rbrack; Localização ausente nos nomes dos ativos gerados
* &amp;lbrack;UI&amp;rbrack; A visualização do ativo ao passar o mouse pode não mostrar
* &amp;lbrack;UI&amp;rbrack; Clicar no botão Redefinir para o valor padrão pode quebrar alguns dos controles
* &amp;lbrack;UI&amp;rbrack; As mensagens de erro não são apagadas ao alternar projetos
* &amp;lbrack;UI&amp;rbrack; Certifique-se de que o nome do material no visor e no painel de propriedades esteja vazio quando não houver nenhum ativo
* &amp;lbrack;UI&amp;rbrack; O botão Redefinir para o valor padrão do parâmetro Ponto de Vista não funciona
* &amp;lbrack;UI&amp;rbrack; Sobreposição do botão Redefinir para valor padrão
* &amp;lbrack;UI&amp;rbrack; Alguns botões não são clicáveis quando um painel é desencaixado
* &amp;lbrack;UI&amp;rbrack; Textura inclinando o parâmetro V parcialmente oculto nas Configurações do visualizador e Visualização 3D

**Removido:**

* &amp;lbrack;captura 3D&amp;rbrack; Remover suporte ao captura 3D
* &amp;lbrack;Aplicativo&amp;rbrack; Remover suporte ao macOS x86

### **AVELÃ 5.0.3**

*(Lançado em: 3 de junho de 2025)*

**Adicionado:**

* &amp;lbrack;Captis&amp;rbrack; Permite dar a um material o mesmo nome de um já existente
* &amp;lbrack;Captis&amp;rbrack; Move mensagens de erro para pop-ups em vez de notificações do sistema
* &amp;lbrack;Filtros&amp;rbrack; Atualizar bordado
* &amp;lbrack;Preferências&amp;rbrack; Adicionar redefinição nas configurações do visualizador e sombreadores
* &amp;lbrack;UI&amp;rbrack; Não apresentar o item de menu “Mostrar localização” nos ativos do projeto

**Corrigido:**

* &amp;lbrack;captura 3D&amp;rbrack; O filtro de pós-processamento de malha não gera os mapas esperados
* A visualização 3D do &amp;lbrack;Visualização 3D&amp;rbrack; não funciona devido à corrupção do cache de sombreador
* &amp;lbrack;Visualização 3D&amp;rbrack; O plano horizontal e a grade ficam verticais quando a cena é Z-up
* &amp;lbrack;Visualização 3D; A malha às vezes desaparece
* &amp;lbrack;Aplicativo&amp;rbrack; Fechar a janela de login na inicialização sem efetuar login às vezes trava o aplicativo
* &amp;lbrack;Application&amp;brack; Falha quando o acesso ao arquivo de configuração de plug-ins é negado
* &amp;lbrack;Aplicativo&amp;rbrack; O material atual não está selecionado quando o projeto é salvo
* &amp;lbrack;Aplicativo&amp;rbrack; Redefinir para o layout padrão define a resolução para 64x64
* &amp;lbrack;O Application&amp;brack; Sampler às vezes trava ao renderizar uma pilha de camadas
* A resolução da exportação do &amp;brack;Export&amp;brack; às vezes é redefinida para 64x64
* &amp;lbrack;Export&amp;rbrack; Às vezes, não é possível exportar arquivos .sbs/.sbsar
* &amp;lbrack;Camadas&amp;rbrack; O botão Adicionar material de base não faz nada quando o material está vazio
* &amp;lbrack;Camadas&amp;rbrack; A divisão em blocos gráficos de Textura é alterada ao duplicar um material
* &amp;lbrack;Tamanho físico&amp;rbrack; A medida automática não funciona se o painel de Tamanho físico foi encaixado antes da importação da imagem
* O plug-in de salvamento automático do &amp;brack;Scripting&amp;brack; está com falha
* &amp;lbrack;UI&amp;rbrack; Espaçamento incorreto na caixa de diálogo Exportar
* &amp;lbrack;UI&amp;rbrack; A animação dos ajustes no controle deslizante não funciona mais
* &amp;lbrack;UI&amp;rbrack; Os controles deslizantes não se encaixam em valores inteiros quando necessário
* &amp;lbrack;UI&amp;rbrack; Alguns menus suspensos são cortados

### **5.0.2 AVELÃ**

*(Lançado em: 22 de abril de 2025)*

**Corrigido:**

* &amp;lbrack;O botão Voltar da página inicial do &amp;aplicativo está quebrado
* &amp;lbrack;Aplicativo&amp;rbrack; O Sampler às vezes não inicia se dados corrompidos de versões anteriores estiverem presentes no disco
* &amp;lbrack;Aplicativo&amp;rbrack; A imagem importada não aparece no visor ou na pilha de camadas
* &amp;lbrack;Captis&amp;rbrack; o campo Endereço IP da Captis permanece vazio mesmo depois de reiniciar o Sampler
* A visualização da câmera do &amp;preto;Captis&amp;rbrack; Live funciona somente quando o idioma do aplicativo está definido como inglês
* &amp;lbrack;Export&amp;brack; Falha durante a exportação &amp;lbrack;Camadas&amp;rbrack; A pintura às vezes não funciona em projetos salvos anteriormente
* &amp;lbrack;Camadas&amp;rbrack; O Sampler às vezes atualiza todas as texturas quando apenas um canal é atualizado
* &amp;lbrack;Camadas&amp;rbrack; Não é possível usar misturas de materiais na pilha de camadas após atualizar para 5.0.x
* &amp;lbrack;Camadas&amp;rbrack; Atualizar um projeto com uma versão anterior do Image to Material (AI) torna o material todo preto
* &amp;lbrack;Camadas&amp;rbrack; Ao tentar importar uma imagem não suportada, o Sampler cria uma camada quebrada
* &amp;lbrack;Scripting&amp;brack; Parte da API Python não funciona com um projeto vazio
* Os itens de menu do &amp;lbrack;UI&amp;rbrack; às vezes transbordam no menu Arquivo

### **5.0.1 AVELÃ**

*(Lançado em: 20 de março de 2025)*

**Adicionado**

* &amp;lbrack;Aplicativo&amp;rbrack; Lista de compatibilidade de driver gráfico atualizada
* &amp;lbrack;Captis&amp;rbrack; Mostra um pop-up quando o uso do HP Z Captis for bloqueado pelas políticas do sistema operacional
* &amp;lbrack;Ações rápidas&amp;rbrack; Explicar por que uma Ação rápida é desativada em uma dica de ferramenta
* &amp;lbrack;UI&amp;rbrack; Estilo da interface da janela do relatório de falhas
* &amp;lbrack;UI&amp;rbrack; Ao copiar para a área de transferência, mostrar uma caixa de informações para dizer que está feito

**Corrigido:**

* &amp;lbrack;O controle deslizante de Exposição do &amp;Visualização 2D; não tem efeito quando a projeção esférica está desativada
* &amp;lbrack;Visualização 2D; Pintar fora da textura cria um traçado descontinuado
* &amp;lbrack;Exibição 2D&amp;rbrack; O botão de exposição não tem dica de ferramenta.
* &amp;lbrack;Visualização 2D; O zoom na lateral de uma imagem não quadrada não segue o mouse
* O &amp;lbrack;captura 3D&amp;rbrack; captura 3D não funciona no Windows 11 24H2
* &amp;lbrack;captura 3D&amp;rbrack; Falha se sairmos do Sampler durante a etapa de reconstrução de malha
* &amp;lbrack;Visualização 3D&amp;rbrack; O tempo de computação às vezes é mostrado como 0ms
* &amp;lbrack;Visualização 3D&amp;rbrack; Ao alterar a projeção de ortográfico para perspectiva, o visor se torna cinza
* &amp;lbrack;Aplicativo&amp;rbrack; Falha na inicialização ao verificar os recursos da GPU
* &amp;lbrack;O aplicativo &amp;rbrack; falha durante a instalação
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao sair após clicar com o botão direito do mouse em um campo de metadados
* &amp;lbrack;Application&amp;brack; Iluminação do ambiente ausente ao abrir um SBSAR a partir do explorador de arquivos do sistema operacional
* &amp;lbrack;Aplicativo&amp;rbrack; Abrir um .sbsar enquanto o Sampler está em execução altera a configuração de Divisão em Texturas Lado a Lado
* &amp;lbrack;Captis&amp;rbrack; Alguns metadados podem não ser transferidos entre as etapas de captura
* &amp;lbrack;Captis&amp;rbrack; O nome do ativo criado não é o inserido no campo de metadados
* &amp;lbrack;Content&amp;brack; Exemplo de projeto solicita uma atualização de filtro, mas já está atualizado
* &amp;lbrack;Filtros&amp;rbrack; O filtro de ajuste Normal/height não tem ícone
* &amp;lbrack;Camadas&amp;rbrack; Não é possível alterar imagens em uma camada de importação de imagem
* &amp;lbrack;Camadas&amp;rbrack; Falha ao usar o filtro Aumento
* &amp;lbrack;Camadas&amp;rbrack; Atualizar um projeto com uma Imagem antiga para Material torna o material todo preto
* &amp;lbrack;Renderização&amp;rbrack; Ajustar uma pilha de camadas imediatamente após criar um ativo interrompe a renderização
* &amp;lbrack;Scripting&amp;brack; O plug-in de salvamento automático falha quando não há ativo no projeto
* &amp;brack;Ferramentas&amp;rbrack; O valor do tamanho do pincel está ausente na barra de ferramentas Pincel
* &amp;lbrack;UI&amp;rbrack; Alterar o idioma do aplicativo não atualiza alguns dos rótulos na tela inicial
* &amp;lbrack;UI&amp;rbrack; Pressionar Escape ou Enter nos campos de texto do controle deslizante não perderá o foco
* &amp;lbrack;UI&amp;rbrack; No painel Propriedades, o botão Redefinir tudo e o rótulo do nome do ativo se sobrepõem
* &amp;lbrack;UI&amp;rbrack; Problemas ao encaixar e desencaixar painéis
* &amp;lbrack;UI&amp;rbrack; A rolagem em um painel de sobreposição também rolará na janela subjacente
* &amp;lbrack;UI&amp;rbrack; Alternar para a exibição de Lista na seção Projetos Recentes da Tela Inicial não funciona
* &amp;lbrack;UI&amp;rbrack; Ícone do botão do modo de exibição do Visor sempre mostra 2D/3D

### **5.0.0 AVELÃ**

*(Lançado em: 20 de fevereiro de 2025)*

**Adicionado**

* &amp;lbrack;Integração&amp;rbrack; Nova Página Inicial com acesso rápido a conteúdo de aprendizagem, projeto de amostra, ações rápidas e projetos recentes.
* &amp;brack;Integração&amp;rbrack; Comece rapidamente com as novas Ações rápidas, acessíveis na página inicial e no painel dedicado
* &amp;lbrack;Integração&amp;rbrack; &amp;lbrack;Conteúdo&amp;rbrack; Ações rápidas são fluxos de trabalho predefinidos que preenchem a pilha de camadas com as camadas mais usadas
* &amp;lbrack;Integração&amp;rbrack; Possibilidade de criar um novo projeto por meio de um novo menu Início rápido, por meio de ações rápidas ou Projeto personalizado
* &amp;lbrack;Integração&amp;rbrack; Possibilidade de criar um projeto vazio diretamente da página inicial através de um botão dedicado
* &amp;lbrack;Visualização 3D&amp;rbrack; Novo rasterizador e rastreador de caminho avançados que trazem novos recursos de renderização (propriedades como revestimento, brilho, translucidez, dispersão de subsuperfície) e consistência visual entre o ecossistema de Substance
* As configurações do visualizador do &amp;brack;Visualização 3D&amp;rbrack; agora podem ser acessadas diretamente na visualização 3D
* &amp;lbrack;Visualização 3D&amp;rbrack; Possibilidade de salvar um instantâneo de renderização na área de transferência ou em arquivos
* &amp;lbrack;Visualização 3D; Exibir uma grade para visualizar a origem da cena
* &amp;lbrack;Visualização 3D; Habilita o plano do solo a capturar sombras e reflexos
* &amp;lbrack;Visualização 3D; Controla o quão reflexivo e opaco é o seu plano terrestre
* &amp;preto;captura 3D; Malha de posição no chão
* &amp;lbrack;Aplicativo&amp;rbrack; Verificar compatibilidade de hardware na inicialização do aplicativo
* A janela Relatório de falhas do &amp;lbrack;Application&amp;brack; agora abre logo após ocorrer uma falha
* &amp;lbrack;Content&amp;brack; Abrir um projeto de amostra para começar facilmente
* &amp;lbrack;Export&amp;rbrack; Exportar sombreador de Adobe Standard Material em arquivos USD
* &amp;lbrack;Generative AI&amp;rbrack; Marque a marca “Não inferir” ao usar uma imagem como entrada em fluxos de trabalho de Imagem para Textura
* &amp;lbrack;Projeto&amp;rbrack; As miniaturas são armazenadas no arquivo de projeto para uma abertura mais rápida dos projetos
* &amp;lbrack;Projeto&amp;rbrack; Configuração nas preferências para armazenar dados do cache dentro do arquivo de projeto, com modos diferentes (sem cache, cache leve, cache cheio)
* &amp;lbrack;Scripting&amp;rbrack; &amp;lbrack;Breaking change&amp;rbrack; Migração do Qt para o Qt6.15 - afeta a compatibilidade dos plug-ins existentes
* &amp;lbrack;Scripting&amp;brack; Os plug-ins padrão e a pasta de scripts agora estão na pasta Documentos
* &amp;lbrack;Scripting&amp;brack; Nova interface para plug-ins, visando a consistência visual com os painéis principais do Sampler
* Exemplos de plug-in do &amp;brack;Scripting&amp;rbrack; Access 2 para descobrir os recursos do plug-in do Sampler
* &amp;lbrack;Scripting&amp;brack; Nova função open_3d_catpure()
* &amp;lbrack;Scripting&amp;brack; Ao inserir uma camada, controle se ela é inserida acima ou abaixo da posição de destino

**Corrigido:**

* &amp;lbrack;captura 3D&amp;rbrack; Falha se a Captura de Objeto não puder ser iniciada no macOS
* &amp;lbrack;O aplicativo &amp;rbrack; falha ao sair
* &amp;lbrack;Aplicativo&amp;rbrack; trava ao sair ao adicionar ativos ao painel do projeto
* &amp;lbrack;Aplicativo&amp;rbrack; Renomear um ativo do projeto não funciona a menos que você pressione enter
* &amp;lbrack;Aplicativo&amp;rbrack; As entradas de menu Desfazer e Refazer não estão desativadas quando deveriam estar
* &amp;lbrack;Ativos&amp;rbrack; Não é possível excluir ativos da seção Todas as Bibliotecas do painel Ativos
* &amp;lbrack;Content&amp;brack; Criador de atlas - Usar mapa de opacidade existente, se presente
* &amp;lbrack;Content&amp;brack; Combinar de ID de Cor - Corrigir a escolha de cores na cor base
* &amp;lbrack;Camadas&amp;rbrack; Evitar cálculos inúteis ao usar geradores
* &amp;lbrack;Camadas&amp;rbrack; Ajustar um gerador pode levar ao acionamento de muitos computadores
* &amp;lbrack;Desempenho&amp;rbrack; Melhorar o gerenciamento de memória da GPU
* &amp;lbrack;Performance&amp;rbrack; O cache de renderização não pode ser usado ao reiniciar o aplicativo
* &amp;lbrack;Recursos&amp;rbrack; Os arquivos somente leitura não estão visíveis no painel Ativos
* &amp;lbrack;Scripting&amp;brack; Permitir a reutilização de uma camada após adicionar outra camada
* &amp;lbrack;Scripting&amp;brack; Alterar a estrutura de pilha de camadas várias vezes em um script pode falhar

**Removido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Remove o suporte para arquivos de imagem .dng e .nef

## Versão 4

### **4.5.2 GRUYERE**

*(Lançado Em: 07 De novembro De 2024)*

**Corrigido:**

* &amp;lbrack;Content&amp;brack; Filtros de mesclagem de Corte, Bordado e Height

### **4.5.1 GRUYERE**

*(Lançado Em 30 De julho De 2024)*

**Corrigido:**

* &amp;preto;Camadas&amp;rbrack; Pintar máscaras em tons de cinza não funciona, afetando ferramentas como Carimbo de Clonar, Distorção de Tinta, Preenchimento sensível ao conteúdo

### **4.5.0 GRUYERE**

*(Lançado Em 18 De julho De 2024)*

**Adicionado**

* &amp;lbrack;Interoperabilidade&amp;rbrack; Enviar materiais para UE5, Blender, Maya, 3DsMax Unity
* &amp;lbrack;Content&amp;brack; Nova categoria de gerador de textura - Gradientes
* &amp;lbrack;Content&amp;brack; Ferramenta HDRI - novo filtro de rotação Ambiente

**Corrigido:**

* &amp;lbrack;Parâmetros expostos&amp;rbrack; A exposição de valores de entrada .sbsar não funciona
* &amp;lbrack;Camadas&amp;rbrack; a Cor de base fica vermelha com imagens em tons de cinza
* &amp;lbrack;Renderização&amp;rbrack; as imagens em Tons de Cinza usadas em canais de cor têm espaço de cor incorreto
* &amp;lbrack;Scripting&amp;brack; Usar uma predefinição de exportação às vezes não exporta os canais esperados
* &amp;lbrack;Content&amp;brack; Dirt - Aplicar um filtro de Dirt sobre a Imagem para o Material gera um normal preto
* &amp;lbrack;Content&amp;rbrack; Relevo - A escala de um padrão no filtro de relevo não é linear entre 0 e 1
* &amp;lbrack;Content&amp;brack; Torne-o lado a lado - Consistência normal e de height aprimorada

### **4.4.1 FONDUE**

*(Lançado Em: 6 De junho De 2024)*

**Corrigido:**

* O filtro de Dirt &amp;lbrack;Content&amp;brack; está ausente
* &amp;lbrack;O erro de rede do AI&amp;rbrack; generativo às vezes ocorre ao usar Imagem para Textura

### **4.4.0 FONDUE**

*(Lançado Em 23 De maio De 2024)*

**Adicionado:**

* O cache do &amp;brack;Application&amp;brack; agora está armazenado em uma subpasta separada
* &amp;preto;Geração de AI&amp;rbrack; Imagem para Textura (Beta)
* &amp;Preta;Geração de AI&amp;rbrack; Texto com Padrão (Beta)
* &amp;Preenchimento;Geração de AI&amp;rbrack; Texto para Textura (Beta)
* &amp;lbrack;Scripting&amp;brack; Os ativos agora têm uma propriedade &#39;resource&#39;
* As camadas do &amp;brack;Scripting&amp;brack; agora têm uma propriedade &#39;output_usages&#39;

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao abrir arquivo de projeto corrompido
* &amp;lbrack;Aplicativo&amp;rbrack; Falha quando o projeto contém ativos corrompidos
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao desconectar um monitor no Windows
* &amp;lbrack;Aplicativo&amp;rbrack; Ícone de aplicativo incorreto na barra de tarefas do Windows
* &amp;lbrack;Aplicativo&amp;rbrack; A corrupção do arquivo de configuração principal pode levar à exclusão de arquivos
* Os Painéis do &amp;Preenchimento;Aplicativo&amp;Rbrack; aparecem na frente dos pop-ups
* &amp;lbrack;Os geradores de Textura do Content&amp;brack; possuem miniaturas desfocadas
* &amp;lbrack;Export&amp;brack; O canal de Opacidade gerado a partir de uma imagem importada é interrompido ao exportar um arquivo .sbs/.sbsar
* &amp;lbrack;Filtros&amp;rbrack; A ampliação pode falhar dependendo de suas camadas de entrada
* &amp;lbrack;Generative AI&amp;rbrack; Possíveis falhas ao receber resultados inesperados do serviço
* &amp;lbrack;Scripting&amp;rbrack; Falha ao carregar automaticamente um plug-in a partir de uma variável de ambiente
* &amp;lbrack;Scripting&amp;rbrack; Possível falha ao atribuir Uso de Saída com a API

### **4.3.3 EMPANADA**

*(Lançado Em 26 De março De 2024)*

**Adicionado:**

* &amp;lbrack;captura 3D&amp;rbrack; Novos parâmetros UV automáticos avançados durante o processo de postagem
* &amp;lbrack;Filtros&amp;rbrack; Filtro perfurado: capacidade de inverter e alterar o tamanho do padrão personalizado

**Corrigido:**

* A Cor de base do &amp;lbrack;captura 3D&amp;rbrack; pode estar incorreta no macOS
* &amp;lbrack;captura 3D; Falha ao processar uma nova versão
* &amp;lbrack;captura 3D; A etapa de Pós-processo pode falhar no macOS
* &amp;lbrack;captura 3D; A camada de Transformo Mesh pode levar à renderização incorreta
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao iniciar o Sampler enquanto uma instância anterior ainda está exportando
* &amp;lbrack;Aplicativo&amp;rbrack; o Sampler não responde por um momento quando iniciado pela primeira vez
* O mapa de Ângulos de anisotropia do &amp;brack;Export&amp;brack; não é exportado
* &amp;lbrack;Filtros&amp;rbrack; Adicionar um tecido à pilha de camadas pode causar um travamento
* &amp;lbrack;Filtros&amp;rbrack; Adicionar um Relevo à pilha de camadas pode causar um travamento
* &amp;lbrack;Filtros&amp;rbrack; O Preenchimento sensível ao conteúdo falha ao usar imagens de 32 bits
* &amp;lbrack;Filtros&amp;rbrack; Relevo: a opacidade das camadas abaixo não é totalmente substituída
* &amp;lbrack;Filtros&amp;rbrack; Preenchimento: o modo Combinar não funciona no Designer e no Painter
* &amp;lbrack;Filtros&amp;brack; Bordado: a seleção automática de cores está corrompida
* &amp;lbrack;Preferências&amp;rbrack; Impedir a definição de um caminho não compatível para o captura 3D Cache
* &amp;lbrack;Preferências&amp;rbrack; A preferência Formato normal não funciona
* &amp;lbrack;Scripting&amp;brack; Os parâmetros de canais de Asset.export_material diferenciam maiúsculas de minúsculas

### **4.3.2 EMPANADA**

*(Lançado Em 22 De fevereiro De 2024)*

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Salvar um projeto em um compartilhamento de rede no Windows corrompe o arquivo de projeto

### **4.3.1 EMPANADA**

*(Lançado Em 15 De fevereiro De 2024)*

**Corrigido:**

* &amp;lbrack;captura 3D&amp;rbrack; Falha quando arquivos de imagem se tornam inacessíveis durante a geração de máscaras em lote
* &amp;lbrack;Export&amp;brack; Exportar um material com Cortar ou relativo à camada de política de entrada fornece resultados inválidos
* &amp;lbrack;Camadas&amp;rbrack; Falha rara ao renderizar uma pilha de camadas
* &amp;lbrack;Filtros&amp;brack; Bordado - Corrigir problema ao usar entrada de material no MacOS
* &amp;lbrack;Filtros&amp;rbrack; Estilização - Suporte a Geradores de Textura
* &amp;lbrack;Filtros&amp;rbrack; Padrão - Corrigir a nomeação de parâmetros
* &amp;lbrack;Localization&amp;rbrack; “Salvar como...” na janela informações de hardware, no menu ajuda, está aparecendo deslocalizado

### **4.3.0 EMPANADA**

*(Lançado Em 25 De Janeiro De 2024)*

**Adicionado**

* &amp;lbrack;Assets&amp;rbrack; Novo tipo de ativo: Geradores de textura
* &amp;lbrack;Ativos&amp;rbrack; Novos materiais incluídos nos Ativos iniciais
* &amp;lbrack;Ativos&amp;rbrack; Novo seletor de ativos para parâmetros de imagem no painel Propriedades
* &amp;lbrack;Ativos&amp;rbrack; Arraste e solte Geradores de textura do painel Ativos para os seletores de imagem no painel Propriedades
* &amp;lbrack;Assets&amp;rbrack; Arrastar e soltar Geradores de Textura do explorador de arquivos do sistema operacional
* &amp;lbrack;Ativos&amp;rbrack; Os filtros podem sugerir o ajuste de geradores por meio de uma tag de usuário na entrada da imagem
* &amp;lbrack;Assets&amp;rbrack; Os Geradores de Textura podem definir qual filtro deve sugerir através de uma tag de usuário
* &amp;lbrack;Content&amp;brack; Novo filtro de Corte de Perspectiva
* &amp;lbrack;Content&amp;brack; Novo filtro de estilização
* &amp;preto;Content&amp;brack; Modo de mesclagem no Filtro de preenchimento
* &amp;lbrack;Content&amp;brack; Filtro de bordado atualizado
* &amp;lbrack;Content&amp;brack; Filtro de quebra de pintura atualizado
* &amp;lbrack;Content&amp;brack; Atualizado todos os filtros para suportar Geradores de Textura
* &amp;lbrack;Camadas&amp;rbrack; Capacidade de escolher um canal de saída do Gerador de Textura ao adicioná-lo à pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Capacidade de listar e aplicar facilmente predefinições em Geradores de textura
* &amp;lbrack;Camadas&amp;rbrack; Exibir uma visualização do Gerador de Textura nos seletores de imagem
* Os parâmetros do Gerador de textura do &amp;brack;Layers&amp;brack; podem ser expostos e exportados
* &amp;lbrack;Camadas&amp;rbrack; Atribui o uso de Cor Base ao importar uma única imagem com o Modelo de Criação de Importação de Textura
* &amp;lbrack;Camadas&amp;rbrack; Feedback ao tentar arrastar e soltar arquivos incompatíveis em seletores de imagem no painel Propriedades
* &amp;lbrack;Camadas&amp;rbrack; Gerar um canal de opacidade a partir do canal alfa de uma imagem importada
* &amp;lbrack;Camadas&amp;rbrack; A imagem para material (AI) é mais rápida de calcular ao alterar sua categoria
* &amp;lbrack;Camadas&amp;rbrack; Selecione a camada mais relevante depois que um Modelo de criação for usado
* &amp;lbrack;Camadas&amp;rbrack; Os widgets de posição agora podem ser ajustados com um controle deslizante no grupo Parâmetros avançados
* &amp;preto;Exportar&amp;rbrack; Exibir uma porcentagem na fila em vez de números brutos
* &amp;lbrack;Interoperabilidade&amp;rbrack; O canal de Opacidade agora é reconhecido como canal alfa ao enviar para o Painter
* &amp;lbrack;Aplicativo&amp;rbrack; Novo diálogo para exibir e salvar informações de hardware
* &amp;lbrack;Aplicativo&amp;rbrack; Nova preferência para alterar a escala de height padrão para cada projeto
* &amp;Preenchimento;Aplicativo&amp;Rbrack; Melhorar a exibição de ativos desatualizados
* &amp;brack;Scripting&amp;brack; Novas funções asset.documentResolution() e asset.setDocumentResolution()
* &amp;lbrack;Scripting&amp;brack; Nova função select_asset()
* &amp;lbrack;Scripting&amp;brack; API Python para Geradores de Textura
* &amp;brack;Scripting&amp;brack; get_project_assets() agora retorna objetos 3D
* &amp;lbrack;UI&amp;rbrack; O tamanho da miniatura do ativo pode ser alterado no painel Ativos
* &amp;lbrack;UI&amp;rbrack; Ícones de exibição do visor atualizados

**Corrigido:**

* &amp;lbrack;O zoom com a roda do mouse está bloqueado em 244%
* &amp;lbrack;Application&amp;brack; Falha no início ao inicializar a API gráfica
* &amp;lbrack;Aplicativo&amp;rbrack; Falha se o nome do projeto contiver o caractere #
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha ao abrir um projeto antigo
* &amp;lbrack;Aplicativo&amp;rbrack; A reabertura do projeto atual pode levar a uma falha
* &amp;lbrack;Aplicativo&amp;rbrack; Algumas alterações do projeto não são registradas e são perdidas sem aviso ao fechar o projeto, se não forem salvas
* &amp;lbrack;Export&amp;brack; .sbs/.sbsar problemas de exportação ao usar vários arquivos com o mesmo nome
* &amp;lbrack;Export&amp;brack; Espaço de cor incorreto para imagens em tons de cinza exportadas no arquivo .sbs/.sbsar
* &amp;lbrack;Filtros&amp;rbrack; Problemas de comportamento de mesclagem de opacidade
* &amp;lbrack;Camadas&amp;rbrack; arquivos .svg às vezes não são renderizados na resolução correta
* &amp;lbrack;Desempenho&amp;rbrack; Alguns salvamentos de projeto em disco são desnecessários
* &amp;lbrack;Projeto&amp;rbrack; Importar um projeto antigo não carrega predefinições associadas
* &amp;lbrack;Scripting&amp;brack; Não é possível obter os parâmetros da primeira camada inserida
* &amp;lbrack;UI&amp;rbrack; O pop-up de visualização ao passar o mouse sobre um ativo pode aparecer no local ou na tela errada
* &amp;lbrack;UI&amp;rbrack; Os painéis desencaixados ficam visíveis e podem ser usados na tela de boas-vindas

### **4.2.2 DORAYAKI**

*(Lançado Em: 5 De dezembro De 2023)*

**Adicionado:**

* O &amp;lbrack;captura 3D&amp;rbrack; captura 3D agora está 5% a 10% mais rápido no Windows
* &amp;lbrack;captura 3D&amp;rbrack; Melhorar limpeza de malha antes da dizimação
* &amp;lbrack;Engine&amp;rbrack; Atualize o Substance Engine para a versão 9.0.3
* &amp;lbrack;Camadas&amp;rbrack; Preenchimento sensível ao conteúdo: atualização upstream, várias correções de caso de uso e suporte a Linux

**Corrigido:**

* &amp;lbrack;captura 3D&amp;rbrack; Clicar em “Voltar” após o alinhamento e “Avançar” não atualiza a nuvem de pontos
* &amp;lbrack;captura 3D&amp;rbrack; Malha exibida com furos após ser adicionada ao projeto
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao sair do modo de tela cheia após uma Captura 3D
* &amp;lbrack;Application&amp;brack; Falha com arquivos de imagem criados
* &amp;lbrack;Aplicativo&amp;rbrack; Se estiver em “Todas as bibliotecas” ao sair do Sampler, o painel Ativos ficará vazio na reinicialização
* &amp;lbrack;Aplicativo&amp;rbrack; Vazamento de memória ao exportar material
* &amp;lbrack;Aplicativo&amp;rbrack; Abrir um projeto salvo com versões anteriores do Sampler pode levar a uma falha
* O &amp;brack;Aplicativo&amp;rbrack; pode travar ao falhar na conversão de malhas 3D
* &amp;lbrack;Aplicativo&amp;rbrack; Falha silenciosa ao abrir um .sbsar enquanto o Sampler está em execução
* &amp;lbrack;Export&amp;rbrack; Falha ao exportar um arquivo .sbs/.sbsar com um uso personalizado
* &amp;lbrack;Export&amp;brack; Mapas normais exportados são sempre DirectXs, independentemente da configuração do usuário
* &amp;lbrack;Exportar&amp;rbrack; exportar um objeto 3D para um arquivo FBX no macos não funciona
* Inconsistências do &amp;brack;Export&amp;brack; ao exportar uma Pilha de camadas com um filtro de Bordado como um arquivo .sbs/.sbsar
* &amp;lbrack;Export&amp;rbrack; Às vezes, exportar arquivos .sbs/.sbsar não funciona
* &amp;lbrack;Export&amp;brack; Às vezes, ao exportar um arquivo .sbs/.sbsar, as imagens não têm a profundidade de bits correta
* &amp;lbrack;Camadas&amp;rbrack; Tornar uma camada de respingo invisível renderiza seu primeiro filho
* &amp;lbrack;Camadas&amp;rbrack; Falha ao carregar a máscara na camada Brilho/Contraste
* &amp;lbrack;Camadas&amp;rbrack; Mensagens de erro enganosas são exibidas após a exclusão da camada
* &amp;lbrack;Camadas&amp;rbrack; Possível falha ao fazer downgrade de um ativo
* &amp;lbrack;Camadas&amp;rbrack; Algumas saídas não são conectadas a entradas, a menos que o uso seja forçado no painel Configurações do canal
* O menu suspenso da camada de referência do &amp;lbrack;Tamanho físico&amp;rbrack; pode ser redefinido por engano
* &amp;lbrack;UI&amp;rbrack; Os ícones de importação de informações de modelos precisam de atualização
* &amp;lbrack;UI&amp;rbrack; A dica de atalho do visor aparece sempre que o layout do visor é alterado

### **4.2.1 DORAYAKI**

*(Lançado Em 21 De setembro De 2023)*

**Adicionado:**

* &amp;lbrack;Content&amp;brack; Imagem para Material - Melhorar a geração de microdetalhes em mapas normais
* &amp;lbrack;Content&amp;brack; Imagem para material - Novo parâmetro de intensidade de deleite
* &amp;lbrack;Camadas&amp;rbrack; As imagens podem ser adicionadas nas camadas de importação de imagem
* &amp;lbrack;Camadas&amp;rbrack; As imagens podem ser removidas nas camadas de importação de imagem
* &amp;lbrack;Camadas&amp;rbrack; Camadas inválidas agora podem ser excluídas
* &amp;lbrack;2D View&amp;rbrack; Shift+C atalho para voltar os canais
* &amp;lbrack;captura 3D; Exibir uma caixa de informações de aviso quando o usuário importar menos de 20 imagens
* &amp;lbrack;Aplicativo&amp;rbrack; Novas preferências para definir o valor padrão da divisão em blocos gráficos da textura do material
* &amp;lbrack;Integração&amp;rbrack; Interface do usuário do tutorial atualizada para Imagem para material (IA) e Aumento
* &amp;lbrack;Scripting&amp;rbrack; API captura 3D: DatasetInfo tem mais dados quando Capture3dState está definido como alinhado
* &amp;lbrack;Scripting&amp;brack; Novo argumento select_asset para create_asset(). Novas funções: wait_for_computation() e clear_render_cache()

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Falha quando a região de corte é muito pequena
* &amp;lbrack;Camadas&amp;rbrack; Falha ao adicionar ou ajustar o filtro Corte demarcado
* &amp;lbrack;Camadas&amp;rbrack; Criar um quadrado na região de corte leva a uma resolução de saída de material incorreta
* &amp;lbrack;Camadas&amp;rbrack; As saídas às vezes desaparecem quando várias camadas estão desativadas
* &amp;lbrack;Camadas&amp;rbrack; O cache de renderização pode não ser invalidado corretamente com os filtros Imagem para material (AI) e Aumento
* &amp;lbrack;Camadas&amp;rbrack; Não é possível adicionar o filtro de Ampliação ao selecionar “Não mostrar esta mensagem novamente” no pop-up de aviso
* &amp;lbrack;Camadas&amp;rbrack; Não é possível restaurar a imagem no filtro Bordado depois de modificada
* &amp;lbrack;Export&amp;brack; A resolução normal de mapas exportada muda ao alterar o formato normal
* &amp;lbrack;Export&amp;brack; Remover o sufixo de nome de arquivo “\_environment” ao exportar um ambiente
* &amp;lbrack;Export&amp;brack; Não é possível exportar um arquivo .sbsar quando há uma camada de Transformação de distorção na pilha de camadas
* &amp;lbrack;O modo de exibição 2D&amp;rbrack; “Ajustar à tela” não funciona quando a resolução é alterada
* &amp;lbrack;Aplicativo&amp;rbrack; Após fechar a janela do aplicativo durante a computação, o processo do aplicativo ainda poderia estar em execução
* &amp;lbrack;O aplicativo &amp;rbrack; falha ao sair
* &amp;lbrack;Aplicativo&amp;rbrack; Invalidar o cache de renderização ao alternar as redes neurais aceleradas por GPU
* &amp;lbrack;Scripting&amp;brack; nomear um plug-in como um nome de painel existente causa comportamentos inesperados
* &amp;lbrack;UI&amp;rbrack; Clicar em um item com uma dica fará com que a dica desapareça até reiniciar
* O valor da escala de Heights do &amp;lbrack;UI&amp;rbrack; pode mudar ao alternar ativos
* &amp;lbrack;UI&amp;rbrack; Margem incorreta em caixas de combinação

### **4.2 DORAYAKI**

*(Lançado Em: 05 De setembro De 2023)*

**Adicionado:**

* &amp;lbrack;Content&amp;rbrack; Filtros de imagem para material (IA) e Delighter extremamente aprimorados
* &amp;lbrack;Content&amp;brack; Novo filtro de Ampliação
* &amp;lbrack;Content&amp;brack; O filtro Cortar agora tem resolução de saída dinâmica.
* &amp;preto;Modelo de criação de material&amp;rbrack; Adicionar configuração de tamanho do documento.
* &amp;preto;Modelo de criação de material&amp;rbrack; Novo botão de alternância “Adicionar um corte”.
* &amp;lbrack;Modelo de criação de material&amp;rbrack; Novo alternador de “Aumentar material”
* &amp;preto;Modelo de criação de material&amp;rbrack; Exibir tamanho da imagem importada
* &amp;preto;Modelo de criação de material&amp;rbrack; Fornecer feedback quando algumas imagens importadas não puderem ser usadas
* &amp;preto;Modelo de criação de material&amp;rbrack; Avisar quando os tamanhos das imagens forem inconsistentes
* &amp;lbrack;Modelo de criação de material&amp;rbrack; Novos avisos e dicas de ferramentas
* &amp;lbrack;Camadas&amp;rbrack; Exibe a resolução das camadas na pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; A resolução de computação da camada agora pode ser definida como Tamanho do documento ou Tamanho de entrada
* &amp;preto;Camadas&amp;rbrack; Mostrar a resolução das camadas na pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Alterne uma política de resolução de camada para Documento ou Entrada de camada quando aplicável
* &amp;lbrack;Layers&amp;brack; Avisa o usuário quando um filtro de Ampliação é adicionado manualmente e fornece alguma documentação
* &amp;lbrack;Camadas&amp;rbrack; Avisar o usuário ao fazer um upscale linear e se oferecer para usar o filtro Upscale
* &amp;lbrack;Camadas&amp;rbrack; Computar uma camada de Imagem para material (AI) agora pode ser cancelada mais rapidamente, para melhorar os tempos de renderização ao ajustar a pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Computar uma camada em upscale agora pode ser cancelado mais rapidamente, para melhorar os tempos de renderização ao ajustar a pilha de camadas
* &amp;lbrack;Export&amp;brack; Permitir substituição de resolução de texturas exportadas
* &amp;lbrack;Export&amp;brack; Os canais para exportar a lista agora estão ordenados
* &amp;lbrack;Export&amp;brack; Exibir resolução do canal nos canais para exportar lista
* &amp;lbrack;Application&amp;brack; Nova preferência para ativar ou desativar redes neurais aceleradas por GPU
* &amp;lbrack;UI&amp;rbrack; Melhorias nas listas suspensas de resolução
* &amp;lbrack;UI&amp;rbrack; Novos ícones para os filtros Transformação em malha, Pós-processo em malha e Entrelinha
* &amp;lbrack;UI&amp;rbrack; Renomeie o painel “Compartilhar” para “Exportar”
* &amp;lbrack;Scripting&amp;brack; Adicionar suporte de resolução de saída de camada à API de exportação
* &amp;lbrack;Scripting&amp;rbrack; Adicionado Corte, Ampliação e Tamanho do documento à API de importação de imagem
* &amp;lbrack;Integração&amp;rbrack; Novos tutoriais
* &amp;lbrack;Integração&amp;rbrack; Atualizar conteúdo de telas de Boas-vindas e Novidades
* &amp;lbrack;Engine&amp;rbrack; Atualização Substance Engine para a versão 9.0.1

**Corrigido:**

* &amp;lbrack;captura 3D&amp;rbrack; Melhorar a nomenclatura das opções de Precisão nos parâmetros de configuração de Alinhamento
* &amp;lbrack;Aplicativo&amp;rbrack; Importar imagens com um não múltiplo de 16 dimensões pode levar a um travamento
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao duplicar um ativo no painel Projeto
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao alternar ativos no painel Projeto
* &amp;lbrack;Content&amp;brack; Pintar uma máscara personalizada para o filtro Snow não funciona corretamente
* &amp;lbrack;Parâmetros expostos&amp;rbrack; As alterações dos parâmetros expostos podem ser perdidas ao alternar os materiais
* &amp;lbrack;Interoperabilidade&amp;rbrack; Enviar um material do painel Exportar pode levar a um travamento
* &amp;lbrack;Camadas&amp;rbrack; O Preenchimento sensível ao conteúdo pára de ser computado ao alternar de uma única entrada de imagem para uma entrada de material
* &amp;lbrack;Camadas&amp;rbrack; Falha após duplicar uma Iluminação do ambiente que contém um material
* &amp;lbrack;Camadas&amp;rbrack; A camada de importação de imagem exibe um nome de imagem incorreto no painel Propriedades se o arquivo de imagem tiver sido renomeado
* &amp;lbrack;Camadas&amp;rbrack; Às vezes, um ícone giratório é exibido em uma camada inativa
* &amp;lbrack;Camadas&amp;rbrack; Às vezes, alterar o uso de saída de uma imagem em uma camada de importação de imagem não funciona
* &amp;lbrack;Camadas&amp;rbrack; Erros de digitação na janela Modelo de criação
* A dica de ferramenta de integração do visor 3D &amp;brack;UI&amp;rbrack; tem problemas de foco
* &amp;lbrack;UI&amp;rbrack; O nome da imagem poderá estourar se o nome do arquivo for muito longo
* &amp;lbrack;UI&amp;rbrack; Pequenos problemas de layout da barra de ferramentas do pincel ao usar a borracha
* &amp;lbrack;UI&amp;rbrack; As strings estão truncadas em alguns idiomas no painel Configurações do visualizador
* &amp;lbrack;UI&amp;rbrack; Enquanto o pop-up da dica de ferramenta do visor é exibido, pressionar “space” cria um novo projeto

### **4.1.2 CANNOLI**

*(Lançado: 20 de junho de 2023)*

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Vazamento de memória ao ajustar materiais e filtros de Substance, causando falhas

### **4.1.1 CANNOLI**

*(Lançado: 06 De junho De 2023)*

**Adicionado**

* &amp;lbrack;Engine&amp;rbrack; Atualização Substance Engine para a versão 9.0
* &amp;lbrack;Interoperabilidade&amp;rbrack; Enviar objetos 3D para o Stager e Painter

**Corrigido:**

* &amp;lbrack;Os aplicativos do captura 3D&amp;rbrack; travam quando o captura 3D falha
* &amp;lbrack;captura 3D; Falha quando uma imagem não pode ser carregada
* &amp;lbrack;captura 3D&amp;rbrack; Falha ao atingir a etapa de Reconstrução de malha
* &amp;lbrack;captura 3D&amp;rbrack; Falha ao redimensionar a caixa delimitadora
* &amp;lbrack;captura 3D&amp;rbrack; A importação de máscaras seguindo a convenção não atribui a máscara corretamente
* &amp;lbrack;captura 3D; A renderização falha ao ajustar a caixa delimitadora
* &amp;lbrack;captura 3D&amp;rbrack; Alternar entre a versão e alternar as opções de renderização durante o processo de Captura 3D é lento
* &amp;lbrack;captura 3D&amp;rbrack; Alternar entre versões durante a etapa de Pós-processamento às vezes é interrompido
* &amp;lbrack;Application&amp;brack; Falha na inicialização
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao duplicar um material renomeado
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao abrir um projeto .alch legado sem sua pasta de dependência
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao conectar/desconectar uma tela, o computador entra em suspensão ou é acessado remotamente
* &amp;lbrack;Aplicativo&amp;rbrack; Falha e vazamentos de memória relacionados ao gerenciamento de ativos não persistentes
* &amp;lbrack;Export&amp;brack; A escolha do formato de material para tipos de arquivo de objeto 3D que incorporam ou fazem referência a texturas deve ser desativada
* &amp;lbrack;Export&amp;brack; Falha se algo der errado durante a exportação de Objeto 3D
* &amp;lbrack;Export&amp;brack; Falha ao exportar um arquivo .sbs/.sbsar
* &amp;lbrack;Export&amp;brack; Falha ao importar predefinição personalizada que tem o mesmo Rótulo, mas não o mesmo nome de arquivo
* &amp;lbrack;Export&amp;brack; Exportar uma iluminação do ambiente para um arquivo .sbs/.sbsar às vezes não funciona
* &amp;lbrack;Export&amp;rbrack; A exportação Gltf/Glb codifica as texturas na base64
* &amp;lbrack;O campo de texto Nome do Export&amp;brack; não funciona ao focar novamente
* &amp;lbrack;Export&amp;brack; Preservar divisão em blocos gráficos não funciona ao exportar uma camada de Imagem para material (alimentada por IA) para um arquivo .sbs/.sbsar
* &amp;lbrack;Export&amp;brack; Ao exportar arquivos gltf e substituir, a lista de arquivos a serem substituídos não está correta
* &amp;lbrack;Parâmetros expostos&amp;rbrack; A propagação aleatória não funciona em arquivos .sbs/.sbsar exportados
* &amp;lbrack;Camadas&amp;rbrack; O Preenchimento sensível ao conteúdo às vezes trava quando adicionado pela segunda vez
* &amp;lbrack;Camadas&amp;rbrack; Falha ao calcular uma pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; O cache de disco de Imagem para material (AI) não funciona
* &amp;lbrack;Camadas&amp;rbrack; Possível falha ao ajustar uma camada
* &amp;lbrack;Desempenho&amp;rbrack; Vazamentos de memória
* &amp;lbrack;Projeto&amp;rbrack; Falha ao salvar um projeto
* &amp;lbrack;Projeto&amp;rbrack; Importar o mesmo projeto duas vezes seguidas duplica os ativos
* &amp;lbrack;UI&amp;rbrack; Botões arredondados com apenas um ícone não são renderizados corretamente

### 4.1.0 Cannoli

*(Lançado: 28 De março De 2023)*

**Adicionado:**

* &amp;lbrack;Content&amp;brack; Novo filtro de Bordado
* &amp;lbrack;Content&amp;brack; Novo filtro de Distorção de Tinta
* &amp;lbrack;UI&amp;rbrack; Adicionar opção de exportação no menu Arquivo
* O botão Voltar do &amp;lbrack;captura 3D&amp;rbrack; agora está disponível na etapa de alinhamento
* &amp;lbrack;captura 3D&amp;rbrack; Imagens Manipular orientação EXIF do JPEG
* &amp;lbrack;captura 3D&amp;rbrack; Script - Nova propriedade dataset_info.camera
* &amp;lbrack;captura 3D&amp;rbrack; Adicionar suporte a Linux (consulte a documentação)
* &amp;lbrack;captura 3D&amp;rbrack; Verificar o acesso de leitura das imagens importadas
* &amp;lbrack;Integração&amp;rbrack; Aprender - 2 novos tutoriais (Bordado e Distorção de Tinta)
* &amp;lbrack;Integração&amp;rbrack; Atualizado conteúdo Novidades

**Corrigido:**

* &amp;lbrack;captura 3D; Manter posição da câmera ao alterar a versão
* &amp;lbrack;captura 3D&amp;rbrack; Mescla todos os grupos de um objeto em um
* &amp;lbrack;captura 3D&amp;rbrack; Malhas geradas renomeadas para Original
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao tentar gerar miniatura de uma imagem não existente
* &amp;lbrack;Ativos&amp;rbrack; Ícone da lixeira não faz nada no painel Ativos
* &amp;lbrack;Content&amp;rbrack; Atualizar filtros com slots de material não funciona como esperado
* &amp;lbrack;Export&amp;brack; Possível falha ao exportar um ativo com filtros específicos
* &amp;brack;Export&amp;brack; SBS/SBSAR Export - as camadas de importação de imagem têm prioridade sobre os parâmetros de imagem
* &amp;lbrack;Export&amp;brack; UE4 A predefinição de exportação não funciona com o PNG
* &amp;lbrack;Camadas&amp;rbrack; Falha ao soltar um material e um filtro ao mesmo tempo do explorador do sistema operacional
* &amp;lbrack;Camadas&amp;rbrack; Falha ao arrastar qualquer arquivo SBSAR com qualquer arquivo de imagem
* &amp;lbrack;Camadas&amp;rbrack; O canal de opacidade do bordado pode ser completamente branco
* &amp;lbrack;Localization&amp;rbrack; O idioma chinês pode ser exibido por padrão no Linux
* &amp;lbrack;Desempenho&amp;rbrack; Corrigido um problema de memória ao remover uma camada de um ativo
* &amp;lbrack;Projeto&amp;rbrack; Possível falha ao salvar
* &amp;lbrack;UI&amp;rbrack; Adicionar espaçamento ausente no botão de menu da Versão
* &amp;lbrack;UI&amp;rbrack; O botão Cancelar não é exibido corretamente
* &amp;lbrack;UI&amp;rbrack; Desativar a animação dos controles deslizantes para os parâmetros de pós-processamento do captura 3D
* &amp;lbrack;UI&amp;rbrack; A janela Modelo de Criação de Material não se fecha ao clicar fora
* &amp;lbrack;UI&amp;rbrack; O acessador rápido do filtro fecha-se ao clicar fora

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 4.0.2 Banana

*(Lançado: 09 de março de 2023)*

**Adicionado:**

* &amp;lbrack;captura 3D&amp;rbrack; A utilização do disco mostra a quantidade usada
* &amp;lbrack;captura 3D&amp;rbrack; A importação de fotos é assíncrona e rápida
* &amp;lbrack;Scripting&amp;rbrack; Novas classes e funções para gerar script do recurso captura 3D
* &amp;lbrack;Scripting&amp;brack; Nova classe ExportController para executar ações quando a exportação for concluída, falha ou cancelada
* &amp;lbrack;Scripting&amp;brack; Passar argumentos scripts python executados com —run-script
* Feedback de IU&amp;rbrack;UI&amp;rbrack; ao arrastar um ativo sobre o painel Camadas
* O filtro de Temperatura de Cor do &amp;lbrack;Content&amp;brack; agora está funcionando nos materiais
* &amp;lbrack;Content&amp;brack; Normal para filtros de Height tem uma nova opção para preservar a divisão em blocos gráficos

**Corrigido:**

* &amp;lbrack;captura 3D; Tamanho da imagem corrigido na etapa de alinhamento do conjunto de dados
* &amp;lbrack;captura 3D&amp;rbrack; Remover vértices duplicados após o desempacotamento UV
* &amp;lbrack;captura 3D&amp;rbrack; MacOS - Detecção aprimorada se o captura 3D estiver disponível
* &amp;lbrack;captura 3D&amp;rbrack; Falha ao fechar a janela do Captura 3D durante a importação de imagens
* &amp;lbrack;captura 3D; Falha ao gerar uma nova versão
* &amp;lbrack;captura 3D; Falha ao tentar carregar o objeto 3D no visualizador
* &amp;lbrack;captura 3D&amp;rbrack; Falha ao usar um caminho com caracteres não UTF8
* &amp;lbrack;captura 3D&amp;rbrack; Acertos &amp; Dicas erro
* &amp;lbrack;captura 3D&amp;rbrack; As malhas não são mais dimensionadas para caber no cubo da unidade
* &amp;lbrack;captura 3D&amp;rbrack; Evitar falhas ao fechar o Captura 3D durante a renderização
* &amp;lbrack;captura 3D; Remover uma máscara faz a imagem desaparecer
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao importar duas vezes um ativo simultaneamente
* &amp;lbrack;Aplicativo&amp;rbrack; Fazer backup da versão anterior dos ativos ao abrir um projeto, se eles nunca tiverem feito backup
* &amp;lbrack;Aplicativo&amp;rbrack; Armazena corretamente em cache os mapas baked quando nem todos os mapas estão armazenados
* &amp;lbrack;O aplicativo&amp;rbrack; trava quando um objeto 3D é exibido.
* &amp;lbrack;Aplicativo&amp;rbrack; O último material é duplicado ao salvar o projeto
* &amp;lbrack;Aplicativo&amp;rbrack; Evitar falhas ao cancelar o computador de Pós-processamento de Malha durante a etapa de cozimento
* &amp;lbrack;Aplicativo&amp;rbrack; A reabertura do projeto atual não descarta as alterações
* &amp;lbrack;Aplicativo&amp;rbrack; Parar de gerar miniaturas para objetos 3D
* &amp;lbrack;Visualização 2D&amp;rbrack; Falha ao usar a ferramenta pincel
* &amp;lbrack;Content&amp;rbrack; Preenchimento sensível ao conteúdo - a computação pode travar
* &amp;lbrack;Content&amp;brack; O filtro Criador de Atlas está reduzindo o canal Opacidade
* &amp;lbrack;Export&amp;rbrack; Corrigir falha ao limpar fila de exportações
* &amp;lbrack;Exportar&amp;rbrack; exportação OBJ cria objeto 100 vezes menor do que o esperado
* &amp;preto;Camadas&amp;rbrack; As imagens coloridas importadas como canais em tons de cinza agora são consideradas tons de cinza
* &amp;lbrack;Os arquivos FBX do Export&amp;brack; não podem ser importados em aplicativos de terceiros
* &amp;lbrack;Export&amp;rbrack; os nomes de saída do Sombreador nos arquivos USD não estão corretos
* &amp;lbrack;Camadas&amp;rbrack; O nome da imagem não é atualizado ao alterar seu nome no explorador do sistema operacional
* &amp;lbrack;Scripting&amp;brack; Exibir uma mensagem de erro ao recarregar um script inválido
* &amp;lbrack;UI&amp;rbrack; botão de Material de base desativado quando não disponível
* &amp;lbrack;UI&amp;rbrack; Falha ao acessar a caixa de diálogo de arquivo na janela Modelo de criação de material
* &amp;lbrack;UI&amp;rbrack; O acessador Rápido está acessível mesmo quando o painel Camadas é fechado
* &amp;lbrack;UI&amp;rbrack; Os ícones Enviar para estão desalinhados
* &amp;lbrack;UI&amp;rbrack; O ícone da camada muda ao clicar no ícone de Combinar

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 4.0.1 Banana

*(Lançado em: 07 de fevereiro de 2023)*

**Corrigido:**

* &amp;lbrack;captura 3D&amp;rbrack; Ao usar máscaras, a projeção de textura pode estar quebrada
* &amp;lbrack;captura 3D&amp;rbrack; Artefatos podem aparecer em seu objeto
* &amp;lbrack;captura 3D; A malha exportada pode ser realmente pequena

**Problemas Conhecidos:**

* &amp;lbrack;captura 3D&amp;rbrack; as exportações de OBJ e FBX diminuem o resultado
* O &amp;lbrack;captura 3D&amp;rbrack; captura 3D está disponível no MacOS mesmo se o hardware não for compatível. Verifique a documentação.
* &amp;lbrack;captura 3D&amp;rbrack; Falha quando a reconstrução da malha é feita.
* &amp;lbrack;Camadas&amp;rbrack; O Preenchimento sensível ao conteúdo pode ficar travado se você ajustar as camadas abaixo
* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 4.0.0 Banana

*(Lançado: 31 De Janeiro De 2023)*

**Adicionado:**

* &amp;lbrack;captura 3D&amp;rbrack; Criar objetos 3D a partir de imagens
* &amp;lbrack;captura 3D&amp;rbrack; Assistente de captura 3D Dedicado
* &amp;lbrack;captura 3D&amp;rbrack; Importar ou gerar máscaras em preto e branco no conjunto de dados
* &amp;lbrack;captura 3D&amp;rbrack; Resultado do alinhamento - visualizar todos os recursos correspondentes como uma nuvem de pontos
* &amp;lbrack;captura 3D&amp;rbrack; Resultado do alinhamento - visualize e interaja com câmeras associadas a cada foto alinhada
* &amp;lbrack;captura 3D; Define a área de reconstrução com um widget de caixa delimitadora
* &amp;lbrack;captura 3D; Dimensionar, traduzir e girar em todos os eixos do widget da caixa delimitadora
* &amp;lbrack;captura 3D; Define a precisão da geometria para a malha reconstruída
* &amp;lbrack;captura 3D&amp;rbrack; Otimize sua malha e texturas criando uma nova versão
* &amp;lbrack;captura 3D; Cada uma das versões é automaticamente dizimada para o conjunto de números de faces de destino
* &amp;lbrack;captura 3D&amp;rbrack; A etapa de pós-processamento automaticamente desembrulha, reprojeta texturas e, em seguida, faz bake as informações normais de height e AO da malha de alto polígono
* &amp;lbrack;captura 3D&amp;rbrack; Adicionar o resultado original ou uma versão ao projeto do Sampler
* &amp;lbrack;captura 3D&amp;rbrack; Nova camada de Pós-processamento de Malha para dizimar, quebrar, reprojetar texturas automaticamente e fazer bake detalhes da camada de malha subjacente
* &amp;lbrack;captura 3D&amp;rbrack; Nova camada de Transformo de Malha para dimensionar, girar ou traduzir a camada de malha subjacente
* &amp;brack;Exportar&amp;rbrack; Nova janela de Exportação
* &amp;lbrack;Export&amp;brack; Configurações dedicadas e interface dependendo do tipo de ativo (material, iluminação do ambiente, malha)
* &amp;lbrack;Export&amp;brack; Exportar a malha como USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &amp;lbrack;Export&amp;brack; Define o tipo de material ao exportar arquivos de Substance (SBSAR, SBS)
* &amp;lbrack;UI&amp;rbrack; Move as configurações de cache para uma nova aba no pop-up Preferências
* &amp;lbrack;Aplicativo&amp;rbrack; As viewports 2D e 3D agora podem ser redimensionadas, trocadas e empilhadas verticalmente
* &amp;lbrack;Aplicativo&amp;rbrack; Nova variável de ambiente SAMPLER_RESOURCES_PATH para adicionar ativos iniciais extras
* &amp;lbrack;Scripting&amp;rbrack; Adicionadas variáveis de ambiente SAMPLER_PLUGIN_PATH e SAMPLER_SCRIPT_PATH para importar plug-ins e scripts na inicialização
* &amp;lbrack;Scripting&amp;brack; Funções de exportação adicionadas para materiais, luzes de ambiente e objetos 3D
* &amp;lbrack;Scripting&amp;rbrack; Identificador adicionado, valor padrão, valores mínimos e máximos, rótulos e valores de enumeração para parâmetros
* &amp;lbrack;Scripting&amp;rbrack; Adicionada a função import_textures para inserir um uso personalizado ao importar imagens

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao abrir um projeto recente e salvar na caixa de diálogo de confirmação
* A caixa de diálogo Arquivo &amp;brack;Application&amp;brack; impede a abertura de arquivos .ssa
* &amp;lbrack;Aplicativo&amp;rbrack; As caixas de diálogo de arquivos podem aparecer em uma janela em segundo plano no macOS
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha ao abrir projetos 3.2
* &amp;lbrack;Aplicativo&amp;rbrack; Selecionar um arquivo fecha a caixa de diálogo Arquivo antes de exibir avisos
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Exportar luzes de ambiente paramétricas não funciona
* &amp;lbrack;Camadas&amp;rbrack; O link “Clique aqui para procurar” na pilha de camadas não funciona mais
* &amp;lbrack;Camadas&amp;rbrack; Pintar várias imagens dentro da mesma camada às vezes não funciona
* &amp;lbrack;Camadas&amp;rbrack; Configurar uma imagem nas propriedades da camada não atualiza a miniatura do seletor de imagens
* &amp;lbrack;Camadas&amp;rbrack; Ajustar um ativo do Sampler adicionado como uma camada não funciona
* &amp;lbrack;Projeto&amp;rbrack; Atualização de ativo indesejado ao abrir um projeto
* &amp;lbrack;Scripting&amp;brack; A navegação para a pasta de plug-ins às vezes falha no Windows
* &amp;lbrack;Scripting&amp;rbrack; Falha ao usar &#39;open_project()&#39; em um script Python
* &amp;lbrack;Scripting&amp;rbrack; a exportação de JPEG está ausente da API
* &amp;lbrack;Scripting&amp;brack; O painel de registro não é somente leitura
* &amp;lbrack;Scripting&amp;brack; o valor do parâmetro image_picker não funciona
* &amp;lbrack;UI&amp;rbrack; Ícone de ativo ausente para luzes ambiente no painel Projeto
* &amp;lbrack;UI&amp;rbrack; A lista suspensa Enviar para o formato do Designer no pop-up Preferências pode estar vazia
* &amp;lbrack;UI&amp;rbrack; Alguns botões têm um estilo incorreto
* &amp;lbrack;UI&amp;rbrack; O rótulo se sobrepõe aos botões nos widgets Grupo de Botões
* &amp;lbrack;UI&amp;rbrack; A posição da dica de ferramenta está incorreta para “Ferramentas” no menu Definir o tamanho físico
* &amp;lbrack;UI&amp;rbrack; Ao alterar o idioma, o menu Arquivo fica desalinhado

**Problemas Conhecidos:**

* &amp;lbrack;captura 3D&amp;rbrack; Ao usar máscaras, a projeção de textura pode estar quebrada
* &amp;lbrack;captura 3D&amp;rbrack; Pequenos artefatos poderão aparecer em seu objeto se sua escala na transformação de malha for muito pequena
* &amp;lbrack;captura 3D&amp;rbrack; A malha exportada pode ser realmente pequena. Redefinir o dimensionamento da transformação e da reexportação da malha
* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

## Versão 3

### 3.4.1 Arancini

*(Lançado: 06 De outubro De 2022)*

**Adicionado:**

* &amp;lbrack;Integração&amp;rbrack; Novas telas de Boas-vindas e Novidades
* &amp;lbrack;Integração&amp;rbrack; Interface do Usuário de Tela Inicial Atualizada
* &amp;lbrack;Integração&amp;rbrack; Novo conteúdo de aprendizado na tela inicial
* &amp;lbrack;Scripting&amp;rbrack; Registra um erro no painel Registro quando um método não é reconhecido
* &amp;lbrack;Scripting&amp;brack; Novo módulo ssa.helpers para permitir a impressão no painel Log
* &amp;lbrack;Aplicativo&amp;rbrack; Suporte para o novo widget de botões lado a lado do Substance 3D Designer

**Corrigido:**

* &amp;lbrack;Export&amp;brack; Falha ao exportar um arquivo .sbsar fazendo referência a uma imagem ausente
* &amp;lbrack;Export&amp;brack; Falha ao exportar um ativo que faz referência a um arquivo de imagem corrompido
* &amp;lbrack;Export&amp;brack; Exportar um arquivo .sbsar com uma camada de Bordado resulta em um material cinza
* &amp;lbrack;Export&amp;brack; Exportar um material para um arquivo .sbs/sbsar pode gerar um material totalmente transparente
* O parâmetro Formato Normal do &amp;brack;Export&amp;brack; não é exposto corretamente em arquivos .sbs/.sbsar
* &amp;lbrack;Export&amp;rbrack; A exportação de Sbs/sbsar de uma pilha de camadas que faz referência a um arquivo .svg está quebrada
* &amp;lbrack;Exportar&amp;rbrack; a camada de transformação não é exportada corretamente / Enscape atualizado - Revit export preset
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Falha ao excluir uma camada contendo um parâmetro exposto
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Atualizar uma camada desatualizada na pilha de camadas pode levar a uma lista corrompida de parâmetros expostos
* &amp;lbrack;Parâmetros Expostos&amp;rbrack; Os parâmetros que não devem ser exportados são exportados mesmo assim
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Remover um filtro de mesclagem ao excluir uma camada não deixa de expor seus parâmetros
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Parâmetros de texto quebram as exportações .sbs/.sbsar
* &amp;lbrack;Camadas&amp;rbrack; Falha ao soltar uma pilha de camadas em outra pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Falha ao carregar um filtro
* &amp;lbrack;Camadas&amp;rbrack; Não é possível recarregar a imagem anterior ao redefinir o campo de Imagem
* &amp;lbrack;Camadas&amp;rbrack; Não é possível desfazer/refazer alterações na ferramenta transformar
* &amp;lbrack;Camadas&amp;rbrack; A camada de Carimbo fica parada após clicar em “Redefinir todas as configurações”
* &amp;lbrack;Camadas&amp;rbrack; Usar qualquer um dos botões de redefinição impede o desenho no campo de Imagem
* &amp;lbrack;Camadas&amp;rbrack; O botão Redefinir não limpa a máscara de desenho no campo Imagem
* &amp;lbrack;Camadas&amp;rbrack; O botão Redefinir no campo de Imagem não faz nada se o usuário tiver pintado algo
* &amp;lbrack;Camadas&amp;rbrack; O cache de renderização não funciona ao usar a ferramenta Pincel
* &amp;lbrack;Camadas&amp;rbrack; A camada excluída ainda pode aparecer no painel Propriedades
* &amp;lbrack;Camadas&amp;rbrack; O cálculo da camada pode parar ao alternar entre ativos de projeto
* &amp;lbrack;Projeto&amp;rbrack; Às vezes, o Sampler não consegue abrir um projeto do disco
* &amp;lbrack;Exibição 2D&amp;rbrack; A exibição 2D sempre retorna como padrão para Saída de material

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.4.0 Arancini

*(Lançado: 06 De setembro De 2022)*

**Adicionado:**

* &amp;preto;Parâmetros Expostos&amp;rbrack; Novo Painel de parâmetros expostos
* &amp;lbrack;Parâmetros expostos&amp;rbrack; O novo botão nos parâmetros passa o mouse para expor e não expor os parâmetros do painel Propriedades
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Novo menu de contexto de clique com o botão direito do mouse nos parâmetros para expor e não expor parâmetros do painel Propriedades
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Os parâmetros expostos são listados no Painel de parâmetros expostos
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Os pontos de cor e os discos de cor são adicionados em vários locais para identificar facilmente os parâmetros expostos
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Os rótulos dos parâmetros podem ser editados no Painel de parâmetros expostos
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Exibir um aviso para parâmetros não exportáveis
* &amp;lbrack;Parâmetros expostos&amp;rbrack; Exibir aviso se mover uma camada com parâmetros de mesclagem expostos em algum lugar onde eles se tornam ocultos
* &amp;preto;Parâmetros expostos&amp;rbrack; Os parâmetros expostos são exportados nos formatos SBS e SBSAR
* &amp;lbrack;Metadados&amp;rbrack; Suporte a modelos de metadados personalizados
* &amp;lbrack;Metadados&amp;rbrack; Novo modelo de metadados de propriedades físicas do CLO
* &amp;lbrack;Metadados&amp;rbrack; Adiciona ícones ao passar o mouse para adicionar/remover metadados personalizados
* &amp;lbrack;API Python&amp;rbrack; Nova API Python
* &amp;lbrack;API Python&amp;rbrack; API para a criação de ativos
* &amp;lbrack;API Python&amp;rbrack; API para gerenciamento de camadas
* API&amp;rbrack; Python API&amp;rbrack; para gerenciamento de Parâmetros
* API&amp;rbrack; Python API&amp;rbrack; para gerenciamento de projetos
* &amp;lbrack;Python API&amp;rbrack; Um plug-in pode ser ativado e desativado
* Documentação da API do &amp;Python&amp;rbrack; Python acessível no menu Ajuda
* &amp;lbrack;Scripting&amp;brack; seção Novos plug-ins e scripts no pop-up Preferências
* &amp;lbrack;Scripting&amp;brack; Crie e importe plug-ins para personalizar a interface do Sampler com seus próprios painéis
* &amp;brack;Scripting&amp;rbrack; Os plug-ins se tornam parte da interface do Sampler e podem ser encaixados e movidos como painéis padrão do Sampler
* &amp;lbrack;Scripting&amp;brack; Barra de botões dedicada para os plug-ins na barra de ferramentas direita do Sampler
* &amp;lbrack;Scripting&amp;rbrack; Cria e importa scripts para executar uma lista de tarefas fornecidas
* &amp;lbrack;Scripting&amp;brack; Inicia scripts Python através do menu Scripts
* &amp;lbrack;Scripting&amp;rbrack; Os plug-ins e scripts podem ser excluídos, reordenados e recarregados na janela Preferências
* &amp;lbrack;Scripting&amp;rbrack; Adicionado — run-script parâmetros da linha de comando
* &amp;lbrack;Logs&amp;rbrack; Novo painel de Logs
* &amp;lbrack;Logs&amp;rbrack; Ativar painel Logs na janela Preferências
* &amp;lbrack;Logs&amp;rbrack; Nova barra de ações para limpar, copiar/colar, exportar logs
* &amp;lbrack;Propriedades&amp;rbrack; Novo botão nos parâmetros passe o mouse para redefinir o valor do parâmetro
* &amp;lbrack;Propriedades&amp;rbrack; Novo menu de contexto acessado com o botão direito do mouse nos parâmetros para redefinir o valor do parâmetro
* &amp;brack;Content&amp;brack; A imagem para material (viabilizada por IA) agora funciona no MacOS
* &amp;lbrack;Engine&amp;rbrack; Atualiza mecanismo de Substance para v8.6.0

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; O aplicativo podia falhar ao sair quando uma geração de miniatura estava em andamento
* &amp;lbrack;Aplicativo&amp;rbrack; O aplicativo pode falhar ao usar &#39;Salvar como&#39; ao sair
* &amp;lbrack;O aplicativo&amp;rbrack; pode travar durante o desligamento no MacOS
* &amp;lbrack;Aplicativo&amp;rbrack; Salvar com a caixa de diálogo de cor aberta não salva suas alterações
* &amp;lbrack;Export&amp;brack; A convenção de nomenclatura de uso não está correta ao exportar
* &amp;lbrack;Camadas&amp;rbrack; Soltar um material sobre um filtro pode falhar
* &amp;lbrack;Camadas&amp;rbrack; Atualizar uma pilha de camadas desatualizada poderia atualizar pilhas de camadas não relacionadas
* &amp;lbrack;Metadados&amp;rbrack; Os campos vazios são exportados
* &amp;lbrack;Metadados&amp;rbrack; Quando há apenas um item de metadados, a interface do usuário permite que você tente reordená-lo
* &amp;lbrack;Projeto&amp;rbrack; A computação nunca termina após a duplicação de um material
* &amp;lbrack;Projeto&amp;rbrack; O ativo do projeto é duplicado após o salvamento inicial do projeto
* &amp;lbrack;Projeto&amp;rbrack; Cálculos desnecessários ao alternar ativo
* &amp;lbrack;Renderização&amp;rbrack; Algumas pilhas de camadas não são renderizadas corretamente após a exclusão de uma camada
* &amp;lbrack;Segurança&amp;rbrack; Corrigir CVE-2015-20107
* &amp;lbrack;UI&amp;rbrack; As saídas 2D podem ficar desfocadas dependendo do tamanho da janela
* &amp;lbrack;UI&amp;rbrack; A visualização do ativo pode permanecer aberta na parte superior quando o aplicativo perde o foco
* &amp;lbrack;UI&amp;rbrack; Os cantos arredondados da tela inicial têm um fundo quadrado opaco

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.3.2. Abobrinha

*(Lançado: 28 de junho de 2022)*

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir falha potencial ao abrir um projeto
* &amp;lbrack;Export&amp;rbrack; Reiniciar o Sampler interrompe a lista de predefinições de exportação personalizadas importadas
* &amp;lbrack;Interoperabilidade&amp;rbrack; Corrigir falha quando um material enviado do Designer é excluído e reenviado do Designer
* &amp;lbrack;Projeto&amp;rbrack; Impossível excluir o último material ou luz ambiente se for o último ativo no projeto
* &amp;lbrack;Projeto&amp;rbrack; Clicar com o botão direito do mouse em uma luz ambiente faz com que o asterisco “modificações não salvas” apareça

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.3.1. Abobrinha

*(Lançado em: 07 de junho de 2022)*

**Adicionado:**

* &amp;lbrack;Suporte nativo ao Apple Silicon (M1)
* &amp;lbrack;UI&amp;rbrack; Novo atalho, tecla “C”, para percorrer os canais no Visualização 2D
* &amp;preto;Ferramentas&amp;rbrack; Campo numérico para editar o valor da cor em tons de cinza na barra de ferramentas Pincel

**Corrigido:**

* &amp;lbrack;Ferramentas&amp;rbrack; Usar a ferramenta Pincel no Windows com uma escala de interface fracionada (150%) desloca os traçados
* &amp;lbrack;Desempenho&amp;rbrack; Melhorar o consumo de memória
* &amp;lbrack;Tamanho físico&amp;rbrack; as informações do Tamanho físico podem estar ausentes ao ativar o recurso
* &amp;lbrack;UI&amp;rbrack; A rolagem do mouse às vezes não funciona conforme o esperado ao pressionar a tecla Alt
* &amp;lbrack;O aplicativo&amp;rbrack; pode falhar ao abrir um projeto salvo
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao arrastar e soltar várias imagens e usar Importação de Textura na janela Modelo de criação de material
* &amp;lbrack;Aplicativo&amp;rbrack; Possível falha ao salvar um projeto contendo um filtro personalizado
* &amp;lbrack;Aplicativo&amp;rbrack; Às vezes, o estado da tecla Control é perdido ao alternar o aplicativo
* &amp;lbrack;Assets&amp;rbrack; Falha ao renomear uma pasta local

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.3.0 Abobrinha

*(Lançado: 17 de maio de 2022)*

**Adicionado:**

* &amp;lbrack;Content&amp;brack; Novo filtro de Preenchimento sensível ao conteúdo (Windows e Mac)
* &amp;lbrack;Content&amp;rbrack; O Preenchimento sensível ao conteúdo está funcionando em imagens, materiais PBR e iluminações do ambiente
* &amp;lbrack;Content&amp;brack; Adicionar o parâmetro “Preservar divisão em blocos gráficos” à Imagem para Material (Ativado por IA)
* &amp;lbrack;Content&amp;brack; O filtro Transformo de Perspectiva pode exibir uma grade entre seus quatro pontos
* &amp;lbrack;Interoperabilidade&amp;rbrack; Enviar materiais para o Adobe Substance 3D Stager
* &amp;lbrack;Ferramentas&amp;rbrack; Centralize a transformação pressionando Ctrl ao redimensionar a ferramenta Transformar ou Cortar
* &amp;lbrack;Ferramentas&amp;rbrack; Bloqueie a proporção para o quadrado pressionando Shift ao redimensionar a ferramenta Transformar ou Cortar
* &amp;lbrack;Ferramentas&amp;rbrack; o cursor do carimbo de Clonar oferece uma previsão do que será carimbado
* &amp;lbrack;Ferramentas&amp;rbrack; Visualize o conteúdo original no cursor Borracha ao usar o Carimbo
* &amp;lbrack;Tools&amp;brack; Ctrl+Clique cria um novo carimbo na camada Clonar Carimbo
* &amp;lbrack;Ferramentas&amp;rbrack; Carimbos de clonagem sucessivos agora são agrupados em uma única camada
* &amp;lbrack;Ferramentas&amp;rbrack; Pincel barra de ferramentas IU Renovar
* &amp;lbrack;Ferramentas&amp;rbrack; A posição da barra de ferramentas Pincel é persistente durante uma sessão
* &amp;lbrack;Ferramentas&amp;rbrack; Novas opções de divisão em blocos gráficos por eixo
* &amp;lbrack;Ferramentas&amp;rbrack; Ocultar/exibir a sobreposição sobre a Visualização 2D ao pintar
* &amp;lbrack;Ferramentas&amp;rbrack; Novo atalho, tecla “X”, para alternar entre Pincel e Borracha
* &amp;lbrack;Ferramentas&amp;rbrack; Novo atalho, “&amp;lbrack;” “&amp;rbrack;” para alterar o tamanho do pincel
* &amp;lbrack;Ferramentas&amp;rbrack; Novo atalho, tecla “E”, para alternar a Borracha
* &amp;lbrack;Exibição 2D&amp;rbrack; Novo modo de Projeção esférica ao criar luz ambiente
* A ferramenta Pincel do &amp;lbrack;Visualização 2D&amp;rbrack; é suportada com o modo de projeção esférica
* &amp;lbrack;A ferramenta de Posição do &amp;2D View&amp;rbrack; é suportada com o modo de projeção esférica
* &amp;lbrack;Visualização 2D; Desfazer/refazer é suportado com o modo de projeção esférica
* &amp;lbrack;Visualização 2D; Na Projeção esférica, defina a posição padrão para olhar para o centro do ambiente
* &amp;lbrack;Visualização 2D&amp;rbrack; Novo controle de exposição
* &amp;lbrack;UI&amp;rbrack; No painel Propriedades, o ajuste da imagem exibe a origem do conteúdo (imagem ou de uma camada)
* &amp;lbrack;UI&amp;rbrack; Melhoria no plano de fundo do menu suspenso de saídas de camada/material
* &amp;lbrack;UI&amp;rbrack; Nova posição das informações de resolução na Visualização 2D
* &amp;lbrack;UI&amp;rbrack; Nova dica de ferramenta com atalhos de controles de navegação de exibição 3D
* &amp;lbrack;UI&amp;rbrack; Nova dica de ferramenta com controles de pincel
* &amp;lbrack;UI&amp;rbrack; Nova dica de ferramenta com atalhos de controles de navegação de projeção
* &amp;preto;Filtros compostos&amp;rbrack; Os filtros compostos manipulam variações para trabalhar em imagens, materiais PBR e luzes ambiente
* &amp;preto;Filtros compostos&amp;rbrack; A ordem dos ajustes corresponde à ordem da lista de nós no filtro composto
* &amp;preto;Filtros compostos&amp;rbrack; Os ajustes de nós diferentes com o mesmo grupo serão mesclados em um único grupo no painel Propriedades
* &amp;lbrack;Aplicativo&amp;rbrack; Possui configurações de visualizador dedicadas por tipo de ativo

**Corrigido:**

* &amp;lbrack;O aplicativo&amp;rbrack; pode falhar ao alternar para a exibição 2D
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir um possível deadlock ou falha ao exportar várias vezes
* &amp;lbrack;Aplicativo&amp;rbrack; Tornar os valores padrão para canais consistentes com o Substance 3D Designer
* &amp;lbrack;Aplicativo&amp;rbrack; Carregar um projeto não aciona o recálculo do material
* &amp;lbrack;Aplicativo&amp;rbrack; Atualizou o URL para a documentação de importação de textura
* &amp;lbrack;Content&amp;brack; Ao usar um filtro composto, ele pede para ser atualizado quando não deveria, ao recarregar
* &amp;lbrack;Content&amp;brack; Os detalhes no mapa de height desaparecem ao usar a Mesclagem de opacidade
* &amp;lbrack;UI&amp;rbrack; Na caixa de diálogo Cor, é possível sair do intervalo usando os campos de texto do controle deslizante
* &amp;lbrack;UI&amp;rbrack; A lista de Uso tem uma barra de rolagem vertical inútil

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* &amp;lbrack;O widget de luz do Content&amp;brack; Shape não está funcionando no modo de projeção esférica
* &amp;lbrack;Interoperabilidade&amp;rbrack; O material com deslocamento enviado para o Stager perderá os controles do deslocamento

### 3.2.1 Iakitori

*(Lançado Em: 08 De março De 2022)*

**Adicionado:**

* &amp;lbrack;Export&amp;brack; Exportar metadados de dpi em arquivos de imagem
* &amp;lbrack;Tamanho físico&amp;rbrack; Mantém a proporção com texturas não quadradas ao editar dimensões físicas
* &amp;lbrack;Tamanho físico&amp;rbrack; os metadados do Tamanho físico são aplicados imediatamente quando o tamanho físico é alterado
* &amp;lbrack;UI&amp;rbrack; Ajusta o controle deslizante máximo da escala de Height para que possa influenciar qualquer tipo de material quando o Tamanho físico estiver ativado
* &amp;lbrack;UI&amp;rbrack; Novas dicas de ferramentas em filtros de pesquisa no Painel de ativos
* &amp;lbrack;UI&amp;rbrack; Use dicas de ferramentas para explicar quando os botões estão desativados no painel Ativos
* &amp;lbrack;Content&amp;brack; Atualização do filtro de contraste de brilho

**Corrigido:**

* &amp;lbrack;Visualização 2D&amp;rbrack; o botão de rotação de 90 graus nas ferramentas Cortar e Transformar não funciona como esperado
* &amp;lbrack;Visualização 2D&amp;rbrack; O widget Cortar às vezes fica ausente
* &amp;lbrack;Aplicativo&amp;rbrack; Limpar um parâmetro de imagem não reconecta a camada subjacente
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao sair após salvar um projeto
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao arrastar e soltar o material atual em uma coleção do painel Ativos
* &amp;lbrack;Aplicativo&amp;rbrack; Arrastar e soltar um ativo no visor pode travar
* &amp;lbrack;Content&amp;brack; A mesclagem normal tem um ajuste de semente aleatório
* O filtro de Snow do &amp;lbrack;Content&amp;brack; tem saída normal incorreta dependendo dos valores dos parâmetros neve fresca e derretida
* &amp;lbrack;Content&amp;brack; Filtro de assoalho: costuras inesperadas fixas
* &amp;lbrack;Content&amp;brack; Filtro de bordados: remover thread em mapa metálico
* &amp;lbrack;Content&amp;brack; filtro de blocos do Número inteiro: corrigir contagem de blocos x e y
* &amp;lbrack;Content&amp;rbrack; Filtro de parede de tijolos: saída normal e height para 16 bits
* &amp;lbrack;Export&amp;brack; O nome de arquivo padrão no pop-up de exportação não é o nome do material atual
* &amp;lbrack;Export&amp;brack; Exportar com proporção física com uma predefinição de exportação fornece dimensões incorretas
* &amp;lbrack;Export&amp;brack; Metálico está ausente na predefinição de exportação CLO
* &amp;lbrack;Export&amp;brack; Ao substituir uma predefinição personalizada de exportação, o nome para exibição não é atualizado
* &amp;lbrack;Camadas&amp;rbrack; Os canais personalizados da primeira camada inserida não são descobertos
* &amp;lbrack;Camadas&amp;rbrack; O material é reavaliado ao alterar ajustes de uma camada oculta
* &amp;lbrack;Dicas de ferramenta do Localization&amp;brack; não estão localizadas no painel Exportar
* &amp;lbrack;Tamanho físico&amp;rbrack; Desativar o Tamanho físico de um ativo não remove a escala física
* O valor da Escala de Height do &amp;lbrack;Tamanho físico&amp;rbrack; não pode ser definido fora dos limites do controle deslizante na primeira vez
* &amp;lbrack;Tamanho físico&amp;rbrack; Importar uma imagem sem tamanho físico impede a abertura do projeto
* O Tamanho físico do &amp;lbrack;Tamanho físico&amp;rbrack; está definido como zero por engano quando está ausente
* &amp;lbrack;Tamanho físico&amp;rbrack; O status da caixa de seleção da escala física do Tamanho físico não é atualizado quando exibido pela primeira vez
* &amp;lbrack;UI&amp;rbrack; Material de base &amp; Normal para Height não tem uma categoria
* &amp;lbrack;UI&amp;rbrack; O cursor às vezes fica invisível ao pintar uma imagem
* &amp;lbrack;UI&amp;rbrack; Desativar as opções “Copiar tudo” e “Recortar tudo” no menu de edição de um campo de texto se estiver vazio
* &amp;lbrack;UI&amp;rbrack; Os nomes dos filtros possuem caracteres incorretos
* O botão de bloqueio de Tamanho físico do &amp;lbrack;UI&amp;rbrack; não tem o estilo correto
* &amp;lbrack;UI&amp;rbrack; O botão Fechar na barra de pesquisa do Painel de Ativos não limpa a string de pesquisa

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.2.0 Yakitori

*(Lançado: 25 De Janeiro De 2022)*

**Adicionado:**

* &amp;lbrack;Tamanho físico&amp;rbrack; Novo painel Tamanho físico
* &amp;lbrack;Tamanho físico&amp;rbrack; Adicionar opções de Tamanho físico à janela Modelo de criação de material
* &amp;lbrack;Tamanho físico&amp;rbrack; Adicionar ferramenta de medida de Tamanho físico
* &amp;lbrack;Tamanho físico&amp;rbrack; Adicionar ferramenta de medição automática de Tamanho físico
* &amp;lbrack;Tamanho físico&amp;rbrack; Adicionar ferramenta de diagnóstico de Tamanho físico
* &amp;lbrack;Tamanho físico&amp;rbrack; Permitir a definição do valor z do Tamanho físico
* &amp;lbrack;Tamanho físico&amp;rbrack; Widget de lista suspensa para definir o nível de zoom no Visualização 2D
* &amp;lbrack;Tamanho físico&amp;rbrack; Nova opção “Exibir com proporção física” no nível do menu suspenso de zoom
* &amp;lbrack;Tamanho físico&amp;rbrack; Nova opção “Ajustar ao tamanho físico” no menu suspenso de nível de zoom
* &amp;lbrack;Tamanho físico&amp;rbrack; Exibir o Tamanho físico na exibição 2D
* &amp;lbrack;Tamanho físico&amp;rbrack; Exibir a Tamanho físico no visor 3D
* &amp;lbrack;Tamanho físico&amp;rbrack; Na caixa de diálogo de importação de imagem, mostrar profundidade de tamanho físico se houver um mapa de altura importado
* &amp;lbrack;Tamanho físico&amp;rbrack; Mostrar o Tamanho físico no menu contextual do ativo
* &amp;lbrack;Tamanho físico&amp;rbrack; Define a unidade de comprimento nas Preferências
* &amp;lbrack;Tamanho físico&amp;rbrack; Exportar texturas respeitando a proporção física
* &amp;lbrack;Metadados&amp;rbrack; Capacidade de adicionar metadados personalizados a um ativo criado pelo usuário
* &amp;lbrack;Exportar&amp;rbrack; Exportar metadados personalizados para arquivos .sbs(ar)
* &amp;lbrack;Export&amp;brack; Exportar metadados de descrição, categoria, autor e marcas para arquivos .sbs(ar)
* &amp;lbrack;Export&amp;brack; Exporta o Tamanho físico para arquivos .sbs(ar)
* &amp;lbrack;Export&amp;brack; Definir configuração de compactação do arquivo .sbsar
* &amp;lbrack;Export&amp;brack; Exporta a miniatura do ativo para arquivos .sbs(ar)
* &amp;lbrack;Export&amp;brack; Define o tipo de gráfico ao exportar um arquivo .sbs(ar)
* O &amp;lbrack;Application&amp;brack; Realtime Engine 2021 não está mais disponível
* &amp;lbrack;O aplicativo&amp;rbrack; Desfazer/Refazer agora suporta mudanças de controle deslizante Lado a lado (U, V) e escala de height
* &amp;lbrack;Renderização&amp;rbrack; Gerar cache de disco quando o ativo criado for salvo
* &amp;lbrack;Ativos&amp;rbrack; Use Ctrl+clique para ativar vários filtros de tipo de ativo no painel Recursos
* &amp;lbrack;UI&amp;rbrack; Capacidade de bloquear os controles deslizantes de divisão em blocos gráficos (U,V)
* &amp;lbrack;UI&amp;rbrack; Adicionar um menu contextual com “Copiar”, “Recortar”, “Colar”, “Copiar tudo” e “Recortar tudo” nos campos de texto
* &amp;lbrack;UI&amp;rbrack; Unidade de comprimento (metros, polegadas, parsecs, ...) suporte em rótulos e campos de texto
* &amp;lbrack;UI&amp;rbrack; O usuário pode definir a precisão decimal usada para exibir números
* &amp;lbrack;UI&amp;rbrack; Usar unidades nos pop-ups de medidas sempre que for relevante
* &amp;lbrack;Localização&amp;rbrack; O novo nome padrão do ativo agora está localizado
* &amp;lbrack;Content&amp;brack; Novo gerador de tecelagem
* &amp;lbrack;Content&amp;brack; Novo filtro de Comutador de Canal
* &amp;lbrack;Content&amp;brack; Todos os filtros relevantes agora estão cientes do Tamanho físico
* &amp;lbrack;Content&amp;brack; Novos ícones para Acabamento em madeira
* &amp;lbrack;Content&amp;rbrack; Todos os filtros agora são compatíveis com canais de Materiais Padrão de Adobe (ASM)
* Os Filtros do &amp;predefinição;Content&amp;brack; agora podem ter uma variação de “ambiente”

**Corrigido:**

* &amp;lbrack;Visualização 2D&amp;rbrack; O canal permanece na lista quando removido
* &amp;lbrack;Aplicativo&amp;rbrack; Não é possível duplicar um ativo carregado do explorador de arquivos do sistema operacional
* &amp;lbrack;O aplicativo &amp;rbrack; falha ao sair
* &amp;lbrack;Aplicativo&amp;rbrack; Falha às vezes ao clicar em “Ativos iniciais” no painel Ativos
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao excluir um material
* &amp;lbrack;Application&amp;brack; A variável de ambiente “SUBSTANCE_DISABLE_SPECIFIC_FEATURES” ainda está ativa quando definida como “0” ou “”.
* &amp;lbrack;Aplicativo&amp;rbrack; Congela ao salvar um projeto com vários materiais
* &amp;lbrack;Aplicativo&amp;rbrack; Importar uma imagem pode levar a um travamento
* &amp;lbrack;Application&amp;brack; Alguns ativos iniciais estão ausentes na primeira inicialização
* &amp;lbrack;Export&amp;brack; Exportar um ativo às vezes leva a um travamento
* &amp;lbrack;Camadas&amp;rbrack; Não é possível importar imagens quando o painel de camadas está fechado ou invisível
* &amp;lbrack;Camadas&amp;rbrack; Alterar o idioma faz com que o ativo atual seja recalculado
* &amp;lbrack;Camadas&amp;rbrack; Alterar o uso de uma imagem importada não atualiza qual variação de filtro usar
* &amp;lbrack;Camadas&amp;rbrack; A Imagem para Material (AI) às vezes não é calculada ao ajustar as camadas abaixo dela
* &amp;lbrack;Camadas&amp;rbrack; Imagem para Material (AI) às vezes recalcula quando não é necessário
* &amp;lbrack;Camadas&amp;rbrack; Nenhuma atualização é sugerida quando um filtro personalizado é atualizado no disco
* &amp;lbrack;Camadas&amp;rbrack; O canal Normal às vezes tem o formato de pixel incorreto
* &amp;lbrack;Camadas&amp;rbrack; Algumas camadas ainda são computadas mesmo quando não visíveis
* &amp;lbrack;Camadas&amp;rbrack; As ferramentas de exibição 2D podem ser interrompidas ao alternar a visibilidade de uma camada
* &amp;lbrack;Camadas&amp;rbrack; A interface congela ao usar a Imagem para material (AI)
* &amp;lbrack;Camadas&amp;rbrack; Alternar a visibilidade da camada de filtro de Transformo interrompe a ferramenta de Visualização 2D e pode levar a um travamento
* &amp;lbrack;Camadas&amp;rbrack; Muitos recálculos ao remover uma camada da pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Quando um filtro composto contém uma entrada/saída incomum ou personalizada, o Sampler não o calcula
* &amp;lbrack;Desempenho&amp;rbrack; O painel Ativos é lento ao abrir
* &amp;lbrack;Performance&amp;rbrack; Evitar alguns recálculos desnecessários da pilha de camadas
* &amp;lbrack;Desempenho&amp;rbrack; Carregar ativos do projeto leva muito tempo
* &amp;lbrack;Performance&amp;rbrack; O cache de renderização em disco não pode ser usado
* &amp;lbrack;Desempenho&amp;rbrack; Alternar entre camadas é lento
* &amp;lbrack;Desempenho&amp;rbrack; Ajustar um material ou filtro é lento
* &amp;lbrack;Projeto&amp;rbrack; Salvar um projeto ao sair pode levar a um travamento
* &amp;lbrack;Renderizando&amp;rbrack; Remover uma imagem pode remover todas as saídas
* &amp;lbrack;Renderização&amp;rbrack; O tempo de renderização exibido no visor está incorreto ao ajustar
* &amp;lbrack;UI&amp;rbrack; Não é possível rolar verticalmente no pop-up de exportação quando necessário
* &amp;lbrack;UI&amp;rbrack; É possível abrir o pop-up de exportação quando não há nada para exportar
* &amp;lbrack;UI&amp;rbrack; Alguns pop-ups não rolam se seu conteúdo transbordar
* &amp;lbrack;UI&amp;rbrack; Os campos de texto não são selecionados ao clicar neles ou ao abrir um menu
* &amp;lbrack;UI&amp;rbrack; O nome do modo de mesclagem no painel de propriedades às vezes não está correto
* &amp;lbrack;UI&amp;rbrack; A opção Salvar no menu Arquivo às vezes fica esmaecida
* &amp;lbrack;UI&amp;rbrack; O campo de texto não desaparece após renomear dois materiais
* &amp;lbrack;UI&amp;rbrack; Erro de ortografia no pop-up de preferência

**Problemas Conhecidos:**

* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.1.2 Xocoatl

*(Lançado: 14 De dezembro De 2021)*

**Corrigido:**

* &amp;lbrack;Interoperabilidade&amp;rbrack; Abrir arquivo .sbsar com o Substance 3D Sampler a partir do Bridge pode falhar no Windows
* &amp;lbrack;Camadas&amp;rbrack; Se você mover a única camada abaixo dela, o desempenho irá falhar
* &amp;lbrack;UI&amp;rbrack; O botão de configurações do canal desaparece ao alterar o idioma
* &amp;lbrack;UI&amp;rbrack; O nome do material no painel Propriedades desaparece após salvar o projeto
* &amp;lbrack;Assets&amp;rbrack; Clicar em “Todas as bibliotecas” pode levar a uma falha

**Problemas Conhecidos:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Computação pesada pode travar o aplicativo
* &amp;lbrack;O Mecanismo em Tempo Real 2021&amp;rbrack; O Mecanismo em Tempo Real 2021 falhará em uma máquina Windows com a CPU AMD e a GPU Nvidia instaladas
* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.1.1 Xocoatl

*(Lançado: 24 De novembro De 2021)*

**Adicionado:**

* &amp;lbrack;Interoperabilidade&amp;rbrack; Enviar ativos (SBS ou SBSAR) para o Substance 3D Designer
* &amp;lbrack;Interoperabilidade&amp;rbrack; Defina nas preferências o formato padrão para interoperabilidade com o Substance 3D Designer
* &amp;lbrack;Interoperabilidade&amp;rbrack; Receber vários ativos do Adobe Bridge
* &amp;lbrack;UI&amp;rbrack; Novo widget de Distribuição Aleatória
* &amp;lbrack;UI&amp;rbrack; Atualização do menu de contexto
* &amp;lbrack;Ativos&amp;rbrack; Arraste e solte imagens do painel Ativos para o painel Propriedades
* &amp;lbrack;Projeto&amp;rbrack; Os nomes dos ativos são limpos para evitar alguns caracteres específicos
* &amp;brack;Marca&amp;rbrack; Atualizar ícone do arquivo para arquivos SBSAR
* &amp;lbrack;Engine&amp;rbrack; Atualização Substance Engine versão 8.3.0

**Corrigido:**

* &amp;lbrack;Content&amp;brack; Cortar - Preservar proporção ao cortar imagens não quadradas
* &amp;lbrack;Transformo do Content&amp;brack; - A transformação horizontal não é invertida ao usar o widget
* &amp;lbrack;Content&amp;brack; Gravel - corrigir pintura de máscara personalizada em todos os canais
* &amp;lbrack;Content&amp;brack; Ladrilhos do piso - corrigir problemas com divisão em blocos gráficos e repetição de padrão
* &amp;lbrack;Assets&amp;rbrack; opção Gray out Adobe Bridge se não estiver instalada
* &amp;preto;Seletor de cores&amp;rbrack; A tecla Escape fecha o Seletor de cores
* &amp;lbrack;Renderização&amp;rbrack; Corrigir a Escala de Distância de Dispersão ao usar entrada em tons de cinza
* &amp;lbrack;Share&amp;brack; As opções Enviar para estão disponíveis somente com licenças Adobe
* &amp;lbrack;Projeto&amp;rbrack; Corrigir um problema de desempenho de memória

**Problemas Conhecidos:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Computação pesada pode travar o aplicativo
* &amp;lbrack;O Mecanismo em Tempo Real 2021&amp;rbrack; O Mecanismo em Tempo Real 2021 falhará em uma máquina Windows com a CPU AMD e a GPU Nvidia instaladas
* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.1.0 Xocoatl

*(Lançado: 28 De setembro De 2021)*

**Adicionado:**

* &amp;preto;Seletor de cores&amp;rbrack; Nova interface do Seletor de cores
* &amp;preto;Seletor de cores&amp;rbrack; Visualizar as cores atuais e anteriores lado a lado
* &amp;preto;Seletor de cores&amp;rbrack; Insira sua cor em Hexadecimal
* &amp;preto;Seletor de cores&amp;rbrack; Novo conta-gotas com visualização de cores
* &amp;preto;Seletor de cores&amp;rbrack; O conta-gotas pode selecionar uma cor fora do Sampler
* &amp;lbrack;Seletor de cores&amp;rbrack; Ajuste sua cor em espaços de cores RGB ou HSV
* &amp;preto;Seletor de cores&amp;rbrack; Salvar e gerenciar amostras
* &amp;lbrack;Interoperabilidade&amp;rbrack; Edite imagens no Illustrator a partir da camada de importação de imagem ou dos parâmetros de imagem
* &amp;lbrack;Interoperabilidade&amp;rbrack; Edite imagens no Photoshop a partir da camada de importação de imagem ou dos parâmetros de imagem
* &amp;lbrack;Widget&amp;rbrack; Novo widget de corte
* &amp;lbrack;Widget&amp;rbrack; Pressione Enter para validar seu corte
* &amp;lbrack;Widget&amp;rbrack; O widget Cortar lê o tamanho da imagem para se ajustar ao widget e manter a proporção ao redimensionar
* &amp;lbrack;UI&amp;rbrack; Nova interface deslizante de escala de cinza
* &amp;lbrack;Aplicativo&amp;rbrack; Adicionar seleção de formato normal nas preferências
* &amp;lbrack;Aplicativo&amp;rbrack; O formato normal nas camadas de importação de imagem segue o formato normal padrão definido nas preferências
* &amp;lbrack;Aplicativo&amp;rbrack; Na exibição 2D, o normal é exibido seguindo o formato normal definido nas preferências
* &amp;lbrack;Aplicativo&amp;rbrack; O normal é exportado no formato normal definido nas preferências
* &amp;lbrack;Export&amp;brack; Adicionar parâmetro de formato normal às exportações de arquivos SBS e SBSAR
* &amp;preto;Exportar&amp;rbrack; Adicionar configurações de sombreador às exportações de arquivos SBS e SBSAR
* &amp;lbrack;Export&amp;brack; Define a resolução padrão dos gráficos SBS exportados
* &amp;lbrack;Filtros Compostos&amp;rbrack; Encapsulamento filtros SSA com 7z
* &amp;preto;Filtros compostos&amp;rbrack; Adicionar metadados de categoria em filtros compostos
* &amp;preto;Filtros compostos&amp;rbrack; Os filtros compostos podem ter uma miniatura incorporada
* &amp;lbrack;Filtros compostos&amp;rbrack; Extensão de Filtros compostos adicionada (.ssafilter) à caixa de diálogo Obter arquivo de conteúdo
* &amp;preto;Filtros compostos&amp;rbrack; Importar filtros compostos (.ssafilter) no painel Ativos
* &amp;lbrack;Mecanismo&amp;rbrack; Atualizar mecanismo do substance para v8.2.0

**Corrigido:**

* &amp;lbrack;Aplicativo&amp;rbrack; As pastas locais conectadas podem travar
* &amp;lbrack;O aplicativo &amp;rbrack; falha ao sair
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao iniciar duas instâncias do Sampler
* &amp;lbrack;Content&amp;brack; O filtro de corte tem um ajuste de semente aleatório
* &amp;lbrack;Content&amp;rbrack; Alguns materiais de Substance às vezes não são atualizados
* &amp;lbrack;Export&amp;brack; Falha ao exportar com uma predefinição personalizada recém-adicionada
* &amp;lbrack;Export&amp;brack; O tamanho estimado do pacote está ausente no pop-up de exportação
* &amp;lbrack;Export&amp;brack; Corrigir vazamento de memória ao exportar arquivos SBS e SBSAR
* &amp;preto;Filtros compostos&amp;rbrack; Os filtros compostos podem ter entradas duplicadas
* &amp;preto;Filtros compostos&amp;rbrack; Falha se um filtro tiver referências não atendidas
* &amp;preto;Filtros compostos&amp;rbrack; Falha ao reordenar uma pilha de camadas com um filtro composto
* &amp;preto;Filtros compostos&amp;rbrack; A renderização às vezes trava
* &amp;preto;Importação de imagem&amp;rbrack; Importar uma imagem dispara várias renderizações
* &amp;preto;Camadas &amp;rbrack; Falha ao desfazer/refazer
* &amp;lbrack;Camadas&amp;rbrack; Falha ao adicionar um Material de base
* &amp;lbrack;Camadas&amp;rbrack; Falha ao usar uma imagem inválida como iluminação do ambiente
* &amp;lbrack;Camadas&amp;rbrack; Corrigir importação duplicada ao inserir um filtro com vários gráficos
* &amp;lbrack;Camadas&amp;rbrack; A reordenação de camadas nem sempre funciona
* &amp;lbrack;Projeto&amp;rbrack; Falha ao carregar um arquivo de projeto incompleto
* &amp;lbrack;Projeto&amp;rbrack; Falha ao abrir um projeto corrompido
* &amp;lbrack;Projeto&amp;rbrack; Alguns ativos podem desaparecer de um projeto
* &amp;lbrack;Propriedades&amp;rbrack; Corrigir predefinições de filtro ausentes
* Os parâmetros de Ângulo do &amp;lbrack;UI&amp;rbrack; não podem ser definidos
* &amp;lbrack;UI&amp;rbrack; Filtros exibição de metadados no painel Ativos
* &amp;lbrack;UI&amp;rbrack; Agrupar por categoria oculta filtros
* &amp;lbrack;UI&amp;rbrack; Problema de rolagem no Painel de ativos
* &amp;lbrack;UI&amp;rbrack; O painel de exportação agora tem uma barra de rolagem
* &amp;lbrack;UI&amp;rbrack; A miniatura não é exibida para alguns formatos de imagem no seletor de imagens

**Problemas Conhecidos:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Computação pesada pode travar o aplicativo
* &amp;lbrack;O Mecanismo em Tempo Real 2021&amp;rbrack; O Mecanismo em Tempo Real 2021 falhará em uma máquina Windows com a CPU AMD e a GPU Nvidia instaladas
* &amp;lbrack;Seletor de Cores&amp;rbrack; Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar

### 3.0.1 Waffle

*(Lançado: 27 de julho de 2021)*

**Adicionado:**

* &amp;lbrack;Pincel&amp;rbrack; Ativar cores na ferramenta pincel se a entrada da imagem suportá-lo
* &amp;lbrack;Pincel&amp;rbrack; manter a tecla Shift pressionada na ferramenta pincel desenha linhas retas
* &amp;lbrack;Pincel&amp;rbrack; Mostra uma visualização de linha ao manter a tecla Shift pressionada na ferramenta Pincel
* A ferramenta Pincel &amp;preto;Pincel&amp;rbrack; agora suporta desfazer e refazer
* &amp;lbrack;Visualização 2D&amp;rbrack; A cor padrão de entrada da imagem é usada ao pintar
* &amp;lbrack;Camadas&amp;rbrack; Leitura do valor padrão de entrada de Substance em arquivos SBSAR
* &amp;lbrack;Renderização&amp;rbrack; Permitir combinar height com normal
* &amp;lbrack;Renderização&amp;rbrack; Suporte à dispersão de subsuperfícies (não disponível no MacOS)
* &amp;lbrack;Ativos&amp;rbrack; Use o tipo de gráfico SBSAR para determinar o tipo de ativo
* &amp;lbrack;Assets&amp;rbrack; Melhor desempenho para pesquisa e descoberta de ativos no painel Ativos
* &amp;Brack;Ativos&amp;rbrack; Adicionada a entrada “Todas as bibliotecas” no painel Ativos, que exibe todos os ativos de todas as suas bibliotecas
* &amp;lbrack;Ativos&amp;rbrack; Agora o usuário pode optar por agrupar ativos por categoria ou tipo
* &amp;lbrack;Import&amp;brack; Detectar automaticamente texturas de anisotropia, capa, brilho e specular edge color na importação
* &amp;lbrack;UI&amp;rbrack; Substitui o título do painel com cabeçalho por um ícone
* &amp;lbrack;UI&amp;rbrack; Atualização do estilo de campos de texto
* &amp;lbrack;UI&amp;rbrack; Novo texto de descrição na janela de Criação do Modelo de Luz do Ambiente
* &amp;preto;Aplicativo&amp;rbrack; Exportar ativos com a resolução atual ao enviar para um aplicativo externo
* &amp;lbrack;A resolução padrão do material agora é 2048\*2048 (1024\*1024 no macos)
* &amp;lbrack;Content&amp;brack; Novos padrões no filtro Ladrilhos
* &amp;lbrack;Content&amp;brack; Novo modo de Cor Dupla no filtro Substituição de cor

**Corrigido:**

* &amp;lbrack;Visualização 2D&amp;rbrack; O primeiro traçado na ferramenta pincel às vezes é quebrado
* &amp;lbrack;Visualização 2D&amp;rbrack; Recursos livres quando a ferramenta pincel não está visível
* &amp;lbrack;Exibição 2D&amp;rbrack; Usar o cursor de redimensionamento direito no widget de transformação
* &amp;lbrack;Visualização 2D&amp;rbrack; Os widgets não são exibidos se o usuário já tiver feito panorâmica na visualização 2D antes
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao abrir um projeto com fluxo de trabalho quebrado
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir o desligamento do aplicativo para evitar inundar o log com erros inúteis
* &amp;lbrack;Aplicativo&amp;rbrack; Refazer, excluir e salvar atalhos de teclado não funcionam em alguns sistemas operacionais
* &amp;lbrack;Aplicativo&amp;rbrack; Desfazer/refazer alteração do uso da imagem na camada de importação está danificado
* &amp;lbrack;Exportar&amp;brack; A cor de emissão das imagens exportadas possui um nome incorreto
* &amp;lbrack;Export&amp;brack; O ambiente é de 8 bits ao usar a exportação SBSAR
* &amp;lbrack;Export&amp;brack; Remove espaços extras em nomes de arquivos de imagem exportados
* &amp;preset;Export&amp;brack; A substituição ou exclusão de uma predefinição de exportação personalizada trava
* &amp;lbrack;Camadas&amp;rbrack; Evitar falha quando houver uma incompatibilidade de contagem de entrada
* &amp;lbrack;Camadas&amp;rbrack; Falha ao inserir uma camada de Material de base
* &amp;lbrack;Camadas&amp;rbrack; A contagem de entrada do filtro está limitada ao valor padrão
* &amp;lbrack;Camadas&amp;rbrack; Refazer altera erroneamente o tipo de Combinar para mesclagem de Height
* &amp;lbrack;Camadas&amp;rbrack; Remover zona de destino acima dos cabeçalhos de entrada
* &amp;preto;Camadas&amp;rbrack; As camadas são inseridas no local errado ao redor dos cabeçalhos de entrada
* &amp;lbrack;Camadas&amp;rbrack; O botão Redefinir todas as configurações não redefine os valores dos widgets suspensos
* &amp;lbrack;Camadas&amp;rbrack; Desfazer/refazer ao alterar uma imagem na camada de importação de imagem marca o projeto como modificado e assim para salvar
* &amp;lbrack;Camadas&amp;rbrack; Os usos podem ser interrompidos pela mesclagem de camadas
* &amp;lbrack;Projeto&amp;rbrack; Falha ao carregar um projeto legado com pasta de dependências ausentes
* &amp;lbrack;Projeto&amp;rbrack; Falha ao usar Desfazer/Refazer após salvar
* &amp;lbrack;Projeto&amp;rbrack; Abrir um arquivo SBSAR contendo uma luz ambiente cria um ativo material
* &amp;lbrack;Projeto&amp;rbrack; Renomear um material pode acionar uma geração de miniatura
* &amp;lbrack;Projeto&amp;rbrack; Salvar após renomear um material marca o projeto como não modificado
* &amp;lbrack;Project&amp;brack; Algumas alterações após renomear um material não são salvas
* &amp;lbrack;Renderização&amp;rbrack; Pontos brilhantes são visíveis no ambiente com o mecanismo em tempo real 2020
* &amp;lbrack;Renderização&amp;rbrack; Falha ao redimensionar usando o Mecanismo em tempo real 2021
* &amp;lbrack;Renderização&amp;rbrack; Recalcular sombras na alteração do nível de height
* &amp;lbrack;Ativos&amp;rbrack; As pastas conectadas param de indexar novos ativos ao adicionar um arquivo inválido
* &amp;lbrack;Assets&amp;rbrack; Falha ao conectar uma pasta local com muitos materiais
* &amp;lbrack;UI&amp;rbrack; botões de visualização 2D/3D sem dicas de ferramentas
* &amp;lbrack;UI&amp;rbrack; Todos os ativos no painel Ativos são destacados na inicialização
* O &amp;lbrack;UI&amp;rbrack; Trilhas às vezes desaparece no painel Ativos ao importar materiais
* &amp;lbrack;UI&amp;rbrack; A alteração do idioma não afeta o painel Projeto
* &amp;lbrack;UI&amp;rbrack; O painel de Configurações do Canal mostra informações de fluxo de trabalho herdadas
* &amp;lbrack;UI&amp;rbrack; Alinha corretamente o texto “Nenhuma configuração para este item” para os filtros sem ajustes no painel de propriedades
* &amp;lbrack;UI&amp;rbrack; Os elementos estão desalinhados na tela de boas-vindas e no pop-up de preferências
* &amp;lbrack;UI&amp;rbrack; A largura dos títulos do painel está incorreta
* &amp;lbrack;UI&amp;rbrack; A rolagem às vezes é interrompida no painel Propriedades
* &amp;lbrack;UI&amp;rbrack; A tela inicial possui uma proporção incorreta e está desfocada
* &amp;lbrack;UI&amp;rbrack; O modo de tela cheia não é de tela cheia
* &amp;lbrack;UI&amp;rbrack; Os painéis desencaixados estão sempre na parte superior, mesmo quando o aplicativo não estiver ativo no MacOS
* &amp;lbrack;UI&amp;rbrack; Atualizar imagem do banner da tela de boas-vindas
* &amp;lbrack;Content&amp;rbrack; O filtro de divisão em blocos gráficos não processa o canal de oclusão de ambiente
* &amp;lbrack;Content&amp;brack; Quilt Stitch problema com a seleção de costura de montagem e padrão de diamante
* &amp;lbrack;Content&amp;rbrack; O filtro Entalhe funciona em 256px por 256px
* &amp;lbrack;Content&amp;rbrack; Corrigir problema de divisão em blocos gráficos com os blocos de piso quando o deslocamento for maior que 0

**Problemas Conhecidos:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Computação pesada, falha o aplicativo
* &amp;lbrack;O Mecanismo em Tempo Real 2021&amp;rbrack; O Mecanismo em Tempo Real 2021 falhará na máquina Windows com a CPU AMD e a GPU Nvidia

### 3.0.0 Waffle

*(Lançado: 23 de junho de 2021)*

**Adicionado:**

* &amp;lbrack;Branding&amp;rbrack; Substance Alchemist se torna Adobe Substance 3D Sampler
* &amp;brack;Marca&amp;rbrack; Ícones de Novo aplicativo
* &amp;lbrack;UI&amp;rbrack; Nova Experiência do Usuário e Interface do Usuário
* &amp;lbrack;UI&amp;rbrack; Nova Tela de Apresentação
* &amp;lbrack;UI&amp;rbrack; Os painéis são desencaixáveis e encaixáveis na interface
* &amp;lbrack;UI&amp;rbrack; Encaixar até 3 painéis na mesma coluna
* &amp;lbrack;UI&amp;rbrack; Encaixar até 3 painéis no mesmo painel (Tabulações)
* &amp;lbrack;UI&amp;rbrack; Desencaixar painéis para criar uma janela separada na mesma tela ou em uma tela diferente
* &amp;lbrack;UI&amp;rbrack; Painéis fechados pop-over ao clicar em seus ícones
* &amp;lbrack;UI&amp;rbrack; Reorganize as barras esquerda e direita movendo os ícones dos painéis
* &amp;lbrack;UI&amp;rbrack; Nova barra de ferramentas para acessar diretamente filtros específicos (Cortar, Transformar, Transformação de perspectiva, Carimbo)
* &amp;lbrack;UI&amp;rbrack; Novo botão “Obter conteúdo” na barra esquerda
* &amp;lbrack;UI&amp;rbrack; Importe arquivos diretamente em seus ativos com o botão Obter conteúdo
* &amp;lbrack;UI&amp;rbrack; Importe arquivos diretamente para suas Camadas com o botão Obter Conteúdo
* &amp;lbrack;UI&amp;rbrack; Acesse diretamente o site do Adobe Substance 3D Assets com o botão Obter Conteúdo
* O widget de resolução do &amp;lbrack;UI&amp;rbrack; agora pode ser acessado diretamente no visor
* &amp;lbrack;UI&amp;rbrack; Todos os elementos da interface agora são carregados dinamicamente
* &amp;lbrack;UI&amp;rbrack; Atalho - Use “2” para alternar a visibilidade da exibição 2D
* &amp;lbrack;UI&amp;rbrack; Atalho - Use “3” para alternar a visibilidade da visualização 3D
* &amp;Preenchimento;Tela de boas-vindas&amp;Preenchimento; Crie um projeto com um clique usando o botão Novo
* &amp;preto;Tela de boas-vindas&amp;rbrack; Novo banner de arte
* &amp;lbrack;Projeto&amp;rbrack; Todos os projetos agora estão associados a um arquivo exclusivo
* &amp;lbrack;Projeto&amp;rbrack; Nova extensão de arquivo de projeto .ssa
* &amp;lbrack;Projeto&amp;rbrack; Salvar como um projeto solicitará que você selecione onde salvar seu projeto
* &amp;lbrack;Projeto&amp;rbrack; Ao fechar o Sampler, você será solicitado a salvar o projeto, caso ele não tenha sido salvo
* &amp;lbrack;Projeto&amp;rbrack; Fechar o Sampler solicitará que você salve seu projeto se houver modificações desde o último salvamento
* &amp;lbrack;Projeto&amp;rbrack; O nome do seu projeto é exibido acima do visor
* &amp;lbrack;Projeto&amp;rbrack; O nome do projeto está em itálico com uma estrela se não for salvo ou se contiver modificações desde o último salvamento
* &amp;lbrack;Projeto&amp;rbrack; Abre um arquivo de projeto .ssa diretamente do explorador do SO
* &amp;lbrack;Projeto&amp;rbrack; Abrir um .sbsar a partir do explorador do sistema operacional iniciará o Sampler com um novo projeto com este arquivo .sbsar pronto para uso
* &amp;lbrack;Projeto&amp;rbrack; Abra um .alch (arquivo de Substance Alchemist legado) do explorador do sistema operacional
* &amp;lbrack;Painel do projeto&amp;rbrack; Novo painel que conterá todos os ativos criados em um projeto
* &amp;preto;Painel do projeto&amp;rbrack; Criar um ativo (material ou luz ambiente) usando o ícone +
* &amp;preto;Painel do projeto&amp;rbrack; Clicar com o botão direito do mouse no ativo abre um menu de contexto
* &amp;lbrack;Painel do Projeto&amp;rbrack; No menu de contexto acessado ao clicar com o botão direito do mouse, é possível excluir um ativo
* &amp;lbrack;Painel do projeto&amp;rbrack; No menu de contexto do botão direito do mouse, você pode duplicar um ativo
* &amp;lbrack;Painel do projeto&amp;rbrack; No menu de contexto do botão direito do mouse, você pode renomear um ativo
* &amp;lbrack;Painel do projeto&amp;rbrack; Alternar entre ativos não perderá as modificações
* &amp;lbrack;Resolução&amp;rbrack; Agora você pode definir uma resolução não quadrada para todos os seus ativos
* &amp;lbrack;Resolution&amp;rbrack; O valor de resolução é salvo por um ativo dentro de um projeto
* &amp;preto;Luz ambiente&amp;rbrack; Criar luz ambiente no Substance 3D Sampler
* &amp;preto;Luz ambiente&amp;rbrack; Ao criar uma luz ambiente, arrastar e soltar imagens exibirá a janela Modelo de criação de luz ambiente
* &amp;preto;Luz do ambiente&amp;rbrack; No Modelo de criação da Luz do ambiente, selecione Importação do ambiente para atribuir sua imagem ao ambiente na visualização 3D
* &amp;lbrack;Luz do ambiente&amp;rbrack; No Modelo de criação da luz ambiente, selecione Mesclar HDR para criar uma luz ambiente de várias imagens de 360 graus com diferentes exposições
* &amp;lbrack;Luz do ambiente&amp;rbrack; No Modelo de criação da Luz do ambiente, selecione “Usar como bitmap” para editar a(s) imagem(ns) antes de criar uma luz do ambiente
* &amp;preto;Luz do ambiente&amp;rbrack; Atribui o uso do ambiente na camada de importação de imagem para atribuir diretamente a imagem ao ambiente na visualização 3D
* &amp;preto;Luz do ambiente&amp;rbrack; Na exibição 2D do canal de ambiente, há uma correção de cores automática para que a renderização apareça da mesma forma que na exibição 3D
* &amp;preto;Luz do ambiente&amp;rbrack; Novo conteúdo dedicado para criação de luz ambiente
* &amp;preto;Painel de ativos&amp;rbrack; Os painéis Recursos e Filtros são mesclados em um novo painel Ativos
* &amp;lbrack;Painel Ativos&amp;rbrack; O painel Ativos agora suporta os seguintes tipos de ativos: materiais, filtros e imagens
* &amp;lbrack;Painel de ativos&amp;rbrack; Todos os ativos iniciais podem ser acessados na seção Ativos iniciais
* &amp;lbrack;Painel Ativos&amp;rbrack; A seção Ativos iniciais é somente leitura
* &amp;lbrack;Painel Ativos&amp;rbrack; Nova seção “Seus ativos”
* &amp;lbrack;Painel de Ativos&amp;rbrack; A seção “Seus ativos” é o local onde você pode importar todos os seus recursos
* &amp;lbrack;Painel de ativos&amp;rbrack; Todos os ativos em “Seus ativos” são adicionados a uma pasta específica em seus Documentos
* &amp;preto;Painel de ativos&amp;rbrack; Conecte as pastas locais no painel Ativos para adicionar novas seções
* &amp;lbrack;Painel de Ativos&amp;rbrack; A pesquisa pesquisará na pasta atual e em suas subpastas
* &amp;preto;Painel de ativos&amp;rbrack; Navegar entre pastas e subpastas com navegação estrutural
* &amp;lbrack;Painel de Ativos&amp;rbrack; Filtrar a pasta atual por material, filtro ou imagem
* &amp;preto;Painel de ativos&amp;rbrack; Combine vários filtros para obter apenas materiais e imagens
* &amp;lbrack;Painel de Ativos&amp;rbrack; Altera a exibição alternando entre uma grade ou uma lista
* &amp;preto;Painel de ativos&amp;rbrack; Os filtros são representados com seus ícones
* &amp;lbrack;Painel de Ativos&amp;rbrack; As imagens são representadas com sua visualização
* &amp;lbrack;Painel de ativos&amp;rbrack; O aumento da largura alterará o layout do painel com uma exibição específica para navegar entre as pastas
* &amp;lbrack;Painel Ativos&amp;rbrack; Em seções não somente leitura, exclua um ativo arrastando-o e soltando-o no ícone de compartimento
* &amp;lbrack;Painel Ativos&amp;rbrack; Clicar com o botão direito do mouse no ativo abre um menu de contexto
* &amp;lbrack;Painel de ativos&amp;rbrack; No menu de contexto do botão direito do mouse, acesse os metadados do ativo (nome, categoria, local)
* &amp;lbrack;Painel de ativos&amp;rbrack; No menu de contexto do botão direito do mouse, exclua o ativo (disponível somente em seções não somente leitura)
* &amp;lbrack;Painel de ativos&amp;rbrack; No menu de contexto do botão direito do mouse, procure seu ativo no Adobe Bridge
* &amp;lbrack;Painel de Camadas&amp;rbrack; Novo ícone para adicionar diretamente uma material de base sobre as camadas
* &amp;preto;Painel de camadas&amp;rbrack; Atalho - Shift + B adicionará um material de base sobre as camadas
* &amp;preto;Painel de camadas&amp;rbrack; As camadas agora têm uma visualização em miniatura (miniatura do material, ícone do filtro ou visualização da imagem)
* &amp;lbrack;Painel Propriedades&amp;rbrack; Novo design do título do painel Propriedades com o nome e a miniatura do ativo
* &amp;lbrack;Painel de Propriedades&amp;rbrack; As camadas de filtro agora suportam predefinições
* &amp;lbrack;Painel de Propriedades&amp;rbrack; Na Camada de Importação de Imagem, clique com o botão direito do mouse na visualização da imagem para editar a imagem no Photoshop
* &amp;lbrack;Adobe Bridge&amp;rbrack; Procure seu ativo no Adobe Bridge e iniciará o Bridge no local do ativo
* &amp;lbrack;O Adobe Photoshop&amp;rbrack; Editar no Adobe Photoshop abrirá a imagem no Photoshop pronta para ser editada
* &amp;lbrack;Adobe Photoshop&amp;rbrack; A cada salvamento no Adobe Photoshop, a imagem editada será recarregada no Sampler
* &amp;lbrack;Os ativos do Substance 3D Designer&amp;rbrack; enviados do Adobe Substance 3D Designer chegarão diretamente na seção “Seus ativos” do painel Ativos
* &amp;lbrack;Exportar&amp;rbrack; Envia ativos diretamente para o Adobe Substance 3D Painter e Adobe Substance 3D Stager
* &amp;lbrack;Export&amp;brack; Enviar materiais e iluminações do ambiente para o Adobe Substance 3D Painter
* &amp;preto;Exportar&amp;rbrack; Enviar iluminações do ambiente para o Adobe Substance 3D Stager
* &amp;lbrack;Renderização&amp;rbrack; Novas propriedades de material agora são suportadas e renderizadas em 3D
* &amp;lbrack;Renderização&amp;rbrack; Adição de suporte a Brilho (Cor do brilho, opacidade de Brilho e aspereza de Brilho)
* &amp;lbrack;Renderização&amp;rbrack; Adição de suporte a Revestimento (Cor do revestimento, Aspereza do revestimento, Normal do revestimento, Nível especular do revestimento e Revestimento IOR)
* &amp;lbrack;Renderização&amp;rbrack; Adicionando suporte a Anisotropia (Nível de anisotropia e Ângulo de anisotropia)
* &amp;lbrack;Renderização&amp;rbrack; Adicionando suporte a Speculares edge colores
* &amp;lbrack;Renderização&amp;rbrack; Ativar estas novas propriedades no painel Configurações do canal
* &amp;lbrack;Renderização&amp;rbrack; Introdução de um novo renderizador de Mecanismo em Tempo Real (2021) na versão Beta
* &amp;lbrack;Renderização&amp;rbrack; Alternar entre as duas versões do Renderizador no painel Configurações do Visualizador
* &amp;lbrack;Renderização&amp;rbrack; O renderizador do Realtime Engine (2021) oferece suporte às propriedades de translucidez, absorção e material de dispersão
* &amp;lbrack;Renderização&amp;rbrack; O renderizador Realtime Engine (2021) apresenta uma nova maneira de calcular sombras a partir da iluminação do ambiente
* &amp;lbrack;Renderização&amp;rbrack; O renderizador Realtime Engine (2021) calcula em tempo real a irradiância da iluminação do ambiente
* &amp;lbrack;Painel de configurações do Sombreador&amp;rbrack; Novo painel de configurações do Sombreador para ajustar parâmetros específicos de sombreador do material
* &amp;lbrack;Painel de configurações do Sombreador&amp;rbrack; Novos parâmetros (escala normal, escala do height, nível do height, intensidade da emissão, IOR, intensidade do Normal do revestimento e Coat IOR)
* &amp;lbrack;Painel de Configurações do Sombreador&amp;rbrack; Parâmetros específicos para o Mecanismo em Tempo Real 2021 (Dispersão da Subsuperfície, Distância de Dispersão, Red Shift e Dispersão de Rayleigh)
* &amp;lbrack;Painel de configurações do Sombreador&amp;rbrack; Os valores das configurações são salvos por ativo
* &amp;preto;Painel de configurações do visualizador&amp;rbrack; Adicionada uma visualização das iluminações do ambiente padrão
* &amp;preto;Painel de configurações do visualizador&amp;rbrack; Adicionada uma visualização das malhas padrão
* &amp;preto;Painel de configurações do visualizador&amp;rbrack; Novo parâmetro de opacidade do ambiente
* &amp;lbrack;Painel de configurações do visualizador&amp;rbrack; Novo parâmetro de desfoque de ambiente (específico para o renderizador Realtime Engine 2021)
* &amp;lbrack;Localização&amp;rbrack; Novas traduções para alemão e francês
* &amp;lbrack;Content&amp;brack; Novos materiais iniciais padrão
* &amp;lbrack;Content&amp;brack; Novas iluminações do ambiente padrão
* &amp;lbrack;Content&amp;rbrack; Todos os filtros foram atualizados, limpos e otimizados
* &amp;lbrack;Content&amp;brack; O filtro Ajuste foi dividido em vários filtros
* &amp;preto;Content&amp;brack; Novo filtro de Brilho/Contraste
* &amp;lbrack;Content&amp;brack; Novo filtro de Matiz/Saturação
* &amp;lbrack;Content&amp;brack; Novo filtro de Vibratilidade
* &amp;lbrack;Content&amp;brack; Novo filtro de nitidez
* &amp;lbrack;Content&amp;brack; Novo ajuste Normal/Height
* &amp;lbrack;Content&amp;brack; Novo painel filtro
* &amp;lbrack;Content&amp;brack; Novo filtro Borrar
* &amp;brack;Content&amp;brack; New Weaves filter
* &amp;lbrack;Content&amp;brack; Novo filtro de transformo de distorção
* &amp;lbrack;Content&amp;brack; Novo Height para filtro AO
* &amp;lbrack;Content&amp;brack; Novo Height para filtro Normal
* &amp;lbrack;Content&amp;brack; Substituição de cor - Substituir em novos canais suportados (Brilho, Revestimento, Anisotropia,...)
* &amp;lbrack;Content&amp;brack; Variação de cor - Modo manual para selecionar exatamente as cores a serem alteradas
* &amp;lbrack;Content&amp;brack; Tiling - opção para visualizar o corte de costuras
* &amp;lbrack;Content&amp;rbrack; Tiling - opção para tinta as costuras cortadas para uma divisão perfeita
* &amp;lbrack;Content&amp;brack; Match - opção para adicionar um material que corresponda à sua cor e aspereza
* &amp;lbrack;Content&amp;brack; Match - agora funciona em imagens para corresponder à cor de outra imagem
* &amp;lbrack;Content&amp;brack; Luz ambiente - Novo filtro de temperatura de cor
* &amp;lbrack;Content&amp;brack; Luz do ambiente - Novo filtro de exposição
* &amp;lbrack;Content&amp;brack; Luz do ambiente - Novo filtro de visualização de exposição
* &amp;lbrack;Content&amp;brack; Luz do ambiente - Novo filtro de Nadir patch
* &amp;lbrack;Content&amp;brack; Luz do ambiente - Novo filtro de Nadir extract
* &amp;lbrack;Content&amp;brack; Luz ambiente - Novos filtros de Luzes (Esfera, Linha, Forma, Plano)
* &amp;lbrack;Content&amp;brack; Luz ambiente - Novo filtro de correção de panorama
* &amp;lbrack;Content&amp;brack; Luz do ambiente - Novo filtro Endireitar horizonte
* &amp;lbrack;Content&amp;brack; Luz do ambiente - Novo filtro de mesclagem HDR

**Problemas Conhecidos:**

* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Alterar o layout, falha o aplicativo
* &amp;lbrack;Realtime Engine 2021&amp;rbrack; Computação pesada, falha o aplicativo
* &amp;brack;Painéis&amp;rbrack; MacOS - Os painéis desencaixados estão na frente de todos os aplicativos
* &amp;lbrack;Widgets&amp;rbrack; Os widgets de Transformação e Posições podem desaparecer. Oculte e reexiba a camada para fazê-las aparecer.
* &amp;lbrack;Export&amp;rbrack; A exportação de SBSAR de uma luz de ambiente perde a precisão 32profundidade de bits
* &amp;lbrack;Painel de Ativos&amp;rbrack; Os ativos podem ser destacados ao abrir uma pasta
* &amp;lbrack;Painel de Propriedades&amp;rbrack; A redefinição dos parâmetros não redefine a interface do usuário da caixa de combinação
* &amp;lbrack;Localização&amp;rbrack; A alteração do idioma não afeta o painel do projeto até que ele seja recriado

## Versão 2

### 2.3.2 (2020.3.2) Vermicelli

*(Lançado: 23 De fevereiro De 2021)*

**Adicionado:**

* &amp;lbrack;Suporte para localizaçãp&amp;rbrack; japonês

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Ajustar um material no filtro de bordados perde a imagem do bordado

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.3.1 (2020.3.1) Vermicelli

*(Lançado: 17 de dezembro de 2020)*

**Adicionado:**

* &amp;lbrack;Atualização do Substance Engine do motor&amp;rbrack;
* &amp;lbrack;Aplicativo&amp;rbrack; Variável de ambiente para desativar recursos específicos
* &amp;lbrack;Content&amp;brack; Substituir cor - Nova opção de segmentação avançada
* &amp;lbrack;Content&amp;brack; Floor Tiles - novos padrões e opções disponíveis
* &amp;lbrack;Content&amp;brack; Bordado - Renovação completa do filtro
* &amp;lbrack;Content&amp;brack; Adjustment - Novo parâmetro metálico + correção de transformação segura de opacidade

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Não é possível importar duas vezes o mesmo filtro personalizado
* &amp;lbrack;Camadas&amp;rbrack; Não é possível usar a entrada de imagem com a ferramenta pincel
* &amp;preto;Exportar&amp;rbrack; Exportar .jpg em vez de .jpeg
* &amp;lbrack;UI&amp;rbrack; Atualizar créditos da imagem de boas-vindas
* &amp;lbrack;UI&amp;rbrack; Corrigir separador invisível nos menus
* &amp;lbrack;UI&amp;rbrack; Os botões de opção exibem uma dica de ferramenta quando estão truncados
* &amp;lbrack;UI&amp;rbrack; Erro de Digitação: Materiais Iniciais
* &amp;lbrack;O aplicativo&amp;rbrack; com caracteres UTF-8 em nomes de ativos não funciona
* &amp;preto;Localização&amp;rbrack; Desativar estilo de fonte em itálico para o idioma chinês
* &amp;lbrack;Localizaçãp&amp;rbrack; Cadeia localizada dividida em 2 linhas
* &amp;lbrack;Localization&amp;brack; Ajusta o nome da pasta e substitui com reticências se for muito longo
* &amp;lbrack;Localização&amp;rbrack; Formatar números com separador de milhar
* &amp;preto;Localização&amp;rbrack; Localizar exibição de data e hora
* &amp;lbrack;Localizaçãp&amp;rbrack; Localizar seletor de cores no Windows
* &amp;lbrack;Content&amp;brack; Transform - Com a transformação segura ativada, o normal gira corretamente a cada 45°
* &amp;lbrack;Content&amp;brack; relevo de Superfície - Corrigir problema de divisão em blocos gráficos com ruído fractal de perlin (ruído avançado)
* &amp;lbrack;Content&amp;rbrack; Brickwall Pattern - Height de entrada em 16 bits
* &amp;lbrack;Content&amp;brack; Ícone de Material Renderizar - problema de reflexos de Specular
* Variação de Cor do &amp;lbrack;Content&amp;brack; - Nenhuma mudança de cor entre as entradas de cor e o resultado
* Variação de cor do &amp;presilha;Content&amp;brack; - Atualização de desempenho

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.3.0 (2020.3.0) Vermicelli

*(Lançado: 26 De outubro De 2020)*

**Adicionado:**

* &amp;lbrack;Imagem para material&amp;rbrack; Suporte da série NVIDIA RTX 3000
* &amp;lbrack;Imagem para material&amp;rbrack; Novos parâmetros para controlar os detalhes da geometria
* &amp;lbrack;Imagem para material&amp;rbrack; Novos parâmetros para controlar a aspereza
* &amp;lbrack;Imagem para material&amp;rbrack; Novos parâmetros para controlar a intensidade da delícia
* &amp;lbrack;Miniaturas&amp;rbrack; Novo gerador de miniaturas baseado no renderizador Substance Designer PBR
* &amp;preto;Miniaturas&amp;rbrack; Atualiza materiais de base e atlas para incorporar a miniatura
* &amp;lbrack;Miniaturas&amp;rbrack; Recupera a miniatura do arquivo .sbsar, se existir
* &amp;lbrack;Miniaturas&amp;rbrack; Alterar a qualidade da miniatura nas Preferências
* &amp;lbrack;Engine&amp;rbrack; Atualizado para a versão 8 do Substance Engine
* &amp;lbrack;Localização&amp;rbrack; Localização em chinês
* &amp;preto;UI&amp;rbrack; Seletor de Cores Especiais Experimentais
* &amp;lbrack;Content&amp;rbrack; Novo Mapa de Ambiente - Studio 06
* &amp;preto;Content&amp;brack; Adicionar filtro Gerador de Atlas
* &amp;preto;Content&amp;brack; Adicionar filtro de Atlas splitter
* &amp;preto;Content&amp;brack; Adicionar filtro de gengivas descartadas
* &amp;lbrack;Content&amp;brack; Adicionar filtro de impressões digitais
* &amp;preto;Content&amp;brack; Adicionar filtro Scratches
* &amp;lbrack;Content&amp;brack; Adicionar filtro de Relevo de Superfície (substituir filtro de modulação do height)
* &amp;preto;Content&amp;brack; Adicionar filtro de distorção
* &amp;preto;Content&amp;brack; Adicionar filtro Inverter
* &amp;preto;Content&amp;brack; Adicionar filtro Colorir
* &amp;preto;Content&amp;brack; Adicionar filtro Substituir cor
* &amp;lbrack;Content&amp;brack; Transform - Adiciona a possibilidade de desativar a transformação em um canal específico
* &amp;lbrack;Content&amp;brack; Transform - Adicionar rotação quando a transformação segura estiver ativada
* Variação de cor do &amp;brack;Content&amp;brack; - Adicione uma opção de segmentação para escolher como distribuir as cores

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Atualizar UI corretamente ao fazer várias ações de desfazer/refazer
* &amp;preto;Camadas&amp;rbrack; Impedir falhas ao fazer várias ações de desfazer/refazer
* &amp;lbrack;Camadas&amp;rbrack; Falha ao usar Imagem para Material (Ativado por IA), com log: ordinal de dispositivo inválido
* &amp;lbrack;Filtros&amp;rbrack; Melhorar a detecção de placa gráfica NVIDIA para recursos específicos do NVIDIA
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao fechar o aplicativo
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir detecção de quantidade de VRAM no MacOS
* &amp;lbrack;Export&amp;brack; Algumas predefinições de exportação às vezes estão ausentes
* &amp;lbrack;Content&amp;brack; Efeito de pintura a óleo - Corrigir o intervalo do height com amplitude de deslocamento alta
* &amp;lbrack;Content&amp;brack; Tornar bloco avançado - Sem cor base desbotada na exportação
* &amp;lbrack;Content&amp;brack; Tornar bloco avançado - Máscara branca na cor base quando o AO for muito forte
* &amp;lbrack;Ajuste de &amp;Content&amp;brack; - Agora funciona em imagens (scan1, ...)

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.2.1 (2020.2.1) Udon

*(Lançado: 21 de julho de 2020)*

**Adicionado:**

* &amp;lbrack;Camadas&amp;rbrack; Mensagem de erro no aplicativo quando a imagem para material (alimentada por IA) está sem memória

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; A imagem para material (viabilizada por IA) não funciona com fluxos de trabalho de Specular/Textura reluzente
* &amp;lbrack;Camadas&amp;rbrack; Falha quando está fora da memória de vídeo ao usar Imagem para material (alimentado por IA)
* &amp;lbrack;Camadas&amp;rbrack; O cache de disco não é usado para exibição ao abrir uma pilha
* &amp;lbrack;Camadas&amp;rbrack; Detecção de Nvidia RTX 8000
* &amp;lbrack;Camadas&amp;rbrack; Às vezes, é impossível mover uma camada para fora de uma entrada Splatter
* &amp;lbrack;Camadas&amp;rbrack; O cache de disco não é usado ao inserir uma pilha em uma pilha
* &amp;lbrack;Camadas&amp;rbrack; Alguns usos de canal são computados embora não sejam usados
* &amp;lbrack;Camadas&amp;rbrack; Saídas em branco são criadas às vezes ao importar imagens
* &amp;lbrack;Exibição 2D&amp;rbrack; Alternando para outra camada com o modo de Desenho ativa bloqueia a panorâmica e o zoom
* &amp;lbrack;Content&amp;brack; Snow - Problema de 8 bits no mapa normal
* &amp;lbrack;Content&amp;brack; Padrão de pavimento - problema de 8 bits no mapa normal
* &amp;lbrack;Content&amp;brack; Equalizador - Problema de 8 bits no mapa normal
* &amp;lbrack;Content&amp;brack; Gravel Generator - problema de 8 bits no mapa normal
* &amp;lbrack;Content&amp;brack; Floor Tiles - Manipular opacidade e specular level
* &amp;lbrack;Content&amp;rbrack; O mesclador reinicia a predefinição de exportação - inverter mapa normal
* &amp;lbrack;Content&amp;brack; Corrigir problema com imagens enormes com Imagem para material (alimentado por IA)
* &amp;lbrack;Application&amp;brack; Falha ao escolher “Fazer Backup e Reiniciar” em erro de banco de dados
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao clicar rapidamente no mesmo ativo
* &amp;lbrack;Aplicativo&amp;rbrack; Falha rara ao sair
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao soltar arquivos na tela de boas-vindas
* &amp;lbrack;Aplicativo&amp;rbrack; Falha quando um arquivo de ambiente corrompido é carregado
* &amp;lbrack;Aplicativo&amp;rbrack; Falha rara ao alternar rapidamente ativo renderizado
* &amp;lbrack;Aplicativo&amp;rbrack; Congela ao sair enquanto um ativo está sendo calculado
* &amp;lbrack;Aplicativo&amp;rbrack; Falha rara na inicialização no macos
* &amp;lbrack;Aplicativo&amp;rbrack; Bloqueio ao fechar o aplicativo logo após a inicialização
* &amp;lbrack;Renderizando&amp;brack; a visualização 3D às vezes pisca
* &amp;lbrack;UI&amp;rbrack; O seletor de cores e os widgets de semente aleatórios não estão alinhados com o restante dos ajustes
* &amp;lbrack;Renderização&amp;rbrack; Tempo de computação incorreto exibido
* &amp;lbrack;Export&amp;brack; Algumas predefinições de exportação às vezes estão ausentes

**Problemas Conhecidos:**

* O uso de imagem para material (viabilizado por IA) em imagens de alta resolução pode ser lento
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* Impossível salvar duas vezes exatamente a mesma pilha de camadas de material

### 2.2.0 (2020.2.0) Udon

*(Lançado: 15 de junho de 2020)*

**Adicionado:**

* &amp;lbrack;Criar&amp;brack; Novo filtro de Imagem para Material (alimentado por IA) disponível no Windows e no Linux
* &amp;lbrack;Criar&amp;rbrack; Renomear Bitmap como Material para Imagem como Material (B2M)
* &amp;preto;Importação de imagem&amp;rbrack; Pop-up Modelo de criação de novo material
* &amp;lbrack;Importação de imagem&amp;rbrack; Nova opção “Adicionar um material de base”
* &amp;lbrack;Importação de imagem&amp;rbrack; Ser capaz de arrastar e soltar imagens adicionais no Modelo de criação de material
* &amp;lbrack;Importação de imagem&amp;rbrack; Ser capaz de remover imagens no Modelo de criação de material
* &amp;preto;Importação de imagem&amp;rbrack; Atribui canal aos bitmaps importados automaticamente com base no nome do arquivo
* &amp;preto;Importação de imagem&amp;rbrack; Ser capaz de inverter mapas normais
* &amp;lbrack;Visualização 2D&amp;rbrack; Introdução de um modo de pintura
* &amp;lbrack;Exibição 2D&amp;rbrack; Os blocos de pintura
* &amp;lbrack;Visualização 2D; Define um valor em tons de cinza para a cor do pincel
* &amp;lbrack;Exibição 2D&amp;rbrack; Panorâmica e zoom ao pintar
* &amp;lbrack;Visualização 2D&amp;rbrack; X atalho para inverter o valor do pincel em escala de cinza
* &amp;lbrack;Exibição 2D&amp;rbrack; &amp;lbrack; e &amp;rbrack; atalhos para alterar o tamanho do pincel
* &amp;lbrack;Exibição 2D&amp;rbrack; Ctrl (ou Cmd) + Roda do mouse alteram o tamanho do pincel
* &amp;lbrack;Exibição 2D&amp;rbrack; Agora é possível modificar a posição do código-fonte ao usar Clonar correção
* &amp;preto;Camadas&amp;rbrack; Shift + arrastar e soltar para atlas de dispersão automática
* &amp;lbrack;Camadas&amp;rbrack; Alt + arrastar e soltar insere um material como um decalque
* &amp;lbrack;Camadas&amp;rbrack; Expor facilmente as matriz de transformação do Substance Designer
* &amp;lbrack;Camadas&amp;rbrack; Soltar texturas em uma pilha não vazia automaticamente atribui aos canais corretos
* &amp;lbrack;Camadas&amp;rbrack; Novo tipo de camada: Filtros compostos
* &amp;lbrack;Parâmetros&amp;rbrack; Suporte a entradas de cadeia de caracteres de Substance
* &amp;lbrack;UI&amp;rbrack; Sombras projetadas adicionadas para pop-ups e menus
* &amp;lbrack;UI&amp;rbrack; Novo Widget de Cor com opções do botão direito (limpar, copiar, colar)
* &amp;lbrack;UI&amp;rbrack; Novo widget de imagem com a opção de ferramenta Pintura
* &amp;lbrack;UI&amp;rbrack; Ser capaz de pintar sobre uma imagem importada em um widget de imagem
* &amp;lbrack;Renderização&amp;rbrack; Nova posição padrão da câmera
* &amp;lbrack;Exportar&amp;rbrack; os arquivos de Substance são exportados para o Substance Designer 2020.1.2 (10.1.2)
* &amp;lbrack;Desempenho&amp;rbrack; Melhor tempo de inicialização do aplicativo
* &amp;lbrack;Desempenho&amp;rbrack; Melhorar a manipulação de tarefas assíncronas
* &amp;lbrack;Desempenho&amp;rbrack; Melhorar o desempenho da pilha de camadas ao adicionar, remover ou mover camadas
* &amp;lbrack;Desempenho&amp;rbrack; Imagem para material (com IA) é executada mais rapidamente em GPUs RTX
* &amp;lbrack;Content&amp;brack; Novas malhas: Camiseta Feminina, Camiseta Masculina, Sapato
* &amp;lbrack;Content&amp;rbrack; Novo Modo de Mesclagem - Mesclagem por Canal
* &amp;lbrack;Conteúdo&amp;rbrack; Opacidade mesclar correção de height com 2 novos parâmetros (posição do height e escala do height)
* &amp;lbrack;Content&amp;brack; Adicionar ajustes de Height no modo de mesclagem Height
* &amp;lbrack;Content&amp;rbrack; Usar a opção de informações do Height na Mesclagem de máscaras personalizadas
* &amp;lbrack;Content&amp;rbrack; Nova ferramenta de correção de perspectiva
* &amp;lbrack;Gerador de padrões do Content&amp;brack; - Adicionar um parâmetro para inverter o padrão
* &amp;lbrack;Content&amp;brack; Gerador de padrões - Adicionar um novo parâmetro Sobrescrever detalhes do material
* &amp;brack;Content&amp;brack; Novo filtro de decalques
* &amp;lbrack;Content&amp;brack; Novo filtro de musgo
* &amp;lbrack;Content&amp;brack; Novo filtro do Rachadura
* &amp;lbrack;Content&amp;brack; Novo filtro de Validações do PBR
* &amp;lbrack;Content&amp;brack; Novo Blocos de Piso, filtro
* &amp;lbrack;Content&amp;brack; Novo Filtro Colar Comichão
* &amp;lbrack;Content&amp;brack; Atlas scatter - Adicionar entrada de Máscara personalizada para ativar a opção de pintura
* &amp;lbrack;Content&amp;brack; Dirt - Adicionar entrada de Máscara personalizada para ativar a opção de pintura
* &amp;predefinição de exportação de CLO do &amp;brack;Content&amp;brack;
* &amp;predefinição de exportação do VStitcher; Content&amp;brack;
* &amp;lbrack;Content&amp;brack; Unity HDRP presets exportar um detailMap

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; As imagens importadas são carregadas muitas vezes
* &amp;lbrack;Camadas&amp;rbrack; Falha ao criar uma correção de clone na parte inferior da pilha
* &amp;lbrack;Camadas&amp;rbrack; Adicionar um material na parte inferior da pilha o torna instável
* &amp;lbrack;Camadas&amp;rbrack; Filtro após importação de imagem funciona incorretamente
* &amp;lbrack;Layers&amp;brack; o valor workflow_type não é atualizado ao alternar o fluxo de trabalho entre projetos com um filtro personalizado
* &amp;lbrack;Camadas&amp;rbrack; Desativar o botão “remover camada” quando nenhuma camada estiver selecionada
* &amp;lbrack;Camadas&amp;rbrack; Falha ao carregar um ativo contendo uma correção de clone
* &amp;lbrack;Camadas&amp;rbrack; O filtro Normal para Height trava no MacOs
* &amp;lbrack;Application&amp;brack; Falha ao carregar mapas de ambiente para frente e para trás
* &amp;lbrack;Aplicativo&amp;rbrack; Problemas de desempenho quando algum driver de tablet gráfico está instalado
* &amp;lbrack;Application&amp;brack; os arquivos de 32 bits EXR importados são pretos
* &amp;lbrack;O aplicativo &amp;rbrack; trava ao carregar e descarregar ativos
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao alternar de explorar para criar
* &amp;lbrack;Aplicativo&amp;rbrack; A coleção de destino ao salvar um material não é do projeto atual
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir backup e reiniciar
* &amp;preto;Importação de imagem&amp;rbrack; Importar imagens em tons de cinza corretamente
* &amp;lbrack;Content&amp;brack; Novos filtros para nova manipulação de matriz
* &amp;lbrack;Conteúdo&amp;rbrack; Os filtros personalizados importados são visíveis na barra de acesso rápido
* &amp;lbrack;Content&amp;brack; Corrigir mudança de cor com o filtro avançado Tornar bloco
* &amp;lbrack;Desempenho&amp;rbrack; Abrir uma caixa de diálogo de cores é lento e recalcula a camada atual
* Atalhos de teclado do &amp;brack;UI&amp;rbrack; às vezes não funcionam
* &amp;lbrack;2D Visualizar&amp;rbrack; Preenchimento sensível a conteúdo precisa de um primeiro clique inútil para funcionar
* &amp;lbrack;Recursos&amp;rbrack; As pastas em discos locais ainda são monitoradas por atualizações após sua remoção
* &amp;lbrack;Resources&amp;rbrack; Excluir uma pasta vinculada do sistema de arquivos não a remove
* &amp;preto;Exportar&amp;rbrack; Os usos personalizados em predefinições de exportação personalizadas não são exportados
* &amp;lbrack;Export&amp;brack; Falha ao exportar arquivo .sbsar com caracteres especiais no caminho

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

* &amp;lbrack;Projeto&amp;rbrack; Exportar e importar metadados
* &amp;lbrack;Application&amp;brack; Ctrl+S agora salva uma predefinição em Explorar
* &amp;lbrack;Desempenho&amp;rbrack; Usar cache de renderização em vez de recalcular materiais salvos para resoluções de até 2k

**Corrigido:**

* &amp;lbrack;UI&amp;rbrack; Indicador de computação fixa no visor
* &amp;lbrack;UI&amp;rbrack; A inserção de valores negativos nos controles deslizantes é fixa
* &amp;lbrack;UI&amp;rbrack; Caixas de combinação: setas do teclado e barra de rolagem agora funcionam
* &amp;lbrack;UI&amp;rbrack; Mantenha o canal selecionado ao alternar entre “Saídas de material” e “Entradas de camada” na exibição 2D
* &amp;lbrack;Camadas&amp;rbrack; Corrigido um erro fatal ao adicionar canais personalizados no Material de base
* &amp;lbrack;Camadas&amp;rbrack; Falha ao manipular camadas
* &amp;lbrack;Camadas&amp;rbrack; Os canais personalizados não são exibidos com um material salvo
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigido uma falha rara ao importar um ativo
* &amp;lbrack;O aplicativo &amp;rbrack; falha ao sair
* As caixas de combinação do &amp;brack;Application&amp;brack; agora mostram os valores corretos ao alternar as predefinições
* &amp;lbrack;Export&amp;rbrack; Predefinição de paisagem renomeada para Enscape Revit
* &amp;predefinição;Exportar&amp;predefinição; Importar uma predefinição de exportação após removê-la funciona
* &amp;lbrack;Export&amp;brack; Falha na exportação
* &amp;lbrack;Renderização&amp;rbrack; Renderização fixa quando a cor base está no formato half float de 16 bits
* &amp;lbrack;Projeto&amp;rbrack; Não falhar ao importar pacote corrompido
* &amp;lbrack;Project&amp;rbrack; Manipular a migração 2019.1.4 para 2.x.x quando Criar nunca tiver sido aberto
* &amp;lbrack;Projeto&amp;rbrack; Corrigir uma falha ao importar o mesmo projeto duas vezes
* &amp;lbrack;Projeto&amp;rbrack; Corrigir uma falha ao importar projetos
* &amp;lbrack;Recursos&amp;rbrack; Os filtros personalizados importados em versões anteriores funcionam
* &amp;lbrack;Recursos&amp;rbrack; Os materiais com o mesmo nome não se apagam mais
* &amp;lbrack;Resources&amp;rbrack; Falha ao vincular uma pasta local
* &amp;lbrack;Resources&amp;rbrack; As pastas criadas pelo usuário dos materiais de início não são mais removidas após uma reinicialização
* &amp;lbrack;Inspire&amp;brack; Corrija a área de soltar material/coleção e adicione uma mensagem de aviso se estiver usando um material não salvo

**Problemas Conhecidos:**

* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante

### 2.1.0 (2020.1.0) Tiramisu

*(Lançado: 12 De março De 2020)*

**Adicionado:**

* &amp;lbrack;Export&amp;brack; Exportar seleção predefinida para empacotar suas texturas para renderizadores e mecanismos de jogo
* &amp;lbrack;Export&amp;brack; Exportar predefinição para Unreal Engine 4
* &amp;predefinição de Exportação do &amp;brack; para o Padrão de Unidade
* &amp;predefinição Exportar; &amp;predefinição Exportar para Unity HDRP
* &amp;predefinição de Exportar para Ciclos de Mesclagem/Evee
* &amp;preset;Exportar predefinição para Arnold 5
* &amp;preto;Exportar &amp;rbrack; Exportar predefinição para Renderizador Corona
* &amp;predefinição;Exportar &amp;predefinição para o Enscape
* &amp;preto;Exportar &amp;rbrack; Exportar predefinição para Keyshot 9
* &amp;predefinição;Exportar &amp;predefinição para Redshift
* &amp;preset;Exportar predefinição para Vray Next
* &amp;preset;Exportar predefinição para o Lens Studio
* &amp;predefinição de Exportação do Adobe Spark; para Spark AR Studio
* &amp;lbrack;Export&amp;brack; Exportar predefinição para Specular PBR Brilho da Aspereza metálica PBR
* &amp;lbrack;Export&amp;brack; Nova interface de exportação
* &amp;preto;Exportar&amp;rbrack; Lembrar configurações de exportação
* &amp;predefinição;Exportar&amp;predefinição; Importar e gerenciar suas predefinições de exportação personalizadas
* &amp;predefinição;Exportar&amp;predefinição; Excluir e substituir suas predefinições de exportação personalizadas
* &amp;preto;Exportar&amp;rbrack; Renomeia suas predefinições de exportação personalizadas
* &amp;preto;Export&amp;brack; Define a resolução de exportação padrão para a resolução atual
* &amp;lbrack;Export&amp;brack; Adicionar a opção de criar uma subpasta para o local de exportação
* &amp;lbrack;Exportar&amp;rbrack; Mensagem de aviso antes de substituir arquivos existentes
* &amp;lbrack;Aplicativo&amp;rbrack; Novo esquema de numeração de versão
* &amp;lbrack;Aplicativo&amp;rbrack; Abrir Criar na inicialização e alterar ordem dos laboratórios
* &amp;preto;Tela de boas-vindas&amp;rbrack; Novo banner de boas-vindas
* &amp;lbrack;Projeto&amp;rbrack; Abrir último projeto na inicialização
* &amp;lbrack;UI&amp;rbrack; Novo estilo de caixa de combinação
* &amp;lbrack;exibição 2D&amp;rbrack; F atalho para focalizar na exibição 2d
* &amp;lbrack;Filtros&amp;rbrack; Adicionado suporte para a tag alchemist::parameterVisibility em gráficos de Substance
* &amp;lbrack;Filtros&amp;rbrack; Tenha um ajuste global para gerenciar a visibilidade de parâmetros com base no seu fluxo de trabalho
* &amp;lbrack;Resources&amp;rbrack; Nova opção de linha de comando para configurar recursos e pastas vinculadas com um arquivo de configuração
* &amp;lbrack;Verificador de versão&amp;rbrack; Configuração da verificação de versão
* &amp;lbrack;Content&amp;brack; Novos materiais iniciais
* &amp;lbrack;Content&amp;brack; Bitmap para Material - Adiciona a possibilidade de definir o canal metálico (uniforme, importação de imagem personalizada, escolha de cores)
* &amp;lbrack;Content&amp;brack; Adjustment - Adicionar o suporte do fluxo de trabalho de specular/brilho PBR
* &amp;lbrack;Content&amp;brack; Atlas scatter - Novos parâmetros

**Corrigido:**

* &amp;lbrack;Projeto&amp;rbrack; Falha ao importar o mesmo projeto duas vezes
* &amp;lbrack;Projeto&amp;rbrack; Corrigido um erro fatal ao importar e abrir projetos várias vezes
* &amp;lbrack;Aplicativo&amp;rbrack; Falha ao carregar um material sem nome
* &amp;lbrack;Aplicativo&amp;rbrack; Reconhecer arquivos ausentes ao importá-los novamente
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigir falha aleatória ao desligar
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigido uma falha rara ao descarregar um material em Criar
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigido um erro fatal aleatório ao usar controles da interface do usuário
* &amp;lbrack;Aplicativo&amp;rbrack; Corrigida a exportação de arquivos de log para a área de trabalho no Windows 10
* O painel de Exportação do &amp;lbrack;UI&amp;rbrack; tem o tamanho incorreto quando você o abre em Criar
* &amp;lbrack;UI&amp;rbrack; Abrir projeto com um único clique
* &amp;lbrack;UI&amp;rbrack; Define corretamente os valores mínimos e máximos da barra deslizante
* &amp;lbrack;UI&amp;rbrack; Mostrar rótulo dos usos do canal em vez de ids
* &amp;lbrack;UI&amp;rbrack; Clicar em um material sempre abre/fecha o painel de ajuste
* &amp;lbrack;UI&amp;rbrack; Corrigir cores de camadas ocultas
* &amp;lbrack;UI&amp;rbrack; Melhorias nos botões da Tela de Boas-vindas
* &amp;lbrack;Camadas&amp;rbrack; Recomputações menos desnecessárias
* &amp;lbrack;Camadas&amp;rbrack; Falha ao usar o Clonar Patch
* &amp;lbrack;Camadas&amp;rbrack; Selecionar uma camada de importação de imagem não dispara mais um computador
* &amp;lbrack;Camadas&amp;rbrack; Clonar As camadas de Correção e Preenchimento sensível a conteúdo não são mais recalculadas quando selecionadas
* &amp;lbrack;Configurações do canal&amp;rbrack; Ativar ou desativar os usos agora aciona uma renderização
* &amp;lbrack;Resources&amp;rbrack; Impedir o congelamento ao clicar em massa em uma pilha da biblioteca
* &amp;lbrack;Recursos&amp;rbrack; Acerto de desempenho ao readicionar uma pasta vinculada adicionada anteriormente
* &amp;lbrack;Recursos&amp;rbrack; Corrigido um erro fatal ao tentar abrir um arquivo .sbsar excluído
* &amp;lbrack;Performance&amp;rbrack; Evite carregar materiais para acessar seus parâmetros
* &amp;lbrack;Desempenho&amp;rbrack; Fazer backup de ativos somente quando usado em um projeto ou em um material criado
* &amp;lbrack;Export&amp;brack; Materiais fixos na fila de exportação às vezes ignorados ou exportados com parâmetros errados
* &amp;lbrack;Visualização 2D; Panorâmica e zoom restaurados
* &amp;lbrack;Content&amp;brack; Parquet Pattern leva em consideração o canal de Oclusão de ambiente
* &amp;lbrack;Content&amp;brack; Tinta - Exibe a entrada da máscara ao ativar a máscara personalizada
* &amp;lbrack;Content&amp;brack; Stonewall Pattern - Remover possíveis efeitos de bandas no mapa normal
* &amp;lbrack;Content&amp;rbrack; Height Modulation - Corrigir entradas de cor de base dupla na exibição 2d

**Problemas Conhecidos:**

* Os filtros de Preenchimento sensível a conteúdo são lentos em alta resolução
* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante

## Versão 1

### 1.1.4 (2019.1.4) Sésamo

*(Lançado: 30 De Janeiro De 2020)*

**Adicionado:**

* &amp;lbrack;Resources&amp;rbrack; Prompt de confirmação ao limpar uma pasta de recursos

**Corrigido:**

* &amp;preto;Camadas&amp;rbrack; Mover camadas para duas e mais camadas abaixo ou acima
* &amp;lbrack;Criar&amp;rbrack; Alocação de orçamento VRAM suficiente para ter bons desempenhos

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

* &amp;lbrack;Workflow&amp;rbrack; Suporte a vários fluxos de trabalho
* &amp;lbrack;Fluxo de trabalho&amp;rbrack; Suporte ao fluxo de trabalho de Brilho de Specular PBR
* &amp;lbrack;Fluxo de trabalho&amp;rbrack; Novo painel de Configurações do canal
* &amp;lbrack;Fluxo de trabalho&amp;rbrack; Seleção de fluxo de trabalho na criação do projeto
* &amp;lbrack;Configurações do canal&amp;rbrack; Ativar/desativar o cálculo específico do canal
* &amp;lbrack;Configurações do canal&amp;rbrack; Exibe a lista de canais personalizados disponíveis no material atual
* &amp;lbrack;Configurações do canal&amp;rbrack; Cálculo automático de canais personalizados quando necessário
* &amp;preto;Configurações do canal&amp;rbrack; Forçar/Bloquear computação de canais personalizados
* &amp;lbrack;Camadas&amp;rbrack; Nova interface do usuário do espaço reservado de entrada de material nos filtros de Atlas scatter e Respingo
* &amp;lbrack;Camadas&amp;rbrack; O parâmetro de Entrada de Imagem de um filtro pode ser alimentado por camadas inferiores
* &amp;lbrack;Camadas&amp;rbrack; Exibir uma notificação quando algumas camadas estiverem desatualizadas
* &amp;lbrack;Camadas&amp;rbrack; Possibilidade de atualizar para a versão mais recente de camadas desatualizadas por meio da notificação
* &amp;lbrack;Projeto&amp;rbrack; Novos campos de metadados na criação do projeto
* &amp;lbrack;Inspire&amp;brack; As variações geradas são específicas de um projeto
* &amp;lbrack;Visualização 2D&amp;rbrack; Alternar entre as entradas da camada, as saídas da camada e as saídas de material
* &amp;lbrack;Tela de boas-vindas&amp;rbrack; Adicionar opção de importar projeto (.alch)
* &amp;lbrack;Preferências&amp;rbrack; Nova janela de Preferências para definir a localização do cache e as configurações de privacidade analítica
* &amp;lbrack;UI&amp;rbrack; Novos botões de interface
* &amp;lbrack;Desempenho&amp;rbrack; Melhoria geral do sistema de paralelização
* &amp;lbrack;Desempenho&amp;rbrack; Otimização do número de computadores de material
* &amp;lbrack;Atualização do Substance Engine do motor&amp;rbrack;
* &amp;lbrack;Framework&amp;rbrack; Atualize para o Qt 5.13
* &amp;lbrack;MacOS&amp;rbrack; Melhorias globais do suporte ao macOS Catalina
* &amp;lbrack;Content&amp;brack; Filtro de ajuste - Intensidade normal e parâmetros invertidos

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Parâmetro Cancelar definição da entrada de imagem ao excluir a camada
* &amp;lbrack;Camadas&amp;rbrack; Corrigir uma falha ao adicionar uma camada de correção de clone
* &amp;lbrack;Camadas&amp;rbrack; Corrigir algumas falhas ao mesclar camadas para empilhar materiais em outros materiais de pilha de camadas
* A seleção de canais para exportação do &amp;brack;Export&amp;brack; agora é respeitada
* &amp;lbrack;Recursos&amp;rbrack; Não trave ao navegar no painel Recursos
* &amp;lbrack;Resources&amp;rbrack; Corrigir falha ao importar arquivos de Substance corrompidos
* &amp;lbrack;Resources&amp;rbrack; Reduz o número de falhas ao carregar pastas grandes
* &amp;lbrack;Miniatura&amp;rbrack; O cálculo da miniatura não congela a interface
* &amp;lbrack;Importação de imagem&amp;rbrack; Uniformização de tipo de imagem suportada pelo aplicativo
* &amp;Preset&amp;brack; Salve a descrição ao criar uma predefinição a partir de um SBSAR
* &amp;lbrack;Inspire&amp;brack; Corrigir arrastar e soltar imagem
* &amp;lbrack;O aplicativo &amp;rbrack; corrige falhas ao sair
* &amp;lbrack;Correção do aplicativo&amp;rbrack; falha ao sair ao exportar materiais
* &amp;lbrack;UI&amp;rbrack; Correções e melhorias
* &amp;lbrack;UI&amp;rbrack; Renomeia o ativo temporário para “material não salvo”
* &amp;lbrack;Content&amp;brack; Atualização global e limpeza de todos os filtros

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

* &amp;preto;Camadas&amp;rbrack; As opções Salvar e Salvar como podem ser acessadas pela interface na barra de ferramentas da pilha de camadas
* &amp;lbrack;Recursos&amp;rbrack; Trilha de navegação mais nítida no painel Recursos para navegar pelas pastas
* &amp;lbrack;Recursos&amp;rbrack; botão Manter anterior pressionado para acessar todas as pastas superiores
* &amp;lbrack;Resources&amp;rbrack; Adicionar recarregamento de materiais importados opção para atualizá-los para a versão mais recente
* &amp;lbrack;Camadas&amp;rbrack; Possibilidade de alterar a imagem na camada de importação da imagem
* &amp;lbrack;Camadas&amp;rbrack; Possibilidade de definir uma imagem como um canal (cor de base, normal, height,...) na camada de importação de imagem
* &amp;lbrack;Content&amp;brack; Novo filtro de Atlas scatter para dispersão novos elementos atlas de Substance Source
* &amp;lbrack;Content&amp;brack; Novo filtro Efeito de Tinta a óleo
* &amp;lbrack;Content&amp;brack; Novo filtro de Geração de Canais para gerar height, oclusão de ambiente e aspereza a partir de cor de base e mapas normais

**Corrigido:**

* &amp;lbrack;UI&amp;rbrack; Reativar dicas de ferramentas na barra de ferramentas da pilha de camadas
* &amp;lbrack;UI&amp;rbrack; Corrigir problema ao digitar duas casas decimais em um valor de controle deslizante
* &amp;lbrack;Performance&amp;rbrack; Corrigir falha ao alternar rapidamente entre materiais
* &amp;lbrack;Export&amp;brack; Alternar para outro material antes do final de uma exportação não trava mais
* &amp;lbrack;Recursos&amp;rbrack; O menu de contexto é exibido na parte superior do material quando você clica com o botão direito nele
* &amp;lbrack;Camadas&amp;rbrack; O link “Clique aqui” está funcionando quando a pilha de camadas estiver vazia
* &amp;lbrack;Predefinições&amp;rbrack; Remove o botão Salvar no painel Ajustar quando for um material criado em Alchemist
* &amp;lbrack;Tweak&amp;rbrack; Mensagem de informações exibida quando é um material criado no Alchemist
* &amp;lbrack;Viewport&amp;rbrack; O valor padrão da textura de Specular level foi corrigido para 0,04
* &amp;lbrack;Menu Arquivo&amp;rbrack; Corrigir e renomear a opção Salvar e Salvar como
* &amp;lbrack;Engine&amp;rbrack; Atualize a versão do mecanismo de Substance para evitar a falha de alguns arquivos SBSAR durante a importação.
* &amp;lbrack;Content&amp;rbrack; O filtro de divisão em blocos está funcionando no canal de oclusão de ambiente
* &amp;lbrack;Content&amp;rbrack; O filtro Cortar está funcionando no canal de oclusão de ambiente
* &amp;lbrack;Content&amp;brack; O filtro Água modifica o mapa de alturas
* &amp;lbrack;Content&amp;brack; Corrigir divisão em blocos gráficos do material superior no modo de mesclagem de opacidade
* &amp;lbrack;O Height de conteúdo&amp;rbrack; do material superior é preservado no modo de mesclagem de opacidade
* &amp;lbrack;Content&amp;brack; Possível adicionar uma máscara personalizada, um padrão personalizado ou um mapa de escala no filtro de Perfuração
* O filtro de modulação de Height &amp;lbrack;Content&amp;rbrack; força o height e os mapas normais em 16 bits
* O filtro &amp;lbrack;Content&amp;rbrack; Ajuste força height e mapas normais em 16 bits

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

* &amp;lbrack;Mesclagem&amp;rbrack; Novo modo de mesclagem de opacidade
* &amp;lbrack;Engine&amp;rbrack; Nova versão do Substance Engine

**Corrigido:**

* &amp;lbrack;Camadas&amp;rbrack; Corrigir falha ao excluir uma camada que ainda está em processamento
* &amp;lbrack;Camadas&amp;rbrack; Corrigir falha ao remover a camada inferior
* &amp;lbrack;Camadas&amp;rbrack; Corrigir falha enquanto o nome do material contém caracteres especiais
* &amp;lbrack;Camadas&amp;rbrack; Parar de computar todos os filtros que usam um widget
* &amp;lbrack;Camadas&amp;rbrack; Evite falhas ao usar os filtros Patch de Clone e Preenchimento sensível ao conteúdo
* &amp;lbrack;Camadas&amp;rbrack; Corrigir falha ao arrastar e soltar um filtro em slots de entrada de respingos
* &amp;lbrack;Recursos&amp;rbrack; Corrigir falha ao vincular pastas locais ou importar recursos no Substance Alchemist
* &amp;lbrack;Collection&amp;rbrack; Corrigir falha ao alternar rapidamente entre materiais
* &amp;lbrack;UI&amp;rbrack; Corrigir falha enquanto o valor é nulo ou inválido na divisão em blocos gráficos, controles deslizantes de deslocamento na viewport
* &amp;lbrack;Inspire&amp;rbrack; Corrigir falha ao acessar a guia Inspire
* &amp;lbrack;Inspire&amp;brack; Corrigir falha ao inspirar em um material de pilha de camadas recém-salvas
* &amp;lbrack;Performance&amp;rbrack; Computação de materiais e filtros de Substance pesados (Lado a lado) mais rápida
* &amp;lbrack;Ajuda&amp;rbrack; Corrigir arquivo de log de exportação
* &amp;lbrack;Content&amp;brack; O filtro Aleatório funciona em todos os canais
* &amp;lbrack;Content&amp;brack; O fluxo de trabalho de multiângulo leva todas as digitalizações em consideração
* &amp;lbrack;Content&amp;brack; AO Mesclar mistura correta
* &amp;lbrack;Conteúdo&amp;rbrack; Curvatura Mesclar mistura correta
* &amp;lbrack;Content&amp;brack; Mistura correta da ID de cor
* &amp;lbrack;Content&amp;brack; Mesclagem de máscara personalizada correta
* &amp;lbrack;Content&amp;rbrack; Corrigir filtro de ajuste para modificação de aspereza
* &amp;lbrack;Content&amp;rbrack; Corrigir filtro de Material de base para upload de canais normais personalizados
* &amp;lbrack;Content&amp;brack; Corrigir padrão de importação personalizada do filtro de entalhe

**Problemas Conhecidos:**

* O uso de múltiplos delighters em um material não é recomendado
* O Delighter trava com drivers NVIDIA mais antigos (menos de 400.x)
* Coma ou ponto pode ser ignorado ao digitar um valor específico em um controle deslizante
* O filtro Normal para Height pode falhar no MacOS

### 1.1.0 (2019.1.0) Sésamo

*(Lançado em: 04 de novembro de 2019)*

**Adicionado:**

* &amp;lbrack;Projeto&amp;rbrack; Criação de um projeto
* &amp;lbrack;Projeto&amp;rbrack; Introdução do formato de arquivo .alch que contém dados do projeto
* &amp;lbrack;Projeto&amp;rbrack; Exportar um projeto .alch contendo as coleções e seus materiais
* &amp;lbrack;Projeto&amp;rbrack; Importar um projeto .alch
* &amp;preto;Projeto&amp;rbrack; Abrir projetos recentes
* &amp;lbrack;Tela de boas-vindas&amp;rbrack; Uma tela de boas-vindas é exibida na inicialização
* &amp;Preenchimento;Tela de boas-vindas&amp;Preenchimento; Criar um projeto a partir da tela de boas-vindas
* &amp;prego;Tela de boas-vindas&amp;rbrack; Acesse a lista de todos os seus projetos na tela de boas-vindas
* &amp;lbrack;Tela de boas-vindas&amp;rbrack; Links rápidos para acessar a documentação, o pop-up sobre e o gerenciamento de licenças
* &amp;lbrack;Menu Arquivo&amp;rbrack; Integração de um Menu de arquivos
* &amp;lbrack;Menu Arquivo&amp;rbrack; Acesse os comandos do projeto na guia Arquivo e salve a pilha de camadas
* &amp;preto;Menu Arquivo&amp;rbrack; Acesse os comandos Desfazer e Refazer na guia Editar
* &amp;lbrack;Menu Arquivo&amp;rbrack; O menu de ajuda anterior foi movido no menu Arquivo na guia Ajuda
* &amp;lbrack;Camadas&amp;rbrack; Nova arquitetura da pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Nova interface do usuário da pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Selecione o modo de mesclagem diretamente na barra de ferramentas
* &amp;lbrack;Camadas&amp;rbrack; Acessar separadamente os parâmetros de mesclagem e os parâmetros de material
* &amp;lbrack;Camadas&amp;rbrack; Adicionar materiais diretamente nas entradas dedicadas do filtro Respingo na pilha de camadas
* &amp;lbrack;Camadas&amp;rbrack; Altera a ordem de digitalização diretamente na camada de importação de imagem
* &amp;lbrack;Visor&amp;rbrack; Controle do campo de visão da câmera
* &amp;lbrack;Visor&amp;rbrack; Possibilidade de alternar entre a câmera ortográfica ou de perspectiva
* &amp;lbrack;Visor&amp;rbrack; Resolução de exibição e informações de profundidade de bits para cada canal
* &amp;lbrack;Recursos&amp;rbrack; Materiais de base é aberto por padrão
* &amp;lbrack;Cache&amp;rbrack; Localiza a pasta de cache em miniaturas
* &amp;lbrack;Cache&amp;rbrack; Localiza sua pasta de cache de renderização
* &amp;lbrack;Painéis&amp;rbrack; O painel Configurações de material está temporariamente oculto
* &amp;lbrack;Fluxo de trabalho&amp;rbrack; Specular/Textura reluzente temporariamente desativado
* &amp;lbrack;MacOS&amp;rbrack; Autenticação da versão do Catalina OS
* &amp;lbrack;Content&amp;brack; Nova versão do filtro Delighter
* &amp;lbrack;Content&amp;brack; Novo filtro de Preenchimento sensível ao conteúdo da imagem
* &amp;lbrack;Content&amp;brack; Novo filtro de Preenchimento sensível a conteúdo de material
* O filtro de Transformação do &amp;Preenchimento; tem uma opção de transformação segura

**Corrigido:**

* Todos os erros anteriores relacionados ao Create são inválidos hoje com a nova interface do usuário e a versão da arquitetura
* As dicas de ferramenta não ocultam os ícones na barra superior (3D, 2D, 2D/3D)
* &amp;lbrack;Content&amp;rbrack; O filtro Respingo aceita Atlas com mapa de altura completo
* &amp;lbrack;Content&amp;brack; O filtro Transformar funciona em imagens (scan1, scan2,...)

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

* &amp;lbrack;Create&amp;brack; Alguns filtros foram listados no acessador rápido, mas não no painel de filtros
* &amp;lbrack;O MacOS&amp;rbrack; corrigiu algumas falhas ao sair

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

* &amp;lbrack;Resources&amp;rbrack; Conectar e espelhar as pastas de materiais nos discos locais
* &amp;lbrack;Resources&amp;rbrack; Procure as pastas de materiais e suas subpastas
* &amp;lbrack;Recursos&amp;rbrack; Destacar o painel de recursos de material em uma janela separada para ver seus recursos em tela cheia
* &amp;lbrack;Recursos&amp;rbrack; Novo painel Recursos Layout para suportar a navegação em pastas e subpastas
* &amp;lbrack;Recursos&amp;rbrack; Use a estrutura para navegar pelas suas pastas
* &amp;lbrack;Resources&amp;rbrack; Forçar a sincronização da pasta local com a opção Sincronizar acessível com um clique com o botão direito do mouse
* &amp;lbrack;Recursos&amp;rbrack; Desconecte a pasta local com a opção Desconectar acessível clicando com o botão direito do mouse
* &amp;lbrack;Gerenciar&amp;rbrack; Exibir tags incorporadas de arquivos Substance
* &amp;lbrack;Gerenciar&amp;rbrack; Adicionar, editar e excluir tags de seus materiais
* &amp;lbrack;Gerenciar&amp;rbrack; Avaliar seus materiais
* &amp;lbrack;Camadas&amp;rbrack; Suporte Panorama saída
* &amp;lbrack;Camadas&amp;rbrack; Você pode excluir entradas de imagem na camada de importação de imagem
* &amp;lbrack;Camadas&amp;rbrack; Seleção automática da nova camada adicionada
* &amp;lbrack;Camadas&amp;rbrack; Seleção automática da camada abaixo após a exclusão de uma camada
* &amp;lbrack;UX&amp;rbrack; Mantém a visibilidade dos painéis à esquerda ao alternar para outro Lab
* &amp;lbrack;UX&amp;rbrack; Não crie uma camada base ou abra o pop-up Fluxo de trabalho de material ao importar imagens em uma pilha de camadas não vazias
* &amp;lbrack;UI&amp;rbrack; Novo estilo de campo de texto
* &amp;lbrack;UI&amp;rbrack; Novo estilo de SearchBox
* &amp;lbrack;UI&amp;rbrack; Novo estilo de cabeçalho do painel
* &amp;lbrack;UI&amp;rbrack; Novo estilo de indicador Ocupado
* &amp;lbrack;UI&amp;rbrack; As novas camadas empilham o estilo de fundo
* &amp;lbrack;UI&amp;rbrack; Usar fonte Adobe Clean
* &amp;lbrack;UI&amp;rbrack; Remover espaço reservado do ícone de conta-gotas do parâmetro de entrada de cores
* &amp;lbrack;Desempenho&amp;rbrack; Otimização do indicador de Ocupado
* &amp;lbrack;Content&amp;brack; Novo filtro Gerador de Padrão
* &amp;lbrack;Content&amp;brack; Novo filtro de desfoque

**Corrigido:**

* &amp;lbrack;Inspire&amp;rbrack; Corrigir falha ao usar mais de 10 cores
* &amp;lbrack;Visualização 2D; Corrigir a barra de rolagem na lista de canais da Visualização 2D
* &amp;lbrack;Viewer&amp;rbrack; Corrigir falha ao importar um mapa de ambiente sem energia de 2
* &amp;lbrack;Content&amp;brack; Corrigir importação de PNG para o padrão personalizado de filtros de Gravação e Perfuração
* &amp;lbrack;Export&amp;rbrack; Corrigir normal e height de 16 bits por canal de exportação
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

* &amp;lbrack;Filtros&amp;rbrack; Acesse rapidamente seus filtros pressionando a barra de espaço
* &amp;lbrack;Filtros&amp;rbrack; Novo painel dedicado para gerenciar, procurar e importar seus filtros
* &amp;lbrack;Metadados&amp;rbrack; Clique com o botão direito do mouse em um material para ver seus metadados
* &amp;lbrack;Metadata&amp;rbrack; Clique com o botão direito do mouse em um material para ver sua localização no disco
* &amp;lbrack;Controles deslizantes&amp;rbrack; Animar controles deslizantes ao passá-los pressionando Ctrl
* &amp;lbrack;Sliders&amp;rbrack; Pare e reinicie a animação dos controles deslizantes pressionando P
* &amp;lbrack;Export&amp;brack; a exportação de SBSAR segue as diretrizes de Substance Source
* &amp;lbrack;Licença&amp;rbrack; Ativar Substance Alchemist usando uma variável de ambiente
* A caixa de diálogo Arquivo do &amp;lbrack;UX&amp;rbrack; lembra o último caminho de arquivo selecionado
* A caixa de diálogo da pasta &amp;lbrack;UX&amp;rbrack; lembra o caminho da última pasta selecionada
* &amp;lbrack;UI&amp;rbrack; Atualizar interface do painel Recursos
* &amp;lbrack;UI&amp;rbrack; Atualizar Interface do Usuário da barra de pesquisa
* &amp;lbrack;UI&amp;rbrack; O ícone Criar novo material foi atualizado
* &amp;lbrack;Ajuda&amp;rbrack; URLs são atualizados para o domínio substance3d.com
* &amp;lbrack;Mesh&amp;rbrack; Uma malha de pano agora está disponível
* &amp;lbrack;Content&amp;brack; Novo filtro de corrosão
* &amp;lbrack;Content&amp;brack; Novo Filtro de Oxidação
* &amp;lbrack;Content&amp;brack; Novo Filtro de Musgo
* &amp;lbrack;Content&amp;rbrack; Novo Filtro de Dust
* &amp;lbrack;Content&amp;rbrack; Novo filtro de padrão de Brickwall
* &amp;lbrack;Content&amp;brack; Novo filtro de padrão Stonewall
* &amp;lbrack;Content&amp;brack; Novo filtro de acabamento em madeira
* &amp;lbrack;Content&amp;brack; Novo filtro de acabamento metálico
* &amp;lbrack;Content&amp;rbrack; Novo Filtro de Snow
* &amp;lbrack;Content&amp;brack; Novo filtro aleatório
* &amp;lbrack;Content&amp;brack; Agora você pode importar suas texturas diretamente no filtro Material de base

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

* &amp;lbrack;Engine&amp;rbrack; atualização de Substance Engine para ser compatível com a versão mais recente do Substance Designer
* &amp;lbrack;Licença&amp;rbrack; Atualizar pasta de licenças para as primeiras instalações
* &amp;lbrack;Camadas&amp;rbrack; Recarregue a qualquer momento a pilha de camadas para atualizar seus filtros personalizados

**Corrigido:**

* &amp;lbrack;Compatibilidade de Dados&amp;rbrack; Correção preventiva para limitar a corrupção de dados no momento da atualização

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

* &amp;lbrack;Metadados&amp;rbrack; Veja e preencha os metadados dos materiais em uma guia dedicada
* &amp;predefinição;Coleta&amp;predefinição; Cria uma coleção diretamente dos resultados da pesquisa
* &amp;Preenchimento;Publicação de mídia&amp;Rbrack; Exportar um quadro de uma coleção
* &amp;lbrack;UX&amp;rbrack; Desfazer uma alteração de ajuste ou importação de imagem pressionando Ctrl+Z
* &amp;lbrack;UX&amp;rbrack; Refaz uma alteração de ajuste ou importação de imagem pressionando Ctrl+Shift+Z
* &amp;lbrack;UI&amp;rbrack; Novos ícones com um novo estilo
* &amp;lbrack;Desempenho&amp;rbrack; Novo gerenciador de sessão para manipular melhor a alternância de guias
* &amp;lbrack;Desempenho&amp;rbrack; Abertura mais rápida da camada de importação de imagem
* &amp;lbrack;Content&amp;brack; Material genérico New Metal
* &amp;lbrack;Content&amp;brack; Novo material de Ferrugem
* &amp;lbrack;Content&amp;brack; Novo material genérico do Stone
* &amp;preto;Content&amp;brack; Atualização do filtro de entalhe
* &amp;lbrack;Content&amp;brack; Atualização do filtro de bordados
* &amp;lbrack;Content&amp;brack; atualização do filtro de Tinta
* &amp;lbrack;Content&amp;brack; Atualização do filtro Delighter

**Corrigido:**

* &amp;lbrack;Content&amp;brack; O filtro Água está funcionando no fluxo de trabalho Specular/Textura reluzente
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

* &amp;lbrack;Stack&amp;brack; Falha ao remover uma camada de respingo
* &amp;lbrack;Data&amp;brack; O banco de dados de ativos é corrompido quando o aplicativo trava
* &amp;lbrack;O Substance Alchemist do &amp;DataBrack; não pode iniciar quando o banco de dados de ativos estiver corrompido
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
* &amp;lbrack;UI&amp;rbrack; Ferramenta Clonar nova interface com visualização do tamanho do pincel
* &amp;lbrack;UI&amp;rbrack; Selecionar e excluir estágios ocultos
* &amp;lbrack;UI&amp;rbrack; Nova IU de Campo de Texto
* &amp;lbrack;Ajuda&amp;rbrack; Acessar sites da academia de Substance Source, Substance share e Substance
* &amp;lbrack;Content&amp;brack; Novos materiais padrão com geradores e atlas
* &amp;lbrack;Content&amp;brack; Bitmap para Atualização de Material
* &amp;lbrack;Atualização de Dirt do Content&amp;brack;
* &amp;lbrack;Atualização de Ferrugem do Content&amp;brack;
* &amp;preto;Content&amp;brack; Novo filtro de entalhe
* &amp;lbrack;Content&amp;brack; Novo filtro de Bordado
* &amp;lbrack;Content&amp;brack; Novo Filtro de erosão
* &amp;lbrack;Content&amp;rbrack; Novo Gerador de cascalho
* &amp;lbrack;Content&amp;brack; Novo filtro de Tinta
* &amp;lbrack;Content&amp;brack; Novo filtro Padrão de Assoalho
* &amp;lbrack;Content&amp;brack; Novo filtro de padrão de pavimentação
* &amp;lbrack;Content&amp;brack; Novo filtro de perfuração
* &amp;lbrack;Content&amp;brack; Novo filtro de respingo
* &amp;lbrack;Content&amp;brack; Novo filtro de Desgaste de Têxteis
* &amp;lbrack;Content&amp;brack; Novo filtro de Transformo

**Corrigido:**

* &amp;lbrack;Visor&amp;rbrack; Malha da esfera com divisão em blocos gráficos x2 em X
* &amp;lbrack;Viewport&amp;rbrack; Falha ao carregar seu próprio ambiente
* &amp;lbrack;Viewport&amp;rbrack; O mapa de ambiente agora está usando o valor de exposição também
* O atalho &amp;brack;Viewport&amp;rbrack; F não redefine o ângulo da câmera
* &amp;lbrack;Exportar&amp;rbrack; a exportação de SBS funciona com o Substance Designer mais recente 2018.3.3
* &amp;lbrack;Export&amp;brack; A exportação SBSAR respeita as mesmas diretrizes dos materiais Substance Source
* &amp;lbrack;UI&amp;rbrack; Barras de rolagem podem ser arrastadas
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

* &amp;lbrack;Pilha de camadas&amp;rbrack; Reordenação de camadas
* &amp;lbrack;Pilha de camadas&amp;rbrack; Excluir uma camada oculta
* &amp;lbrack;Pilha de camadas&amp;rbrack; Importar um material diretamente na posição de sua escolha
* &amp;lbrack;Pilha de camadas&amp;rbrack; Entrada de material como um novo tipo de parâmetro de filtro
* &amp;lbrack;Desempenho&amp;rbrack; Substance Engine orçamento é dinâmico para melhores desempenhos
* &amp;lbrack;Desempenho&amp;rbrack; Melhores desempenhos do OpenGL, especialmente no MacOS
* &amp;lbrack;Data&amp;brack; Atualização de dados mais rápida após o lançamento de uma nova versão
* &amp;lbrack;Content&amp;brack; AI Delighter disponível no Windows 7 e no Windows 8
* &amp;lbrack;Content&amp;brack; AI Delighter disponível na GPU RTX

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

* &amp;lbrack;Exportar&amp;rbrack; Substance (sbsar) exportar sua coleção
* &amp;lbrack;Exportar&amp;rbrack; arquivo Substance (sbs) exportar sua coleção
* &amp;preto;Exportar&amp;rbrack; Fila de exportação visível no painel Exportar
* &amp;lbrack;Export&amp;rbrack; Nomeie sua coleção ou material antes da exportação
* &amp;preto;Data&amp;brack; Salvar como seu material pressionando Ctrl+Shift+S
* &amp;lbrack;Data&amp;brack; Salve seu material pressionando Ctrl+S
* &amp;lbrack;Data&amp;brack; Coleções e Materiais são compatíveis entre as versões
* &amp;lbrack;Data&amp;brack; Atualize sua pilha de camadas de material com filtros atualizados
* &amp;lbrack;Data&amp;brack; Recarga a quente de filtros personalizados importados
* &amp;lbrack;UI&amp;rbrack; Feedback visual no visor enquanto ele está em computação
* &amp;lbrack;UI&amp;rbrack; Novo estilo de botão
* &amp;lbrack;UI&amp;rbrack; Salvar pop-up exibe o nome da coleção ativa
* &amp;lbrack;UI&amp;rbrack; Modificar imagens de origem de uma Camada de Importação de Imagem(ns)
* &amp;lbrack;Content&amp;brack; Os usos personalizados agora são suportados
* &amp;lbrack;Content&amp;brack; Mais formatos de imagens são suportados em parâmetros de entrada de imagem
* &amp;lbrack;Conteúdo&amp;rbrack; Novo Filtro Lado a Lado chamado Torná-lo Lado a Lado Avançado
* &amp;lbrack;Content&amp;brack; Atualização do filtro Água

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

* &amp;preto;Exportar&amp;rbrack; Novo pop-up de exportação
* &amp;predefinição;Exportar&amp;predefinição; Exporta uma coleção inteira
* &amp;lbrack;Exportar&amp;rbrack; Exportar bitmaps no formato de sua escolha
* &amp;preto;Exportar&amp;rbrack; Exportar bitmaps na resolução de sua escolha
* &amp;lbrack;Export&amp;brack; Exportar somente os canais de sua escolha
* &amp;lbrack;Export&amp;brack; Visualizar o tamanho da estimativa da exportação
* &amp;lbrack;Export&amp;brack; Visualizar o tamanho disponível no disco antes de exportar
* &amp;lbrack;UX&amp;rbrack; Ações na coleção acessíveis usando o botão direito
* &amp;lbrack;UX&amp;rbrack; Permite cancelar a definição de uma imagem ou de um ativo no Inspire
* &amp;lbrack;UX&amp;rbrack; Substance Alchemist é lançado maximizado
* &amp;lbrack;Assets&amp;rbrack; Nova maneira de salvar seus materiais para mantê-los persistentes com as próximas versões
* &amp;lbrack;Ajuda&amp;rbrack; Acesso à documentação online através do menu Ajuda
* &amp;lbrack;Desempenho&amp;rbrack; Variações de cores mais rápidas em materiais complexos criados com Substance Alchemist
* &amp;lbrack;Performance&amp;brack; Reduzir vazamentos de memória ao alternar Labs
* &amp;lbrack;Content&amp;brack; Verificador de escala para diagnosticar o tamanho físico do seu material
* &amp;lbrack;Content&amp;brack; Atualizar material ladrilho italiano de Veneza
* &amp;lbrack;Content&amp;rbrack; Atualizar respingos de musgo

**Corrigido:**

* Não há mais nome padrão ao salvar um material
* Os parâmetros dos filtros são perdidos após salvar um material e reabrir o Substance Alchemist
* &amp;lbrack;Content&amp;brack; Corrigir da parte inferior e da lógica superior para mesclagem de AO e curvatura

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
* &amp;lbrack;Log&amp;brack; Exportar arquivo de log pelo menu Ajuda
* &amp;preto;UI&amp;rbrack;Novo estilo de controles deslizantes
* &amp;lbrack;UI&amp;rbrack;Os painéis Predefinições e Ajustar foram mesclados
* &amp;preto;UI&amp;rbrack;Novo estilo de miniaturas
* Configurações de deslocamento, divisão em blocos gráficos e sombras acessíveis diretamente na viewport
* &amp;lbrack;Content&amp;rbrack; Novos Materiais Padrão
* &amp;lbrack;Content&amp;brack; Atualização do Moss Splatter
* &amp;lbrack;Framework&amp;rbrack; Atualizar Substance Engine Framework

**Corrigido:**

* A exclusão da pilha de camadas por meio da alternância de laboratórios foi corrigida
* Os valores de tempo de carregamento exibidos na viewport estão corretos
* Os canais padrão do fluxo de trabalho de material foram inicializados corretamente
* Desativar importação de malha personalizada
* Exportação de bitmap
* &amp;lbrack;O MacOS&amp;rbrack; para fechar o Substance Alchemist pode precisar de um “Force to quit”

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
* O Substance Alchemist do &amp;lbrack;MacOS&amp;rbrack; pode ser configurado em tela cheia
* &amp;lbrack;Filter&amp;rbrack; Importar máscara personalizada para gerenciar a mesclagem entre dois materiais
* &amp;lbrack;Filter&amp;brack; Control Moss scale
* &amp;lbrack;Filter&amp;rbrack; Atualização de correção de clone

**Corrigido:**

* Adicionar uma imagem em uma entrada de imagem na lista de parâmetros atualiza as saídas
* O filtro Importar Personalizado não adiciona uma Oclusão Ambiente preta e uma opacidade preta

**Problemas Conhecidos:**

* Os materiais criados com uma versão anterior não estarão disponíveis na nova versão.
* &amp;lbrack;O MacOS&amp;rbrack; para fechar o Substance Alchemist pode precisar de um “Force to quit”
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
