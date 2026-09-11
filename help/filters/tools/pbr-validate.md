---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/pbr-validate.html"
breadcrumb-title: ''
description: Use a ferramenta Validação do PBR no Substance 3D Sampler para validar e garantir que os materiais atendam aos padrões de renderização físicos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > PBR Validate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Validação do PBR
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '653'
ht-degree: 0%

---


# Validação do PBR

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pbrvalidate-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o **filtro de Validações do PBR** para garantir que os valores de PBR do material estejam corretos. Ao contrário da maioria dos filtros, o **filtro de Validações do PBR** não deve ser uma parte permanente da pilha de camadas. Em vez disso, use-o para validar seu material e removê-lo para que ele não o modifique.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Modo de Validação**:\
  Selecione se os valores de albedo (cor de base ou difuso), os valores metálicos ou os valores de albedo e metálico serão validados. Outros parâmetros serão atualizados com base nesta seleção
  * **Modo de Validação: Albedo**
    * **Limite de Intervalo Escuro do Albedo**:\
      Defina o limite para valores escuros a serem escolhidos pelo filtro como inválidos.
    * **Sobrepor Mapa**: alternar\
      Alternar entre os modos de sobreposição - se habilitado, o mapa de cor de base será sobreposto pelos pixels inválidos.
    * **Ocultar Validação na Cor de base**: alternar\
      Ocultar as informações de validação do canal de cor de base.
  * **Modo de Validação: Metal**
    * **Intervalo de Reflexão Metálica**:\
      Defina o intervalo de valores de refletância a ser selecionado pelo filtro como inválido.
    * **Sobrepor Mapa**: alternar\
      Alternar entre os modos de sobreposição - se habilitado, o mapa de cor de base será sobreposto pelos pixels inválidos.
    * **Ocultar Validação na Cor de base**: alternar\
      Ocultar as informações de validação do canal de cor de base.
  * **Modo de Validação: Combinado**
    * **Limite de Intervalo Escuro do Albedo**:\
      Defina o limite para valores escuros a serem escolhidos pelo filtro como inválidos.
    * **Intervalo de Reflexão Metálica**:\
      Defina o intervalo de valores de refletância a ser selecionado pelo filtro como inválido.
    * **Ocultar Validação na Cor de base**: alternar\
      Ocultar as informações de validação do canal de cor de base.

## Guia de Uso

O **filtro** do **filtro** ajuda a evitar problemas com valores metálicos e de albedo em um material. Para entender como o **filtro de Validações do PBR** funciona, é bom primeiro falar um pouco sobre o que é o PBR.

## O que é PBR?

PBR significa Physical Based Rendering (Renderização baseada em física) e é um método de renderização de objetos e materiais por meio da representação de propriedades físicas de uma superfície com vários canais. O PBR foi criado para representar com mais precisão o mundo real e físico do que os métodos de renderização e sombreamento anteriores.

No mundo real, existem algumas cores e combinações de propriedades que são impossíveis ou incrivelmente raras. Por exemplo, quase nada no mundo real tem um albedo ou cor de base branco puro ou preto puro.

Assim, como o PBR está tentando representar valores reais, e como alguns valores não aparecem ou raramente aparecem no mundo real, é possível ter valores PBR &#39;incorretos&#39;. Este é o objetivo do **filtro de Validações do PBR**.

## Como usar Validações do PBR

Para usar **Validações do PBR**, adicione-a à parte superior da pilha de camadas. Você deve ver uma mudança drástica na aparência do material. Isso ocorre porque o **filtro de Validações do PBR** exibe os resultados da validação no canal de albedo.

O filtro usa uma escala de vermelho a verde para mostrar onde estão os erros. Se todo o material for verde, não há nada de errado com as cores ou valores metálicos do material. No entanto, se você vir áreas amarelas, laranja ou vermelhas, há problemas com o material.

Se você estiver usando o modo de validação de cor, as áreas não verdes geralmente indicam que há valores na cor de base que estão próximos de preto ou branco. Use filtros de ajuste como **Matiz/Saturação** ou **Brilho/Contraste** para ajustar os valores do canal de cor até que o **filtro de Validação do PBR** não mostre mais erros.

Se você estiver usando o modo de validação de metal, áreas não verdes geralmente significam que a combinação de sua cor, aspereza e mapas metálicos nessas áreas é irrealista. Normalmente, isso acontece com valores de cor escura, 0 de aspereza e 1 de valores metálicos. Para corrigir esses erros, você pode modificar os valores de aspereza, metálico ou de cor até que o **filtro de Validação do PBR** não mostre mais erros.
