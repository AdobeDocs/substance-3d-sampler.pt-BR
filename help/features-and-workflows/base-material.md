---
breadcrumb-title: ''
description: Saiba como usar o Material de base no Sampler, um ótimo ponto de partida para a edição eficiente de materiais.
title: Usar como bitmap
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 4%

---


# Material de base

O **Material de base** é uma camada de material fundamental projetada para fornecer a você um ponto de partida rápido e flexível ao criar materiais no Sampler. Ele expõe um conjunto abrangente de parâmetros que se adaptam automaticamente ao **modelo de material** usado pelo seu material (OpenPBR ou ASM), permitindo que você crie qualquer coisa, de superfícies simples a materiais complexos e fisicamente ricos.
Não importa se você está começando de uma predefinição ou criando um material do zero, o Material de base garante que você sempre comece com uma **base clara, previsível e editável**.

## Reconhecimento do modelo de material (OpenPBR versus ASM)

O Material de base tem **reconhecimento de modelo de material**.
Isso significa que as propriedades disponíveis e os valores padrão mudam dependendo se o material foi criado usando:

* OpenPBR
* ASM (Adobe Standard Material)

Embora ambas as versões sirvam para o mesmo propósito, elas expõem **diferentes grupos de parâmetros e comportamentos**, correspondendo ao modelo de material subjacente:

### Material de base de OpenPBR

Os grupos de parâmetros incluem:

* Base
* Especular
* Transmissão
* Subsuperfície
* Casaco
* Fuzz
* Emissão
* Filme fino
* Geometria
* Diversos

Esses parâmetros se alinham à representação unificada e baseada fisicamente do OpenPBR e são projetados para interoperabilidade em todo o ecossistema 3D.

### MATERIAL DE BASE ASM

Os grupos de parâmetros incluem:

* Superfície
* Absorção
* Dispersão
* Translucidez
* Casaco
* Brilho
* Emissão
* Geometria

Esse layout espelha o modelo de sombreamento do ASM e garante a continuidade com os fluxos de trabalho existentes baseados no ASM.

>[!NOTE]
>
>O Material de base sempre se adapta ao modelo de material do material ao qual é aplicado. Um Material de base aplicado a um material de OpenPBR não exporá os parâmetros do ASM e vice-versa.

## Valores Uniformes e Mapas Personalizados

Para cada parâmetro exposto, o Material de base fornece duas maneiras de trabalhar:

### Valores uniformes (padrão)

Por padrão, os parâmetros usam valores uniformes (controles deslizantes ou seletores de cores).
Isso permite definir rapidamente a aparência geral do material sem nenhuma entrada de textura.

Valores uniformes são ideais para:

* Bloqueando materiais
* Criar superfícies simples e limpas
* Estabelecer um ponto de partida visual

### Mapas personalizados

Se você já tiver mapas de textura, poderá **substituir qualquer valor uniforme** habilitando sua **entrada de mapa personalizado**.

* Alternar a opção de mapa personalizado para o parâmetro
* Conectar a textura existente
* O mapa substitui completamente o valor uniforme

## Predefinições

O Material de base inclui um conjunto de **predefinições**, visíveis como miniaturas na parte superior do painel Propriedades.
As predefinições fornecem:

* Valores de Material de base pré-configurados
* Uma maneira rápida de começar com uma configuração visualmente significativa
* Pontos de partida consistentes e legíveis para tipos de superfície comuns

Selecionar uma predefinição não bloqueia o material. Todos os parâmetros permanecem totalmente editáveis.

## Aplicar valores predefinidos ao criar um material

Ao criar um novo material, você pode optar por aplicar valores predefinidos do painel Criar novo material.
O que isso faz

* Substitui os valores padrão da Material de base pelos valores representados pela miniatura predefinida selecionada
* Fornece um ponto de partida visual imediato, em vez de padrões neutros
* Ajuda a reduzir o efeito de “página em branco” ao iniciar um novo material

O que ela não faz

* Ele não faz bake nem congela valores
* Isso não impede outras edições
* Isso não adiciona mapas de textura automaticamente

Você pode pensar nisso como escolher por onde começar, não limitar aonde pode ir.

## Ativação do canal: uma etapa crítica

Para que um parâmetro de Material de base tenha um efeito visível, o canal correspondente deve estar ativado nas Configurações do canal do material.

### Prática recomendada

Antes de ajustar um parâmetro, verifique se o canal está ativado
Ative apenas os canais necessários para manter seu material limpo e eficiente