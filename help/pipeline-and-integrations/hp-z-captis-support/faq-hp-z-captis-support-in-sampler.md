---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/faq-hp-z-captis-support-in-sampler.html"
breadcrumb-title: ''
description: Acesse perguntas frequentes sobre o suporte ao HP Z Captis no Substance 3D Sampler para encontrar respostas sobre a integração e o uso do hardware.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Perguntas frequentes sobre o suporte ao HP Z Captis no Sampler
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1547'
ht-degree: 0%

---


# Perguntas mais frequentes

## Amostras de materiais

+++Quais casos de uso são cobertos pelo Captis?
A solução abrange casos de uso entre setores (automotivo, vestuário, design de produtos, mídia e entretenimento, arquitetura...). O Modo Studio permite a captura no desktop (repetível, eficiente e simples) enquanto o Modo Explorer permite a captura móvel “flexível, em qualquer lugar, adaptando-se a cada situação”.

+++

+++Quais tipos de material podem ser digitalizados e capturados com o Captis?
Qualquer tipo de material pode ser digitalizado e capturado, exceto com várias camadas de revestimento claras (tintas de carro são excluídas do escopo Captis). Alguns materiais específicos podem exigir processamento adicional no Sampler para otimizar os resultados. Observe que os algoritmos de processamento serão continuamente otimizados ao longo do tempo.

+++

+++Quais são as restrições sobre o tamanho ou a forma da amostra do material? As amostras precisam ser planas?
Captis pode digitalizar uma grande variedade de amostras de material de tamanho ou forma. É administrado com ímãs para achatar as amostras no tabuleiro de amostra. Há vários modos para capturar uma amostra de material com o Captis:

* Modo de estúdio: com a base de estúdio em sua mesa, no estúdio ou na fábrica, a Captis colherá amostras de até 30cm x 30cm - com iluminação de fundo para opacidade. A profundidade da bandeja de amostras é de 1,8 CM.

* Modo Explorer: você pode utilizar o anel do explorador no campo, no conjunto ou em ambientes exclusivos e ativar a captura flexível para amostras maiores do que 30cm x 30cm. Limitação atual: observe que o modo Explorer ainda é uma versão anterior e ainda não foi otimizado (a partir da versão de 29 de julho de 2024).

+++

## Software

+++O dispositivo HP Z Captis requer uma assinatura ou licença de software para uso?
O dispositivo Captis requer uma licença ativa do Substance 3D Sampler para corporações, equipes ou universidades, disponível na coleção do Substance 3D nas mesmas condições e termos de uso de qualquer assinatura do Substance 3D.

O dispositivo (HP Z Captis) e a licença (Substance 3D Sampler) são vendidos separadamente.

+++

+++Qual é o nível de integração com o pacote de Substance do Adobe?
O dispositivo HP Z Captis é totalmente controlado e operado por meio do Adobe Substance 3D Sampler: você pode visualizar e iniciar a captura no Substance 3D Sampler e, quando a captura for concluída, ele carregará automaticamente os canais PBR como uma camada e criará um material 3D. Você pode continuar processando seus materiais com todas as ferramentas e filtros disponíveis no Sampler.

Depois que o material capturado estiver no Substance 3D Sampler, você poderá exportá-lo para qualquer aplicativo do conjunto do Substance 3D (Substance 3D Designer, Painter, Stager) e para qualquer aplicativo de terceiros que ofereça suporte ao Substance, incluindo 3DS Max, Maya, Blender, Unreal Engine, CLO, Browzwear, VRED, Rhino, Cinema4D e muitos outros (veja a lista completa aqui: <https://www.adobe.com/products/substance3d/plugins.html>).

+++

+++Quais são as especificações recomendadas para usar o Substance 3D Sampler com o Captis?
As especificações de hardware do Sampler estão disponíveis [aqui](system-requirements-to-use-hp-z-captis.md).

+++

+++O fluxo de trabalho do HP Z Captis está disponível no Windows e no Mac?
A partir da versão de 20 de fevereiro de 2025, o fluxo de trabalho do Sampler com HP Z Captis estará disponível somente no Windows.

+++

+++Onde posso encontrar a versão do Substance 3D Sampler com o fluxo de trabalho do HP Z Captis?
A partir da versão de 20 de fevereiro de 2025, você pode acessar o Adobe Substance 3D Sampler com o fluxo de trabalho do Captis como parte das compilações regulares do Substance 3D Sampler, baixadas do aplicativo de desktop Creative Cloud. Não é mais necessário baixá-los do Adobe Prerelease.

+++

+++O que ainda não está disponível?
*Limitações a partir de agosto de 2025 (compilação do Sampler 5.1.0):*

* O fluxo de trabalho do Sampler com HP Z Captis está disponível somente no Windows por enquanto.

* Os cinco mapas que estão sendo exportados hoje são Cor de base, Aspereza, Normal, Height, Opacidade.

* O Modo Explorer ainda é uma versão anterior e ainda não está otimizado.

* A divisão em blocos é executada no Sampler pilha de camadas usando os filtros de divisão em blocos atuais.

+++

+++Quais canais PBR estão disponíveis?
A partir da versão de 7 de agosto de 2025, os cinco mapas que estão sendo exportados são Cor de base, Aspereza, Normal, Height, Opacidade. O pipeline de processamento atual ainda não trata do mapa do Metalness.

+++

+++A divisão em blocos gráficos é feita automaticamente?
A divisão em blocos gráficos é executada na pilha de camadas do Sampler usando os filtros de divisão em blocos gráficos atuais.

O filtro de revestimento automático pode ser usado para revestir automaticamente materiais com uma estrutura repetitiva definida ou pequenos padrões, com um mínimo de 3 padrões em cada direção. Saiba mais sobre este filtro na [seção dedicada da documentação](../../filters/tools/auto-tiling.md).

+++

+++Como quais formatos os materiais digitalizados podem ser exportados?
O HP Z Captis é operado de forma nativa pela Adobe Substance 3D Sampler. O HP Z Captis captura 64 imagens raw (que podem ser recuperadas de sua pasta local) e mapas PBR (que são processados a partir das imagens raw capturadas e que são carregadas automaticamente no Substance 3D Sampler). O Substance 3D Sampler criará um material 3D com base nos canais PBR que são carregados automaticamente no Sampler pilha de camadas após a captura.

No Adobe Substance 3D Sampler, você pode exportar seu material digital em qualquer formato de exportação disponível no Substance 3D Sampler: como arquivos Substance (arquivos .SBS e .SBSAR) ou como texturas de bitmap, incluindo .PNG, .JPG, .TIFF, ... (consulte os detalhes na página da documentação da Sampler: [https://helpx.adobe.com/substance-3d-sampler/getting-started/export.html](../../getting-started/export/export.md)).

+++

+++Qual é a diferença entre LDR e HDR durante a captura?
Durante a visualização, você tem a possibilidade de escolher o tipo de saída entre LDR (intervalo dinâmico baixo) e HDR (intervalo dinâmico).\
Mesmo se o LDR for escolhido, os mapas de HDR serão capturados e salvos no seu dispositivo.\
É aconselhável selecionar o LDR, pois isso tornará o tamanho do projeto mais gerenciável no Sampler e em qualquer aplicativo de terceiros onde o arquivo sbsar será usado.

+++

## Processamento

+++Como posso usar o Captis no meu pipeline 3D atual se eu usar formatos de arquivo, padrões e especificações específicos ou aplicativos de terceiros?
O HP Z Captis é operado de forma nativa pela Adobe Substance 3D Sampler. Depois de capturar e digitalizar sua amostra de material no Substance 3D Sampler, você pode exportar perfeitamente seus materiais digitais:

Em quaisquer aplicativos do ecossistema Substance 3D (incluindo Substance 3D Designer ou Substance 3D Painter que suportam vários formatos de exportação: https://experienceleague.adobe.com/en/docs/substance-3d/general-knowledge/ecosystem/import-and-export-formats).

Em todos os aplicativos que integram o formato de arquivo Substance como 3DS Max, Maya, Blender, C4D, Rhino, Browzwear, CLO... (veja a lista completa aqui: <https://www.adobe.com/products/substance3d/plugins.html>). Se você estiver usando um aplicativo não listado nele, sempre poderá exportar imagens de textura PBR e conectá-las manualmente em qualquer aplicativo que não ofereça suporte ao formato de arquivo Substance nativamente.

+++

+++Quantas fotos estão sendo tiradas para criar os mapas?
[8 painéis de luz + 1 retroiluminação] x [8 estados de polarização] x [8 exposições de agrupamento para HDR] x [4 sobreposições para reduzir o ruído] = 2048 + 256 (para retroiluminação)

+++

## Gerenciamento de dispositivos

Saiba mais sobre o dispositivo e suas especificações no [site da HP](https://www.hp.com/us-en/workstations/z-captis.html "HP Z Captis").

+++Posso alterar o endereço IP do dispositivo?
Para alterar o endereço IP do dispositivo, você pode modificar o arquivo do Windows C:\Windows\System32\drivers\etc\hosts.txt by adicionando uma linha extra:

Por exemplo, você pode adicionar 192.168.55.1 captis-device e, em <b>Configurações do Sampler > Armazenamento e cache > Captura de material > endereço Captis</b>, substituir o IP por captis-device

+++

## Problemas de uso

+++O Sampler não detecta o HP Z Captis.
Verifique se o HP Z Captis está conectado a uma porta USB 3.0.

Verifique se o cabo USB está conectado à base do HP Z Captis e não ao cone.

+++

+++Minha visualização está completamente preta na janela do Sampler.
Certifique-se de ter a proteção da câmera removida.

+++

+++A cópia de arquivos do HP Z Captis para o meu computador é lenta.
Verifique se o HP Z Captis está conectado a uma porta USB 3.0.

Se for solicitada a recuperação do material e das imagens fotométricas, é normal que a cópia demore mais.

+++

+++O Sampler não copiou as imagens para o meu computador. Tenho que reiniciar a varredura?
Não, você não tem. Você pode navegar pelo conteúdo do dispositivo e copiar as imagens encontradas na pasta Adobe usando o explorador de arquivos de seu sistema operacional.

+++

+++O menu indica que o dispositivo está no modo de recuperação.
Pressione o botão liga/desliga por alguns segundos para desligá-lo. Ligue-o novamente.

+++

+++Movi o cone de sua base para o anel do explorador e não consigo mais varrer.
É recomendável desativar o HP Z Captis antes de desconectá-lo da base ou do anel do explorador.

+++

+++A exportação do meu material em SBSAR está lenta.
Verifique se as imagens não estão no formato float de 32 bits no painel Propriedades.

Você também pode definir o nível de compactação como “nenhum” para agilizar a exportação.

+++

+++Quero alterar o caminho de salvamento dos materiais capturados e das imagens de fotometria.
Agora é possível editar o local onde os materiais e as imagens de fotometria capturados serão salvos, em Editar > Preferências > Armazenamento e cache > Captura de material.

+++

+++A janela é maior que a tela e não posso redimensioná-la.
A janela do Captis não é de fato redimensionável. Talvez você esteja usando uma ampliação de tela que não foi manipulada. O Captis oferece suporte ao seguinte:

* Resolução: 1920 x 1080
  * Ampliação máxima: 100%

* Ampliação máxima: 100%

* Resolução: 2560 x 1440
  * Ampliação máxima: 125%

* Ampliação máxima: 125%

* Resolução: 3840 x 2160
  * Ampliação máxima: 200%

* Ampliação máxima: 200%

* Resoluções abaixo de 1920x1080 não são compatíveis.



+++
