---
description: Sua empresa deve atender a esses padrões mínimos antes de poder start usando o Experience Cloud Device Co-op.
seo-description: Sua empresa deve atender a esses padrões mínimos antes de poder start usando o Experience Cloud Device Co-op.
seo-title: Requisitos de adesão
title: Requisitos de adesão
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 1ab7be570ea63645c6d6065341d31bf170f79715
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 16%

---


# Requisitos de associação{#membership-requirements}

Sua empresa deve atender a esses padrões mínimos antes de poder start usando o Experience Cloud Device Co-op.

## Requisitos {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Fale com seu [!DNL Adobe representative to get started]. a Adobe reserva-se o direito de negar qualquer participação potencial do cliente no Experience Cloud Device Co-op se a Adobe determinar que a participação de um cliente potencial no Device Co-op pode (1) violar qualquer lei aplicável; ou (2) causem um risco material à segurança ou às operações da Adobe ou de qualquer dos seus clientes.

## requisitos de Experience Cloud {#section-76218a50385d43e6b9323e49f598394a}

Você deve estar habilitado para [!DNL Adobe Experience Cloud] e usar as seguintes soluções e serviços para participar da cooperativa.

**Soluções**

Os requerentes devem utilizar pelo menos uma das seguintes soluções:[!DNL Adobe]

* [Analytics](http://www.adobe.com/br/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/br/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**Serviços principais**

Os candidatos devem implementar o serviço [Experience Cloud ID](https://docs.adobe.com/content/help/pt-BR/id-service/using/home.html).

## Requisitos da biblioteca de códigos de Adobe {#section-931a3fca1ce54afd90b88ba032e75f05}

A tabela a seguir lista as versões mínimas das bibliotecas de código ou SDKs usadas por várias [!DNL Experience Cloud] soluções e serviços. Se você usar qualquer um desses códigos e quiser participar do Device Co-op, certifique-se de atender a esses requisitos mínimos.

>[!TIP]
>
>Como prática recomendada, recomendamos que você use as versões mais recentes do código em vez dos mínimos necessários.

**AppMeasurement (Flash)**

Exige a versão 4.1. Consulte [AppMeasurement para Flash, Flex e AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Exige a versão 1.5.4. Consulte [AppMeasurement para Flash, Flex e AIR](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/js/migrate-from-hcode.html).

**SDKs móveis**

Requisitos mínimos do SDK móvel:

* Android versão 4.8.3.
* iOS versão 4.8.5.

Seu código SDK deve estar habilitado para o serviço de ID [!DNL Experience Cloud]. Ative e baixe o código SDK mais recente para cada aplicativo na sua conta [Adobe Mobile Services](https://mobilemarketing.adobe.com/). Consulte [Configurar opções do serviço de ID de Visitante do SDK](https://docs.adobe.com/content/help/pt-BR/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

Para cada SDK, use o método `visitorSyncIdentifier` apropriado que se ajuste às suas necessidades. Consulte:

* [Métodos de serviço de ID de Experience Cloud do Android](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [Métodos do serviço de ID de Experience Cloud do iOS](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Exige a versão 1.5.4.

[!DNL Analytics] os clientes podem baixar a biblioteca VisitorAPI.js de  [!DNL Code Manager]. Ele está localizado nos arquivos JavaScript (Novo) ou JavaScript (Herdado). Entre em contato com [Atendimento ao cliente](https://helpx.adobe.com/br/marketing-cloud/contact-support.html) se você não tiver acesso a [!DNL Code Manager].

**Biblioteca de públicos alvos**

Exige uma das seguintes [!DNL Target] bibliotecas JavaScript:

* at.js (qualquer versão)
* mbox.js versão 58 ou posterior

