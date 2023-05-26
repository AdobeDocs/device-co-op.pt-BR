---
description: Respostas a perguntas comuns sobre o Device Co-op (Cooperativa de serviços de identidade e Gráfico de identidade).
title: Perguntas frequentes sobre Device Co-op
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# Perguntas frequentes{#faq}

Descrições e respostas a perguntas comuns sobre a cooperativa de serviços de identidade e o gráfico de identidade.

**O que é o [!DNL Device Co-op]?**

O Device Co-op é uma cooperativa digital para clientes participantes da Adobe Experience Cloud trabalharem em conjunto para melhor identificar seus consumidores em todos os dispositivos.

**Quais tecnologias são usadas no Device Co-op?**

O Device Co-op consiste em duas tecnologias:

* **Serviço de ID de Experience Cloud:** Esse serviço principal da Adobe Experience Cloud fornece uma ID comum para identificar consumidores de forma consistente em soluções, canais, experiências e dispositivos.
* **Device Co-op da Adobe Experience Cloud:** Essa tecnologia conecta diferentes dispositivos usados por um consumidor ou residência.

**Como o [!DNL Device Co-op] trabalhar?**

À medida que as marcas lançam sua parte do quebra-cabeça entre dispositivos por meio de logons anônimos e visitas ao site, o Adobe processa esses dados para formar clusters de dispositivos que representam um grupo de dispositivos usados por uma pessoa desconhecida. Esses clusters de dispositivos são fornecidos aos membros do Device Co-op e usados para fornecer aos consumidores uma experiência melhor e mais consistente entre dispositivos.

**Como o [!DNL Device Co-op] vincular dispositivos?**

Consulte [Vínculos Determinísticos e Probabilísticos](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Quais dados os participantes fornecem [!DNL Adobe]?**

Consulte [Ferramenta de recusa do consumidor, privacidade e gráfico de dispositivos](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Quais dados são compartilhados entre [!DNL Device Co-op] membros?**

Consulte [Compartilhamento de links no gráfico de dispositivos](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Pode um [!DNL Device Co-op] membro vê links para dispositivos que nunca viram antes?**

Não. Os membros do Device Co-op só podem obter dados com base em dispositivos que visitaram uma das propriedades da Web de sua marca. Consulte [Dispositivos conhecidos](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) e [Dispositivos desconhecidos](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Preciso compartilhar alguma informação de marketing da minha empresa?**

Não. As marcas só fornecem dados de dispositivos anônimos para o Adobe.

**Faz [!DNL Adobe] usar informações de identificação pessoal (PII) na [!DNL Device Co-op]?**

Não. Todas as informações de identificação pessoal são transformadas em hash antes de serem trazidas para qualquer sistema de Adobe, de modo que as informações do cliente nunca são transferidas para sistemas de Adobe.

**As marcas menores que contribuem com menos dados do dispositivo para o Device Co-op obtêm mais valor do que o que agregam em comparação com suas contrapartes maiores?**

Não. Todos os membros da Cooperativa recebem de volta valor relativo ao que colocam. Por exemplo, se uma marca contribuir com 10.000 dispositivos, eles poderão receber informações adicionais de dispositivos vinculados associadas a esses 10.000. Olhando para o cenário geral, essa contribuição pode parecer mínima; mas à medida que mais e mais marcas de todos os tamanhos se juntam, a contribuição agregada é significativa e fornecerá o link que falta para muitos dispositivos que muitas outras marcas, talvez maiores, estão procurando. Consulte [Equidade e o dispositivo conhecido](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**Como o [!DNL Adobe] gerenciar endereços IP se alguns países considerarem um endereço IP como informações pessoais?**

O Device Co-op é lançado pela primeira vez nos Estados Unidos e no Canadá, onde o endereço IP não é considerado informação pessoal. Quando a Cooperativa é liberada em países onde o endereço IP é considerado informação pessoal, o endereço IP não será usado.
