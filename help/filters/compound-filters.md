---
helpx_url: 'https://helpx.adobe.com/br/substance-3d-sampler/filters/compound-filters.html'
breadcrumb-title: ''
description: Saiba como criar e usar filtros compostos no Substance 3D Sampler para combinar vários filtros em camadas reutilizáveis únicas.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Compound Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Filtros compostos
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 0%

---


# Filtros compostos

Esse recurso permite criar um novo tipo de filtro que é representado como uma única camada na interface e que é composto de vários filtros.

>[!NOTE]
>
> Compatível desde o Substance 3D Sampler 3.1.0

## Descrição

Um filtro composto é um arquivo **.ssafilter** que é uma pasta compactada .7zip de:

* um arquivo de descrição usando formatação JSON: **meufiltro\_nome.json**
* uma pasta **recursos** contendo:
  * a miniatura do filtro: icon.png
  * dependências de arquivos externos

### Descrição do conteúdo do arquivo

* Nome: rótulo do filtro composto exibido na interface
* ID: identificador exclusivo do filtro composto
* Categoria: categoria do filtro composto usada no painel Ativos ao agrupar ativos por categoria
* Versão: número incremental para definir a versão do filtro composto.
* Nó: lista de nós a serem usados
* Link: lista de conexões entre os diferentes nós

### Exemplo

```JSON
{ "SamplerFilter":  
 { 
 "Name": "My filter", 
 "Category": "My filter category", 
 "Id": "my_unique_id", 
 "Version": 2, 
 "Node": [ 
        { 
            "Id": "foo", 
            "InternalFilter": "Foo" 
        }, 
        { 
            "Id": "bar", 
            "File": "bar.sbsar" 
        } 
    ], 
    "Link": [ 
        { 
            "From": { "Node": "FilterInput", "Usage": "baseColor" }, 
            "To": { "Node": "foo", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "FilterInput", "Usage": "normal" }, 
            "To": { "Node": "foo", "Usage": "normal"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "baseColor" }, 
            "To": { "Node": "bar", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "bar", "Usage": "baseColor" }, 
            "To": { "Node": "FilterOutput", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "normal" }, 
            "To": { "Node": "FilterOutput", "Usage": "normal"} 
        } 
    ] 
}}
```

## Criação passo a passo

1. Criar um novo arquivo: **meu\_novo\_filtro.json**
1. Definir nome, ID, categoria,...
1. Defina a lista de nós necessários
1. Se precisar de arquivos externos, crie a pasta **recursos** ao lado de seu **.json**
1. Adicionar seu(s) arquivo(s) à pasta **recursos**
1. Escreva a lista de links entre os nós
1. Verifique se o JSON é válido (sem erro de digitação, coma ausente ou colchete ausente)
1. Se quiser uma miniatura, adicione uma imagem **icon.png** na pasta **recursos**
1. Selecione o arquivo **.json** e a pasta **resources** e compacte-os em um arquivo 7zip

## Documentação

### Versão

Usar um número de versão permite controlar as diferentes iterações. Ao abrir uma pilha de camadas em uma versão anterior do filtro composto, uma notificação será exibida sugerindo que você atualize para a versão mais recente.

### Nó

Um nó pode fazer referência a um filtro interno do Substance 3D Sampler. Defina um identificador exclusivo **Id** a ser usado para definir links entre nós e o rótulo do filtro interno **InternalFilter**

```JSON
{ 
  "Id": "step1_identifier", 
  "InternalFilter": "Dirt" 
}
```

Um nó pode fazer referência a um arquivo SBSAR que não está no Substance 3D Sampler. Defina um identificador exclusivo **Id** a ser usado para definir links entre nós e o nome de arquivo **Arquivo** do arquivo SBSAR. O arquivo SBSAR deve estar em uma pasta **resources** ao lado do arquivo .alchfilter.

```JSON
{ 
  "Id": "step1_identifier", 
  "File": "foo.sbsar" 
}
```

>[!NOTE]
>
> **filterImg** e **filterMat** não podem ser usados como ID de nó

### Vincular

Um link é uma descrição de como dois nós são vinculados e são compostos por dois elementos:

* De: Uso a ser usado pelo nó
* Para: Saída de uso do nó

Cada elemento tem 3 atributos:

* Nó: declare a **Id** do nó que deseja usar
  * defina a entrada do filtro composto; a ID do nó é **FilterInput**
  * defina a saída da camada composta; a ID do nó é **FilterOutput**
* Uso: declara o uso que deseja usar. Há três opções:
  * Uso único de cada vez e declarar link por link (baseColor, normal, height, ambientOcclusion, aspereza, metálico, difuso, specular, brilho, specularLevel, opacidade, emissivo, scan1, ...)
  * Você também pode especificar uma lista [”baseColor”, “normal”]. O primeiro item da lista de **De** corresponderá ao primeiro item da lista de **Para**. etc.
  * Use **\*** para permitir que o Substance 3D Sampler faça a correspondência entre usos idênticos de todos os usos do nó De e do nó Para (não é possível combinar **\*** com outro link, enquanto links únicos e links de lista são possíveis entre os mesmos nós)
* Grupo: No caso de um nó ter várias vezes o mesmo uso, você pode usar o atributo Grupo para selecionar um uso específico. Ou seja: para filtros de mesclagem, para obter a baseColor do material inferior, use *Material1* e para obter a baseColor do material superior, use *Material2*

```JSON
Link between two nodes  
{ 
  "From": { "Node": "node1","Usage": "baseColor", "Group": ""}, 
  "To": { "Node": "node2", "Usage": "baseColor"} 
} 
 
Link between outputs of layers below of the compound filter and the compound filter: 
{ 
  "From": { "Node": "FilterInput", "Usage": "*" }, 
  "To": { "Node": "node1", "Usage": "*"} 
} 

Link to declare outputs of the compound filter: 
{ 
  "From": { "Node": "node1", "Usage": "*" }, 
  "To": { "Node": "FilterOutput", "Usage": "*"} 
}
```
