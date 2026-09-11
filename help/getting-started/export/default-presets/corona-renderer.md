---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/export/default-presets/corona-renderer.html"
breadcrumb-title: ''
description: Saiba mais sobre como exportar materiais do Substance 3D Sampler usando a predefinição Renderizador Corona para fluxos de trabalho de visualização arquitetônica.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Default Presets > Corona Renderer
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Renderizador Corona
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '91'
ht-degree: 2%

---


# Renderizador Corona

| Predefinição | Compatibilidade | Descrição da Saída de Embalagem |
| --- | --- | --- |
| Renderizador Corona | <ul data-preserve-html="true"><li data-preserve-html="true">PBR metálico/aspereza</li><li data-preserve-html="true">Specular/textura reluzente do PBR</li></ul> | **Difusões***RefletionGlossiness **(\*)** RefletionColor **(\*\*)** FresnelIOR **(\*\*\*)** Normal ****Deslocamento**** Emissivo****Opacidade** |

>[!NOTE]
>
> **(\*)** Textura reluzente de reflexão: Versão quadrada do canal de textura reluzente (Textura reluzente \*)
> 
> **(\*\*)** Cor de reflexão: exportar um mapa em que o branco indica materiais dielétricos e outras cores para materiais metálicos
> 
> **(\*\*\*)** Frenesl IOR: 1 dividido pelo valor ior, ior é gerado do mapa metálico: 1,4 para dielétricos, 100 para metais (cor preta)
