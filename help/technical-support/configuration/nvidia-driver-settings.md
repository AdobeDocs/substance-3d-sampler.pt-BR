---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/configuration/nvidia-driver-settings.html"
breadcrumb-title: ''
description: Saiba como definir as configurações do driver NVIDIA para o Substance 3D Sampler a fim de otimizar o desempenho da GPU e resolver o comportamento lento.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > NVIDIA Driver Settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Configurações do driver NVIDIA
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---


# Configurações do driver NVIDIA

Se você estiver usando uma GPU NVIDIA, mas descobrir que o desempenho é lento, há duas causas comuns:

1. Drivers ausentes ou não atualizados
1. O Sampler está usando a GPU incorreta

## Atualizar drivers

Para atualizar os drivers NVIDIA:

1. Ir para a página de download de driver da NVIDIA - <https://www.nvidia.com/Download/index.aspx?lang=en-us>
1. Selecione o modelo da GPU e baixe os drivers.
1. Instale os drivers com o arquivo baixado.

Depois que os drivers mais recentes forem instalados, abra o Sampler para ver se o desempenho melhorou. Se o desempenho estiver lento, o Sampler pode estar usando a GPU incorreta.

## Configurar o Sampler

Para verificar qual GPU Sampler está usando, faça o seguinte:

![](../../assets/nvidiacontrolpanel.png)

1. Abra o painel de controle do NVIDIA. Para abrir o painel de controle da NVIDIA, siga um destes procedimentos:
   1. Procure o painel de controle do NVIDIA usando o menu Iniciar
   1. Na bandeja do sistema, clique com o botão direito do mouse no ícone Geforce e selecione NVIDIA Control Panel.
1. No painel de controle da NVIDIA, selecione Gerenciar configurações 3D no menu esquerdo.
1. Selecione a guia Configurações do programa.
1. Em Selecione um programa para personalizar, use o menu suspenso para localizar o Sampler.
1. Se o Sampler não estiver listado na lista suspensa, use Adicionar.
   1. Procure para encontrar o local de instalação da Sampler (O local de instalação padrão é **C:/Arquivos de Programas/Adobe/Adobe Substance 3D Sampler**).
   1. Selecione **Adobe Substance 3D Sampler.exe** do local de instalação.
1. Com o Sampler selecionado, em “Selecione o processador gráfico preferido para este programa:”, selecione “Processador de alto desempenho NVIDIA”.
1. Clique em Aplicar.

Após ter seguido esse processo, abra o Sampler para ver se o desempenho melhorou.
