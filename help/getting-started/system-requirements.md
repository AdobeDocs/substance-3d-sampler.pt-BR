---
helpx_url: 'https://helpx.adobe.com/br/substance-3d-sampler/getting-started/system-requirements.html'
breadcrumb-title: ''
description: Revise os requisitos de sistema do Substance 3D Sampler para garantir que seu hardware e software atendam aos padrões de compatibilidade.
helpx_creative_field: ''
helpx_description: Sampler > Getting Started > System requirements
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Requisitos do sistema
user-guide-description: ''
user-guide-title: ''
hold: true
source-git-commit: 8b2438eb381e35c19ab379a5fc14c962fd5b9b0a
workflow-type: tm+mt
source-wordcount: '684'
ht-degree: 0%
---

# Sistemas compatíveis

Veja abaixo uma lista de hardware e sistemas suportados pelo aplicativo:

>[!WARNING]
>
> Os seguintes drivers Nvidia são conhecidos por causar instabilidade ao executar o Sampler:
>
> * 610.47
>
> Recomendamos evitar o uso dessas versões. O ideal é usar uma versão mais recente ou, se não houver uma versão mais recente disponível, usar a versão anterior.

>[!NOTE]
>
> Se o seu hardware estiver abaixo dos requisitos mínimos de sistema, o Sampler será aberto automaticamente no [modo de baixa especificação](../technical-support/low-spec-mode.md), que limita alguns recursos.

>[!TIP]
>
> Se você deseja melhorar o desempenho do Sampler, use o [Modo de desempenho](../technical-support/performance-mode.md) para desativar os recursos intensivos.

## Windows

|  | Mínimo | Recomendado | Ideal |
| --- | --- | --- | --- |
| **SO** | Windows 11 64 bits versão 23H2 | Windows 11 64 bits versão 24H1 | Windows 11 64 bits versão 24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 Ada Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8 GB | 16 GB | 24 GB |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **Armazenamento** | SSD com 30 GB de espaço disponível | SSD com 50 GB de espaço disponível | SSD com 70 GB de espaço disponível |

### macOS

|  | Mínimo | Recomendado | Ideal |
| --- | --- | --- | --- |
| **SO** | macOS 15 Sequoia | macOS 27 Golden Gate | macOS 27 Golden Gate |
| **CPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **GPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **RAM** | 24 GB | 32 GB | 64 GB |
| **Armazenamento** | SSD com 30 GB de espaço disponível | SSD com 50 GB de espaço disponível | SSD com 70 GB de espaço disponível |

>[!WARNING]
>
> Para pipelines criados com a [Plataforma de Referência VFX](https://vfxplatform.com/) em mente, o Substance 3D Sampler ainda pode ser instalado no macOS 14 Sonoma. No entanto, o Sampler não é mais testado em versões do sistema operacional abaixo dos requisitos mínimos de sistema, portanto, a estabilidade não é garantida. É recomendável atualizar para uma versão mais recente do sistema operacional.

### Linux

| Corporativo | Vapor |
| --- | --- |
| RHEL 8 <br>RHEL 9 | Ubuntu 22.04 |

>[!NOTE]
>
> Se o seu sistema atende aos requisitos de sistema acima, mas o desempenho ainda é lento, o Sampler pode estar usando a GPU errada.
>
> Se você estiver usando uma GPU NVIDIA, [altere qual GPU o Sampler usa seguindo as instruções nesta página](../technical-support/configuration/nvidia-driver-settings.md).

## Recomendações gerais

* Para trabalhar em condições confortáveis, recomendamos um monitor com uma resolução superior a 1 MegaPixel e maior do que 1280 pixels.
* Muitos aplicativos Substance dependem do OpenSSL 1.1.1 para compatibilidade com RHEL8/9. Para sistemas com versões OpenSSL mais recentes, você precisará fornecê-lo manualmente.

## Configurações sem suporte

**Windows**

* Não há suporte para máquinas virtuais.
* Não há suporte para o Windows Server.

**Mac**

* Somente configurações oficiais do Apple são compatíveis.
* Atualmente, não há suporte para eGPUs e elas podem apresentar problemas de estabilidade.

**Linux**

* Drivers Mesa no Linux não são suportados.

**Qualquer plataforma**

* As GPUs integradas não são compatíveis com CPUs x86-64 (Intel, AMD).
* O uso do Sampler em combinação com software de terceiros que intercepta chamadas Sampler para os drivers gráficos não é suportado. Esse software inclui:
  * Injetores pós-processamento, como recodificadores que aplicam correção de cores, efeitos de câmera, etc.
  * Sobreposições na tela, como linhas cruzadas personalizadas, métricas de desempenho de GPU, capas para streaming de vídeo...

## Versões mínimas do driver de GPU

Veja abaixo uma lista das versões mínimas de driver de GPU necessárias para que o aplicativo seja executado sem problemas. Esta lista está sujeita a alterações à medida que novas versões são lançadas.

Para baixar novos drivers, consulte: [A GPU tem drivers desatualizados](https://experienceleague.adobe.com/pt-br/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers).

| SO | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **Windows** | GeForce 551.86 Quadro/RTX 538.33 | Radeon 23.8.1 Radeon Pro/FirePro 24.q2 | 31.0.1015590 |
| **Linux** | 525.116.04 ou posterior *ou* 535.54.03 ou posterior | Radeon 23.20 Pro 23.Q3 | Sem suporte |

>[!NOTE]
>
> No **sistema operacional Mac**, o driver de GPU é fornecido pelo próprio sistema operacional. Atualize para a versão mais recente do seu sistema operacional para acessar o driver mais recente.

## Idiomas

A interface de software está disponível nos seguintes idiomas:

* Inglês
* Alemão
* Francês
* Japonês
* Coreano
* Chinês
* Italiano
* Português
* Espanhol