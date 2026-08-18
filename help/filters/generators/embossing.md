---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/embossing.html"
breadcrumb-title: ''
description: Use o gerador de entalhe no Substance 3D Sampler para criar padrões em alto-relevo e efeitos de relevo de superfície elevados nos materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embossing
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Em alto-relevo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---


# Em alto-relevo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embossing-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

Entalhe texto ou padrões em seus materiais.

</td>
</tr>
</table>

## Parâmetros

**Parâmetros Básicos**

* **Tamanho do Entalhe**: 0-1\
  Alterar o tamanho de cada instância
* **Distância de entalhe**: 0-1\
  Alterar o thickness das linhas em alto-relevo
* **Seleção de padrão**:\
  Selecione o padrão de entalhe. Aqui, você pode selecionar para entalhar o texto ou um padrão personalizado.
* **Bloco X de Padrão**: 1-64\
  Alterar o número de instâncias no eixo X
* **Bloco de Padrão Y**: 1-64\
  Alterar o número de instâncias no eixo Y

**Entalhe**

* **Usar Entalhe de Borda**: alternar\
  Alterna entre gravar ou não a borda do padrão escolhido
* **Inversão de Entalhe de Borda**: alternar\
  Inverter o height do entalhe da borda
* **Intensidade de entalhe da borda**: 0-1\
  Alterar a intensidade do efeito de entalhe
* **Usar Entalhe de Preenchimento**: alternar\
  Alterna se o preenchimento do padrão escolhido será gravado
* **Inversão de Entalhe de Preenchimento**: alternar\
  Inverter o height do efeito de entalhe de preenchimento
* **Intensidade de entalhe de preenchimento**: 0-1\
  Alterar a intensidade do efeito de entalhe

**Padrão**

* **Usar cor**: alternar\
  Alternar se a cor deve ou não ser adicionada à área em alto-relevo\
  Quando a opção **Usar Cor** estiver ativada, um parâmetro adicional de **Cor** aparecerá para ajustar a cor.
* **Máscara de padrão** **Distância**: 0-1\
  Alterar o tamanho da máscara usada para aplicar cor à área em alto-relevo
* **Contraste de máscara de padrão**: 0-1\
  Ajuste o contraste da máscara. Diminuir o contraste faz com que as bordas da máscara pareçam mais desfocadas.
* **Usar bloco de padrão**: alternar\
  Ative para cobrir o padrão, desative para ter apenas uma única instância. Quando o padrão não estiver lado a lado, as opções de **Bloco de Padrão** não aparecerão na seção **Parâmetros Básicos**.
* **Rotação de Padrão**: 0-1\
  Girar o padrão
* **Deslocamento de Padrão**: 0-1\
  Desloca cada linha do padrão da linha anterior.
* **Usar aspereza de padrão**: alternar\
  Ative essa opção para substituir a aspereza do material subjacente por um valor de aspereza personalizado onde quer que o efeito de entalhe seja exibido.\
  Quando habilitado, um controle de **Aspereza do padrão** aparecerá para definir a aspereza.
* **Usar padrão metálico**: alternar\
  Ative essa opção para substituir os valores metálicos do material subjacente por um valor metálico personalizado onde quer que o efeito de entalhe seja exibido.\
  Quando habilitado, um controle **Metálico de Padrão** aparecerá para definir a aspereza.

**Texto** - Esta seção só será exibida se a **Seleção de Padrão** em **Parâmetros básicos** estiver definida como **Texto**

* **Seleção de fonte**:\
  Selecionar uma fonte
* **Texto**: campo de texto\
  Digite o texto a ser gravado em alto-relevo
* **Tamanho do texto**: 0-1\
  Ajustar o tamanho da fonte

**Borracha**

* **Borracha Normal**: 0-1
* **Apagar Oclusão de Ambiente**: 0-1
* **Opacidade da Borracha**: 0-1

**Parâmetros avançados**

Esses parâmetros permitem ajustar valores para o material inteiro.

* **Luminosidade**: 0-1
* **Contraste**: -1 a 1
* **Alteração de matiz**; 0-1
* **Saturação**: 0-1
* **Intensidade Normal**; 0-1

## Guia de Uso

Adicione o filtro Entalhe no topo da pilha de camadas e comece a ajustar os parâmetros.

Os parâmetros mais importantes geralmente são **Parâmetros Básicos > Seleção de Padrão** para modificar qual padrão o filtro usará e **Padrão > Usar Bloco de Padrão** para ativar e desativar o enquadramento.
