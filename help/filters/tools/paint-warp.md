---
title: Distorção de tinta
description: Saiba como usar o filtro Distorção de Tinta no Substance 3D Sampler para um controle fino sobre a distorção do material.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '516'
ht-degree: 2%
---

# Distorção de pintura

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top">Ferramentas de <img src="../../assets/Filters/S_WarpPaint_18_N_D.png" alt=""/><br><strong>Entrada:</strong></td>
    <td style="border: 0;" valign="top"><strong>Descrição</strong><br>O filtro <strong>Distorção de Tinta</strong> é uma ferramenta poderosa projetada para corrigir distorções geométricas em digitalizações baseadas em imagens. É particularmente útil para materiais com padrões lineares - como tecido de veludo, tábuas de madeira ou tijolo - onde as linhas naturais não são perfeitamente retas ou alinhadas com os eixos. Ao definir manualmente o fluxo do padrão, você pode “endireitar” o material para garantir uma divisão em blocos gráficos perfeita e mapas de textura de nível profissional.<br></td>
  </tr>
</table>

## Alinhamento de padrões de material

Você pode adicionar o filtro Distorção de Tinta manualmente à sua Pilha de camadas, mas o fluxo de trabalho mais eficiente para digitalizações é usar a Ação rápida dedicada.

### Usando a ação rápida

1. Abra a guia **Ação Rápida**.
1. Selecione **Alinhar padrões de material por pintura**.

* O Sampler adicionará automaticamente três camadas à sua pilha: **Equalizar**, **Distorção de Tinta horizontal** e **Distorção de Tinta vertical**.

1. Na **Pilha de camadas**, identifique qual direção seu padrão segue.

* *Exemplo:* para veludos com hastes verticais, mantenha a **Distorção de Tinta Vertical** e desabilite ou exclua a versão Horizontal.

### Pintura de guias de distorção

Uma vez selecionado o filtro, é necessário definir o caminho atual “torto” do padrão para que o Sampler saiba como endireitá-lo.

1. Vá para o painel **Propriedades** do filtro Distorção de Tinta.

1. Localize a propriedade **Entrada de imagem** e clique no ícone do **Pincel** ao lado dela para entrar no modo de pintura.

1. Ajuste o **Tamanho do pincel** usando os widgets ou atalhos da interface.

1. Tinta ao longo das linhas do seu material:

   >[!TIP]
   >
   > Pressione **Shift** enquanto clica para criar segmentos perfeitamente retos entre os pontos.

1. Rastreie várias linhas na largura ou no height da textura para fornecer dados suficientes ao algoritmo.

1. No painel **Propriedades**, alterne o parâmetro **Corrigir** para **Ativado**. O Sampler distorcerá a imagem para que as linhas pintadas fiquem perfeitamente paralelas ao eixo escolhido.

## Referência de Parâmetros

| Nome | Descrição | Intervalo/Opções | Padrão |
| --- | --- | --- | --- |
| **Direção** | Determina o eixo ao qual a distorção se alinhará. | Vertical, horizontal | Vertical |
| **Corrigir** | Ativa ou desativa o efeito de distorção com base na máscara pintada. | Alternar (Ativar/desativar) | Desativado |
| **Mostrar entrada** | Uma sobreposição do helper que exibe guias para auxiliar na precisão da pintura. | Alternar (Ativar/desativar) | Desativado |
| **Distorção suave** | Controla a queda e o smoothness da deformação entre guias pintadas. | 0.0 - 1.0 | 0.5 |

## Dicas e práticas recomendadas

* **Usar Mostrar entrada:** habilite a alternância **Mostrar entrada** ao pintar. Isso fornece uma sobreposição de grade que facilita ver exatamente onde a digitalização original se desvia de uma grade perfeita.
* **Não Tinta demais:** você não precisa rastrear cada linha em um padrão. Normalmente, 3 a 5 linhas bem posicionadas na textura são suficientes para que o algoritmo calcule a deformação necessária.
* **Combinar com Divisão em Lado a Lado:** use Distorção de Tinta antes de aplicar o filtro de **Divisão em Lado a Lado**. Um padrão endireitado é significativamente mais fácil de ser ladrilhado sem emendas visíveis ou linhas “quebradas” nas bordas.
* **Equalizar primeiro:** como visto na Ação rápida, colocar um filtro **Equalizar** antes da Distorção de Tinta ajuda a remover gradientes de iluminação, facilitando a visualização dos detalhes do padrão que você está tentando alinhar.

## Artigos relacionados

* [Equalizar](../adjustments/equalize.md)
* [Revestimento](tiling.md)
* [Ações rápidas](../../features-and-workflows/quick-actions.md)
* [Verificando práticas recomendadas](../../pipeline-and-integrations/hp-z-captis-support/scanning-best-practices.md)
