---
keywords: adobe experience cloud; Adobe Experience Cloud; device co-op; Device Co-op; fim da vida útil
title: Perguntas frequentes sobre o fim da vida útil do Device Co-op
description: Saiba mais sobre os planos de fim de vida útil do Device Co-op.
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: c19e8425d5d6c2498186c19929907d2ee5327b31
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 2%

---

# Perguntas frequentes sobre o fim da vida útil do Device Co-op

Este documento fornece respostas a perguntas frequentes sobre o plano de fim de vida útil (EOL) do Adobe Experience Cloud Device Co-op. Quando esse plano entrar em vigor, o Adobe fornecerá um aviso avançado nas [Notas de versão do Experience Cloud](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=pt-BR) e [Atualização de produto prioritária](https://www.adobe.com/subscription/priority-product-update.html).

## Perguntas frequentes

Veja a seguir uma lista de respostas para perguntas frequentes sobre o plano EOL [!DNL Device Co-op].

## Por que [!DNL Device Co-op] está sendo descontinuado?

As próximas alterações no ambiente AdTech devem resultar em [!DNL Device Co-op] se tornar uma solução obsoleta nos próximos anos. [!DNL Device Co-op] O é composto principalmente de cookies de terceiros e o  [!DNL Google's] anúncio de que o bloqueio de cookies de terceiros em  [!DNL Google Chrome] 2022 diminuirá a eficácia do  [!DNL Device Co-op]. [!DNL Chrome] O tem aproximadamente 65% da quota de mercado do navegador e outros principais navegadores já implementaram o bloqueio de cookies de terceiros. Quando [!DNL Chrome] bloquear cookies de terceiros, a maioria dos cookies de terceiros será bloqueada e [!DNL Device Co-op] ficará obsoleta.

## Por que as inscrições [!DNL Device Co-op] do Adobe estão sendo encerradas agora?

As inscrições estão acabando para evitar riscos de não atender às expectativas dos clientes devido às próximas alterações do setor em cookies de terceiros. [!DNL Device Co-op] demora alguns meses para ser preparado e outros meses para extrair valor do serviço. Quaisquer inscrições adicionais neste ponto podem resultar em marcas que não apresentam o valor total de [!DNL Device Co-op].

## Os novos clientes podem se inscrever?

A partir de 11 de junho de 2021, o Adobe deixará de aceitar novas inscrições em [!DNL Device Co-op].

## Os contratos existentes estão a ser renovados?

A partir de 11 de junho de 2021, o Adobe não renovará mais os contratos [!DNL Device Co-op]. Se quiser continuar usando os serviços [!DNL Device Co-op], continue a fazê-lo sob os termos de licença atuais até o fim do programa.

## Qual é a data final exata do programa [!DNL Device Co-op]?

O programa [!DNL Device Co-op] terminará em 2022. O tempo e a data específicos dependem de quando [!DNL Google] começa a bloquear cookies de terceiros.

## Quais aplicativos serão afetados pelo fim da vida útil do Device Co-op?

Os seguintes aplicativos serão afetados pelos [!DNL Device Co-op] procedimentos de fim de vida:

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## Quais opções tenho como alternativas para [!DNL Device Co-op]?

### [!DNL Analytics]

Você pode usar o recurso [!DNL Analytics] [Análise entre dispositivos (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html), pois ele é compatível com o Serviço de identidade da Adobe Experience Platform [Gráfico privado](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) e [Configuração em campo](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en).

### [!DNL Audience Manager]

[!DNL Audience Manager] O mantém integrações com parceiros de gráficos de dispositivos de terceiros, incluindo  [!DNL LiveRamp] e  [!DNL Tapad], embora seja necessário estabelecer relações comerciais diretamente com parceiros de gráficos, para aproveitar o  [!DNL Audience Manager].

### [!DNL Real-time Customer Data Platform]

Não há planos para modificar o [!DNL Audience Manager Data Management Platform] (DMP) atual. No entanto, a desativação de cookies de terceiros provavelmente criará desafios de escala para a maioria dos usuários do DMP. Para ajudar os clientes a desenvolver suas práticas de gerenciamento de dados, o Adobe está incentivando a redução das dependências de identificadores que enfrentarão restrições no próximo ano. As equipes de marketing devem criar estratégias de dados primários focadas em identificadores duráveis que incluem informações de identificação pessoal (PII), que podem ser resolvidas com [!DNL Real-time Customer Data Platform] (CDP em tempo real).

[!DNL Real-time CDP] reduz as dependências de cookies de terceiros e IDs de dispositivo, expandindo o conjunto de identificadores disponíveis para a criação de público-alvo para incluir PII. A base para [!DNL Real-time CDP] é o Perfil do cliente em tempo real, que reúne os dados do atributo da pessoa com os dados comportamentais em tempo real e permite que os profissionais de marketing criem segmentos avançados de público com controles patenteados de governança de dados. Como [!DNL Audience Manager], [!DNL Real-time CDP] fornece insights e casos de uso de personalização, mas também gera insights mais granulares no nível da pessoa e pode ativar públicos-alvo para uma variedade maior de destinos, abrangendo tecnologias de publicidade e tecnologias de marketing, incluindo mídia paga, mídia social, email e sistemas de clientes.

[!DNL Real-time CDP] O também incluirá o acesso à Correspondência de segmentos da  [Adobe Experience Platform (Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en), que permite que as marcas expandam seus próprios conjuntos de dados primários por meio de parcerias e obtenham insights e personalização aprimorados.

### [!DNL Target]

No momento, não há alternativas disponíveis para [!DNL Target] porque [!DNL Target] fornece um recurso determinístico de identificação entre dispositivos conhecido como `mbox3rdPartyId`, que funciona de forma semelhante à ID do cliente Adobe. Esse recurso permite que os clientes [!DNL Target] mesclem perfis e participação de atividades em [!DNL Target] testes e personalização sendo feitos em canais de entrada.

### Adobe Advertising Cloud

[!DNL Advertising Cloud] Os clientes do não poderão mais usar o  [!DNL Device Co-op] para direcionamento e medição de público-alvo entre dispositivos. Com [!DNL Advertising Cloud], você ainda poderá alavancar a parceria com o Adobe [!DNL Device Graph] para continuar a executar essas funções até a extensão [!DNL LiveRamp’s] capacidade e escala. [!DNL LiveRamp] Você deve permitir que suas campanhas que estão usando [!DNL Device Co-op] terminem e, em seguida, alternem para o provedor de gráfico de dispositivo [!DNL LiveRamp] ou não aproveitem mais o direcionamento baseado em pessoas.

## Quais recursos e implementações existentes podem ajudar minha preparação para um futuro sem cookies?

Sua implementação do Serviço de ID de visitante existente capacita o Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). Se a ID declarada existente for um email com hash, isso poderá ser usado para potencializar os seguintes recursos:

- [!DNL Audience Manager] [Destinos com base em pessoas](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Correspondência de segmento de Experience Platform (Alfa)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en).

## Posso manter meus dados de [!DNL Device Co-op]?

Para usuários [!DNL Audience Manager] e [!DNL Advertising Cloud], os dados de [!DNL Device Co-op] não estarão disponíveis para serem transferidos para gráficos de terceiros. [!DNL Device Co-op] Os dados só serão migrados para  [!DNL Analytics Ultimate] usuários que usam o CDA com a  [!DNL Device Co-op] alternância para a configuração em campo. Todas as outras soluções não terão seus dados migrados.

## É obrigatório adotar outras características?

Embora a adoção de outros recursos do Adobe não seja obrigatória, você deve iniciar a implementação de outros recursos o mais rápido possível para permitir tempo e a coordenação apropriada antes da desativação de [!DNL Device Co-op].

## Quando terei de adotar soluções alternativas, se assim o decidi?

A adoção de outros recursos não é obrigatória. Só é recomendável se você quiser continuar abordando casos de uso que foram abordados por [!DNL Device Co-op]. Se optar por adotar outros recursos, deverá fazê-lo até 2022 (data exata a ser anunciada) antes do fim do programa [!DNL Device Co-op].

## Quanto tempo irá demorar a adoção?

Isso dependerá do recurso . Por exemplo, se um cliente do Analytics Ultimate que usa o Cross-Device Analytics com [!DNL Device Co-op] precisar migrar para o Gráfico de dispositivos privados em tempo real ou a Configuração em campo, a adoção levará algum tempo.
