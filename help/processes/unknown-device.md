---
description: Quando uma pessoa tem dispositivos que não são usados para interagir com a sua marca, tais dispositivos são chamados de dispositivos desconhecidos.
seo-description: Quando uma pessoa tem dispositivos que não são usados para interagir com a sua marca, tais dispositivos são chamados de dispositivos desconhecidos.
seo-title: Dispositivos desconhecidos
title: Dispositivos desconhecidos
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Unknown devices{#unknown-devices}

Quando uma pessoa tem dispositivos que não são usados para interagir com a sua marca, tais dispositivos são chamados de dispositivos desconhecidos.

## Unknown device categories {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

Existem várias formas ou categorias pelas quais um dispositivo pode ser considerado &quot;desconhecido&quot; para você. Dentre eles:

* **Visitas de primeira parte a outros membros do :** visitas a outros sites de membros do [!DNL Device Co-op]Device Co-op ou publicidade a um dispositivo não torna, por si só, um dispositivo conhecido para a sua marca.

* **Inventário de anúncio não rastreado:** o inventário de publicidade que está disponível, mas ainda não servido ou assimilado, não torna um dispositivo conhecido para a sua marca.
* **Cancelamento de adesão do consumidor:** para respeitar o desejo do consumidor, os dispositivos cuja adesão foi cancelada não são considerados dispositivos conhecidos.

Ao contrário dos dispositivos conhecidos, os dispositivos desconhecidos não estão vinculados a outros dispositivos ou associados a pessoas individuais.

## Rules for setting known/unknown status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

The [!DNL Device Graph] tries to be inclusive as possible when classifying devices as known compared to unknown. As regras que ajudam a determinar o estado conhecido/desconhecido funcionam em ordem de prioridade (1 é a mais alta), como mostrado abaixo:

* **Regra 1:** a adesão do dispositivo foi cancelada? Se sim, então o dispositivo é desconhecido.
* **Regra 2:** o dispositivo é conhecido por *algum* método? Se sim, então o dispositivo é conhecido.

* **Regra 3: ** Se as opções anteriores não se aplicarem, o dispositivo é desconhecido.

>[!MORELIKETHIS]
>
>* [Dispositivos conhecidos](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

