---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/getting-started/export/export-window.html"
breadcrumb-title: ''
description: Saiba como usar a janela de exportação no Substance 3D Sampler para configurar e exportar materiais em vários formatos e predefinições.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Export Window
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Janela de exportação
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '737'
ht-degree: 0%

---


# Janela de exportação

Você pode exportar seu ativo do painel <b>Exportar</b> na <b>barra Direita</b>.

As opções de exportação dependem do tipo de ativo que está sendo exportado.

![Uma imagem da janela de exportação](../../../assets/6.0_ExportWindowMaterialSettings.png)

A janela Exportar para uma exportação de material.

>[!NOTE]
>
> O painel Exportar também tem opções para Enviar seus ativos para o Substance 3D Designer, Painter ou Stager. Isso exportará automaticamente seu ativo com as configurações corretas para outros aplicativos da Substance 3D.

## Configurações gerais

As configurações a seguir estão disponíveis para todos os tipos de ativos.

* <b>Nome: </b>Este campo define o nome do ativo que você está exportando. Será usado como um prefixo no nome do arquivo dos arquivos exportados.
* <b>Salvar em: </b>Selecione o destino de exportação do ativo. Opcionalmente, você também pode criar uma subpasta no local escolhido. A subpasta será nomeada em homenagem ao seu ativo se esta opção estiver ativada.

## Configurações de material

Ao exportar materiais, o painel Configurações de material da janela Exportar tem as seguintes opções:

* <b>Formato</b>: selecione um formato de arquivo para o ativo exportado.
  * <b>SBSAR</b>: exporte seu material para uso em qualquer aplicativo que ofereça suporte a materiais Substance.
  * <b>SBS</b>: exporte seu material para que ele possa ser aberto no Substance 3D Designer.
  * <b>EXR, JPEG, PNG, TARGA, TIFF</b>: exporte o material como uma coleção de arquivos de imagem.

>[!NOTE]
>
> A profundidade de bits é forçada a 16 bits para os canais Normal e Height. Outros canais são exportados em 8/16 bits, dependendo dos materiais e filtros usados. Dependendo do formato do arquivo, a profundidade de bits pode ser alterada, pois alguns formatos de arquivo não oferecem suporte a alta profundidade de bits.

![](../../../assets/export-format.png){width="400px"}

* <b>Predefinição </b>(EXR, JPEG, PNG, TARGA, TIFF): selecione uma predefinição para configurar automaticamente a exportação de arquivo para um determinado aplicativo ou pipeline.
  * A opção <b>Padrão (fluxo de trabalho do projeto)</b> mostra uma lista de todos os canais disponíveis do(s) seu(s) material(is) sem nenhuma predefinição aplicada.
  * Use o botão <b>Gerenciar predefinições </b> à direita do parâmetro Predefinições para editar predefinições ou adicionar suas próprias predefinições.<b> </b>
  * [Mais informações sobre as Predefinições estão disponíveis aqui.](../managing-presets.md)

>[!NOTE]
>
> A seleção de predefinição não está disponível quando o formato de exportação é SBS ou SBSAR. Para esses formatos, o arquivo de saída já está configurado para ser utilizável em todos os produtos Substance e integrações de Substance.

* <b>Tipo de material </b>(SBSAR, SBS): selecione se o material exportado se comporta como um material padrão, decalque ou atlas. Essa configuração pode alterar como é tratada por outros aplicativos que suportam arquivos SBSAR e SBS.

![](../../../assets/screenshot-2023-01-24-at-16-32-58.png)

* <b>Compactação </b>(SBSAR, SBS): selecione como o arquivo exportado será compactado
  * <b>Automático</b>: permita que o Sampler determine as configurações de compactação.
  * <b>Ideal</b>: essa opção resulta em arquivos menores, mas também pode significar tempos de carregamento e salvamento mais longos enquanto o arquivo está codificado ou decodificado.
  * <b>Nenhum</b>: sem a compactação, os arquivos serão maiores, mas serão carregados e salvos mais rapidamente.
* <b>Resolução (</b>SBSAR, SBS<b>)</b>: selecione uma resolução de saída para o material.
  * Por padrão, a resolução é baseada nos parâmetros globais do Sampler. Se você selecionar uma resolução diferente, o Sampler recalculará todos os seus materiais com essa nova resolução. Ela pode afetar a aparência final do(s) material(is).

![](../../../assets/SAPR_ResolutionSBSAR.png)

* <b>Resolução </b>(Formatos de imagem): selecione se a resolução de cada camada é exportada de forma independente ou substitua a resolução para que todas as camadas sejam exportadas em um tamanho uniforme. Se a opção Substituir tudo estiver selecionada, serão exibidas opções para modificar a resolução da saída.
  * Por padrão, a resolução é baseada na resolução de saída de cada camada. Se você selecionar uma resolução diferente, o Sampler recalculará todos os seus materiais com essa nova resolução. Ela pode afetar a aparência final do(s) material(is).

![](../../../assets/SAPR_ResolutionTextures.png)

* **Modelo de material** (Todos os formatos enquanto estiver na predefinição padrão): selecione um padrão de sombreador para as texturas exportadas.
  * Alterar o Modelo de material afetará os nomes dos arquivos exportados. Por exemplo, OpenPBR usa “Metalness” em vez de ASM que usa “Metallic”.

### Informações adicionais

O espaço em disco disponível na unidade de destino selecionada é visível na parte inferior da <b>janela Exportar</b>.

>[!NOTE]
>
> O <b>Tamanho físico</b> é definido durante a criação do material e não pode ser modificado durante a exportação.

### Canais

![](../../../assets/SAPR_Channelspreview.png)

No lado direito do <b>painel Configurações de material</b>, uma lista de canais que podem ser exportados e suas resoluções estão visíveis (canais padrão e canais personalizados).

Cada predefinição tem um conjunto diferente de canais para exportar, e o nome dos arquivos exportados se baseia nos nomes visíveis na área <b>Canais para exportar</b>. É possível usar a caixa de seleção ao lado de qualquer canal para ativar ou desativar a exportação para esse canal.

![](../../../assets/SAPR_Channels_ExportPreset.gif)
