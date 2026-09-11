---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-1.html"
breadcrumb-title: ''
description: Revise as notas de versão do Substance 3D Sampler versão 4.1 para saber mais sobre o filtro Distorção de Tinta, atualizações do filtro Bordado e melhorias de captura 3D.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 4.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 4.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '812'
ht-degree: 0%

---


# Versão 4.1

O <b>Substance 3D Sampler 4.1.0 </b>apresenta novo conteúdo com o filtro <b>Distorção de Tinta </b> e uma versão aprimorada do filtro <b>Bordados </b>. Esta atualização inclui algumas melhorias no captura 3D.

*Data de lançamento: 28 de março de 2023*

## Distorção de pintura

O filtro Distorção de pintura permite deformar materiais desenhando curvas na exibição 2D.\
A opção Retificar permite realinhar materiais para obter um fluxo de trabalho de divisão em blocos gráficos simples e contínuo.

## Bordado

O novo gerador de bordados permite criar patches de bordados a partir de um único arquivo de vetor de imagem ou de um desenho.\
Pode bordar até 6 cores e combina várias técnicas de costura.

## Tutorials

## Nota de versão

<b>4.1.2 CANNOLI</b>

*(Lançado: 20 de junho de 2023)*

<b>Corrigido:</b>

* [Camadas] Vazamento de memória ao ajustar materiais e filtros de Substance causando falhas

<b>4.1.1 CANNOLI</b>

*(Lançado: 06 De junho De 2023)*

<b>Adicionado</b>:

* [Engine] Atualização do Substance Engine para a versão 9.0
* [Interoperabilidade] Enviar objetos 3D para o Stager e Painter

<b>Corrigido:</b>

* [captura 3D] Os aplicativos travam quando o captura 3D falha
* [captura 3D] Falha quando uma imagem não pode ser carregada
* [captura 3D] Falha ao atingir a etapa de Reconstrução de malha
* [captura 3D] Falha ao redimensionar a caixa delimitadora
* [captura 3D] Importar máscaras seguindo a convenção não atribui a máscara corretamente
* [captura 3D] Falhas de renderização ao ajustar a caixa delimitadora
* [captura 3D] Alternar entre a versão e alternar as opções de renderização durante o processo de Captura 3D é lento
* [captura 3D] Às vezes, a alternância entre as versões durante a etapa de Pós-processamento é interrompida
* [Application] Falha na inicialização
* [Aplicativo] Falha ao duplicar um material renomeado
* [Aplicativo] Falha ao abrir um projeto .alch herdado sem sua pasta de dependência
* [Aplicativo] Falha ao conectar/desconectar uma tela, o computador entra em suspensão ou é acessado remotamente
* [Aplicativo] Falhas e vazamentos de memória relacionados ao gerenciamento de ativos não persistentes
* [Exportar] A escolha do formato de material para tipos de arquivo de objeto 3D que incorporam ou fazem referência a texturas deve ser desativada
* [Exportar] Falha se algo der errado durante a exportação de objeto 3D
* [Exportar] Falha ao exportar um arquivo .sbs/.sbsar
* [Export] Falha ao importar predefinição personalizada que tem o mesmo rótulo, mas não o mesmo nome de arquivo
* [Exportar] Exportar uma iluminação do ambiente para um arquivo .sbs/.sbsar às vezes não funciona
* [Exportar] A exportação Gltf/Glb codifica as texturas na base64
* [Exportar] O campo de texto de nome não funciona ao focar novamente
* [Exportar] A opção Preservar divisão em blocos gráficos não funciona ao exportar uma camada de Imagem para material (desenvolvida por IA) para um arquivo .sbs/.sbsar
* [Exportar] Ao exportar gltf e substituir arquivos, a lista de arquivos a serem substituídos não está correta
* [Parâmetros expostos] A propagação aleatória não funciona em arquivos .sbs/.sbsar exportados
* [Camadas] O Preenchimento sensível ao conteúdo às vezes falha quando adicionado pela segunda vez
* [Camadas] Falha ao calcular uma pilha de camadas
* [Camadas] O cache de disco de Imagem para material (AI) não funciona
* [Camadas] Possível falha ao ajustar uma camada
* [Desempenho] Vazamentos de memória
* [Project] Falha ao salvar um projeto
* [Projeto] Importar o mesmo projeto duas vezes seguidas duplica ativos
* [IU] Botões arredondados com apenas um ícone não são renderizados corretamente

### 4.1.0 Cannoli

*(Lançado: 28 De março De 2023)*

<b>Adicionado:</b>

* [Conteúdo] Novo filtro de bordado
* [Conteúdo] Novo filtro de Distorção de Tinta
* [UI] Opção Adicionar exportação no menu Arquivo
* [captura 3D] O botão Voltar agora está disponível na etapa de alinhamento
* [captura 3D] As imagens manipulam a orientação EXIF do JPEG
* [captura 3D] Script - Nova propriedade dataset\_info.camera
* [captura 3D] Adicionar suporte a Linux (consulte a documentação)
* [captura 3D] Verificar o acesso de leitura das imagens importadas
* [Integração] Aprendizado - 2 novos tutoriais (Bordado e Distorção de Tinta)
* [Integração] Conteúdo de novidades atualizado

<b>Corrigido:</b>

* [captura 3D] Manter a posição da câmera ao alterar a versão
* [captura 3D] Mesclar todos os grupos de um objeto em um
* [captura 3D] Malhas geradas renomeadas para Original
* [Aplicativo] Falha ao tentar gerar miniatura de uma imagem não existente
* [Ativos] O ícone da lixeira não faz nada no painel Ativos
* [Content] Atualizar filtros com slots de material não funciona como esperado
* [Exportar] Possível falha ao exportar um ativo com filtros específicos
* [Exportar] Exportação SBS/SBSAR - as camadas de importação de imagem tinham prioridade sobre os parâmetros de imagem
* [Exportar] A predefinição de exportação UE4 não funciona com PNG
* [Camadas] Falha ao soltar um material e um filtro ao mesmo tempo do explorador do sistema operacional
* [Camadas] Falha ao arrastar qualquer arquivo SBSAR com qualquer arquivo de imagem
* [Camadas] O canal de opacidade do bordado pode ser completamente branco
* [Localização] O idioma chinês pode ser exibido por padrão no Linux
* [Desempenho] Correção de um problema de memória ao remover uma camada de um ativo
* [Project] Possível falha ao salvar
* [IU] Adicionar espaçamento ausente no botão de menu da Versão
* Botão Cancelar [IU] não exibido corretamente
* [UI] Desativar a animação de controles deslizantes para parâmetros de pós-processo do captura 3D
* [UI] A janela Modelo de criação de material não se fecha ao clicar fora
* [UI] O acessador rápido de filtro fecha a si mesmo ao clicar fora

<b>Problemas Conhecidos:</b>

* [Seletor de cores] Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar
* [Content] O widget de luz da forma não está funcionando no modo de projeção esférica
* [Interoperabilidade] O material com deslocamento enviado para o Stager perderá os controles do deslocamento
