---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/sphere-light.html"
breadcrumb-title: ''
description: Use a ferramenta Luz de esfera no Substance 3D Sampler para adicionar fontes de luz esféricas a ambientes HDRI para efeitos de iluminação de ponto.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Sphere Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luz da esfera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---


# Luz da esfera

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-spherelight-18-n-d.png)

**Entradas:** Ferramentas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Adicione uma luz de esfera ao seu ambiente.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Modo de Cores da Forma**:\
  Selecione o método a ser usado para determinar a cor da luz. Os parâmetros disponíveis serão alterados com base nessa seleção.
  * **Temperatura (Kelvin)**
    * **Temperatura**: 1000 - 27000\
      Ajuste a temperatura da luz.
  * **RGB**
    * **Cor**: seleção de cor\
      Selecione a cor da luz.
  * **Entrada de imagem**
    * **Entrada de imagem da forma**: imagem/pincel\
      Importar uma imagem para usar como cor. Você pode usar a ferramenta pincel para pintar diretamente na **exibição 2D**, mas isso pode ter resultados imprevisíveis com este filtro.
  * **Amostra de plano de fundo**
    * O plano de fundo de amostra não disponibiliza novos parâmetros; em vez disso, ele baseia a cor da luz nos valores do plano de fundo.
* **Exposição (EV)**: 0-10\
  Ajuste a exposição ou o brilho da luz.
* **Raio da esfera**: 0-1\
  Ajuste o tamanho da luz.
* **Modo de Posição**:\
  Altere o método usado para determinar a posição das luzes. Os parâmetros na seção **Coordenadas de Posição** serão alterados com base na seleção.

**Coordenadas de Posição**

Os parâmetros disponíveis dependem da seleção feita para **Parâmetros básicos > Modo de Posição**. Se a **Distância da origem** estiver selecionada, os seguintes parâmetros estarão disponíveis:

* **Distância da origem**: 0-20\
  Ajuste a distância da luz da câmera.
* **Posição da Câmera**: 0-1\
  Ajuste a posição relativa da câmera para a luz nos eixos X, Y e Z.

Se a **Posição Mundial** estiver selecionada, os seguintes parâmetros estarão disponíveis:

* **Vetor para cima**:\
  Mude a direção para cima.
* **Posição Mundial da Esfera**: -2 a 2\
  Ajuste a posição da luz de esfera nos eixos X, Y e Z.
* **Distância da origem**: 0-20\
  Ajuste a distância da luz da câmera.
* **Posição da Câmera**: 0-1\
  Ajuste a posição relativa da câmera para a luz nos eixos X, Y e Z.

**Forma**

* **Dureza da esfera**: 0-1\
  Suavizar ou endurecer as bordas da luz da esfera
* **Sombreamento**:\
  Altere o gradiente da exposição da luz com base em diferentes estilos de luz do mundo real. Com a **Luz de Sombreamento** selecionada, parâmetros adicionais são exibidos:
  * **Posição Mundial da Luz do Sombreamento**: -1 a 1\
    Modificar a posição da área sombreada na luz
  * **Transparência do Penumbra**: 0-1\
    Ajuste o nível de opacidade da área sombreada da luz.

**Fundo**

* **Gama de fundo**:\
  Selecione o sistema de cores usado para determinar a gama do plano de fundo.
