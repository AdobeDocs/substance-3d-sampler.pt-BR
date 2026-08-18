---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/technical-support/technical-issues/startup-issues/application-doesn-t-start-on-linux.html"
breadcrumb-title: ''
description: Saiba como corrigir problemas de inicialização do Substance 3D Sampler no Linux para resolver problemas de inicialização de aplicativos e mensagens de erro.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Startup issues > Application doesnt start on Linux
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: O aplicativo não inicia no Linux
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---


# O aplicativo não inicia no Linux

O aplicativo pode não iniciar no Linux com a seguinte mensagem de erro em um terminal:

```
error while loading shared libraries: libicui18n.so.50
```


Isso significa que o ICU da biblioteca ([Componentes Internacionais para Unicode](http://site.icu-project.org/)) está ausente ou a versão instalada é muito recente. O aplicativo precisa da versão 50.

Para resolver esse problema, instale a versão 50 do gerenciador de pacotes ou [baixe manualmente](http://mirror.centos.org/centos/7/os/x86_64/Packages/libicu-50.2-4.el7_7.x86_64.rpm) a versão ausente ao instalá-la em **/usr/lib64** .
