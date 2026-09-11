---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/scratch.html"
breadcrumb-title: ''
description: Use o filtro Rascunho no Substance 3D Sampler para adicionar marcas de rascunho realistas e efeitos de danos na superfície dos materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Scratch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Arranhão
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '701'
ht-degree: 0%

---


# Arranhão

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-scratches-18-n-d.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Adicione arranhões e desgaste ao material.

*Antes e depois de aplicar o **Filtro de arranhões**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0001-scratch-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0000-scratch-out.jpg){width="200px"}

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
* **Rascunho**: alternar\
  Habilitar ou desabilitar riscos. Se habilitada, a seção **Rascunho** aparece.
* **Chip**: alternar\
  Adicione um efeito lascado à superfície. Se habilitada, a seção **Chip** será exibida.
* **Microarranhão**: alternar\
  Adicione microarranhões à superfície. Se habilitada, a seção **Microscratch** será exibida.

**Rascunho**

É necessário habilitar **Parâmetros básicos > Rascunho** para que esta seção apareça.

* **Valor**: 0-1\
  Controla o número de arranhões exibidos.
* **Intensidade**: 0-1\
  Ajuste a profundidade e a força dos arranhões.
* **Escala**: 1-4\
  Altere o tamanho dos arranhões. Aumente este controle deslizante para diminuir o tamanho do rabisco.

**Chip**

É necessário habilitar **Parâmetros básicos > Rascunho** para que esta seção apareça.

* **Valor**: 0-1\
  Controla o número de chips exibidos.
* **Intensidade**: 0-1\
  Ajuste a profundidade e a resistência dos chips.
* **Escala**: 1-4\
  Mudar o tamanho dos chips. Aumente este controle deslizante para diminuir o tamanho do chip.

**MicroArranhão**

* **Valor**: 0-1\
  Controla o número de microarranhões exibidos.
* **Intensidade**: 0-1\
  Ajuste a profundidade e a resistência dos microarranhões.
* **Rotação**: 0-1\
  Gire os microarranhões.
* **Rotação aleatória**: 0-1\
  Varie a rotação dos microarranhões aleatoriamente.
* **Escala**: 0-2\
  Ajuste o tamanho dos microarranhões. Aumente este controle deslizante para aumentar o tamanho do microarranhão.
* **Escala aleatória**: 0-1\
  Varie a escala dos microarranhões aleatoriamente.
* **Largura**: 0-1\
  Controlar a largura dos arranhões
* **Largura aleatória**: 0-1\
  Varie a largura dos microarranhões aleatoriamente.
* **Distorção**: 0-1\
  Adicione distorção aos arranhões para quebrar a uniformidade.
* **Distorção aleatoriamente**: 0-1\
  Controle a aleatoriedade do efeito de distorção.
* **Frequência de Distorção**: 0-1\
  Controle a escala de frequência do efeito de distorção.

**Máscara**

* **Máscara personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D.
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara.
  * **Máscara personalizada - Inverter**: alternar\
    Inverta a máscara.

**Parâmetros Avançados**

* **Opacidade Geral**: 0-1\
  Ajuste a opacidade do efeito **Filtro de rascunho**.
* **Cor de base**: alternar\
  Define se o canal de cor de base é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Cor de base - Cor**: seleção de cores\
    Selecione a cor de base dos arranhões e lascas.
* **Metálico**: alternar\
  Define se o canal metálico é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Valor Metálico**: 0-1\
    Ajuste o valor metálico das áreas arranhadas.
* **Aspereza**: alternar\
  Defina se o canal de aspereza é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Aspereza - Valor**: 0-1\
    Ajuste o valor de aspereza das áreas arranhadas.
* **Normal**: alternar\
  Define se o canal normal é afetado pelo filtro. Se ativado, controles adicionais serão exibidos:
  * **Normal - Intensidade**: -1 a 1\
    Ajuste a intensidade dos normais.
  * **Normal -** **Achatar**:\
    Diminua esse valor para nivelar os normais.
* **Height**: alternar\
  Define se o canal de height é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Height - Intensidade**: 0-1\
    Ajuste o contraste do mapa de altura.
* **Emissivo**: alternar\
  Define se o canal de emissivo é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Emissivo - Cor**: seleção de cor\
    Defina a cor do canal do emissivo.
* **Specular level**: alternar\
  Controla se o canal de specular level é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Specular level** **- Valor**: 0-1\
    Ajuste o valor do canal de specular.
* **Oclusão de ambiente**: alternar\
  Define se o canal de oclusão de ambiente é afetado pelo filtro. Se ativado, os seguintes controles adicionais serão exibidos:
  * **Oclusão de ambiente - Intensidade**: 0-1\
    Ajuste a intensidade do AO gerado.
  * **Oclusão de ambiente** **- Raio**: 0-1\
    Ajuste o raio do efeito AO.
* **Opacidade**: alternar\
  Define se o canal de opacidade é afetado pelo filtro. Se ativado, um controle adicional será exibido:
  * **Opacidade - Valor**: 0-1\
    Altere a opacidade do material.
