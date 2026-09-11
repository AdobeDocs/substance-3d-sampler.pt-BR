---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/weave.html"
breadcrumb-title: ''
description: Use o gerador de tecelagem no Substance 3D Sampler para criar padrões de tecelagem de tecido e texturas têxteis para a criação de materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Weave
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Entrelaçar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '756'
ht-degree: 0%

---


# Entrelaçar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o filtro Entrelinha para converter imagens em padrões tecidos.

</td>
</tr>
</table>

## Parâmetros

**Predefinições**

Use predefinições para alterar rapidamente os parâmetros de visualização de diferentes estilos de trama

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A semente aleatória na qual todos os outros parâmetros aleatórios deste filtro se baseiam.
* **Imagem**: imagem/pincel\
  Selecione uma imagem ou tinta diretamente no **Visualização 2D**. O **filtro de tecelagem** funciona melhor quando uma imagem é selecionada.
* **Contagem de cores**: 1-10\
  O **filtro de tecelagem** divide automaticamente a entrada da imagem em várias cores com base nesse parâmetro. Os parâmetros de cada cor podem ser controlados de forma independente.
* **Tamanho da Área (cm)**: 2-50\
  Altere a tamanho físico que está sendo representada pelo espaço 2D. Isso mudará o número de pontos usados para recriar a imagem de entrada.
* **Densidade (Pontos por cm)**: 1-105\
  Trabalha com o controle **Tamanho da Área (cm)** para ajustar o número de pontos no espaço 2D.
* **Aspereza global**: 0-1.0\
  Ajustar a aspereza do material
* **Modo de Cores da Esquerda**:\
  Selecione se a Web será colorida com base na entrada da imagem ou em seleções de cores personalizadas. Se a opção **Substituir por cor** estiver selecionada, um parâmetro adicional de **Cor** aparecerá em cada Cor.

**Cor X**

O número de cores disponíveis para modificação depende de **Parâmetros básicos > Contagem de cores**.

* **Cor**: seleção de cor\
  Disponível apenas se o **Parâmetros Básicos > Modo de Cores de Texto** estiver definido como **Substituir por Cor**. Escolha a cor do material desta seção.
* **Tamanho da borda**: 0-1\
  Adicionar uma borda nas bordas da cor selecionada. A borda aumenta o comprimento da trama entre os fios de distorção próximos à borda da cor, evitando que os pontos de distorção apareçam próximos à borda dos conjuntos de cores.
* **Deslocamento de aspereza**: 0-1\
  Modificar a aspereza para este conjunto de cores
* **Metálico**: 0-1\
  Modificar o valor metálico deste conjunto de cores
* **Posição do Height**: 0-1\
  Ajuste o height deste conjunto de cores. Use isso para adicionar profundidade à versão tecida da imagem.

**Avançado**

* **Cor de distorção**: seleção de cor\
  Alterar a cor dos encadeamentos de distorção (por padrão, os encadeamentos de distorção são executados perpendicularmente aos encadeamentos mais visíveis.)
* **Distorção - Troca De Trama**:\
  Troque quais segmentos são distorcidos e quais são tramas. Isto tem o efeito de girar os pontos em 90 graus,
* **Eixos de Distorção**: 1-16\
  Ajuste a frequência relativa de segmentos de distorção para segmentos de trama. Pode ser usado para criar diferentes padrões de jacquard.
* **Tamanho da Distorção**: 0-1\
  Torne os fios de distorção mais espessos ou mais finos
* **Intensidade de desfoque da diferença do Height**: 0-1\
  Controle a inclinação ou desfoque causado pelas diferenças de **Posição da Height**. Isso não tem efeito a menos que você altere o controle deslizante **Posição do Height** para pelo menos um conjunto de Cores.

## Guia de Uso

O filtro Entrelinha pode ser um pouco confuso no início, mas com apenas alguns parâmetros importantes para começar, você logo estará criando entrelinhas complexas para adicionar aos seus materiais.

>[!NOTE]
>
> Se você já usou o filtro [Bordado](embroidery.md)antes, o filtro Tecido funciona de maneira semelhante. Eles produzem efeitos diferentes, mas você pode usar imagens com eles da mesma maneira.
> 
> As imagens para entrelaçamento devem ser proporções quadradas, de alta resolução (mínimo de 2K) e apresentar no máximo 10 cores diferentes. O canal alfa ou de transparência pode ser usado para recortar formas. O ideal é que eles sejam baseados em vetor, mas exportados como bitmap PNG.

Para usar o filtro Entrelinha:

1. Arraste e solte uma imagem em
1. Adicione o filtro Entrelinha à sua pilha de camadas.
1. Ajuste **Parâmetros básicos > Contagem de cores** até que o equilíbrio de cores pareça correto para a imagem. Com um limite de 10 cores, o filtro Entrelinha funciona melhor com cores planas e imagens ilustradas.
1. Ajuste outros parâmetros para ajustar a aparência da correção.

Estas são as noções básicas sobre como usar o filtro Entrelinha.

É possível usar imagens transparentes no filtro de tecelagem, mas, por padrão, elas também afetarão o mapa de opacidade do seu material. Partes transparentes da imagem também tornarão o material transparente. Para criar uma correção com o filtro Transição e colocá-la em cima das camadas abaixo dela, use o filtro Decalque.

1. Crie um filtro de decalque.
1. Adicione o filtro Tena ao slot de entrada do filtro Decalque.
1. Siga as etapas normais para ajustar o padrão de tecelagem.

A camada de decalque converte a entrada da tecelagem em um decalque. Portanto, a transparência da camada de tecelagem diz à camada de decalque como mascarar o padrão tecido. Com a camada Decalque, você também pode mover o padrão no material ou ativar funcionalidades como divisão em blocos gráficos.
