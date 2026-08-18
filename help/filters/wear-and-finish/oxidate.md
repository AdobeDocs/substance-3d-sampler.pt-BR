---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/oxidate.html"
breadcrumb-title: ''
description: Use o filtro Oxidado no Substance 3D Sampler para adicionar efeitos de oxidação e mancha em materiais metálicos para aparências antigas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Oxidate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Oxidato
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---


# Oxidato

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-oxidate-18-n-d.png)

**Dentro:** desgaste e acabamento

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Adicione uma camada de oxidação sobre a parte superior do material.*Uma superfície enrugada tem o **filtro de oxidado**&#x200B;aplicado.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0019-oxidate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0018-oxidate-out.jpg){width="200px"}

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
* **Áreas de Destino**: alternar\
  Permite alterar como o efeito de oxidação é aplicado ao material. Quando ativado, o seguinte controle será exibido:
  * **Intensidade das Áreas de Destino**: 0-1\
    Ajuste a propagação do efeito das áreas de destino.
  * **Propagação**: 0-1\
    Ajuste o quanto o oxidante se espalha.
* **Cor**: seleção de cor\
  Selecione a cor de base do filtro. As cores de base alteram o matiz de todas as cores que compõem o efeito oxidante.
* **Variações de cores**: 0-1\
  Ajuste a escala do efeito de variação de cor.
* **Densidade**: 0-1\
  Altere a densidade de cobertura do efeito.
* **Sangria de borda**: 0-1\
  Modifique como as bordas do efeito de oxidação sangram em áreas não oxidadas.
* **Patches**: 0-1\
  Esse é um controle separado para modificar a máscara entre áreas oxidadas e não oxidadas. Combine-a com a densidade e outros controles para ajustar as bordas das áreas oxidadas.
* **Chipping**: 0-1\
  Faça uma lasca na área oxidada para revelar o material subjacente.
* **Manchas**: 0-1\
  Ajuste a quantidade de mancha sobreposta sobre o material.
* **Aspereza de corrosão**: 0-1\
  Ajuste a aspereza das áreas oxidadas.
* **Metálico de corrosão**: 0-1\
  Ajuste os valores metálicos das áreas oxidadas.
* **Intensidade de Ruído**: 0-1

**Máscara**

* **Usar Máscara Personalizada**: alternar\
  Ativar ou desativar o uso de uma máscara personalizada. Se ativado, os seguintes parâmetros serão exibidos:
  * **Máscara**: imagem/pincel\
    Selecione uma imagem para usar como máscara ou use o pincel para pintar uma máscara personalizada diretamente na exibição 2D.
  * **Máscara Personalizada - Desfoque**: 0-1\
    Desfocar a máscara.
  * **Máscara personalizada - Inverter**: alternar\
    Inverta a máscara.
  * **Opacidade da máscara personalizada**: 0-1\
    Ajuste a opacidade da máscara.

**Parâmetros Técnicos**

Os parâmetros a seguir permitem ajustar o valor nomeado de todo o material sem adicionar uma camada de ajuste, como **Brilho/Contraste** ou **Matiz/Saturação**

* **Luminosidade**: 0-1
* **Contraste**: -1 a 1
* **Alteração de matiz**: 0-1
* **Saturação**: 0-1
* **Intensidade Normal**: 0-1
* **Intervalo de Heights**: 0-1
* **Posição do Height**: 0-1
* **Intensidade de Oclusão do ambiente**: 0-1
