---
description: Saiba como usar o modo Desempenho no Substance 3D Sampler para melhorar o desempenho ou até mesmo executar o Sampler em computadores abaixo dos requisitos mínimos de sistema.
title: Modo de desempenho
hold: true
source-git-commit: ce1229a1dfc9f6c8871c524b54a0641bdde19ee7
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 1%
---

# Modo de desempenho

O modo Desempenho reúne todas as configurações que podem tornar seu fluxo de trabalho mais lento: limites de resolução, sombras, qualidade do deslocamento e rastreamento de caminho. Desative o que não é necessário e obtenha a capacidade de resposta desejada, especialmente em hardwares mais leves.

>[!NOTE]
>
> O modo Desempenho é ativado automaticamente com limitações máximas se o hardware não atender aos [requisitos mínimos](../getting-started/system-requirements.md) da Sampler. Isso possibilita continuar usando o Sampler em um hardware menos potente.

## Alternar modo de desempenho

O modo de desempenho pode ser alternado com o **botão Modo de desempenho** no canto superior direito da **janela do Sampler**.

![](../assets/performance-mode-button.png)

## Alterar configurações do Modo de desempenho

Use a lista suspensa ao lado do **botão Modo de desempenho** para controlar os limites que o Modo de desempenho habilita.

![](../assets/performance-mode-settings.png)

| Configuração | Descrição |
| --- | --- |
| **Resolução máxima de visualização** | O modo Desempenho reduz a resolução da visualização para acelerar a renderização. Isso não altera a resolução dos ativos importados ou do seu documento, mas altera a qualidade do renderizador do visor. |
| **Desabilitar qualidade do deslocamento** | Quando esta configuração está habilitada, o **Modo de desempenho** bloqueia o **valor de qualidade do Deslocamento** para 0, desabilitando o efeito de deslocamento no visor. Para materiais lisos, como ladrilhos ou tecidos finos, isso tem impacto visual mínimo, mas pode melhorar substancialmente o desempenho. |
| **Desabilitar sombras** | Malhas e materiais deslocados podem projetar sombras, criando uma imagem mais realista ao custo do desempenho. Com a opção **Desabilitar sombras** ativada, o modo Desempenho desabilita todo o processamento de sombra, melhorando o desempenho. |
| **Desabilitar rastreamento de caminho** | O traçado de caminho é um método de renderização eficiente que segue caminhos de luz à medida que eles refletem na cena, criando renderizações fotorrealistas. No entanto, o traçado de caminho é caro. Quando a opção **Desabilitar rastreamento de caminho** está ativada, o Modo de desempenho desabilita a opção de ativar o rastreamento de caminho no **Visor 3D**. |

>[!NOTE]
>
> O rastreamento de caminho pode ser acessado pela **barra de ferramentas do Visor 3D**.
>
> ![](../assets/enable-path-tracing.png)
>
> Se o rastreamento de Caminho não estiver habilitado, ativar o modo Desempenho somente com **Desabilitar rastreamento de caminho** ativado não terá efeito.
