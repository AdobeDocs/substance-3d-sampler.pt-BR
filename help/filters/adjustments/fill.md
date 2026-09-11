---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/adjustments/fill.html"
breadcrumb-title: ''
description: Use o filtro Preenchimento no Substance 3D Sampler para preencher áreas de textura com cores sólidas ou padrões para fluxos de trabalho de criação de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Fill
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Preenchimento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '741'
ht-degree: 4%

---


# Preenchimento

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/Fill_Icon_1.png)

**Entrada:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O **Filtro de preenchimento** permite substituir ou ajustar os valores de canais específicos com base em um valor selecionado.
No Sampler 6.0, o filtro Preenchimento adapta seus parâmetros com base no tipo de canal ao qual é aplicado. Isso garante que os controles disponíveis sempre correspondam ao significado físico e ao tipo de dados do canal selecionado, e que o filtro possa ser aplicado a qualquer mapa, mesmo a partir de fluxos de trabalho personalizados.

Nas imagens abaixo, o canal de cor de base foi substituído.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/fillnobc.png.img.png){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/fillbc.png){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parâmetros

<b>Aplicado a...</b>

O menu suspenso Aplicado a... determina o canal afetado pelo filtro Preenchimento.
**Somente os canais que estão atualmente habilitados nas configurações de canal do material aparecem nesta lista.** Se o canal que você deseja preencher não estiver disponível:

* Abra o painel de configurações do canal (na parte inferior da barra de navegação esquerda)
* Clique em “Editar lista”
* Habilitar o canal desejado
* Reaplicar ou atualizar o filtro Preenchimento

Uma vez ativado, o canal fica disponível no menu suspenso Aplicado a....

<b>Parâmetros básicos</b>

Os parâmetros do filtro Preenchimento **mudam dinamicamente dependendo do tipo de canal** selecionado em Aplicado a.... Há quatro conjuntos de parâmetros, cada um correspondente a um tipo específico de mapa.

### Parâmetros do mapa de cores

Usado quando o filtro Preenchimento é aplicado a canais de cores.

#### Exemplos de canais:

* Cor de base
* Cor do revestimento
* Cor da Subsuperfície...

#### Parâmetros disponíveis

* Cor
Seleciona a cor do RGB para preencher o canal.
* Valor personalizado
Alterne para abrir o mapa personalizado. Selecione uma imagem para substituir o canal selecionado ou tinta diretamente no **Visualização 2D**.
* Semente aleatória
Altera a aleatoriedade usada quando variações processuais estão habilitadas.
* Modo de mesclagem
Determina como o preenchimento se mescla com as camadas abaixo (por exemplo: Copiar, Adicionar, Multiplicar).
* Opacidade
Ajuste a opacidade das informações do novo canal em relação às informações do canal existente. Em outras palavras, controla a opacidade da máscara usada para aplicar o novo preenchimento de canal.

Esse modo é geralmente usado para inicializar ou substituir informações de cores.

### Parâmetros do mapa em tons de cinza

Usado quando o filtro Preenchimento é aplicado a canais em tons de cinza escalares.

#### Exemplos de canais:

* Rugosidade especular
* Espessura da base metálica
* Opacidade
* Height...

#### Parâmetros disponíveis

* Valor
Define um único valor de tons de cinza para o canal.
* Semente aleatória
Altera a aleatoriedade usada quando variações processuais estão habilitadas.
* Valor personalizado
Alterne para abrir o mapa personalizado. Selecione uma imagem para substituir o canal selecionado ou tinta diretamente no **Visualização 2D**.
* Modo de mesclagem
Copiar, Adicionar (Subexposição linear), Subtrair, Multiplicar, Adicionar inferior, Máx (clarear), Mín (Escurecer), Alternar, Dividir, Sobreposição, Tela, Luz indireta.
Selecione o modo de mesclagem para mesclar a entrada personalizada com as camadas abaixo.
* Opacidade
Ajuste a opacidade das informações do novo canal em relação às informações do canal existente. Em outras palavras, controla a opacidade da máscara usada para aplicar o novo preenchimento de canal.

Esse modo é útil para definir propriedades físicas uniformes, como um valor constante de aspereza ou opacidade.

#### parâmetros de mapa normal

Usado quando o filtro Preenchimento é aplicado a canais **Normais**.

##### Exemplos de canais:

* Normal
* Revestimento normal

##### Parâmetros disponíveis

* Semente aleatória
Altera a aleatoriedade usada quando variações processuais estão habilitadas.
* Valor personalizado
Alterne para abrir o mapa personalizado. Selecione uma imagem para substituir o canal selecionado ou tinta diretamente no **Visualização 2D**.
* Opacidade
Ajuste a opacidade das informações do novo canal em relação às informações do canal existente. Em outras palavras, controla a opacidade da máscara usada para aplicar o novo preenchimento de canal.

Esse modo é usado principalmente para redefinir ou neutralizar informações normais, ou para estabelecer uma linha de base limpa antes de adicionar detalhes normais.

### Parâmetros de valor uniforme

Usado para canais que dependem de um único valor físico uniforme em vez de um mapa de textura.

#### Exemplos de canais

* Specular...

#### Parâmetros disponíveis

* Semente aleatória
Altera a aleatoriedade usada quando variações processuais estão habilitadas.
* Valor
Define o valor constante aplicado ao canal.
* modo Combinar
Entre normal e multiplicação

Esse modo é particularmente útil ao trabalhar com comportamentos avançados de material introduzidos por meio de modelos, em que algumas propriedades são controladas por valores escalares em vez de mapas.

## Casos de uso típicos

O filtro Preenchimento é normalmente usado para:

* Inicializar canais ao criar um material do zero
* Substituir valores de canal existentes
* Definir propriedades físicas uniformes (por exemplo, aspereza fixa ou metalidade)
* Neutralize canais como Normal antes de reconstruir os detalhes
* Ajuste rapidamente propriedades avançadas, como valores de difusão, translucidez ou revestimento

Como o filtro Preenchimento se adapta automaticamente ao canal selecionado, ele fornece um fluxo de trabalho consistente e previsível em todos os tipos de material.
