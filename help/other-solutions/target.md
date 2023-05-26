---
description: Saiba como usar os dados do Device Co-op em atividades do Adobe Target.
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - testes A/B, testes multivariados e direcionamento de experiência
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target - testes A/B, testes multivariados e direcionamento de experiência{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Saiba como usar os dados do Device Co-op em atividades do Adobe Target.

Você pode usar os dados do Device Co-op em testes A/B, testes multivariados (MVT) e atividades de direcionamento de experiência. A opção Device Co-op está disponível durante a criação da atividade no [!DNL Goals & Settings] página no [!DNL Target] fluxo de trabalho guiado de três etapas.

Não é possível usar os dados do Device Co-op em atividades do Automated Personalization, atividades do Recommendations ou atividades que usam [!DNL Adobe Analytics] como fonte de relatórios (a variável [!DNL Target] e [!DNL Analytics] (conhecido como A4T).

>[!NOTE]
>
>Verifique se você tem a versão necessária do `mbox.js`. É possível usar qualquer versão do `at.js`. Para obter mais informações, consulte [Requisitos de associação](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Fornecer conteúdo relevante independentemente do dispositivo {#section-bba8d41e96914c82a6d267a54f776354}

Os profissionais de marketing desejam fornecer a experiência mais relevante para cada visitante, independentemente do dispositivo que o visitante está usando atualmente para interagir com a empresa ou marca.

Os usuários interagem com a mesma empresa ou marca de vários dispositivos diferentes: laptops de trabalho, computadores domésticos, iPads, iPhones, vários navegadores e assim por diante. Se você não puder reconhecer que cada dispositivo ou navegador específico está sendo usado pela mesma pessoa que interagiu anteriormente com sua marca em outro dispositivo ou navegador, você não poderá fornecer uma experiência consistente e direcionada para essa pessoa.

Com o Device Co-op, vários dispositivos de um usuário podem ser identificados como sendo usados pelo mesmo usuário. Quando esse usuário visualiza uma página com [!DNL Target] atividades — atividades ou conteúdo direcionado — [!DNL Target] O pode garantir que o usuário veja a mesma experiência vista em outro dispositivo.

## Analisar atividades do Target por pessoas em vez de por visitantes {#section-c25cf4f8483942d7836d60756235e62c}

Profissionais de marketing querem analisar [!DNL Target] atividades por &quot;pessoas&quot; em vez de &quot;visitantes&quot;.

Cada pessoa provavelmente está interagindo com a mesma empresa ou marca em dispositivos e navegadores, mas sem o Device Co-op, cada dispositivo ou navegador individual é considerado um &quot;visitante&quot; separado no [!DNL Target] relatórios.

A visualização de relatórios por dispositivos e navegadores individuais aumenta a contagem de &quot;visitantes&quot; para um número maior do que o número de pessoas diferentes interagindo com a empresa ou marca. Normalmente, essas pessoas convertem apenas uma vez nesses vários dispositivos e navegadores, portanto, a taxa de conversão será menor do que na realidade, pois mais &quot;visitantes&quot; serão contados para uma única conversão.

Com o Device Co-op, a entrega de conteúdo e os relatórios são feitos no nível das &quot;pessoas&quot;, de modo que os relatórios mostram com precisão quantas pessoas diferentes viram a atividade e quantas pessoas foram convertidas.

Sem os dados do Device Co-op, você pode determinar que uma determinada atividade é a vencedora; no entanto, como os relatórios são mais precisos com o Device Co-op, outra atividade pode realmente ter uma taxa de conversão mais alta e, portanto, ser a vencedora.

Para obter mais informações sobre esse conceito, consulte [Analytics: Métrica Pessoas](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Usar dados do Device Co-op por atividade {#section-fb46fae482654023abb1a1e26564db9a}

Os profissionais de marketing podem optar por usar os dados do Device Co-op por atividade. Certos [!DNL Target] As atividades podem não ser apropriadas para dados do Device Co-op, como:

* Conteúdo específico apropriado para usuários em uma iPad.

   Os usuários que visualizarem uma experiência pela primeira vez em um iPad continuarão a visualizá-la em seus computadores domésticos.

* Uma oferta de taxa de juros disponível somente para um segmento restrito de visitantes.
* Produtos permitidos para serem anunciados apenas em um estado específico (por exemplo, uma apólice de seguro com restrições de licença).

Quando os profissionais de marketing criam públicos-alvo no [!DNL Target], eles serão alertados se o público-alvo não for apropriado para atividades habilitadas para dados do Device Co-op. Os públicos-alvo apropriados incluem todos os visitantes, novos visitantes e visitantes recorrentes.
