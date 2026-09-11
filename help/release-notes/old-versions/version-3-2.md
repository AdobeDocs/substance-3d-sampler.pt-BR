---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-2.html"
breadcrumb-title: ''
description: Revise as notas de versão do Substance 3D Sampler versão 3.2 para saber mais sobre o fluxo de trabalho de digitalização de material, novos filtros e metadados personalizados.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.2
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 3.2
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1058'
ht-degree: 0%

---


# Versão 3.2

O **Substance 3D Sampler 3.2** apresenta um fluxo de trabalho de digitalização de material completo que captura e processa o tamanho físico de material, novos filtros como Tecido de pano e Comutador de canal e a capacidade de criar metadados personalizados.

Data de lançamento: 25 *janeiro de 2022*

## Principais recursos

### Tamanho físico

Um novo fluxo de trabalho de digitalização de material que captura e processa o tamanho físico de materiais foi introduzido nesta versão.

Corresponda o [tamanho físico](../../features-and-workflows/end-to-end-physical-size-workflow.md) real de suas amostras/imagens em um contexto digital para criar materiais fisicamente precisos em qualquer software.

![](../../assets/physicalsize-1.png){width="400px"}

### Tecido

O novo gerador foi adicionado nesta versão. A tecelagem de pano permite que você crie e projete tecidos de pano com padrões de tecelagem personalizados.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/weavecollection.png){width="390px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/weaveinterface.png){width="400px"}

</td>
</tr>
</table>

### Metadados personalizados

Adicione metadados personalizados aos seus materiais. Todos os metadados personalizados serão incluídos no arquivo de material (SBSAR) para garantir um fluxo de trabalho mais eficiente para compartilhar materiais digitais entre aplicativos.

![](../../assets/custommetadata.png){width="264px"}

### Comutador de canal

Com o Switch de canal, agora você pode alternar os canais dos mapas de saída do material.

![](../../assets/screenshot-2022-02-15-at-15-53-00.png){width="300px"}

### Exportar

Novos recursos de exportação foram adicionados a esta versão.

* Definir configuração de compactação do arquivo .sbsar

  ![](../../assets/compressionsbsar.png){width="400px"}
* Definir o tipo de gráfico ao exportar um arquivo .sbs(ar)
* Manter proporção física para EXR, JPEG, PNG, TARGA, TIFF

  ![](../../assets/screenshot-2022-02-16-at-15-28-09.png){width="400px"}

## Notas de versão

### 3.2.0 Yakitori

*(Lançado Em 25 De Janeiro De 2022)*

**Adicionado:**

* [Tamanho físico] Novo painel Tamanho físico
* [Tamanho físico] Adicionar opções de Tamanho físico à janela Modelo de Criação de Material
* [Tamanho físico] Ferramenta Adicionar medida de Tamanho físico
* [Tamanho físico] Ferramenta Adicionar medida automática do Tamanho físico
* [Tamanho físico] Adicionar ferramenta de diagnóstico de Tamanho físico
* [Tamanho físico] Permite definir o valor z do Tamanho físico
* [Tamanho físico] Widget de lista suspensa para definir o nível de zoom no Visualização 2D
* [Tamanho físico] Nova opção “Exibição com proporção física” no nível do menu suspenso de zoom
* [Tamanho físico] Nova opção “Ajustar ao tamanho físico” no menu suspenso de nível de zoom
* [Tamanho físico] Exibir o Tamanho físico no Visualização 2D
* [Tamanho físico] Exibir a Tamanho físico na viewport 3D
* [Tamanho físico] Na caixa de diálogo de importação de imagem, mostrar profundidade de tamanho físico se houver um mapa de altura importado
* [Tamanho físico] Mostrar o Tamanho físico no menu contextual do ativo
* [Tamanho físico] Defina a unidade de comprimento nas Preferências
* [Tamanho físico] Exportar texturas respeitando a proporção física
* [Metadados] Capacidade de adicionar metadados personalizados a um ativo criado pelo usuário
* [Exportar] Exportar metadados personalizados para arquivos .sbs(ar)
* [Exportar] Exportar metadados de descrição, categoria, autor e marcas para arquivos .sbs(ar)
* [Exportar] Exporta o Tamanho físico para arquivos .sbs(ar)
* [Exportar] Definir configuração de compactação do arquivo .sbsar
* [Exportar] Exportar a miniatura do ativo para arquivos .sbs(ar)
* [Exportar] Define o tipo de gráfico ao exportar um arquivo .sbs(ar)
* O mecanismo em tempo real [Application] 2021 não está mais disponível
* [Aplicativo] Desfazer/Refazer agora suporta mudanças de controle deslizante Lado a lado (U, V) e escala de height
* [Renderização] Gerar cache de disco quando o ativo criado for salvo
* [Ativos] Use Ctrl+clique para habilitar vários filtros de tipo de ativo no painel Recursos
* [UI] Capacidade de bloquear os controles deslizantes de divisão em blocos (U, V)
* [UI] Adicionar um menu contextual com “Copiar”, “Recortar”, “Colar”, “Copiar tudo” e “Recortar tudo” em campos de texto
* [IU] Unidade de comprimento (metros, polegadas, parsecs, etc.) suporte em rótulos e campos de texto
* [UI] O usuário pode definir a precisão decimal usada para exibir números
* [UI] Use unidades em pop-ups de medida sempre que for relevante
* [Localização] O nome padrão do novo ativo agora está localizado
* [Conteúdo] Novo gerador de tecelagem de pano
* [Content] Novo filtro de Comutação de Canal
* [Conteúdo] Todos os filtros relevantes agora estão cientes do Tamanho físico
* [Conteúdo] Novos ícones para acabamento de madeira
* [Content] Todos os filtros agora são compatíveis com canais Adobe Standard Material (ASM)
* Os filtros do [Content] agora podem ter uma variação de “ambiente”

**Corrigido:**

* [Visualização 2D] O canal permanece na lista quando removido
* [Aplicativo] Não é possível duplicar um ativo carregado do explorador de arquivos do sistema operacional
* [Application] Falha ao sair
* [Aplicativo] Às vezes, falha ao clicar em “Ativos iniciais” no painel Ativos
* [Aplicativo] Falha ao excluir um material
* [Application] A variável de ambiente “SUBSTANCE\_DISABLE\_SPECIFIC\_FEATURES” ainda está ativa quando definida como “0” ou “”.
* [Aplicativo] Congela ao salvar um projeto com vários materiais
* [Aplicativo] Importar uma imagem pode levar a uma falha
* [Aplicativo] Ativos iniciais ausentes na primeira inicialização
* [Exportar] Exportar um ativo às vezes leva a uma falha
* [Camadas] Não é possível importar imagens quando o painel de camadas está fechado ou invisível
* [Camadas] Alterar o idioma faz com que o ativo atual seja recalculado
* [Camadas] Alterar o uso de uma imagem importada não atualiza qual variação de filtro usar
* [Camadas] A imagem para material (AI) às vezes não é calculada ao ajustar as camadas abaixo dela
* [Camadas] A imagem para material (AI) às vezes recalcula quando não é necessário
* [Camadas] Nenhuma atualização é sugerida quando um filtro personalizado é atualizado no disco
* [Camadas] Às vezes, o canal normal tem um formato de pixel incorreto
* [Camadas] Algumas camadas ainda são computadas mesmo quando não visíveis
* [Camadas] As ferramentas podem ser quebradas ao alternar a visibilidade de uma camada
* [Camadas] A interface do usuário congela ao usar a Imagem para material (AI)
* [Camadas] Alternar a visibilidade da camada de filtro Transformo interrompe a ferramenta Visualização 2D e pode levar a um travamento
* [Camadas] Muitos recálculos ao remover uma camada da pilha de camadas
* [Camadas] Quando um filtro composto contém uma entrada/saída incomum ou personalizada, o Sampler não o calcula
* [Desempenho] O painel de ativos é lento para abrir
* [Desempenho] Evite alguns recálculos desnecessários da pilha de camadas
* [Desempenho] Carregar ativos do projeto leva muito tempo
* [Desempenho] O cache de renderização no disco não pode ser usado
* [Desempenho] Alternar entre camadas é lento
* [Desempenho] Ajustar um material ou filtro é lento
* [Projeto] Salvar um projeto ao sair pode levar a uma falha
* [Renderização] Remover uma imagem pode remover todas as saídas
* [Renderização] O tempo de renderização exibido no visor está incorreto ao ajustar
* [IU] Não é possível rolar verticalmente no pop-up de exportação quando necessário
* [IU] É possível abrir o pop-up de exportação quando não há nada para exportar
* [IU] Alguns pop-ups não rolam se seu conteúdo transbordar
* [UI] Os campos de texto não são selecionados ao clicar neles ou abrir menus
* [UI] O nome do modo de mesclagem no painel de propriedades às vezes não está correto
* [UI] A opção Salvar no menu Arquivo às vezes fica esmaecida
* [IU] O campo de texto não desaparece após renomear dois materiais
* [UI] Erro de digitação no pop-up de preferência

**Problemas Conhecidos:**

* [Seletor de cores] Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
