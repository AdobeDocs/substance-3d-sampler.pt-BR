---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/filters/generators/embroidery.html"
breadcrumb-title: ''
description: Use o gerador de bordados no Substance 3D Sampler para criar padrões de tecido bordado e texturas de costura para materiais.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embroidery
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Bordado
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---


# Bordado

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embroidery-18-n-d.png)

Geradores de **Entrada:**

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descrição

O filtro Bordado permite que você converta rapidamente imagens em patches bordados. Você pode personalizar a aparência dos patches e usar as ferramentas de gerenciamento de cores para agir como uma máscara para vários materiais.

As imagens abaixo mostram o **filtro de bordados** em ação.

![](../../assets/3d-2d-filters-cropped-0035-embroidery-in.jpg)

Na imagem acima, a imagem de origem foi importada. Observe que a imagem é opaca e tem um plano de fundo branco.

![](../../assets/3d-2d-filters-cropped-0034-embroidery-out.jpg)

Na imagem acima, o **filtro de bordados** foi adicionado à pilha de camadas e converteu a imagem de origem em um patch bordado. Observe que, embora a imagem de origem fosse opaca, a saída do **Filtro de bordados** tinha transparência.

</td>
</tr>
</table>

## Plugin de bordados TajimaName

Interessado em experimentar o plugin de bordados Tajima? \
Saiba mais sobre isso [aqui](../../pipeline-and-integrations/tajima-exporter-plugin.md).

## Parâmetros

<b>Parâmetros Básicos</b>

* <b>Distribuição aleatória</b>:\
  A semente aleatória na qual todos os outros parâmetros aleatórios deste filtro se baseiam.
* <b>Imagem</b>: imagem/máscara\
  Selecione uma imagem do sistema ou pinte uma máscara personalizada.
* <b>Contagem de cores</b>: 1-8\
  O filtro de bordados tentará dividir as imagens importadas em cores separadas, modificando esse valor para alterar o número de cores usadas.
* <b>Densidade</b>: 80-300\
  Selecione a densidade das fibras.
* <b>Design</b>: Preenchimento, Contorno, Preenchimento + Contorno, Topstitch\
  Selecione o modo de bordado: *Preenchimento* preenche toda a zona de cores, *Contorno* cria um contorno da zona de cores, *Preenchimento + Contorno* criam ambos em cada zona de cores e *Ponto de extremidade* cria um contorno de ponto de extremidade da zona de cores.
* <b>Preenchimento/Estrutura de Tópicos: </b>0-1\
  Altere a forma como as fibras são distribuídas na zona de cores.
* <b>Thread</b>:\
  Ajuste o Thickness e o comprimento dos encadeamentos.
* <b>Áreas Suaves: </b>0-1\
  Equilibre as zonas de cores e afete o comportamento dos encadeamentos.
* <b>Imperfeições</b>: 0-1\
  Adicionar imperfeições ao encadeamento para ajudar a quebrar o padrão

<b>Cor 1</b>

Use os controles para ajustar cada zona de cor individualmente.

* <b>Preenchimento</b>: alternar\
  Torne a zona de cores visível ou invisível.
* <b>Height</b>: \
  Deslocar a orientação dos encadeamentos

<b>Término da costura</b>

* <b>Cor Personalizada:</b>\
  Personalize a cor de todo o bordado
* <b>Aspereza: </b>0-1\
  Altere o valor de Aspereza para tornar o bordado áspero ou brilhante.
* <b>Metálico: </b>0-1\
  Altere o valor Metálico para adicionar uma sensação metálica aos encadeamentos.
* <b>Nível de Anisotropia: </b>0-1\
  Altere o Nível de Anisotropia para acentuar o Metalness.

<b>Avançado</b>

* <b>Intensidade Normal</b>: 0-1\
  Ajuste a força dos normais.
* <b>Intervalo de Heights:</b> 0-1\
  Ajuste a posição do Height do Bordado na material de base.
* <b>Posição do Height:</b> 0-1\
  Ajuste a posição do Height do Bordado na material de base.

## Guia de Uso

O filtro Bordado pode ser um pouco confuso no início, mas com apenas alguns parâmetros importantes para começar, você estará adicionando patches aos seus materiais em um piscar de olhos.

>[!NOTE]
>
> Se você já usou o filtro [Entrelaçar](weave.md)antes, o filtro Bordado funciona de maneira semelhante.

Para usar o filtro Bordados:

1. Adicione o filtro Bordado à sua pilha de camadas.
1. Use <b>Parâmetros básicos > Imagem</b> para adicionar uma imagem ao filtro ou adicionar uma imagem à pilha de camadas sob o filtro Bordado (não em um dos slots de entrada). Se uma imagem não for adicionada a <b>Parâmetros básicos > Imagem</b>, o filtro selecionará automaticamente imagens dos canais de digitalização, se disponíveis.
1. Ajuste <b>Parâmetros básicos > Contagem de cores </b> até que o equilíbrio de cores pareça correto para a imagem. Com um limite de 8 cores, ative ou desative as cores para isolar as cores necessárias.\
   O filtro Bordado funciona melhor com cores planas e imagens ilustradas.
1. Ajuste outros parâmetros para ajustar a aparência da correção.

É possível usar imagens transparentes no filtro Bordado, mas, por padrão, elas também afetarão o mapa de opacidade do seu material. Partes transparentes da imagem também tornarão o material transparente. Para criar uma correção com o filtro Bordado e colocá-lo em cima das camadas abaixo dela, use o filtro Decalque.

1. Crie um filtro de decalque.
1. Adicione o filtro Bordado ao slot de entrada do filtro Decalque.
1. Siga as etapas normais para ajustar o padrão de bordados.

A camada Decalque converte a entrada do Bordado em um Decalque. Portanto, a transparência da camada Bordado diz à camada de decalque como mascarar o padrão Bordado. Com a camada Decalque, você também pode mover o padrão no material ou ativar funcionalidades como divisão em blocos gráficos.
