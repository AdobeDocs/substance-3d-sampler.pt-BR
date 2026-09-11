---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/tools/make-it-tile.html"
breadcrumb-title: ''
description: Use a ferramenta Torná-lo lado a lado no Substance 3D Sampler para criar automaticamente padrões de divisão em blocos gráficos contínuos a partir de texturas sem divisão em blocos gráficos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Make it Tile
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Torná-lo lado a lado
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '556'
ht-degree: 0%

---


# Torná-lo lado a lado

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Use o **Filtro Torná-lo Bloco** para tornar seu material legível. O **filtro de divisão em blocos gráficos** também torna seu material legível, mas cada filtro funciona de maneira diferente. Se você achar que o **Filtro Torná-lo Lado a Lado** não está funcionando, tente o **Filtro Lado a Lado**.

Nas imagens abaixo, você pode ver como o **Filtro Torná-lo Lado a Lado** pode converter um material não ladrilhado em um material ladrilhável. Esse material se azuleja bem porque segue um padrão semelhante a uma grade e não há pontos específicos que atraem o foco.

![](../../assets/3d-2d-filters-cropped-0015-make-it-tile-in.jpg)

Na imagem acima, a linha vermelha mostra o limite do material. É bastante claro que há uma costura forte, e que este material não ladrilha.

![](../../assets/3d-2d-filters-cropped-0014-make-it-tile-out.jpg)

Depois de **Torná-lo Lado a Lado**, este material é bem ladrilhado e, sem a linha vermelha, seria impossível ver costuras nos limites do material.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros básicos**

* **Limite**: 0-1\
  Ajuste o tamanho e a correspondência da camada superior.
* **Smoothness**: 0-1\
  Suavize a costura da camada superior.
* **Contraste**: 0-1\
  Ajuste o contraste da costura. Diminuir o contraste tem o mesmo efeito que desfocar a costura.
* **Remoção de manchas**: alternar\
  Se habilitado, o filtro tentará remover artefatos próximos à fenda entre as camadas superior e inferior.
* **Color Equalizer**: 0-50\
  Equalize os valores de cor para diminuir a visibilidade da costura.
* **Correspondência de Height**:\
  Altere como os mapas de height são mesclados para as camadas superior e inferior do filtro. Para ver os resultados com mais clareza, exiba o canal de height no **Visualização 2D**. Observe que a correspondência de heights não afeta outros canais além do canal do height, portanto, os normais e o AO não serão afetados pelas alterações na correspondência de heights.

**Parâmetros Avançados**

* **Influência de crominância**: 0-1\
  Ajuste a quantidade de valores de cor que afetam a linha de junção.
* **Inversão de máscara**: alternar\
  Inverta as máscaras de camadas superiores e inferiores.
* **Smoothness Correspondente ao Height**: 0-16\
  Ajuste o desfoque de height correspondente entre as camadas superior e inferior.
* **Origem de Patch Esquerda/Direita**: -1 a 1\
  Ajuste o local de origem para os patches esquerdo e direito.
* **Origem do Patch Superior/Inferior**: -1 a 1\
  Ajuste o local de origem para os patches superior e inferior.

## Guia de Uso

O **Bloquear** **filtro** funciona sobrepondo várias cópias do material umas sobre as outras.

A imagem abaixo mostra o layout das camadas:

* O perímetro verde mostra as bordas do material resultante do **Filtro Tornar Bloco**
* As linhas vermelhas mostram as bordas da camada inferior. A camada inferior é deslocada em 50% do espaço UV nos eixos X e Y, de modo que as linhas vermelhas são costuras de revestimento que precisam ser cobertas.
* O quadrado e os semicírculos azuis cobrem as emendas vermelhas. Os parâmetros do filtro permitem ajustar as bordas das formas azuis para garantir que a costura vermelha não fique visível, mantendo a costura azul o mais suave possível.

![](../../assets/makeittilediagram.png){width="512px"}

Os semicírculos esquerdo e direito combinam-se para garantir que o material seja ladrilhado horizontalmente, e os semicírculos superior e inferior garantem que o material seja ladrilhado verticalmente. O quadrado azul no centro remove e oculta todas as emendas restantes para criar um material totalmente ladrilhável sem emendas.
