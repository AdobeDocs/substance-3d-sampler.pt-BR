---
title: Modo de especificação baixa
description: Saiba mais sobre o modo de baixa especificação, que o Sampler habilita quando o hardware não atende aos requisitos mínimos de sistema.
hold: true
source-git-commit: 59761aab02bff266047813f1714e3f53ddcb805c
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%
---

# Modo de especificação baixa

![](../assets/v6.1/6_1-Checked.png)

Se o hardware não atender aos [requisitos mínimos](../getting-started/system-requirements.md) do Sampler, o Sampler será iniciado automaticamente no modo de especificação Baixa, que se comporta como o [modo Desempenho](performance-mode.md) sem a opção de alterar as configurações.

## Limitações do modo de especificação baixa

O modo de especificação baixa ativa automaticamente o **Modo de desempenho** com todos os recursos desabilitados e uma resolução máxima de visualização de 2048 × 2048.

O modo de especificação baixa desabilita:

* **Deslocamento**
* **Sombras**
* **Rastreamento de caminho**

Além disso, o modo de baixa especificação impede exportações acima de 2048 px × 2048 px.

![](../assets/low-spec-mode-export-message.png)

*Esta mensagem aparece na **janela de exportação**&#x200B;enquanto está no **modo de especificação baixa**&#x200B;para fornecer informações adicionais.*

## Como posso saber se o modo Especificações baixas está ativado?

Ao iniciar o Sampler, se o hardware não atender aos requisitos mínimos, uma janela será exibida indicando quais requisitos não foram atendidos e oferecendo a opção de continuar iniciando o Sampler.

A imagem abaixo mostra um exemplo de uma máquina com menos de 8 GB de VRAM.

![](../assets/low-device-specs-popup.png)

Se você optar por **Iniciar mesmo assim**, o Sampler será iniciado no **modo de especificação baixa**. Se você usou a caixa de seleção na mensagem acima para não mostrar e iniciar de qualquer maneira, ainda verá o banner a seguir nas inicializações subsequentes.

![](../assets/low-spec-mode-banner.png)

Finalmente, enquanto o **Modo de especificação baixa** estiver habilitado, não será possível desativar o Modo de desempenho nem ajustar as configurações do Modo de desempenho.

![](../assets/performance-mode-locked.png)
