---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/interface/panels/share-panel.html"
breadcrumb-title: ''
description: Saiba como usar o painel Exportar no Substance 3D Sampler para exportar materiais como arquivos ou enviá-los diretamente para outros aplicativos.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Export panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Painel Exportar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '487'
ht-degree: 3%

---


# Painel Exportar

O <b>painel Exportar</b> é onde você pode exportar seus ativos como arquivos gerais ou enviar ativos diretamente para outros aplicativos.

## Enviar para...

As opções Enviar para... permitem enviar diretamente o ativo para outros aplicativos instalados no sistema. Isso geralmente é muito mais rápido do que importar e exportar ativos.

Atualmente, o Sampler oferece suporte ao envio para:

* **Substance 3D Painter**: importe materiais e ambientes que você pode usar ao texturizar seus ativos.
* **Substance 3D Stager**: importa luzes ambiente para alterar o clima da cena. Disponível apenas com luzes ambiente, desativadas para materiais.

Os materiais são sempre enviados como SBSAR, ambientes como EXR.

## Exportar

Clique em **Exportar como...** para exportar o ativo no qual você está trabalhando. Selecione se deseja modificar Configurações gerais ou Configurações de material no menu à esquerda.

### Configurações gerais

Com Configurações gerais selecionadas, é possível alterar o nome do material e o local de salvamento. Você também pode alternar entre criar uma subpasta para o material. Isso pode ser útil ao exportar em um formato de imagem que cria vários arquivos.

### Configurações do material

Com as Configurações de material selecionadas, você pode alterar vários parâmetros para controlar como o material será exportado:

| Configuração | Descrição |
| --- | --- |
| Formato | Escolha se deseja exportar como SBS, SBSAR ou como uma coleção de imagens em um formato de imagem específico |
| Predefinição | Selecione uma predefinição para organizar automaticamente sua exportação para um aplicativo específico. [Mais informações sobre predefinições estão disponíveis aqui](../../getting-started/export/default-presets/default-presets.md). As predefinições só estão disponíveis quando um formato de imagem é selecionado. |
| Compactação | Escolha se a compactação prioriza velocidade ou eficiência <br> <ul> <li> **Automático**: permita que o Sampler escolha. <li> **Melhor**: maximize a eficiência da compactação para arquivos menores. <li> **Nenhum**: nenhuma compactação significa abertura e fechamento mais rápidos dos arquivos exportados, mas tamanhos de arquivo maiores. </ul> |
| Resolução | Altere a resolução da exportação. Esta opção aparece de forma diferente com base no Formato selecionado <br> <ul> <li> **SBSAR/SBS**: selecione uma largura e um height padrão para o material. Eles podem ser atualizados posteriormente. <li> **Formato de imagem**: selecione entre **a saída de camadas**, que exporta cada mapa no tamanho definido pela pilha de camadas, ou **Substitua tudo**, que permite especificar uma largura e um height para exportação. |
| Modelo do material | Selecione se deseja exportar como um Material padrão da Adobe ou como um material de OpenPBR. A opção selecionada deve depender dos outros aplicativos que você está usando no pipeline. Canais diferentes estarão disponíveis com base no Modelo de material. |
| Canais | Alterne quais canais devem ser exportados como parte do ativo. |

>[!NOTE]
>
> Para obter mais informações sobre as opções da caixa de diálogo Exportar e outras informações, como formatos de arquivo, consulte o [Artigo de exportação](../../getting-started/export/export.md) e seu [subartigo na Janela de Exportação](../../getting-started/export/export-window/export-window.md).

Quando estiver satisfeito com as configurações de exportação, clique em **Exportar**. Sua exportação aparecerá na fila de exportação, que mostra uma lista de exportações recentes. Clique no ícone de pasta em qualquer exportação para abrir o local do arquivo dessa exportação.
