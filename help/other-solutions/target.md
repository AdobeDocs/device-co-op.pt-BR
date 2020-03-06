---
description: Saiba como usar dados do Device Co-op em atividades do Adobe Target.
seo-description: Saiba como usar dados do Device Co-op em atividades do Adobe Target.
seo-title: Target - testes A/B, testes multivariados e direcionamento de experiência
title: Target - testes A/B, testes multivariados e direcionamento de experiência
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Saiba como usar dados do Device Co-op em atividades do Adobe Target.

Você pode usar dados do Device Co-op em testes A/B, testes multivariados (MVT) e atividades de direcionamento de experiência. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

Você não pode usar os dados do Device Co-op nas atividades de Personalização automatizada, nas atividades de Recomendação ou nas atividades utilizando o [!DNL Adobe Analytics] como fonte de relatórios (a integração do [!DNL Target] com o [!DNL Analytics], conhecida como A4T).

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. Você pode usar qualquer versão do `at.js`. Para obter mais informações, consulte Requisitos [de associação](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

Os profissionais de marketing querem oferecer a experiência mais relevante para cada visitante, independentemente do dispositivo que o visitante está usando atualmente para interagir com a sua empresa ou marca.

Os usuários interagem com a mesma empresa ou marca de muitos dispositivos diferentes: laptops de trabalho, computadores domésticos, iPads, iPhones, vários navegadores, e assim por diante. Se você não puder reconhecer que um dispositivo ou navegador específico está sendo usado por uma pessoa que já interagiu com a sua marca em outro dispositivo ou navegador, você não poderá fornecer uma experiência consistente e direcionada para essa pessoa.

Com o Device Co-op, os diferentes dispositivos de um usuário podem ser identificados como sendo usados pelo mesmo usuário. Quando o usuário vê uma página com atividades do [!DNL Target], sejam atividades ou conteúdo direcionado, o [!DNL Target] pode garantir que o usuário veja a mesma experiência vista em outro dispositivo.

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

Os profissionais de marketing querem analisar as atividades do [!DNL Target] por &quot;pessoas&quot; em vez de por &quot;visitantes&quot;.

Cada pessoa provavelmente interage com a mesma empresa ou marca nos dispositivos e navegadores, mas sem o Device Co-op, cada dispositivo ou navegador individual é considerado um &quot;visitante&quot; separado nos relatórios do [!DNL Target].

Exibir relatórios por dispositivos e navegadores individuais infla a contagem de “visitantes” para um número maior que o número de pessoas diferentes que interagem com a empresa ou marca. Essas pessoas normalmente são convertidas apenas uma vez em todos estes dispositivos e navegadores, assim, a taxa de conversão será menor do que na realidade porque mais “visitantes” serão contabilizados para uma única conversão.

Com o Device Co-op, a entrega de conteúdo e a geração de relatórios é feita em nível de “pessoas”, de modo que os relatórios mostram com precisão quantas pessoas diferentes viram a atividade e quantas pessoas foram convertidas.

Sem os dados do Device Co-op, você pode determinar que uma certa atividade é a vencedora; contudo, como os relatórios são mais precisos com o Device Co-op, outra atividade pode realmente ter uma taxa de conversão mais elevada e, por conseguinte, ser a vencedora.

Para obter mais informações sobre este conceito, consulte [Analytics: Métrica](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)de Pessoas.

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

Os profissionais de marketing podem optar por usar os dados do Device Co-op por atividade. Determinadas atividades do [!DNL Target] podem não ser adequadas para os dados do Device Co-op, tais como:

* Conteúdo específico apropriado para os usuários em um iPad.

   Os usuários que primeiro visualizam uma experiência em um iPad, continuarão a ver essa experiência em seus computadores domésticos.

* Uma oferta de taxa de juro disponível apenas para um segmento restrito de visitantes.
* Os produtos autorizados a serem anunciados apenas em um estado específico (por exemplo, uma apólice de seguro com restrições de licença).

Quando os profissionais de marketing criam públicos no [!DNL Target], eles são alertados se o público é apropriado para atividades habilitadas por dados do Device Co-op. Públicos adequados incluem todos os visitantes, novos visitantes e visitantes de retorno.
