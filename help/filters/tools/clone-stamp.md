---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/clone-stamp.html"
breadcrumb-title: ''
description: Use a ferramenta Carimbo de Clonar no Substance 3D Sampler para clonar e tinta áreas de textura para obter edição e reparo de material perfeitos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Clone Stamp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Carimbo de Clonar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---


# Carimbo de Clonar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-clonestamp-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

A **ferramenta Carimbo de Clonar** ajuda você a duplicar ou corrigir manualmente partes do seu material. Isso é útil para corrigir emendas ou remover erros do material. O **filtro Carimbo** é uma das ferramentas disponíveis na barra lateral esquerda.

As imagens abaixo mostram o **Clonar Stamp** sendo usado para remover detritos de um material de neve.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

Na imagem acima, o material da neve inclui uma série de galhos e outros detritos espalhados ao redor.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

A ferramenta **Carimbo de Clonar** é usada para remover alguns galhos e substituí-los por neve limpa.

</td>
</tr>
</table>

## Tutorial sobre carimbo de Clonar

## Parâmetros

<b>Parâmetros básicos</b>

* <b>Expandir máscara</b>: 0-1\
  Ajuste a distância em torno da área pintada em que o filtro tentará corresponder ao material subjacente.
* <b>Mesclagem de atenuação</b>: 0-1\
  Suavize a borda da área clonada para ajudar a misturar com o material subjacente.
* <b>Máscara de desfoque</b>: 0-1\
  Ajuste a quantidade de detalhes da borda do carimbo. Aumentar esse valor fará com que as bordas da área clonada fiquem mais semelhantes a bolhas.
* <b>Manter proporção</b>: alternar\
  Quando desativada, esta opção permite ajustar as proporções da área estampada.
  * <b>Horizontal</b>: 0-2
  * <b>Vertical</b>: 0-2
* <b>Rotação</b>: -180 a 180\
  Gire a área estampada.
* <b>Virar horizontalmente</b>: alternar\
  Espelha a área estampada ao longo de um eixo horizontal.
* <b>Virar verticalmente</b>: alternar\
  Espelha a área estampada ao longo de um eixo vertical.

<b>Mesclagem de atenuação</b>

Use os controles de mesclagem de atenuação para ajustar individualmente a mesclagem de atenuação para cada canal no material.

<b>Avançado</b>

* <b>Intensidade normal</b>: 0-2\
  Ajuste a intensidade dos normais na área estampada.
* <b>Posição de origem</b>: \
  0-1: ajuste a posição horizontal da origem.\
  0-1: ajuste a posição vertical da origem.
* <b>Posição de destino</b>:\
  0-1: ajuste a posição horizontal de destino.\
  0-1: ajuste a posição vertical de destino.
* <b>Modo lado a lado</b>: lista suspensa\
  Habilitar ou desabilitar divisão em blocos.

## Guia de Uso

Clique na **ferramenta Carimbo de Clonar** para criar uma nova camada de filtro Carimbo de Clonar na parte superior da pilha de camadas. Você também pode adicionar um filtro de Clonar Stamp usando o **botão Adicionar uma camada** no **painel Camadas**.

Criar uma camada de filtro Carimbo de Clonar abre automaticamente o **Visualização 2D** no **Viewport**. Uma **Barra de ferramentas** aparece na parte superior do **Visualização 2D** quando a camada de Carimbo de Clonar está selecionada.

![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

Para começar a usar a ferramenta Carimbo de Clonar, clique e arraste sobre a área problemática no **Visualização 2D**. O material começará a ser atualizado automaticamente com base na origem. As áreas em que você usa a **ferramenta Carimbo** são realçadas.

## Barra de ferramentas

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Quando a camada de carimbo de Clonar está selecionada, uma barra de ferramentas aparece no Visualização 2D com controles adicionais.

* Selecione a <b>ferramenta Pincel </b> para adicionar à máscara ou a <b>ferramenta Apagar </b> para remover da máscara.
* Define o tamanho da ferramenta atualmente selecionada.
* Controles adicionais de acesso:
  * <b>Divisão de pincel</b>: \
    Alterna a divisão em blocos gráficos do pincel X e Y.
  * <b>Sobreposição:</b>\
    Se marcada, a sobreposição é exibida ao passar o mouse sobre a Visualização 2D.
* Exibir controles Visualização 2D.

</td>
</tr>
</table>

>[!NOTE]
>
> Assim como outras barras de ferramentas da viewport, você pode arrastar a alça na parte superior da barra de ferramentas para reposicionar a barra de ferramentas dentro da viewport, clicar duas vezes na alça para alternar entre os modos vertical e horizontal ou usar a divisa dupla para ocultar ou expandir a barra de ferramentas.

## Seleção de Origem

Use Ctrl + clique na visualização 2D para adicionar uma nova fonte. Adicionar uma nova origem criará um carimbo adicional abaixo da camada Carimbo de Clonar no <b>painel Camadas</b>. Você pode controlar cada estampa individualmente.

>[!NOTE]
>
> Normalmente, é uma boa ideia tentar evitar que o ponto de origem fique próximo à área que você está clonando. Se o ponto de origem estiver próximo à área problemática, será possível clonar essa área.

## Atalhos

| Ação | Windows + Linux | MacOs |
| --- | --- | --- |
| Aumentar tamanho do pincel | ] ou Ctrl + Roda do mouse | ] ou Cmd + Roda do mouse |
| Diminuir tamanho do pincel | [ ou Ctrl + Roda do mouse | [ ou Cmd + Roda do mouse |
| Definir a origem | Ctrl + clique com o botão esquerdo | Cmd + clique com o botão esquerdo |
