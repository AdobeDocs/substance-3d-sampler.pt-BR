---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/scripting-and-development/create-a-script-with-python.html"
breadcrumb-title: ''
description: Saiba como criar scripts Python para o Substance 3D Sampler para automatizar fluxos de trabalho e ampliar a funcionalidade do aplicativo.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Criar um script com Python
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---


# Criar um script com Python

Este guia descreve como criar um plug-in simples de salvamento automático com o Python.

## Estrutura de script

Os scripts exigem um único arquivo PY para serem importados para o Sampler. Você pode salvar o script de exemplo abaixo como um arquivo PY e importá-lo para o Sampler.

## Exemplo de script

O script abaixo cria automaticamente variações do seu material selecionando uma nova semente aleatória para cada camada no material. Isso é útil para garantir que seu material possa ser usado em um caso geral, em vez de depender de sementes aleatórias específicas.

### random\_seed\_variation.py

```
import substance_sampler as ssa 

from random import randrange 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Create a list of all layers of the current asset

my_asset_layers = my_asset.get_layers() 

 

## Go through the layers list

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## if the parameter is Random Seed, change is value

        if parameter.label == "$randomseed": 

            parameter.value = randrange(10000) 

            print(f"Random Seed for layer {layer.name}: {parameter.value}") 

 
```


O código acima inclui comentários para explicar o que está acontecendo em cada linha.

## Importar o script

Depois de salvar o script acima como um arquivo PY em seu computador, você pode importá-lo com Editar > Preferências > Plug-ins e scripts. Uma vez importada, uma opção de **Scripts** aparecerá na barra de menus ao lado de **Arquivo** e **Editar**. Aqui você pode executar o script.

Você pode saber mais sobre o gerenciamento de scripts [aqui](../manage-installed-plugins-and-scripts.md).
