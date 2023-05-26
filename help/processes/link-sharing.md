---
description: Sobre o compartilhamento de links no Gráfico de dispositivos.
seo-description: About link sharing in the Device Graph.
seo-title: Link sharing in the Device Graph
title: Compartilhamento de links no Gráfico de dispositivos
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
exl-id: 91ecc493-89d8-40d6-a98b-c2349e25c854
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---

# Compartilhamento de links no Gráfico de dispositivos{#link-sharing-in-the-device-graph}

Sobre o compartilhamento de links no Gráfico de dispositivos.

A variável [!DNL Device Graph] O compartilha links determinísticos e probabilísticos com diferentes membros do Device Co-op da Adobe Experience Cloud. O compartilhamento de links é o que torna o [!DNL Device Co-op] tão poderoso. Ele estende o que cada membro sabe sobre os dispositivos associados a uma pessoa anônima, mas somente se você já viu pelo menos um dos dispositivos dessa pessoa anônima antes.

## Análise do resumo do Gráfico de dispositivos {#section-7858e9f61b5644c981ffb53626fcc19d}

Antes de começar, vamos analisar como a [!DNL Device Graph] funciona. Membros da [!DNL Device Co-op] enviar dados para o [!DNL Device Graph]. A variável [!DNL Device Graph] usa esses dados para criar a identidade de uma pessoa a partir de [vínculos determinísticos e probabilísticos](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) entre dispositivos. Como um [!DNL Device Co-op] participante, esses links fornecem informações sobre a relação entre usuários autenticados, outros usuários e seus dispositivos. Vamos analisar como isso funciona na seção abaixo.

## Exemplo de compartilhamento de link {#section-cb410d827cf14f76bc9b0bd4d31ed767}

O exemplo a seguir demonstra o potencial do compartilhamento de links no Device Co-op. Neste exemplo, temos duas empresas fictícias, a News Company e a Finance Company. Ambas as empresas são membros da [!DNL Device Co-op]. A Pessoa A é um consumidor que faz logon ou navega pelos sites de cada empresa a partir de vários dispositivos.

![](assets/share1.png)

Como a Pessoa A foi autenticada no site de notícias com seu celular e tablet, a Empresa de notícias a identifica com uma ID de consumidor. Ele envia essa ID para o [!DNL Device Graph] como um hash criptográfico. A Empresa Financeira viu esses dispositivos antes, mas a Pessoa A não fez logon no site. Consequentemente, a Finance Company não sabe se ou como esses dispositivos se relacionam entre si ou como estão associados à Pessoa A.

![](assets/share2.png)

Dado o hash criptográfico da ID do consumidor, o [!DNL Device Graph] O reconhece que esses dispositivos estão relacionados entre si e com uma pessoa em particular. A empresas que não participam na [!DNL Device Co-op] essas visitas ao site parecem vir de dispositivos separados e aleatórios. Em qualquer caso, uma vez [!DNL Device Graph] tem a ID com hash:

* Sabe que o telefone celular e o notebook estão vinculados.
* Reconhece que a Finance Company quer saber se o telefone celular e o notebook estão vinculados.

Dadas estas condições, a [!DNL Device Graph] agora compartilha o link que conecta esses dispositivos da News Company com a Finance Company. Durante esse processo, a [!DNL Device Graph] duplica e compartilha o link de um membro cooperativo para outro.

![](assets/share3.png)

Neste ponto, a variável [!DNL Device Graph] O executou a função com sucesso. Tanto a Companhia de Notícias como a Companhia Financeira têm uma imagem clara de uma identidade. Eles podem alcançar a Pessoa A com precisão em todos os seus dispositivos.

## Privacidade e compartilhamento de links {#section-7b566018b3304420a4b3e4c079826110}

Manutenção da privacidade do consumidor e da integridade dos dados para [!DNL Device Co-op] membros é fundamental durante todo o processo de compartilhamento de links. Durante esse processo de identificação do cliente e compartilhamento de links, a [!DNL Device Graph] não:

* Informe à Companhia Financeira que o link veio da Companhia de Notícias.
* Compartilhar a ID do cliente usada por um [!DNL Device Co-op] membro com outro.
* Forneça qualquer informação diferente de que o dispositivo móvel e o laptop compartilham um link em comum.

## Próximas etapas {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Ler a documentação sobre identidade, link e compartilhamento de links deve fornecer uma boa noção de como [!DNL Device Graph] O monta os dados internamente. Como próxima etapa, recomendamos consultar nossa documentação que descreve como o conceito de um *`known device`* O fornece links entre dispositivos para membros do Device Co-op. Consulte [Dispositivos conhecidos](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) e [Dispositivos desconhecidos](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).
