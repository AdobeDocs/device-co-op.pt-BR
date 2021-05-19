---
description: Respostas a perguntas comuns sobre o Device Co-op (Cooperativa de serviços de identidade e Gráfico de identidade).
title: Perguntas frequentes sobre o Device Co-op
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# Perguntas frequentes{#faq}

Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.

**O que é o  [!DNL Device Co-op]?**

O Device Co-op é uma cooperativa digital para clientes participantes da Adobe Experience Cloud trabalharem em conjunto para identificar melhor seus consumidores em todos os dispositivos.

**Quais tecnologias são usadas no Device Co-op?**

O Device Co-op consiste em duas tecnologias:

* **Serviço de Experience Cloud ID:** esse serviço principal da Adobe Experience Cloud fornece uma ID comum para identificar os consumidores de forma consistente em soluções, canais, experiências e dispositivos.
* **Adobe Experience Cloud Device Co-op:** esta tecnologia vincula diferentes dispositivos usados por um consumidor ou residência.

**Como  [!DNL Device Co-op] funciona?**

À medida que as marcas aumentam sua parte do quebra-cabeça entre dispositivos por meio de logons anônimos e visitas a sites, o Adobe processa esses dados para formar grupos de dispositivos que representam um grupo de dispositivos usados por uma pessoa desconhecida. Esses grupos de dispositivos são fornecidos aos membros do Device Co-op e são usados para fornecer aos seus consumidores uma experiência melhor e mais consistente entre dispositivos.

**Como o  [!DNL Device Co-op] vincula os dispositivos?**

Consulte [Links probabilísticos e determinísticos](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Quais dados os participantes fornecem  [!DNL Adobe]?**

Consulte [Ferramenta de cancelamento de adesão do consumidor, Privacidade e o Gráfico de dispositivos](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Quais dados são compartilhados entre  [!DNL Device Co-op] membros?**

Consulte [Compartilhamento de link no Gráfico de dispositivos](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Um  [!DNL Device Co-op] membro pode ver links para dispositivos que nunca viu antes?**

Não. Os membros do Device Co-op só podem obter dados com base em dispositivos que visitaram uma das propriedades da Web de suas marcas. Consulte [Dispositivos conhecidos](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) e [Dispositivos desconhecidos](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Precisarei compartilhar alguma informação de marketing da minha empresa?**

Não. As marcas só fornecem dados anônimos de dispositivos para o Adobe.

**O  [!DNL Adobe] usa informações de identificação pessoal (PII) no  [!DNL Device Co-op]?**

Não. Todas as informações de identificação pessoal são transformadas em hash antes de serem trazidas para qualquer sistema de Adobe, de modo que as informações do cliente nunca são transferidas para sistemas de Adobe.

**Marcas menores que contribuem com menos dados de dispositivos ao Device Co-op obtêm mais valor do que contribuem em relação às marcas maiores?**

Não. Todos os membros da Cooperativa obtêm valor relativo ao que inseriram. Por exemplo, se uma marca contribuir com 10.000 dispositivos, eles poderão receber informações adicionais de dispositivos vinculados associados a esses 10.000 dispositivos. Olhando para o panorama geral, esta contribuição pode parecer mínima; mas à medida que mais e mais marcas de todos os tamanhos se unem, a contribuição agregada é significativa e fornecerá o link ausente para muitos dispositivos que muitas outras marcas, talvez maiores, estão procurando. Consulte [Equidade e o dispositivo conhecido](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**Como  [!DNL Adobe] gerenciar endereços IP se alguns países considerarem um endereço IP como informação pessoal?**

O Device Co-op é lançado primeiro nos Estados Unidos e no Canadá, onde o endereço IP não é considerado informação pessoal. Quando a Cooperativa for lançada em países onde o endereço IP é considerado informação pessoal, o endereço IP não será usado.
