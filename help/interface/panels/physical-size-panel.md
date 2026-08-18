---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/interface/panels/physical-size-panel.html"
breadcrumb-title: ''
description: Saiba como usar o painel Tamanho físico no Substance 3D Sampler para definir dimensões reais para materiais e texturas.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Physical Size Panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Painel tamanho físico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 13%

---


# Painel tamanho físico

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/3-2-0-cover.png)

</td>
<td width="58.30%" style="border: 0;" valign="top">

Use o **Painel de Tamanhos físicos** para configurar o tamanho físico da vida real de suas amostras e imagens digitalizadas.

</td>
</tr>
</table>

Combine o tamanho físico real de suas amostras e imagens digitalizadas em um contexto digital para criar visuais fisicamente precisos nos aplicativos.\
As ferramentas e os parâmetros a seguir permitem definir o tamanho físico dos materiais e criar visuais precisos e realistas ao aplicar material em um objeto.

## Definir o tamanho físico

>[!NOTE]
>
> Para definir o Tamanho físico do material, você precisa ter uma camada de importação de imagem(ns).

Para calcular o tamanho físico de sua amostra/imagem, habilite **Definir tamanho físico**.

### Insira o tamanho da imagem

Esta seção permite definir manualmente o tamanho da amostra e fornece ferramentas para calcular o tamanho físico automaticamente.

**Camada de referência:** faça referência à imagem a partir da qual o tamanho físico é calculado.\
**Largura (X):** defina a largura física da camada de referência\
**Height(es):** defina o height físico da camada de referência\
**Ferramentas:**

![](../../assets/screenshot-2022-01-17-at-13-59-37.png)

O diagnóstico de medidas permite medir a distância entre dois pontos na sua imagem (apenas para fins informativos).

![](../../assets/screenshot-2022-01-17-at-14-00-06.png)

A ferramenta medição automática permite obter um tamanho físico estimado da amostra com base nos metadados da imagem (dpi). Esse método só é preciso com amostras digitalizadas.

![](../../assets/screenshot-2022-01-17-at-14-00-24.png)

A ferramenta Medida permite calibrar o tamanho físico, designando a distância física entre dois recursos da amostra. Geralmente, esse é o melhor método para calcular o tamanho físico da amostra.

### Superfície de malha 3D

Essas ferramentas permitem definir o aspecto da superfície do material.

**Escala física:** habilite ou desabilite a escala física. A escala física é a circunferência da malha ao longo dos três eixos.\
Dimensione seu material com valores físicos. Manipulação da largura (X) do Height (Y) e da Profundidade (Z).\
**Divisão em blocos gráficos de textura:** defina a divisão em blocos gráficos do seu material

### Material de saída

Ajudam a visualizar o resultado do material com seu aspecto real.

**Exibição com proporção física:**\
A exibição na viewport 2D respeita a proporção física.\
**Escala de Height:** definida/calculada a partir da viewport 3D com base na escala física.
