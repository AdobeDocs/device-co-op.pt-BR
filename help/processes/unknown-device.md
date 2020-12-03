---
description: Quando uma pessoa tem dispositivos que não são usados para interagir com sua marca, esses dispositivos são chamados de dispositivos desconhecidos.
seo-description: Quando uma pessoa tem dispositivos que não são usados para interagir com sua marca, esses dispositivos são chamados de dispositivos desconhecidos.
seo-title: Dispositivos desconhecidos
title: Dispositivos desconhecidos
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---


# Dispositivos desconhecidos{#unknown-devices}

Quando uma pessoa tem dispositivos que não são usados para interagir com sua marca, esses dispositivos são chamados de dispositivos desconhecidos.

## Categorias de dispositivo desconhecidas {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

Existem várias maneiras ou categorias pelas quais um dispositivo pode ser considerado &quot;desconhecido&quot; para você. Eles incluem:

* **Visitas primárias a outros membros do Device Co-op:** Visitas a outros sites [!DNL Device Co-op] membros ou publicidade a um dispositivo não tornam, por si só, um dispositivo conhecido da sua marca.

* **Inventário de anúncio não rastreado:** O inventário de publicidade que está disponível, mas que ainda não foi atendido ou assimilado, não torna um dispositivo conhecido de sua marca.
* **Cancelamento de adesão do consumidor:** Para respeitar o desejo do consumidor, os dispositivos que foram excluídos não são considerados dispositivos conhecidos.

Diferentemente dos dispositivos conhecidos, os dispositivos desconhecidos não estão vinculados a outros dispositivos ou associados a pessoas individuais.

## Regras para definir o status conhecido/desconhecido {#section-fa5c85e59e2d4f88bb79f27f17f02344}

O [!DNL Device Graph] tenta ser o mais inclusivo possível ao classificar dispositivos como conhecidos em comparação ao desconhecido. As regras que ajudam a determinar o status conhecido/desconhecido funcionam em ordem de prioridade (1 é a mais alta), conforme mostrado abaixo:

* **Regra 1:** O dispositivo foi excluído? Se sim, então o dispositivo é desconhecido.
* **Regra 2:** O dispositivo é conhecido por *algum* método? Se sim, então o dispositivo é conhecido.

* **Regra 3: ** Se as opções anteriores não se aplicarem, o dispositivo é desconhecido.

>[!MORELIKETHIS]
>
>* [Dispositivos conhecidos](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

