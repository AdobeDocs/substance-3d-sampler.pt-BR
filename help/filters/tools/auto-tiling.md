---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/tools/auto-tiling.html"
breadcrumb-title: ''
description: Use a ferramenta Lado a lado automático no Substance 3D Sampler para criar automaticamente padrões de lado a partir de texturas usando a tecnologia AI.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Lado a lado automático
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '575'
ht-degree: 0%

---


# Lado a lado automático

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

Ferramentas de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O <b>Filtro de revestimento automático</b> procura estruturas repetitivas em seu material e as usa para criar um material de revestimento. Diferentemente do <b>Filtro de ladrilho</b> ou do <b>Filtro de ladrilho</b>, o <b>Ladrilho Automático</b> concentra-se em isolar a menor área do material que pode ser ladrilhado.

<b>A divisão automática em blocos </b> é particularmente útil para têxteis.

</td>
</tr>
</table>

>[!NOTE]
>
> Para que o filtro de divisão em blocos gráficos automática funcione, é necessário um mínimo de repetições de 3x3 na imagem ou no material de origem.

## Tutorial sobre o filtro de divisão automática

## Sobre a divisão em blocos gráficos automática

Quando você adicioná-lo à sua pilha de camadas, o <b>Enquadramento automático</b> tentará localizar automaticamente padrões repetitivos e gerar um material de enquadramento. Se isso não for bem-sucedido, você poderá usar o botão <b>Configurações avançadas </b> para ajustar manualmente o processo.

Se você planeja criar um material de revestimento a partir de uma imagem, é melhor usar o <b>Filtro de revestimento automático</b> primeiro e depois usar o <b>Filtro de imagem para material</b>.

A <b>Divisão em Blocos Automáticos</b> é executada completamente em seu dispositivo, nenhum conteúdo é enviado para a nuvem.

## Parâmetros

Diferentemente da maioria dos filtros, o <b>Enquadramento automático</b> não tem parâmetros. Em vez disso, há um botão <b>Configurações avançadas </b>, que o guiará pelo processo de configuração do filtro. Você não precisa fazer ajustes manuais em cada etapa e pode pular para a frente ou para trás selecionando uma etapa na parte superior da janela.

Esse processo consiste nas seguintes etapas:

1. <b>Introdução</b>: explica como o filtro funciona. Use a caixa de seleção para ocultar esta tela no futuro.
1. <b>Seleção de mapa</b>: selecione o canal que o filtro deve usar. Recomenda-se o canal com o padrão de repetição mais visível. Geralmente, esse é o canal Cor base ou Height, mas outros canais podem ser úteis dependendo do material.
1. <b>Configurações de exemplo</b>: faça alterações no material de entrada para obter os melhores resultados. Isso inclui escolher uma resolução e girar ou distorcer a entrada. Se o seu padrão for muito pequeno, pode ser útil selecionar uma resolução mais alta para garantir que o padrão fique visível. No entanto, para padrões maiores, uma resolução mais baixa pode fornecer resultados melhores e mais rápidos.
1. <b>Tamanho do padrão</b>: nesta etapa, o filtro procura o menor padrão que possa encontrar. Você pode selecionar entre uma detecção automática maior ou menor, ou selecionar um tamanho personalizado para especificar seu próprio tamanho. Para obter os melhores resultados, selecione o menor tamanho com o padrão de repetição uma vez por caixa.\
   Se todas as caixas tiverem um formato irregular e parecerem não corresponder ao padrão, use o tamanho personalizado para obter resultados mais regulares.
1. <b>Detecção de padrão</b>: posicione os pontos de forma que cada ponto fique no mesmo local do padrão. Por exemplo, em um padrão quadriculado preto e branco, você pode querer que os pontos estejam no centro dos quadrados pretos.
1. <b>Região de interesse</b>: selecione a área do material a ser usada para criar o padrão final. Usar uma região maior diminuirá a quantidade de repetição visível, mas incluir áreas com artefatos ou diferenças de iluminação visíveis pode aumentar a quantidade de repetição visível.
1. <b>Remoção de costura</b>: ajuste as configurações para minimizar a visibilidade da costura. <b>O smoothness de corte </b>controla o nível de suavidade da linha da junção, enquanto a <b>Largura de mesclagem </b>desfoca a junção entre os blocos.

Depois de passar por todas as etapas, use <b>Aplicar</b> para confirmar suas escolhas. O filtro de <b>Enquadramento Automático</b> processará o material para gerar um resultado final.
