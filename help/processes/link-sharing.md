---
description: Sobre o compartilhamento de links no Gráfico de dispositivos.
seo-description: Sobre o compartilhamento de links no Gráfico de dispositivos.
seo-title: Compartilhamento de links no Gráfico de dispositivos
title: Compartilhamento de links no Gráfico de dispositivos
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Link sharing in the Device Graph{#link-sharing-in-the-device-graph}

Sobre o compartilhamento de links no Gráfico de dispositivos.

The [!DNL Device Graph] shares deterministic and probabilistic links with different members of the Adobe Experience Cloud Device Co-op. Link sharing is what makes the [!DNL Device Co-op] so powerful. Ele estende o que cada membro sabe sobre os dispositivos associados a uma pessoa anônima, mas somente se você já tiver visto ao menos um dos dispositivos dessa pessoa anônima.

## Device Graph summary review {#section-7858e9f61b5644c981ffb53626fcc19d}

Before getting started, let&#39;s take a moment to review how the [!DNL Device Graph] works. Os membros do [!DNL Device Co-op] enviam dados para o [!DNL Device Graph]. O [!DNL Device Graph] usa esses dados para construir a identidade de uma pessoa a partir de links [](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) determinísticos e probabilísticos entre dispositivos. Como um participante do [!DNL Device Co-op], esses links fornecem informações sobre a relação entre os usuários autenticados, outros usuários e seus dispositivos. Vejamos como isso funciona na seção abaixo.

## Link sharing example {#section-cb410d827cf14f76bc9b0bd4d31ed767}

O exemplo a seguir demonstra a capacidade do compartilhamento de link no Device Co-op. Neste exemplo, temos duas empresas fictícias: a Empresa de notícias e a Empresa de finanças. Both companies are members of the [!DNL Device Co-op]. A Pessoa A é um consumidor que faz logon ou navega nos sites de cada empresa a partir de vários dispositivos.

![](assets/share1.png)

Como a Pessoa A está autenticada no site de notícias com o seu telefone celular e tablet, a Empresa de notícias a identifica com uma ID de consumidor. It sends that ID to the [!DNL Device Graph] as a cryptographic hash. A Companhia Financeiro já viu esses dispositivos, mas a Pessoa A não fez logon no site. Consequentemente, a Empresa de finanças não sabe se ou como esses dispositivos estão relacionados ou como estão associados à Pessoa A.

![](assets/share2.png)

Given the cryptographic hash of the consumer ID, the [!DNL Device Graph] recognizes that these devices are related to each other and a particular person. Para as empresas que não participam do [!DNL Device Co-op] estas visitas ao site parecem vir de dispositivos aleatórios separados. In any case, once the [!DNL Device Graph] has the hashed ID it:

* Sabe que o telefone celular e o laptop estão vinculados.
* Reconhece que a Empresa de finanças quer saber se o telefone celular e o laptop estão vinculados.

Given these conditions, the [!DNL Device Graph] now shares the link connecting these devices for the News Company with the Finance Company. During this process, the [!DNL Device Graph] duplicates and shares the link from one co-op member to another.

![](assets/share3.png)

At this point, the [!DNL Device Graph] performed its role successfully. Tanto a Empresa de notícias quanto a Empresa de finanças têm uma visão clara de uma identidade. Eles podem atingir a Pessoa A com precisão em todos os seus dispositivos.

## Privacy and link sharing {#section-7b566018b3304420a4b3e4c079826110}

Manter a privacidade do consumidor e a integridade dos dados para os membros do [!DNL Device Co-op] é fundamental em todo o processo de compartilhamento de links. During this customer identification and link sharing process the [!DNL Device Graph] did not:

* Informou à Empresa de finanças que o link veio da Empresa de notícias.
* Compartilhou a ID do cliente usada por um membro do [!DNL Device Co-op] com o outro.
* Forneceu qualquer informação diferente de se o dispositivo móvel e o laptop têm um vínculo em comum.

## Próximas etapas {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Reading the documentation on identity, linking, and link sharing should give you a good sense of how the [!DNL Device Graph] assembles data internally. Como próximo passo, recomendamos consultar nossa documentação que descreve como o conceito de um dispositivo *`known device`* fornece links entre dispositivos para membros do Device Co-op. Consulte Dispositivos [](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) conhecidos e dispositivos [desconhecidos](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
