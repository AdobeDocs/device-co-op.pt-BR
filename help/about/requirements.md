---
description: Sua empresa deve atender a esses padrões mínimos antes de começar a usar o Experience Cloud Device Co-op.
seo-description: Your company must meet these minimum standards before you can start using the Experience Cloud Device Co-op.
seo-title: Membership requirements
title: Requisitos de associação
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
exl-id: 923ce9c5-7716-4c5a-95f2-05a81a05c9cf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 17%

---

# Requisitos de associação{#membership-requirements}

Sua empresa deve atender a esses padrões mínimos antes de começar a usar o Experience Cloud Device Co-op.

## Exigências {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Fale com o seu [!DNL Adobe representative to get started]. A Adobe reserva-se o direito de negar qualquer associação potencial de cliente ao Experience Cloud Device Co-op se a Adobe determinar que a participação de um cliente potencial no Device Co-op pode (1) violar qualquer lei aplicável; ou (2) causar um risco material para a segurança ou as operações do Adobe ou de qualquer um de seus clientes.

## requisitos de Experience Cloud {#section-76218a50385d43e6b9323e49f598394a}

Você deve estar habilitado para o [!DNL Adobe Experience Cloud] e use as seguintes soluções e serviços para participar da cooperação.

**Soluções**

Os candidatos devem usar pelo menos um dos seguintes [!DNL Adobe]soluções:

* [Analytics](http://www.adobe.com/br/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/br/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/br/marketing-cloud/testing-targeting.html)

**Serviços principais**

Os candidatos devem implementar a [Serviço de ID Experience Cloud](https://docs.adobe.com/content/help/pt-BR/id-service/using/home.html).

## requisitos da biblioteca de códigos Adobe {#section-931a3fca1ce54afd90b88ba032e75f05}

A tabela a seguir lista as versões mínimas das bibliotecas de código ou SDKs usadas por vários [!DNL Experience Cloud] soluções e serviços. Se você usar qualquer um desses códigos e quiser participar do Device Co-op, verifique se atende a esses requisitos mínimos.

>[!TIP]
>
>Como prática recomendada, é recomendado usar as versões mais recentes do código em vez dos mínimos necessários.

**AppMeasurement (Flash)**

Exige a versão 4.1. Consulte [AppMeasurement para Flash, Flex e AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Exige a versão 1.5.4. Consulte [AppMeasurement para Flash, Flex e AIR](https://docs.adobe.com/content/help/pt-BR/analytics/implementation/js/migrate-from-hcode.html).

**SDKs móveis**

Requisitos mínimos do SDK móvel:

* Android versão 4.8.3.
* iOS versão 4.8.5.

O código do SDK deve ser habilitado para o [!DNL Experience Cloud] Serviço de ID. Habilite e baixe o código do SDK mais recente para cada aplicativo no [Adobe Mobile Services](https://mobilemarketing.adobe.com/) conta. Consulte [Configurar as opções do serviço de ID de visitante do SDK](https://docs.adobe.com/content/help/pt-BR/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

Para cada SDK, use o apropriado `visitorSyncIdentifier` que atenda às suas necessidades. Consulte:

* [Métodos do serviço de ID de Experience Cloud do Android](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [Métodos do serviço de ID de Experience Cloud da iOS](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Exige a versão 1.5.4.

[!DNL Analytics] Os clientes do podem baixar a biblioteca VisitorAPI.js no [!DNL Code Manager]. Ele está localizado nos arquivos JavaScript (Novo) ou JavaScript (Herdado). Contato [Atendimento ao cliente](https://helpx.adobe.com/br/marketing-cloud/contact-support.html) se você não tiver acesso ao [!DNL Code Manager].

**Biblioteca do Target**

Requer um dos seguintes [!DNL Target] Bibliotecas de JavaScript do:

* at.js (qualquer versão)
* mbox.js versão 58 ou posterior
