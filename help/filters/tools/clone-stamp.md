---
description: Use a ferramenta Carimbo de Clonar no Substance 3D Sampler para clonar e tinta áreas de textura para obter edição e reparo de material perfeitos.
title: Carimbo de Clonar
source-git-commit: 09278e59a21757710d15d1bb447002a4aecb25a7
workflow-type: tm+mt
source-wordcount: '872'
ht-degree: 1%
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

A ferramenta **Carimbo de Clonar** permite duplicar ou corrigir manualmente partes do material. É usado principalmente para corrigir emendas e remover erros de materiais digitalizados, como detritos, sombras ou artefatos. Você pode tinta vários traçados de carimbo de diferentes áreas de origem em uma única camada de Carimbo de Clonar e gerenciar cada carimbo individualmente no **painel Camadas**.

As imagens abaixo mostram o **Clonar Stamp** sendo usado para remover detritos de um material de neve.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

O material da neve inclui uma série de galhos e outros detritos espalhados ao redor.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

Depois de usar a ferramenta **Clonar Stamp**, os galhos são substituídos por neve limpa.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Expandir máscara**: 0-1

  Ajuste a distância em torno da área pintada em que o filtro tentará corresponder ao material subjacente.

* **Mesclagem de atenuação**: 0-1

  Suavize a borda da área clonada para se misturar mais naturalmente com o material ao redor.

* **Máscara de desfoque**: 0-1

  Ajuste a quantidade de detalhes de aresta no carimbo. Valores mais altos produzem bordas mais suaves, semelhantes a bordas.

* **Manter proporção**: alternar

  Quando desativada, esta opção permite ajustar as proporções horizontal e vertical da área estampada de maneira independente.

  * **Horizontal**: 0-2
  * **Vertical**: 0-2
* **Rotação**: -180 a 180

  Gire a área estampada para corresponder à direção ou granulação do material ao redor.

* **Virar horizontalmente**: alternar

  Espelha a área estampada ao longo de um eixo horizontal.

* **Virar verticalmente**: alternar

  Espelha a área estampada ao longo de um eixo vertical.

**Mesclagem de atenuação**

Use os controles de mesclagem de atenuação por canal para ajustar de forma independente a intensidade da mesclagem para cada canal de material.

**Avançado**

* **Intensidade normal**: 0-2

  Ajuste a intensidade do mapa normal na área estampada para controlar como a superfície clonada responde à iluminação.

* **Posição de origem**:
  * Horizontal: 0-1 — Ajuste a posição horizontal da origem do clone.
  * Vertical: 0-1 — Ajuste a posição vertical da origem do clone.
* **Posição de destino**:
  * Horizontal: 0-1 — Ajuste a posição horizontal do destino da tinta.
  * Vertical: 0-1 — Ajuste a posição vertical do destino da tinta.
* **Modo lado a lado**: lista suspensa

  Ativa ou desativa a divisão em blocos gráficos ao clonar perto das bordas do material.

## Como usar o Clonar Stamp

1. Clique no **Carimbo de Clonar** na barra lateral esquerda ou adicione-o pelo botão **Adicionar uma camada** no **painel Camadas**. Uma nova camada de Carimbo de Clonar aparece na parte superior da pilha de camadas e o **Visualização 2D** abre automaticamente.

1. **Definir um ponto de origem**: segure `Ctrl` (`Cmd` no macOS) e clique em uma área limpa do material no **Visualização 2D**. Define a região que será copiada.

   > 📸 CAPTURA DE TELA [ID: clone-stamp-001]
   > Mostrar: viewport 2D com uma mira de ponto de origem visível em uma área limpa de um material de neve
   > Estado: camada de carimbo de Clonar selecionada; Ctrl pressionada; indicador de origem visível
   > Anotação: Rotular a mira de origem

1. **Tinta sobre a área com problema**: clique e arraste sobre a área que deseja corrigir. O material do ponto de origem substitui a área pintada em tempo real.

   ![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

1. Ajuste a **Mesclagem de atenuação** e a **Máscara de expansão** no **painel Propriedades** para ajustar a forma como a área clonada se mescla com seus arredores.

>[!NOTE]
>
> Evite colocar o ponto de origem próximo à área que está sendo clonada. Se a origem se sobrepuser à área com problema, o artefato poderá ser clonado junto com o conteúdo limpo.

## Trabalhar com várias fontes

É possível adicionar vários pontos de origem em uma única camada de carimbo de Clonar, cada um com suas próprias configurações de posição, rotação e mesclagem. Isso permite que você corrija várias áreas diferentes, ou desenhe a partir de várias regiões limpas diferentes, sem empilhar várias camadas.

Para adicionar uma nova origem, mantenha pressionado `Ctrl` (`Cmd` no macOS) e clique em uma nova área no **Visualização 2D**. Uma nova entrada de carimbo aparece abaixo da camada Carimbo de Clonar no **painel Camadas**.

> 📸 CAPTURA DE TELA [ID: clone-stamp-002]
> Mostrar: o painel Camadas com uma camada de carimbo de Clonar expandida, mostrando três entradas de carimbo individuais aninhadas abaixo dele
> Estado: camada de carimbo de Clonar expandida; três carimbos visíveis com posições de origem diferentes
> Anotação: seta apontando para as entradas de carimbo aninhadas no painel Camadas

Selecione qualquer entrada de carimbo individual no **painel Camadas** para ajustar seus parâmetros de forma independente no **painel Propriedades**, incluindo a posição de origem, a rotação e as configurações de mesclagem.

>[!TIP]
>
> Use a **visualização de pincel** em **Visualização 2D** para ver o resultado do carimbo antes de confirmar um traçado. Isso ajuda a verificar se a região de origem corresponde à área ao redor antes de pintar.

## Barra de ferramentas

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Quando uma camada de Carimbo de Clonar está selecionada, uma barra de ferramentas aparece no **Visualização 2D**.

* Selecione a **ferramenta Pincel** para adicionar à máscara.
* Selecione a **ferramenta Apagar** para remover da máscara.
* Define o tamanho da ferramenta atualmente selecionada.
* Controles adicionais de acesso:
  * **Divisão em blocos gráficos do pincel**: alterne a divisão em blocos gráficos X e Y.
  * **Sobreposição**: alterne a visibilidade da sobreposição ao passar o mouse sobre a Visualização 2D.
* Exibir **controles Visualização 2D**.

</td>
</tr>
</table>

>[!NOTE]
>
> Como outras barras de ferramentas da viewport, você pode arrastar a alça na parte superior da barra de ferramentas para reposicioná-la, clicar duas vezes na alça para alternar entre o layout vertical e horizontal ou usar a divisa dupla para ocultá-la ou expandi-la.

## Atalhos

| Ação | Windows + Linux | macOS |
| --- | --- | --- |
| Aumentar tamanho do pincel | `]` ou `Ctrl` + Roda do Mouse | `]` ou `Cmd` + Roda do Mouse |
| Diminuir tamanho do pincel | `[` ou `Ctrl` + Roda do Mouse | `[` ou `Cmd` + Roda do Mouse |
| Definir a origem | `Ctrl` + clique com o botão esquerdo | `Cmd` + clique com o botão esquerdo |

## Relacionado

* [Distorcer](./warp.md)
* [Torná-lo lado a lado](./make-it-tile.md)
* [Imagem para material](./image-to-material.md)
