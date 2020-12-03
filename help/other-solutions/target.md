---
description: Saiba como usar dados do Device Co-op no Adobe Target atividade.
seo-description: Saiba como usar dados do Device Co-op no Adobe Target atividade.
seo-title: Público alvo - testes A/B, testes multivariados e direcionamento de experiência
title: Público alvo - testes A/B, testes multivariados e direcionamento de experiência
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---


# Público alvo - testes A/B, testes multivariados e direcionamento de experiência{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Saiba como usar dados do Device Co-op no Adobe Target atividade.

Você pode usar dados do Device Co-op em testes A/B, testes multivariados (MVT) e atividades de direcionamento de experiência. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

Não é possível usar os dados do Device Co-op no Automated Personalization atividade, no Recommendations atividade ou no atividade usando [!DNL Adobe Analytics] a fonte de relatórios (a integração [!DNL Target] [!DNL Analytics] e a integração, conhecida como A4T).

>[!NOTE]
>
>Verifique se você tem a versão necessária do `mbox.js`. Você pode usar qualquer versão do `at.js`. Para obter mais informações, consulte Requisitos [de associação](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Fornecer conteúdo relevante independentemente do dispositivo {#section-bba8d41e96914c82a6d267a54f776354}

Os profissionais de marketing querem oferecer a experiência mais relevante a cada visitante, independentemente do dispositivo que o visitante está usando atualmente para interagir com sua empresa ou marca.

Os usuários interagem com a mesma empresa ou marca de vários dispositivos diferentes: laptops de trabalho, computadores domésticos, iPads, iPhones, vários navegadores e assim por diante. Se você não puder reconhecer que cada dispositivo ou navegador específico está sendo usado pela mesma pessoa que interagiu com sua marca anteriormente em outro dispositivo ou navegador, não será possível fornecer uma experiência consistente e direcionada a essa pessoa.

Com o Device Co-op, vários dispositivos de um usuário podem ser identificados como sendo usados pelo mesmo usuário. Quando o usuário vê uma página com [!DNL Target] atividades — atividades ou conteúdo direcionado — [!DNL Target] pode garantir que o usuário veja a mesma experiência vista em outro dispositivo.

## Analisar atividades de Públicos alvos por pessoas em vez de por visitantes {#section-c25cf4f8483942d7836d60756235e62c}

Os profissionais de marketing querem analisar [!DNL Target] atividades por &quot;pessoas&quot; em vez de &quot;visitantes&quot;.

Cada pessoa provavelmente interage com a mesma empresa ou marca em dispositivos e navegadores, mas sem o Device Co-op, cada dispositivo ou navegador individual é considerado um &quot;visitante&quot; separado nos [!DNL Target] relatórios.

Exibir relatórios por dispositivos e navegadores individuais aumenta a contagem de &quot;visitantes&quot; para um número maior do que o número de pessoas diferentes que interagem com a empresa ou marca. Normalmente, essas pessoas convertem apenas uma vez nesses vários dispositivos e navegadores, de modo que a taxa de conversão será menor do que na realidade, pois mais &quot;visitantes&quot; serão contados para uma única conversão.

Com o Device Co-op, o delivery e o relatórios do conteúdo são feitos no nível &quot;pessoas&quot;, de modo que os relatórios mostram com precisão quantas pessoas diferentes viram a atividade e quantas pessoas foram convertidas.

Sem dados do Device Co-op, você pode determinar que uma atividade específica é a vencedora; no entanto, como o relatórios é mais preciso com o Device Co-op, outra atividade pode ter uma taxa de conversão maior e, portanto, ser a vencedora.

Para obter mais informações sobre esse conceito, consulte [Analytics: Métrica](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)de Pessoas.

## Usar dados do Device Co-op por atividade {#section-fb46fae482654023abb1a1e26564db9a}

Os profissionais de marketing podem optar por usar os dados do Device Co-op por atividade. Algumas [!DNL Target] atividades podem não ser apropriadas para dados do Device Co-op, como:

* Conteúdo específico apropriado para usuários em um iPad.

   Os usuários que primeiro visualizações uma experiência em um iPad continuarão a ver essa experiência em seus computadores domésticos.

* Uma oferta de taxa de juro disponível apenas para um segmento restrito de visitantes.
* Produtos autorizados a serem anunciados apenas em um estado específico (por exemplo, uma apólice de seguro com restrições de licença).

Quando os profissionais de marketing criam audiências no [!DNL Target], eles são alertados se a audiência não é apropriada para atividades habilitadas para dados do Device Co-op. As audiências apropriadas incluem todos os visitantes, novos visitantes e visitantes recorrentes.
