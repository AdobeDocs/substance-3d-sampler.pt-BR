---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-3-4.html"
breadcrumb-title: ''
description: Consulte as notas de versão do Substance 3D Sampler versão 3.4 para saber mais sobre os novos recursos desenvolvidos para aumentar a velocidade e a qualidade em fluxos de trabalho 3D.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.4
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versão 3.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '838'
ht-degree: 0%

---


# Versão 3.4

O **Substance 3D Sampler 3.4.0** apresenta uma série de novos recursos desenvolvidos para aumentar a velocidade e a qualidade em fluxos de trabalho 3D.

*Data de lançamento: 6 de setembro de 2022*

## Principais recursos

## Parâmetros expostos

Modifique materiais paramétricos em qualquer software compatível com arquivos SBSAR, como CLO, UE5, Blender, Photoshop e Illustrator, entre outros.\
Isso agora é possível graças à nova capacidade da Sampler de expor parâmetros de ativos, permitindo acelerar iterações e se livrar de idas e vindas entre softwares da Sampler e outros.

Exponha os parâmetros do material clicando em um pino.

Pontos de cor o ajudarão a navegar nos parâmetros expostos e nos diferentes painéis.

## Criação em Python

Agora você pode criar plug-ins e scripts, para personalizar sua interface e facilitar a integração do Sampler ao seu pipeline, além de configurar o fluxo de trabalho geral da maneira que desejar.\
Isso permite, por exemplo, criar um script que permite automatizar tarefas repetitivas como exportar vários materiais em um clique.

Descubra como criar seu primeiro plug-in ou script [aqui](../scripting-and-development/scripting-and-development.md).

## Propriedades Físicas do CLO

Agora você pode criar têxteis que se comportam de forma realista com simulações em física. Isso é obtido inserindo propriedades físicas do tecido, como Curvatura, Cisalhamento e Atrito.\
Com esta atualização, o SBSAR conterá as informações físicas em seus metadados, que são usados pelo CLO para garantir que o material reaja realisticamente.

## Imagem para material (viabilizado por IA)

Imagem para material (alimentado por IA) agora está disponível no MacOS e é executado nativamente em dispositivos Apple Silicon.

## Notas de versão

### 3.4.0 Arancini

*(Data de lançamento: 6 de setembro de 2022)*

**Adicionado:**

[Parâmetros Expostos] Novo Painel de parâmetros expostos\
[Parâmetros expostos] O novo botão nos parâmetros passa o mouse para expor e não expor os parâmetros do painel Propriedades\
[Parâmetros expostos] Novo menu de contexto de clique com o botão direito do mouse nos parâmetros para expor e não expor parâmetros do painel Propriedades\
[Parâmetros expostos] Os parâmetros expostos são listados no Painel de parâmetros expostos\
[Parâmetros expostos] Pontos e discos de cores são adicionados em vários locais para identificar facilmente os parâmetros expostos\
[Parâmetros expostos] Os rótulos de parâmetro podem ser editados no Painel de parâmetros expostos\
[Parâmetros expostos] Exibe um aviso para parâmetros não exportáveis\
[Parâmetros expostos] Exibe um aviso se você mover uma camada com parâmetros de mesclagem expostos em algum lugar onde eles se tornam ocultos\
[Parâmetros expostos] Os parâmetros expostos são exportados nos formatos SBS e SBSAR\
[Metadados] Oferecer suporte a modelos de metadados personalizados\
[Metadados] Novo modelo de metadados de propriedades físicas do CLO\
[Metadados] Adicionar ícones ao passar o mouse para adicionar/remover metadados personalizados\
[API Python] Nova API Python\
[API Python] API para criação de ativos\
[API Python] API para o gerenciamento de camadas\
[API Python] API para o gerenciamento de parâmetros\
[API Python] API para o gerenciamento de projetos\
[API Python] Um plug-in pode ser ativado e desativado\
[API Python] Documentação da API Python acessível no menu Ajuda\
[Script] Nova seção Plug-ins e scripts no pop-up Preferências\
[Script] Criar e importar plug-ins para personalizar a interface do Sampler com seus próprios painéis\
[Script] Os plug-ins se tornam parte da interface do Sampler e podem ser encaixados e movidos como painéis padrão do Sampler\
[Script] Barra de botões dedicada para os plug-ins na barra de ferramentas direita do Sampler\
[Scripts] Criar e importar scripts para executar uma lista de determinadas tarefas\
[Scripting] Iniciar scripts Python através do menu Scripts\
[Script] Plug-ins e scripts podem ser excluídos, reordenados e recarregados na janela Preferências\
[Scripting] Parâmetros de linha de comando —run-script adicionados\
[Logs] Novo painel Logs\
[Logs] Ative o painel Logs na janela Preferências\
[Logs] Nova barra de ações para limpar, copiar/colar, exportar logs\
[Propriedades] O novo botão nos parâmetros passa o mouse para redefinir o valor do parâmetro\
[Propriedades] Novo menu de contexto de clique com o botão direito do mouse em parâmetros para redefinir o valor do parâmetro\
[Content] Image to Material (desenvolvido por IA) agora funciona no MacOS\
[Engine] Atualize o mecanismo de Substance para a v8.6.0

**Corrigido:**

[Application] O aplicativo podia falhar ao sair quando uma geração de miniatura estava em andamento\
[Application] O aplicativo pode falhar ao usar “Salvar como” ao sair\
[Application] O aplicativo pode travar durante o desligamento no MacOS\
[Aplicativo] Salvar com a caixa de diálogo de cor aberta não salva suas alterações\
[Exportar] A convenção de nomenclatura de uso não está correta ao exportar\
[Camadas] Soltar um material sobre um filtro pode falhar\
[Camadas] Atualizar uma pilha de camadas desatualizada pode atualizar pilhas de camadas não relacionadas\
[Metadados] Campos vazios são exportados\
[Metadados] Quando há apenas um item de metadados, a interface permite que você tente reordená-lo\
[Projeto] A computação nunca termina após a duplicação de um material\
[Project] O ativo do projeto é duplicado após o salvamento inicial do projeto\
[Project] Cálculos desnecessários ao alternar o ativo\
[Renderização] Algumas pilhas de camadas não são renderizadas corretamente após a exclusão de uma camada\
[Segurança] Corrigir CVE-2015-20107\
[UI] As saídas 2D podem ficar desfocadas dependendo do tamanho da janela\
[IU] A visualização do ativo pode permanecer aberta na parte superior quando o aplicativo perde o foco\
[IU] Os cantos arredondados da tela inicial têm um fundo quadrado opaco

**Problemas conhecidos:**

[Seletor de cores] Escolher uma cor em um segundo monitor com uma resolução diferente pode não funcionar\
[Content] O widget de luz da forma não está funcionando no modo de projeção esférica\
[Interoperabilidade] O material com deslocamento enviado para o Stager perderá os controles do deslocamento
