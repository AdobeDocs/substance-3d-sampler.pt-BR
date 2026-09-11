---
helpx_url: "https://helpx.adobe.com/br/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: Saiba como importar texturas para o Substance 3D Sampler para usar arquivos de imagem existentes em seus fluxos de trabalho de criação de material.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Importação de textura
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 4%

---


# Importação de textura

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

O modelo de **Importação de Textura** carrega várias imagens e as conecta automaticamente aos canais de saída corretos com base em seus nomes de arquivo.

A correspondência de canais se baseia nas convenções de nomenclatura específicas detalhadas abaixo. No caso de duplicatas ou texturas sem correspondência, as imagens serão marcadas como tal na interface.

## OpenPBR

O Sampler fará a correspondência dos arquivos com os seguintes identificadores de OpenPBR com o canal equivalente no material.

>[!NOTE]
>
> Os identificadores de canal de height são os mesmos usados para o ASM.


| Identificador de OpenPBR | Uso de SBSAR |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | metalness/metallic |
| base_diffuse_roughness | asperezaDifusaBase |
| specular_peso | specularEspessura |
| specular_color | specularColor |
| specular_rugosidade | aspereza/aspereza especular |
| specular_roughness_anisotropia | aspereza especularAnisotropia/anisotropyLevel |
| specular_ior | specularIOR/IOR |
| transmission_weight | transmissionWeight |
| transmission_color | corDaTransmissão/CorDaAbsorção |
| transmission_profundidade | transmissionDepth/ativationDistance |
| transmission_dispersão | transmissionScatter |
| transmission_dispersão_anisotropia | transmissionScatterAnisotropy |
| transmission_dispersion_scale | transmissionDispersionScale |
| transmission_dispersion_abbe_number | transmissionDispersionAbbeNumber |
| subsurface_weight | subsuperfíciePeso/translucidez |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsuperfícieEscalaRaio/dispersãoEscalaDistância |
| subsurface_dispersão_anisotropia | subsurfaceScatterAnisotropy |
| coat_weight | espessuraDaPelagem/opacidadeDaPelagem |
| coat_color | coatColor |
| coat_roughness | aspereza do casaco |
| coat_roughness_anisotropia | AnisotropiaDeAsperezaDePelagem |
| coat_ior | coatIOR |
| coat_darkening | coatDarkening |
| fuzz_weight | fuzzWeight/sheenOpacity |
| fuzz_color | fuzzColor/sheenColor |
| fuzz_roughness | fuzzRoughness/sheenRoughness |
| emission_weight | emissionWeight |
| emission_luminance | LuminânciaEmissão |
| emission_color | emissionColor/emisive |
| thin_film_weight | thinFilmWeight |
| thin_film_thickness | thinFilmThickness |
| thin_film_ior | thinFilmIOR |
| opacidade | opacidade |
| thin_walled | thinWalled |
| normal | normal |
| tangente | tangente |
| coat_normal | casacoNormal |
| coat_tangent | coatTangent |

## Material Padrão da Adobe

Veja abaixo uma lista das convenções de nomeação de arquivos compatíveis para cada canal:

| **Canal** | **Adobe Standard Material** |
| --- | --- |
| **Oclusão de ambiente** | <ul><li>ambientoclusão</li><li>ao</li><li>oclusão</li><li>ambient_occlusion</li></ul> |
| **Cor base** | <ul><li>basecolor</li><li>cores</li><li>albedo</li><li>base_color</li><li>base</li><li>col</li><li>cor</li><li>base_color</li><li>basecolor</li></ul> |
| **Difusa** | <ul><li>difusa</li><li>diff</li></ul> |
| **Emissivo** | <ul><li>emissivo</li></ul> |
| **Textura reluzente** | <ul><li>glossiness</li><li>brilho</li></ul> |
| **Height** | <ul><li>height</li><li>heightmap</li><li>deslocamento</li><li>disp</li></ul> |
| **Metálico** | <ul><li>metálico</li><li>mtl</li><li>metalness</li></ul> |
| **Normal** | <ul><li>normal</li><li>nrm</li></ul> |
| **Opacidade** | <ul><li>opacidade</li><li>alpha</li></ul> |
| **Aspereza** | <ul><li>de aspereza</li><li>áspero</li></ul> |
| **Specular** | <ul><li>specular</li><li>espec</li></ul> |
| **Specular level** | <ul><li>specularlevel</li><li>specular_level</li></ul> |

