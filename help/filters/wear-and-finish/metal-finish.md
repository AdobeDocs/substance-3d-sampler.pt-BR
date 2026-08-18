---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/metal-finish.html"
breadcrumb-title: ''
description: Use o filtro Acabamento de metal no Substance 3D Sampler para aplicar vários acabamentos e texturas de superfície de metal aos materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Metal Finish
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Acabamento de metal
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '624'
ht-degree: 0%

---


# Acabamento de metal

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/metal-finish-filter-icon.png.img.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Converta seu material em um metal com uma série de acabamentos e estilos.

*Uma matéria-prima metálica é convertida em uma superfície de metal escovada com o **filtro de Acabamento de Metal.***

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0023-metal-finish-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0022-metal-finish-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:\
  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.
* **Modificar Somente Metálico**: alternar\
  Quando habilitado, este filtro limitará suas alterações no canal metálico.
* **Modo de Cores Metálicas**:\
  Selecione uma cor baseada em um metal existente ou escolha sua própria cor. Com a **Cor Personalizada** selecionada, o seguinte controle será exibido:
  * **Cor metálica**: seleção de cores\
    Selecione uma cor personalizada para o acabamento metálico.
* **Tipo de Conclusão**:\
  Selecione um estilo para aplicar ao seu metal. Cada estilo tem parâmetros diferentes que permitem ajustar sua aparência. Os seguintes parâmetros podem ser exibidos:
  * **Intensidade**: 0-1\
    Ajuste a intensidade do acabamento escolhido.
  * **Escala**: 0-1\
    Modifique a escala do padrão que conduz o acabamento escolhido.
  * **Aspereza**: 0-1\
    Controle o valor de aspereza do metal.
  * **Escala de grânulos**: 0-1\
    Disponível para **Jateado**. Defina o tamanho das contas usadas para criar o efeito de jato de areia.
  * **Polido**: 0-1\
    Disponível para **Elenco**. Ajuste a quantidade de polimento que suaviza as partes mais altas do material.
  * **Padrão**:\
    Disponível para **Grinded**. Defina o padrão usado pelo moedor.
  * **Detalhes do Relevo**: 0-1\
    Disponível para **Raw**. Ajuste a força normal.
  * **Orientação**: 0-1\
    Disponível para **Pincelados**. Altere a direção do efeito do pincel.
  * **Comprimento do pincel**: 0-1\
    Disponível para **Pincelados**. Altere o comprimento dos traçados usados para criar o efeito de pincel.
  * **Pincelado**: 0-1\
    Disponível para **Galvanizado**. Sobreponha uma aparência escovada no acabamento galvanizado.

**Máscara**

* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D.
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara.
  * **Máscara personalizada - Inverter**: alternar\
    Inverta a máscara.

**Parâmetros Avançados**

* **Cor base**: alternar\
  Define se o canal da cor base é afetado pelo filtro.
* **Metálico**: alternar\
  Define se o canal metálico é afetado pelo filtro.
* **Aspereza**: alternar\
  Defina se o canal de aspereza é afetado pelo filtro.
* **Specular level**: alternar\
  Controla se o canal de specular level é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Specular level** **- Valor**: 0-1\
    Ajuste o valor do canal de specular.

>[!NOTE]
>
> No momento, há um erro conhecido em que o controle **Specular level** poderá desaparecer se for desabilitado sem controle para reabilitá-lo. Se você perder o controle **Specular level**, mas precisar dele novamente, poderá usar a opção de desfazer (ctrl + z ou cmd + z no macOS) para desfazer a desabilitação do alternador.

* **Normal**: alternar\
  Define se o canal normal é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Intensidade Normal**: 0-1\
    Ajuste a força da modificação normal pelo filtro.
* **Height**: alternar\
  Define se o canal de height é afetado pelo filtro.
* **Emissivo**: alternar\
  Define se o canal emissivo é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Emissivo - Cor**: seleção de cor\
    Defina a cor do canal emissivo.
* **Oclusão de ambiente**: alternar\
  Define se o canal de oclusão ambiente é afetado pelo filtro. Se ativado, os seguintes controles adicionais serão exibidos:
  * **Oclusão Ambiente - Intensidade**: 0-1\
    Ajuste a intensidade do AO gerado.
  * **Oclusão Do Ambiente** **- Raio**: 0-1\
    Ajuste o raio do efeito AO.
* **Opacidade**: alternar\
  Define se o canal de opacidade é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Opacidade - Valor**: 0-1\
    Altere a opacidade do material.
