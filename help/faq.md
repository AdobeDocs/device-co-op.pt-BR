---
description: Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.
seo-description: Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.
seo-title: Perguntas frequentes
title: Perguntas frequentes
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Perguntas frequentes{#faq}

Descrições e respostas a perguntas comuns sobre a Cooperativa de serviços de identidade e o Gráfico de identidade.

**Qual é o[!DNL Device Co-op]?**

O Device Co-op é uma cooperativa digital para os clientes participantes da Adobe Experience Cloud trabalharem juntos para identificar melhor seus consumidores em todos os dispositivos.

**Quais tecnologias são usadas no Device Co-op?**

O Device Co-op consiste em duas tecnologias:

* **Serviço da Experience Cloud ID:** Esse serviço principal da Adobe Experience Cloud fornece uma ID comum para identificar os consumidores de forma consistente em soluções, canais, experiências e dispositivos.
* **Adobe Experience Cloud Device Co-op:** Essa tecnologia vincula diferentes dispositivos usados por um consumidor ou por uma residência.

**Como[!DNL Device Co-op]funciona?**

Conforme as marcas aumentam sua participação no quebra-cabeça de dispositivos através de logons anônimos e visitas a sites, a Adobe processará esses dados para formar grupos de dispositivos que representam um grupo de dispositivos usados por uma pessoa desconhecida. Estes grupos de dispositivos são fornecidos aos membros do Device Co-op e são utilizados para proporcionar aos seus consumidores uma experiência melhor e mais consistente entre dispositivos.

**Como os dispositivos de[!DNL Device Co-op]link funcionam?**

See [Deterministic and Probabilistic Links](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Quais dados os participantes fornecem para a[!DNL Adobe]?**

Consulte [Ferramenta de cancelamento de adesão do consumidor e o Gráfico de dispositivos](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Quais dados são compartilhados entre[!DNL Device Co-op]os membros?**

See [Link Sharing in the Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Um membro do[!DNL Device Co-op]pode ver os links para dispositivos que nunca viu antes?**

Não. Os membros do Device Co-op só podem obter dados com base nos dispositivos que visitaram uma das propriedades da web de suas marcas. Consulte Dispositivos [conhecidos](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) e dispositivos [desconhecidos](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Precisarei compartilhar alguma informação de marketing da minha empresa?**

Não. As marcas somente fornecem dados anônimos de dispositivos para a Adobe.

**Você[!DNL Adobe]usa informações de identificação pessoal (PII) no[!DNL Device Co-op]?**

Não. Todas as informações de identificação pessoal são transformadas em hash antes de serem enviadas para qualquer sistema Adobe, de modo que as informações do seu cliente nunca são transferidas para os Adobe Systems.

**Marcas menores que contribuem com menos dados de dispositivos ao Device Co-op obtêm mais valor do que contribuem em relação às marcas maiores?**

Não. Todos os membros da Cooperativa obtêm o valor relativo ao que contribuem. Por exemplo, se uma marca contribui com 10.000 dispositivos, eles poderão receber informações adicionais de dispositivos vinculados associados a esses 10.000 dispositivos. Analisando o panorama geral, esta contribuição pode parecer mínima; porém, à medida que mais e mais marcas de todos os tamanhos se juntarem, a contribuição agregada será significativa e fornecerá o elemento que falta para vários dispositivos que muitas outras marcas, até mesmo grandes marcas, estão procurando. Consulte [Equidade e dispositivo](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)conhecido.

**Como a[!DNL Adobe]gerenciará endereços IP, se alguns países consideram um endereço IP como informação pessoal?**

O Device Co-op será lançado primeiro nos Estados Unidos e Canadá, onde endereços IP não são considerados informações pessoais. Quando a Cooperativa for lançada em países onde o endereço IP é considerado informação pessoal, estes dados não serão utilizados.
