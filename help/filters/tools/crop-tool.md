---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/crop-tool.html"
breadcrumb-title: ''
description: Use a ferramenta Corte demarcado no Substance 3D Sampler para cortar e redimensionar texturas e camadas de material com controle preciso sobre as dimensões.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Crop tool
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ferramenta Corte demarcado
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '707'
ht-degree: 0%

---


# Ferramenta Corte demarcado

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-crop-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use a **ferramenta Corte demarcado** para ajustar o corte da imagem ou do material. A **ferramenta Cortar** funciona de forma muito semelhante à **ferramenta Transformar**. Com a **ferramenta Transformar**, as alterações na caixa transformar se comportam de uma para uma maneira com a imagem subjacente, portanto, aumentar a escala da caixa Transformar aumenta o tamanho da imagem subjacente. Com a **ferramenta Cortar**, essa relação é invertida, o aumento da escala da caixa Cortar diminui o tamanho da imagem subjacente. Por esse motivo, ao usar a **Ferramenta Corte demarcado**, pode ser útil definir o **Visualização 2D** para exibir Entradas de camada, em vez das Saídas de material padrão.

A **ferramenta Corte demarcado** é útil para fazer ajustes em imagens que têm proporções não padrão. Por exemplo, você pode usar a ferramenta recortar para ajustar a escala de uma imagem importada por meio dos parâmetros de Tamanho de Entrada no **painel Propriedades**.

>[!NOTE]
>
> Observe que a **ferramenta Corte demarcado** pode funcionar em imagens ou materiais. Se houver uma imagem ou um canal de digitalização na pilha de camadas sob a **camada de Corte**, o **filtro de Corte** será aplicado ao canal de Digitalização. Se não existir nenhuma imagem ou canal de digitalização, o **filtro de Corte** modificará o material.

Nas imagens abaixo, você pode ver a **Ferramenta Corte demarcado** em ação.

![](../../assets/3d-2d-filters-cropped-0047-crop-in.jpg)

Observe que a Visualização 2D está definida para exibir Entradas de Camada para que as alças na **Visualização 2D** mostrem qual área da entrada se tornará a saída.

![](../../assets/3d-2d-filters-cropped-0046-crop-out.jpg)

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Tamanho de entrada**: 0-8192\
  Ajuste o tamanho da entrada em pixels nos eixos X e Y.

**Parâmetros avançados**

* **Filtragem**:\
  Selecione o método de filtragem aplicado aos pixels redimensionados. A filtragem bilinear desfoca os pixels uns nos outros, enquanto a filtragem mais próxima mantém as bordas dos pixels.
* **Transformo de corte**: 0-1\
  Modifique os valores de matriz do transformo. A edição desses valores pode fornecer um controle mais preciso sobre a rotação e o dimensionamento, além de permitir que você incline as alças de corte.
* **Deslocamento de corte**: 0-1\
  Desloque o corte da posição inicial.

## Guia de Uso

>[!NOTE]
>
> O filtro Cortar tem sua própria resolução e corta e gera a resolução adequada dependendo do material ou da imagem cortada. Para manter os melhores resultados, coloque as camadas acima no Input Max e use um Upscale para ampliar os resultados finais.

Clique na **ferramenta Corte demarcado** para adicionar uma nova camada de filtro de Corte demarcado à parte superior da pilha de camadas.

Criar ou selecionar uma camada de filtro de corte abre automaticamente o **Visualização 2D**. Com a camada Cortar selecionada, uma barra de ferramentas aparece na parte superior do **Visualização 2D**.

## Funcionalidade

>[!NOTE]
>
> O filtro Corte demarcado executa o inverso do movimento, da escala ou da rotação solicitada. Se você achar que o filtro Cortar não está correto, pode achar o filtro Transformar mais útil.

### Mover

Para mover a camada:

1. Passe o mouse dentro da caixa de transformo
1. Seu cursor mudará para quatro setas
1. Clique e arraste para mover a caixa do transformo.

### Dimensionar

Para dimensionar a camada:

1. Passe o mouse sobre uma das alças na borda ou no canto da caixa de transformação
1. Seu cursor mudará para quatro setas.
1. Clique e arraste para dimensionar a caixa de transformo.

>[!NOTE]
>
> As alças no canto da caixa de transformo permitirão dimensionar em duas dimensões de uma só vez, enquanto as alças na borda da caixa de transformo limitarão o dimensionamento em uma dimensão.

### Girar

Para girar a camada:

1. Passe o mouse fora da caixa de transformo, mas dentro do **Visualização 2D**.
1. Uma pequena seta horizontal aparecerá ao lado do cursor.
1. Clique e arraste para girar a caixa do transformo.

>[!NOTE]
>
> É possível alterar o centro da rotação arrastando o pequeno círculo no centro da caixa do transformo. A caixa de transformo sempre gira em torno desse círculo.

## Barra de ferramentas

![](../../assets/transform-toolbar.png){width="200px"}

A barra de ferramentas contém os seguintes atalhos:

* Tornar quadrado: ajuste o dimensionamento da transformação atual para torná-la quadrada.
* Rotação +90° (para a direita): rotação de 90° no sentido horário.
* Rotação -90° (para a esquerda): rotação de 90° no sentido anti-horário.
* Redefinir centro de rotação: redefina o centro de rotação para o centro da caixa do Transformo.
* Redefinir transformação: redefine a ferramenta Transformar para a posição padrão.
