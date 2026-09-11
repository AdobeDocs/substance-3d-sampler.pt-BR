---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/hdri-tools/plane-light.html"
breadcrumb-title: ''
description: Use a ferramenta Luz de plano no Substance 3D Sampler para adicionar fontes planares de luz a ambientes HDRI para efeitos de iluminação de área.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Plane Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luz do plano
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '502'
ht-degree: 0%

---


# Luz do plano

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-planelight-18-n-d.png)

**Entradas:** Ferramentas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Adicione uma luz na forma de um plano plano ao seu ambiente.

![](../../assets/3d-2d-filters-cropped-0002-plane-light-out.jpg)

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Exposição (EV)**: 0-10\
  Ajuste a exposição ou o brilho da luz.
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
* **Modo de Posição**:\
  Altere o método usado para determinar a posição das luzes. Os parâmetros na seção **Coordenadas de Posição** serão alterados com base na seleção. Com a **Posição mundial** selecionada, as alças desaparecerão da **Visualização 2D**. Em vez disso, use os parâmetros nas **Coordenadas de posição** para modificar a posição da luz.

**Forma**

* **Escala do plano**; 0-1\
  Ajuste a escala da luz.
* **Tamanho do plano**: 0-1\
  Ajuste as dimensões da luz nos eixos X e Y.
* **Rotação do plano**: 0-1\
  Ajuste a rotação da luz ao longo dos eixos X, Y e Z.
* **Padrão**:\
  Selecione a forma da luz.
* **Dureza do padrão**: 0-1\
  Suavizar ou desfocar as bordas da luz
* **Modo UV de padrão**:\
  Escolha se as transformas esticarão toda a forma ou somente o meio da forma para manter os detalhes da borda e do canto.

**Coordenadas de Posição**

Os parâmetros disponíveis dependem da seleção feita para **Parâmetros básicos > Modo de Posição**. Se **Solo/Teto** ou **Distância da origem** estiverem selecionados, os seguintes parâmetros estarão disponíveis:

* **Height Absoluto de Linha**: 0-1\
  Altere a distância entre a luz e a câmera.
* **Posição da Câmera**: 0-1\
  Ajuste a posição relativa da câmera para a luz nos eixos X, Y e Z.

Se a **Posição Mundial** for escolhida em **Parâmetros básicos > Modo de Posição**, os seguintes parâmetros estarão disponíveis:

* **Vetor para cima**:\
  Mude a direção para cima.
* **Posição Mundial do Ponto 1**: -2 a 2\
  Ajuste a posição do primeiro ponto da linha nos eixos X, Y e Z.
* **Posição Mundial do Ponto 2**: -2 a 2\
  Ajuste a posição do segundo ponto da linha nos eixos X, Y e Z.
* **Posição da Câmera**: 0-1\
  Ajuste a posição relativa da câmera para a luz nos eixos X, Y e Z.

**Fundo**

* **Mostrar grade terrestre**: alternar\
  Exibir ou ocultar a grade do solo.
* **Habilitar recorte terrestre**: alternar\
  Selecione se a luz pode ser cortada ou não pelo solo. Se ativado, o seguinte controle será exibido:
  * **Height terrestre**: -2 a 2\
    Ajuste o height do solo para fins de recorte da luz.
* **Gama de fundo**:\
  Selecione o sistema de cores usado para determinar a gama do plano de fundo.
