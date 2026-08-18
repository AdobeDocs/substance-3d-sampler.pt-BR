---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/nadir-patch.html"
breadcrumb-title: ''
description: Use a ferramenta Nadir patch no Substance 3D Sampler para corrigir a área inferior de imagens HDRI e obter mapas de ambiente perfeitos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Nadir Patch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Nadir patch
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Nadir patch

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-nadirpatch-18-n-d.png)

**Entradas:** Ferramentas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Corrija a base da luz ambiente para ocultar artefatos ou emendas.

Nas imagens abaixo, você pode ver como o **Nadir patch** é usado para remover o suporte da câmera nesta imagem panorâmica.

![](../../assets/3d-2d-filters-cropped-0011-nadir-patch-in.jpg)![](../../assets/3d-2d-filters-cropped-0010-nadir-patch-out.jpg)

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Habilitar**: alternar\
  Ativar ou desativar o patch - isso pode ser útil para ver rapidamente o impacto do patch sem precisar alterar a visibilidade da camada.
* **Mostrar auxiliar de quadros**: alternar\
  Ative ou desative os Quadros.
* **Thickness de quadros**: 0-1\
  Ajuste o thickness do quadro. Isso pode ser útil quando a origem do patch está longe do nadir.
* **Escala de correção**: 0-1\
  Ajuste o limite da área a ser corrigida.
* **Tamanho do Patch**:\
  Ajuste as dimensões do patch.
* **Rotação de correção**: 0-1\
  Gire os limites da correção. Isso gira a origem e o local do patch, para que o patch ainda tenha a mesma orientação. Para girar a correção no local, use o **Deslocamento de rotação da origem**.
* **Alpha de patch**:\
  Selecione a forma usada para mascarar o patch. Se a **Entrada de máscara** estiver selecionada, um parâmetro adicional será exibido:
  * **Entrada de máscara**: imagem/pincel\
    Importe uma imagem para usar como máscara ou pinte uma máscara diretamente na **exibição 2D**.
* **Dureza do patch**: 0-1\
  Ajuste o desfoque nas bordas da máscara de correção.
* **Deslocamento da Rotação da Origem**: 0-1\
  Desloque a rotação da origem - isso tem o efeito de girar o patch.

## Guia de Uso

Um problema comum que pode ocorrer ao criar uma luz ambiente a partir de fotografias são artefatos que ocorrem em torno das extremidades superior e inferior da textura. O **filtro** filtro **do** do Nadir patch ajuda a minimizar esses problemas.

1. Adicione o **filtro de Nadir patch** ao topo da pilha de camadas.
1. Use o identificador no **modo de exibição 2D** para alterar o local de origem do patch.
   1. O nadir corrigido muda dependendo do local da origem. Se a fonte estiver na metade inferior do espaço de textura, a base será corrigida; se a fonte estiver na metade superior, a base será corrigida.
1. Modifique os parâmetros para ajustar a transformação da correção para ocultar melhor costuras e artefatos.
