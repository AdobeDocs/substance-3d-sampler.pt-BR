---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/known-issues-and-limitations-hp-z-captis-support.html"
breadcrumb-title: ''
description: Analise os problemas e limitações conhecidos ao usar o HP Z Captis com o Substance 3D Sampler para entender as restrições atuais e as soluções alternativas.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Problemas conhecidos, limitações ao suporte a HPZ Captis
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 0%

---


# Limitações e problemas conhecidos

<b>Versão: Sampler 6.0, lançada em 16 de abril de 2026</b>

* O fluxo de trabalho do Sampler com HP Z Captis está disponível somente no Windows por enquanto.

* Desconectar fisicamente o dispositivo enquanto uma digitalização estiver em andamento não interrompe a captura. Se o dispositivo estiver desconectado durante a captura, aguarde 30 segundos antes de reconectá-lo para que ele possa se reconectar à sessão de captura em andamento.
* Os cinco mapas que estão sendo exportados hoje são Cor de base, Aspereza, Normal, Height, Opacidade.
* Ao fechar a janela durante uma captura, os metadados que foram preenchidos são perdidos.
* Ao clicar em qualquer um dos botões “Procurar conteúdo” ou “Desligar” durante a transferência dos dados do Captis via USB, a transferência é interrompida.

* Se você tiver problemas de TDR, consulte [esta página de documentação](https://experienceleague.adobe.com/en/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-drivers-crash-with-long-computations-tdr-crash) do Substance Painter, que deve ajudar a corrigi-los.
* Se a etapa “Visualização” estiver toda preta, em vez de visualizar a alimentação em tempo real dentro do dispositivo, certifique-se de ter removido a tampa da lente de dentro do cone do dispositivo.
