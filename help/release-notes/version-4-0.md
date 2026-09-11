---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/release-notes/version-4-0.html"
breadcrumb-title: ''
description: Consulte as notas de versão do Substance 3D Sampler versão 4.0 para saber mais sobre a criação de objetos 3D a partir de imagens, mascaramento automático e melhorias de UX.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 4.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 4.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1026'
ht-degree: 1%

---


# Versão 4.0

Com o **Substance 3D Sampler 4.0**, você pode usar imagens do mundo real para criar objetos 3D com mascaramento automático de objetos, mapeamento de textura e dizimação de geometria. Esta versão apresenta algumas melhorias de UX como novas possibilidades na API Python.

*Data de lançamento: 31 de janeiro de 2023*

![](../assets/main-promo.jpg)

## Captura 3D

Com o Substance 3D Sampler 4.0, agora é possível criar objetos 3D a partir de imagens.

Temos recursos de fotogrametria integrados. Fotogrametria é o processo técnico de tirar medidas de imagens. É assim que o Sampler cria malhas 3D a partir de uma série de fotografias.

Tudo o que você precisa para começar é uma série de fotos que capturam as superfícies visíveis de um objeto - um smartphone ou câmera DLSR funciona muito bem.

Descubra o fluxo de trabalho passo a passo [aqui](../features-and-workflows/3d-capture.md).

## Realces

### Mascaramento automático

Remova o plano de fundo do objeto que você deseja Captura 3D. Crie uma máscara gerada automaticamente do objeto após importar suas imagens pela guia Máscara.

O uso de máscaras tem muitas vantagens. Permite detectar recursos e reconstruir apenas áreas não mascaradas.

![](../assets/release-page-masking.jpg){width="500px"}

### Definir a área de reconstrução

Alterne Região de interesse para ativar uma caixa delimitadora após alinhar as imagens. Defina e alinhe a área precisa que deseja reconstruir.

![](../assets/3d-capture-bounding-box-modified.png){width="500px"}

### Pós-processamento conectado

Assim que o objeto 3D for reconstruído, otimize o resultado com a dizimação automática, o desembrulho UV e o fça bake.

O pós-processamento o ajuda a adaptar e otimizar sua malha e texturas às suas necessidades e como você deseja usá-las.

O resultado da reconstrução pode gerar uma malha com milhões de polígonos e texturas de até 16K. Isso geralmente não será otimizado para a experiência de renderização, tempo real ou realidade aumentada.

A etapa de pós-processamento encadeia 4 etapas automaticamente:

* Decimação
* Desembrulhar UV
* Reprojeção
* Baking

![](../assets/release-page-post-processing.jpg){width="500px"}

### Exportar para os principais formatos de arquivo

Exporte seus objetos 3D reconstruídos em todos os formatos de arquivo padrão para usá-los onde precisar.

![](../assets/v4-0-0-export.jpg){width="500px"}

## Janela de visualização

As viewports 2D e 3D podem ser redimensionadas, trocadas e empilhadas verticalmente.

![](../assets/screenshot-2023-01-25-at-16-23-09.png){width="500px"}

## Scripts

Dividimos a função de exportação em 4:

* exportar materiais: `export_material`
* exportar iluminações do ambiente: `export_environment_light`
* exportar malha com ou sem textura: `export_mesh` ou `export_3d_object`

Adicionamos uma nova função para importar texturas com um uso específico: `import_textures`

O Sampler agora carregará na inicialização o script e os plug-ins armazenados em caminhos definidos por duas variáveis de ambiente:

* `SAMPLER_PLUGIN_PATH`
* `SAMPLER_SCRIPT_PATH`

## Tutorials

## Nota de versão

1. **0.0 Banana**

   *(Lançado Em 31 De Janeiro De 2022)*

   **Adicionado**

* [captura 3D] Criar objetos 3D a partir de imagens
* [captura 3D] Assistente de captura 3D dedicado
* [captura 3D] Importar ou gerar máscaras em preto e branco em seu conjunto de dados
* [captura 3D] Resultado do alinhamento - exibir todos os recursos correspondentes como uma nuvem de pontos
* [captura 3D] Resultado do alinhamento - visualize e interaja com câmeras associadas a cada foto alinhada
* [captura 3D] Definir a área de reconstrução com um widget de caixa delimitadora
* [captura 3D] Dimensionar, traduzir e girar em todos os eixos o widget da caixa delimitadora
* [captura 3D] Definir a precisão da geometria para a malha reconstruída
* [captura 3D] Otimize sua malha e texturas criando uma nova versão
* [captura 3D] Cada versão é automaticamente dizimada para o conjunto de números de faces de destino
* [captura 3D] A etapa de pós-processo automaticamente desembrulha, reprojeta texturas e, em seguida, faz bake as informações normais de height e AO da malha de alto polígono
* [captura 3D] Adicione o resultado original ou uma versão ao projeto do Sampler
* [captura 3D] Nova camada de pós-processamento de malha para dizimar, desempacotar, reprojetar texturas e fazer bake automaticamente os detalhes da camada de malha subjacente
* [captura 3D] Nova camada de Transformo de malha para dimensionar, girar ou traduzir a camada de malha subjacente
* [Exportar] Nova janela de exportação
* [Exportar] Configurações dedicadas e interface dependendo do tipo de ativo (material, iluminação do ambiente, malha)
* [Exportar] Exportar a malha como USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* [Exportar] Defina o tipo de material ao exportar arquivos de Substance (SBSAR, SBS)
* [UI] Mova as configurações do cache para uma nova guia no pop-up Preferências
* [Aplicativo] As viewports 2D e 3D agora podem ser redimensionadas, trocadas e empilhadas verticalmente
* [Aplicativo] Nova variável de ambiente SAMPLER\_RESOURCES\_PATH para adicionar ativos iniciais extras
* [Script] Adicionadas variáveis de ambiente SAMPLER\_PLUGIN\_PATH e SAMPLER\_SCRIPT\_PATH para importar plug-ins e scripts na inicialização
* [Script] Funções de exportação adicionadas para materiais, iluminações do ambiente e objetos 3D
* [Script] identificador adicionado, valor padrão, valores mínimos e máximos, rótulos e valores enum para parâmetros
* [Scripting] Foi adicionada a função importar\_textura para inserir um uso personalizado ao importar imagens

**Corrigido**

* [Aplicativo] Falha ao abrir um projeto recente e salvar na caixa de diálogo de confirmação
* A caixa de diálogo Arquivo [Aplicativo] impede a abertura de arquivos .ssa
* [Aplicativo] As caixas de diálogo de arquivo podem aparecer em uma janela de plano de fundo no macOS
* [Aplicativo] Possível falha ao abrir projetos 3.2
* [Aplicativo] Selecionar um arquivo fecha a caixa de diálogo Arquivo antes de exibir avisos
* [Parâmetros expostos] Exportar iluminações do ambiente paramétricas não funciona
* [Camadas] O link “Clique aqui para procurar” na pilha de camadas não funciona mais
* [Camadas] Às vezes, pintar várias imagens na mesma camada não funciona
* [Camadas] A configuração de uma imagem nas propriedades da camada não atualiza a miniatura do seletor de imagens
* [Camadas] Ajustar um ativo do Sampler adicionado como uma camada não funciona
* [Project] Atualização de ativo indesejado ao abrir um projeto
* [Script] A navegação para a pasta de plug-ins às vezes falha no Windows
* [Scripting] Falha ao usar &#39;open\_project()&#39; em um script Python
* [Scripting] A exportação de JPEG está ausente da API
* [Script] O painel de registro não é somente leitura
* [Script] o valor do parâmetro image\_picker não funciona
* [IU] Ícone de ativo ausente para iluminações do ambiente no painel Projeto
* [UI] A lista suspensa Enviar para formato do Designer no pop-up Preferências pode estar vazia
* [IU] Alguns botões têm um estilo incorreto
* [IU] O rótulo se sobrepõe aos botões nos widgets Grupo de botões
* [UI] A posição da dica de ferramenta está incorreta para “Ferramentas” no menu Definir o tamanho físico
* [UI] Ao alterar o idioma, o menu Arquivo fica desalinhado

**Problemas conhecidos**

* [captura 3D] Ao usar máscaras, a projeção de textura pode estar quebrada
* [captura 3D] Pequenos artefatos poderão aparecer no objeto se a escala no transformo Malha for muito pequena
* [captura 3D] A malha exportada pode ser muito pequena. Redefinir o dimensionamento da transformação e da reexportação da malha
* [Seletor de cores] Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* [Content] O widget de luz da forma não está funcionando no modo de projeção esférica
* [Interoperabilidade] O material com deslocamento enviado para o Stager perderá os controles do deslocamento
