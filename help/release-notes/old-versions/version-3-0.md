---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-0.html"
breadcrumb-title: ''
description: Revise as notas de versão do Substance 3D Sampler versão 3.0 para saber mais sobre retrabalho de interface, iluminação do ambiente, filtros e integração de Creative Cloud.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 3.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '2019'
ht-degree: 0%

---


# Versão 3.0

O **Substance 3D Sampler 3.0.0** é o novo nome do Substance Alchemist agora que ele está conectado ao Adobe Creative Cloud. Ele traz um retrabalho de interface completo, suporte para a criação de Iluminações do ambiente, filtros totalmente reformulados e novos, funcionalidade Enviar para e suporte ao sombreador ASM.

Data de lançamento: *23 de junho de 2021*

## Principais recursos

### Nova interface e gerenciamento de painel

Com um novo nome, vem um novo visual. A interface do usuário do Sampler foi completamente remodelada para permitir mais personalização e acesso mais fácil.

![](../../assets/ui-dualscreen.jpg){width="600px"}

Os painéis podem ser encaixados e desencaixados, permitindo que você utilize totalmente uma configuração de tela dupla.

### Novo fluxo de trabalho do projeto

![](../../assets/ui-project-panel.png)

O Sampler agora funciona com projetos. O[painel Projeto](../../interface/panels/project-panel.md)permite que você gerencie e agrupe seus ativos por projeto. Os projetos são armazenados em arquivos Substance Sampler, facilmente compartilhados.

### Novo painel Ativos

![](../../assets/image2021-6-22-17-58-15.png)

O[painel de ativos](../../interface/panels/assets-panel.md)é um design novo e comum do painel Recursos, combinado com suas coleções.

* 3 seções: Ativos iniciais + Seus ativos + Pastas locais conectadas
* Suporte a novos tipos de ativo: filtros e imagens
* Exibição estreita/ampla
* Filtros e filtros de pesquisa

### Nova criação de Iluminação do ambiente

![](../../assets/idl.jpg){width="600px"}

O Sampler agora permite fazer mais do que apenas materiais. O Iluminação do ambiente é um novo tipo de ativo com seu [próprio conjunto de filtros](../../filters/hdri-tools/hdri-tools.md). Inicie a partir de [fotos com 360 colchetes](../../filters/hdri-tools/hdr-merge.md), crie uma iluminação do ambiente [do zero](../../filters/hdri-tools/shape-light.md) ou [edite um arquivo HDR existente](../../filters/hdri-tools/nadir-patch.md).

### Filtros novos e reformulados

![](../../assets/filter-all-filters.jpg){width="600px"}

Todos os filtros existentes foram reformulados:

* Suporte para canais de especificação/brilho.
* Suporte para máscaras personalizadas
* Nomes de parâmetro padronizados
* Ícones para quase todos os filtros

O Filtro de ajuste foi dividido em filtros separados com base na funcionalidade para imitar o Photoshop:

![](../../assets/filter-adjustment-filters.jpg)

Alguns novos filtros foram adicionados:

* [Distorcer Transformo](../../filters/tools/warp-transform.md)
* [Entrelaçar](../../filters/generators/weave.md)
* [Painel](../../filters/generators/panel.md)

### Nova funcionalidade Enviar para

![](../../assets/image2021-6-22-18-2-10.png)

Agora, o Sampler pode [compartilhar facilmente materiais e ambientes leves](../../interface/panels/share-panel.md)com o Substance 3D Painter e o Stager, com apenas um único clique.

### Novo mecanismo de renderização em tempo real

* Suporte a materiais do ASM, permitindo uma aparência consistente entre aplicativos com mais canais de materiais.
* Alternar entre 2 [mecanismos em tempo real](https://helpx.adobe.com/substance-3d/unlisted/documentation/sadoc/viewer-settings-188973164.html)
* Capacidade de controlar texturas padrão em uma malha

### Melhorias gerais

* Novos idiomas
* Capacidade de resposta do aplicativo
* Suporte a textura não quadrado
* Ferramentas Desfazer/Refazer
* Atribuir usos personalizados a imagens na camada de importação de imagem
* Redefinir um valor de parâmetro
* Progresso da exportação na barra de tarefas do Windows

## Tutorials

Veja abaixo nossos tutoriais em vídeo que abrangem os novos recursos:

## Notas de versão

### 3.0.0 Waffle

*(Lançado Em 23 De junho De 2021)*

**Adicionado:**

* [Branding] Substance Alchemist se torna Adobe Substance 3D Sampler
* [Marcas] Novos ícones de aplicativos
* [UI] Nova experiência de usuário e interface de usuário
* [UI] Nova tela inicial
* [UI] Os painéis são desencaixáveis e encaixáveis na interface
* [IU] Encaixar até 3 painéis na mesma coluna
* [IU] Encaixar até 3 painéis no mesmo painel (Guias)
* [IU] Desencaixar painéis para criar uma janela separada na mesma tela ou em uma tela diferente
* [UI] Pop-over de painéis fechados ao clicar em seus ícones
* [IU] Reorganizar suas barras esquerda e direita movendo ícones de painéis
* [UI] Nova barra de ferramentas para acessar diretamente filtros específicos (Cortar, Transformar, Transformar Perspectiva, Carimbo de Clonar)
* [UI] Novo botão “Obter conteúdo” na barra esquerda
* [IU] Importar arquivos diretamente em seus ativos com o botão Obter conteúdo
* [IU] Importar arquivos diretamente para suas camadas com o botão Obter conteúdo
* [UI] Acesse diretamente o site do Adobe Substance 3D Assets com o botão Obter conteúdo
* [UI] O widget de resolução agora pode ser acessado diretamente no visor
* [UI] Todos os elementos da interface agora são carregados dinamicamente
* [UI] Atalho - use “2” para alternar a visibilidade da Visualização 2D
* [UI] Atalho - use “3” para alternar a visibilidade da exibição 3D
* [Tela de boas-vindas] Crie um projeto em um clique com o botão Novo
* [Tela de boas-vindas] Novo banner de ilustração
* [Project] Todos os projetos agora estão associados a um arquivo exclusivo
* [Projeto] Nova extensão de arquivo de projeto .ssa
* [Project] Salvar como um projeto solicitará que você selecione onde salvar seu projeto
* [Project] Se você fechar o Sampler, será solicitado a salvar o projeto caso ele não tenha sido salvo
* [Project] Fechar o Sampler solicitará que você salve seu projeto se houver modificações desde o último salvamento
* [Project] O nome do seu projeto é exibido acima do visor
* [Projeto] O nome do projeto está em itálico com uma estrela se não estiver salvo ou se contiver modificações desde o último salvamento
* [Project] Abra um arquivo de projeto .ssa diretamente do explorador do sistema operacional
* [Projeto] Abrir um .sbsar no explorador do seu sistema operacional iniciará o Sampler com um novo projeto com este arquivo .sbsar pronto para uso
* [Project] Abra um arquivo .alch (Substance Alchemist legado) do explorador do sistema operacional
* [Painel Projeto] Novo painel que conterá todos os ativos criados em um projeto
* [Painel Projeto] Crie um ativo (material ou iluminação do ambiente) usando o ícone +
* [Painel do projeto] Clicar com o botão direito no ativo abre um menu de contexto
* [Painel Projeto] No menu de contexto do botão direito do mouse, você pode excluir um ativo
* [Painel Projeto] No menu de contexto do botão direito, você pode duplicar um ativo
* [Painel Projeto] No menu de contexto do botão direito, você pode renomear um ativo
* [Painel Projeto] Alternar entre ativos não perderá as modificações
* [Resolução] Agora você pode definir uma resolução não quadrada para todos os seus ativos
* [Resolução] O valor de resolução é salvo por ativo em um projeto
* [Iluminação do ambiente] Criar iluminação do ambiente no Substance 3D Sampler
* [Iluminação do ambiente] Ao criar uma iluminação do ambiente, arrastar e soltar imagens exibirá a janela Modelo de criação de Iluminação do ambiente
* [Iluminação do ambiente] No Modelo de criação de Iluminação do ambiente, selecione Importação de ambiente para atribuir sua imagem ao ambiente na exibição 3D
* [Iluminação do ambiente] No Modelo de criação de Iluminação do ambiente, selecione HDR mesclar para criar uma iluminação do ambiente a partir de várias imagens de 360 graus com exposições diferentes
* [Iluminação do ambiente] No Modelo de criação de Iluminação do ambiente, selecione “Usar como bitmap” para editar as imagens antes de criar uma iluminação do ambiente
* [Iluminação do ambiente] Atribuir o uso do ambiente na camada Importação de imagem para atribuir diretamente a imagem ao ambiente na visualização 3D
* [Iluminação do ambiente] No Visualização 2D do canal de ambiente, há uma correção de cores automática para que a renderização apareça da mesma forma que na visualização 3D
* [Iluminação do ambiente] Novo conteúdo dedicado para criação de iluminação do ambiente
* [Painel Ativos] Os painéis Recursos e Filtros são mesclados em um novo painel Ativos
* [Painel Ativos] O painel Ativos agora oferece suporte aos seguintes tipos de ativos: materiais, filtros e imagens
* [Painel Ativos] Todos os ativos iniciais podem ser acessados na seção Ativos iniciais
* [Painel Ativos] A seção Ativos iniciais é somente leitura
* [Painel Ativos] Nova seção “Seus ativos”
* [Painel Ativos] A seção “Seus ativos” é o local onde você pode importar todos os seus recursos
* [Painel Ativos] Todos os ativos em “Seus ativos” são adicionados em uma pasta específica em seus Documentos
* [Painel Ativos] Conecte pastas locais no painel Ativos para adicionar novas seções
* [Painel Ativos] A pesquisa pesquisará na pasta atual e em suas subpastas
* [Painel Ativos] Navegar entre pastas e subpastas com navegação estrutural
* [Painel Ativos] Filtrar a pasta atual por material, filtro ou imagem
* [Painel Ativos] Combine vários filtros para obter apenas materiais e imagens
* [Painel Ativos] Alterar a exibição alternando entre uma grade ou uma lista
* [Painel Ativos] Os filtros são representados com seus ícones
* [Painel Ativos] As imagens são representadas com a visualização
* [Painel Ativos] Aumentar a largura mudará o layout do painel com uma exibição específica para navegar entre as pastas
* [Painel Ativos] Em seções não somente leitura, exclua um ativo arrastando e soltando-o no ícone de compartimento
* [Painel Ativos] Clicar com o botão direito no ativo abre um menu de contexto
* [Painel Ativos] No menu de contexto do botão direito, acesse os metadados do ativo (nome, categoria, local)
* [Painel Ativos] No menu de contexto do botão direito do mouse, exclua o ativo (disponível somente em seções não somente leitura)
* [Painel Ativos] No menu de contexto do botão direito, procure seu ativo no Adobe Bridge
* [Painel Camadas] Novo ícone para adicionar diretamente uma material de base sobre as camadas
* [Painel Camadas] Atalho - Shift + B adicionará uma material de base em cima das camadas
* [Painel Camadas] As camadas agora têm uma visualização em miniatura (miniatura do material, ícone de filtro ou visualização da imagem)
* [Painel Propriedades] Novo design do título do painel Propriedades com o nome e a miniatura do ativo
* [Painel Propriedades] As camadas de filtro agora suportam predefinições
* [Painel Propriedades] Na camada de importação de imagem, clique com o botão direito do mouse na visualização da imagem para editar a imagem no Photoshop
* [Adobe Bridge] Procure seu ativo no Adobe Bridge e iniciará o Bridge no local do ativo
* [Adobe Photoshop] Editar no Adobe Photoshop abrirá a imagem no Photoshop pronta para ser editada
* [Adobe Photoshop] A cada salvamento no Adobe Photoshop, a imagem editada será recarregada no Sampler
* [Substance 3D Designer] Os ativos enviados da Adobe Substance 3D Designer chegarão diretamente na seção “Seus ativos” do painel Ativos
* [Exportar] Enviar ativos diretamente para o Adobe Substance 3D Painter e o Adobe Substance 3D Stager
* [Exportar] Enviar materiais e iluminações do ambiente para o Adobe Substance 3D Painter
* [Exportar] Enviar iluminações do ambiente para o Adobe Substance 3D Stager
* [Renderização] As novas propriedades do material agora são compatíveis e renderizadas em 3D
* [Renderização] Adição de suporte para brilho (Cor do brilho, opacidade de brilho e aspereza de brilho)
* [Renderização] Adição de suporte a revestimento (Cor do revestimento, Aspereza do revestimento, Normal do revestimento, Nível especular do revestimento e revestimento IOR)
* [Renderização] Adição de suporte a Anisotropia (Nível de anisotropia e Ângulo de anisotropia)
* [Renderização] Adição de suporte a Specular edge color
* [Renderização] Ativar estas novas propriedades no painel Configurações do canal
* [Renderização] Introdução de um novo renderizador de Mecanismo em tempo real (2021) na versão beta
* [Renderização] Alternar entre as duas versões do Renderizador no painel Configurações do visualizador
* [Renderização] O renderizador Realtime Engine (2021) oferece suporte às propriedades de translucidez, absorção e material de dispersão
* [Renderização] O renderizador Realtime Engine (2021) apresenta uma nova maneira de calcular sombras a partir da iluminação do ambiente
* [Renderização] O renderizador Realtime Engine (2021) calcula em tempo real a irradiância da iluminação do ambiente
* [Painel de configurações de Sombreador] Novo painel de configurações de Sombreador para ajustar parâmetros específicos de sombreador de material
* [Painel de configurações do Sombreador] Novos parâmetros (escala normal, escala do height, nível do height, intensidade de emissão, IOR, intensidade do Normal do revestimento e Coat IOR)
* [Painel de configurações de Sombreador] Parâmetros específicos para o Mecanismo em tempo real 2021 (Dispersão na subsuperfície, Distância de dispersão, Red Shift e Dispersão de Rayleigh)
* [Painel de configurações do Sombreador] Os valores das configurações são salvos por ativo
* [Painel de configurações do visualizador] Adicionada uma visualização das iluminações do ambiente padrão
* [Painel Configurações do visualizador] Adicionada uma visualização das malhas padrão
* [Painel Configurações do visualizador] Novo parâmetro de opacidade do ambiente
* [Painel Configurações do visualizador] Novo parâmetro de desfoque de ambiente (específico para o renderizador Realtime Engine 2021)
* [Localização] Novas traduções para alemão e francês
* [Content] Novos materiais iniciais padrão
* [Conteúdo] Novas iluminações do ambiente padrão
* [Content] Todos os filtros foram atualizados, limpos e otimizados
* [Conteúdo] O filtro Ajuste foi dividido em vários filtros
* [Conteúdo] Novo filtro de Brilho/Contraste
* [Conteúdo] Novo filtro de Matiz/Saturação
* [Conteúdo] Novo filtro de Vibratilidade
* [Conteúdo] Novo filtro de nitidez
* [Conteúdo] Novo ajuste de Normal/Height
* [Conteúdo] Novo filtro de Painéis
* [Conteúdo] Novo filtro Borrar
* [Conteúdo] Novo filtro Entrelinhas
* [Conteúdo] Novo filtro de transformo de distorção
* [Content] Novo Height para filtro AO
* [Conteúdo] Novo Height para o filtro Normal
* [Conteúdo] Substituição de cor - Substitua nos novos canais compatíveis (Brilho, Revestimento, Anisotropia,...)
* [Conteúdo] Variação de cor - Modo manual para selecionar exatamente as cores a serem alteradas
* [Conteúdo] Divisão em blocos gráficos - opção para visualizar as costuras cortadas
* [Content] Lado a lado - opção para tinta as costuras cortadas para um azulejo perfeito
* [Conteúdo] Correspondência - opção para adicionar um material de acordo com sua cor e sua aspereza
* [Conteúdo] Corresponder - agora funciona em imagens para corresponder à cor de outra imagem
* [Content] Luz do ambiente - Novo filtro de temperatura de cor
* [Content] Luz do ambiente - Novo filtro de exposição
* [Content] Luz do ambiente - Novo filtro de visualização de exposição
* [Content] Luz do ambiente - Novo filtro de Nadir patch
* [Content] Luz do ambiente - Novo filtro de Nadir extract
* [Content] Luz do ambiente - Novos filtros de luzes (esfera, linha, forma, plano)
* [Content] Luz do ambiente - Novo filtro de correção de panorama
* [Content] Luz do ambiente - Novo filtro Endireitar horizonte
* [Content] Luz do ambiente - Novo filtro de mesclagem HDR

**Problemas Conhecidos:**

* [Mecanismo em tempo real 2021] Alterar o layout e travar o aplicativo
* [Mecanismo em tempo real 2021] Computação pesada, falha no aplicativo
* [Panels] MacOS: painéis desencaixados estão na frente de todos os aplicativos
* [Widgets] Os widgets Transformo e Posições podem desaparecer. Oculte e reexiba a camada para fazê-las aparecer.
* [Exportar] A exportação SBSAR de uma iluminação do ambiente perde a precisão de 32profundidade de bits
* [Painel Ativos] Os ativos podem ser destacados ao abrir uma pasta
* [Painel Propriedades] A redefinição dos parâmetros não redefine a interface do usuário da caixa de combinação
* [Localização] A alteração do idioma não afeta o painel do projeto até que ele seja recriado
