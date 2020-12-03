---
description: Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.
seo-description: Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.
seo-title: Perguntas frequentes
title: Perguntas frequentes
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---


# Perguntas frequentes{#faq}

Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.

**Qual é o [!DNL Device Co-op]?**

O Device Co-op é uma cooperativa digital para clientes participantes da Adobe Experience Cloud trabalharem juntos para melhor identificar seus consumidores em dispositivos.

**Quais tecnologias são usadas no Device Co-op?**

O Device Co-op consiste em duas tecnologias:

* **Serviço de ID de Experience Cloud:** Este serviço principal da Adobe Experience Cloud fornece uma ID comum para identificar os consumidores de forma consistente em soluções, canais, experiências e dispositivos.
* **Adobe Experience Cloud Device Co-op:** Essa tecnologia vincula diferentes dispositivos usados por um consumidor ou por uma residência.

**Como [!DNL Device Co-op] funciona?**

À medida que as marcas aumentam sua parte do quebra-cabeça entre dispositivos através de logons anônimos e visitas ao site, o Adobe processa esses dados para formar grupos de dispositivos que representam um grupo de dispositivos usados por uma pessoa desconhecida. Esses grupos de dispositivos são fornecidos aos membros do Device Co-op e são usados para fornecer aos seus consumidores uma experiência melhor e mais consistente entre dispositivos.

**Como os dispositivos de [!DNL Device Co-op] link funcionam?**

Consulte Links [determinísticos e probabilísticos](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Quais dados os participantes fornecem [!DNL Adobe]?**

Consulte Ferramenta [de cancelamento de adesão do consumidor, Privacidade e o Gráfico](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)de dispositivos.

**Quais dados são compartilhados entre [!DNL Device Co-op] os membros?**

Consulte Compartilhamento de [links no Gráfico](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf)de dispositivos.

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Um [!DNL Device Co-op] membro pode ver links para dispositivos que nunca viu antes?**

Não. Os membros do Device Co-op só podem obter dados com base em dispositivos que visitaram uma das propriedades da Web de sua marca. Consulte Dispositivos [](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) conhecidos e dispositivos [desconhecidos](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Precisarei compartilhar qualquer informação de marketing da minha empresa?**

Não. As marcas só fornecem dados anônimos do dispositivo ao Adobe.

**Você [!DNL Adobe] usa informações de identificação pessoal (PII) no [!DNL Device Co-op]?**

Não. Todas as informações de identificação pessoal são colocadas em hash antes de serem colocadas em qualquer sistema de Adobe, de modo que as informações do cliente nunca são transferidas para sistemas de Adobe.

**As marcas menores que contribuem com menos dados de dispositivos para o Device Co-op obtêm mais valor do que o que colocam, em comparação com as marcas maiores?**

Não. Todos os membros da Cooperativa recebem o valor relativo ao que eles colocaram. Por exemplo, se uma marca contribui com 10.000 dispositivos, eles poderão receber informações adicionais de dispositivos vinculados associados a esses 10.000 dispositivos. Olhando para o panorama geral, esta contribuição pode parecer mínima; mas à medida que mais e mais marcas de todos os tamanhos se juntam, a contribuição agregada é significativa e fornecerá o link faltando para muitos dispositivos que muitas outras marcas, talvez maiores, estão procurando. Consulte [Equidade e dispositivo](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)conhecido.

**Como [!DNL Adobe] gerenciar endereços IP se alguns países considerarem um endereço IP como informações pessoais?**

O Device Co-op é lançado primeiro nos Estados Unidos e Canadá, onde o endereço IP não é considerado como informação pessoal. Quando a Cooperativa é lançada em países onde o endereço IP é considerado como informação pessoal, o endereço IP não será usado.
