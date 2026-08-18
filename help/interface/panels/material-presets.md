---
breadcrumb-title: ''
description: Saiba mais sobre predefinições de material, como aplicar uma predefinição ao material e como criar e gerenciar predefinições personalizadas.
title: Predefinições de material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6fe7ff5c975480f2e8852dd8b443c6650bd883ea
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 4%

---


# Predefinições de material

Os modelos de criação de material fornecem pontos de partida predefinidos para materiais de construção com comportamento físico avançado. Cada modelo configura o modelo de material, os canais ativados e os parâmetros padrão necessários para um tipo específico de superfície, permitindo que você crie materiais complexos rapidamente, mantendo o controle total sobre o resultado.
Os modelos estão disponíveis ao criar um novo material e podem ser usados com modelos de material de OpenPBR e ASM.

![A janela Criar novo material](../../assets/6.0_materialPresets.png)

## Criar um material a partir de um modelo

Para criar um material usando um modelo:

Abra a caixa de diálogo Criar novo material.
Selecione um modelo nas guias Predefinido ou Personalizado.
Ajuste as configurações do material (nome, resolução, modelo de material, canais).
Clique em Criar para começar a trabalhar com o material configurado.

O modelo selecionado define a estrutura inicial do material, incluindo quais canais estão ativados e como estão configurados na Pilha de camadas.

## Categorias predefinidas

### Modelos predefinidos

Os modelos predefinidos são configurações de material prontas para uso projetadas para cobrir comportamentos comuns de material físico. Eles codificam práticas recomendadas e configurações de canal recomendadas para cada caso de uso.
Os modelos predefinidos disponíveis incluem:

* Material de base
Um material padrão de base física com canais comumente usados ativados. Use este modelo para materiais simples ou genéricos que não exigem comportamento especializado.

* Anisotropia
Configura o material para reflexões dependentes de direção, adequado para metais escovados ou superfícies com microdetalhes orientados.

* Revestimento
Adiciona uma camada reflexiva secundária na parte superior do material de base, permitindo efeitos de revestimento transparente ou semelhante a verniz.

* Fuzz
Permite efeitos de superfície suaves e de dispersão de luz usados para tecidos, fibras ou materiais com uma aparência aveludada.

* Subsuperfície
Ativa o transporte de luz subsuperficial para materiais como cera, plástico ou superfícies orgânicas onde a luz penetra abaixo da superfície.

* Transparente
Configura o material para transmissão de luz, adequado para materiais transparentes finos ou semelhantes a vidro.


Cada predefinição configura os canais necessários e os valores padrão automaticamente, reduzindo a configuração manual e a complexidade técnica.

### Predefinições personalizadas

As predefinições personalizadas permitem que você reutilize suas próprias configurações de material.
Qualquer predefinição de material criada pode ser salva como um modelo personalizado e aparecerá na guia Personalizado. Isso permite a criação consistente de materiais entre projetos ou equipes, usando padrões compartilhados e configurações de canal.

## Detalhes da predefinição

O painel Detalhes da predefinição exibe e controla as configurações usadas para criar o novo material.

### Nome do ativo

Define o nome do ativo de material que será criado.

### Resolução

Controla a resolução padrão dos mapas de material (largura e Height). Essa resolução se aplica a todos os canais ativados quando o material é criado.

### Modelo do material

Especifica o modelo de material usado pelo material:

OpenPBR para fluxos de trabalho físicos modernos e padronizados
ASM para compatibilidade com pipelines existentes

O modelo selecionado se adapta ao modelo de material escolhido.

### Adicionar material de base

Quando ativada, o Sampler cria uma camada base de preenchimento usando uma material de base compatível com o modelo selecionado. Isso fornece um resultado visual imediato e um ponto de partida utilizável. O material de base é adaptado para modelos de material de OpenPBR e ASM.

### Aplicar valores predefinidos de miniaturas

Quando ativado, o material é inicializado com os valores usados para gerar a miniatura de visualização do modelo, em vez de padrões neutros. Isso ajuda a demonstrar o comportamento pretendido do modelo e a ter uma base visual para começar a desenvolver.

### Editar lista

Clique em **Editar lista** para personalizar o conjunto de canais antes de criar o material. É possível ativar ou desativar canais conforme necessário ou salvar a configuração como um novo modelo personalizado.

