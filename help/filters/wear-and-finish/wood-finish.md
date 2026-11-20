---
description: Use o filtro Acabamento de madeira no Substance 3D Sampler para aplicar vários acabamentos e texturas de superfície de madeira aos seus materiais.
title: Acabamento de madeira
hold: true
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 0%
---

# Acabamento de madeira

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../assets/Filters/S_Wood_18_N_D.png" alt=""/><br><strong>Dentro:</strong> desgaste e acabamento</td>
    <td style="border: 0;" valign="top">Descrição<br>Adicione detalhes normais e de aspereza ao material para adicionar acabamentos geralmente associados à madeira, como verniz, ceruse ou granulação de madeira.<br><em>Uma cor de preenchimento simples</em><strong><em> </em></strong><em>é fornecida a aparência de madeira adicionando granulação de madeira com o </em><strong><em>filtro de Acabamento de madeira</em></strong><em>.</em><br><img src="../../assets/wood-finish-before.png" alt=""/><img src="../../assets/wood-finish-after.png" alt=""/></td>
  </tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Distribuição aleatória**:

  A distribuição aleatória determina os valores aleatórios de outros parâmetros que usam a aleatoriedade neste filtro.

* **Tipo de Conclusão**:

  Selecione um estilo para aplicar ao seu metal. Cada estilo tem parâmetros diferentes que permitem ajustar sua aparência. Além do término **Natural**, cada término tem um conjunto de parâmetros disponíveis para controlar o efeito.

  Estão disponíveis os seguintes acabamentos:

  * **Natural**: um acabamento natural suave para madeira processada.
  * **Ceruse**: crie uma aparência suave de dois tons preenchendo os poros abertos com um pigmento.
  * **Verniz fosco**: adicione um acabamento de verniz fosco suave.
  * **Verniz**: adicione um acabamento de verniz altamente reflexivo.
  * **Antiga**: ajuste a cor e a aspereza do material subjacente para criar a aparência de madeira envelhecida.
  * **Bruto**: adicione grãos de madeira para criar a aparência de madeira crua cortada.
  * **Serrados**: adicione trilhos de serra para criar a aparência de madeira fresca da serraria.

### Parâmetros compartilhados

Os seguintes parâmetros são exibidos para várias finalizações:

* **Matiz**: ajuste a cor do material.
* **Saturação**: ajuste a intensidade da cor.
* **Luminosidade**: ajuste o brilho.
* **Intensidade de aspereza**: ajuste a aspereza do material.
* **Intensidade de aspereza das fibras**: adiciona informações de aspereza de alta frequência ao mapa de aspereza. Combina com o controle deslizante de Intensidade de aspereza para modificar os valores de Aspereza, quer o material esteja muito suave ou muito áspero.
* **Intensidade normal**: ajuste a intensidade do mapa normal.
* **Contraste da máscara de fibras**:

### Finaliza

#### Ceruse

* **Cor 1**:
* **Cor 2**:
* **Variações de Cor de base**:
* **Detalhes de Alta Frequência**:

#### Verniz

* **Variações de orientação de fibras normais**:

#### Antiga

* **Intensidade de aspereza do verniz**:
* **Rotação de efeitos**:

#### Cru

* **Informações adicionais normais**:

#### Serrado

* **Redução de aspereza com fibras**: ajuste a aspereza ao longo das linhas de serra, criando contraste de aspereza.
* **Número de cortes de serra**: ajuste o número de linhas de serra.
* **Regularidade da máscara**: ajuste a regularidade com que as linhas de serra aparecem. Um valor mais alto torna as linhas menos regulares.
* **Fibras adicionais**: ajuste o número de fibras que são adicionadas paralelamente às linhas de serra.
