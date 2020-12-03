---
description: Sobre dispositivos conhecidos no Gráfico de dispositivos.
seo-description: Sobre dispositivos conhecidos no Gráfico de dispositivos.
seo-title: Dispositivos conhecidos
title: Dispositivos conhecidos
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '571'
ht-degree: 1%

---


# Dispositivos conhecidos{#known-devices}

Sobre dispositivos conhecidos no Gráfico de dispositivos.

No Gráfico de dispositivos, temos o conceito de um *`known device`*. Um dispositivo conhecido é um dispositivo que um cliente usa para interagir com sua marca.

>[!NOTE]
>
>No [!DNL Adobe Experience Cloud Device Co-op], termos como *`device`*, *`person`*, *`identity`* etc. têm significados específicos. Por exemplo, &quot;dispositivo&quot; pode se referir ao hardware físico, como um telefone ou tablet, e aos aplicativos executados nesse hardware. Consulte o [glossário](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) para ver as definições.

## Objetivos de suporte com o dispositivo conhecido {#section-80deae33660e4280ac65c659ceff5601}

O conceito de dispositivo conhecido suporta algumas metas essenciais para a criação e manutenção de um [!DNL Device Co-op] programa eficaz. Um dispositivo conhecido é aquele que um [!DNL Device Co-op] membro conhece de alguma interação com um consumidor (por exemplo, uma visita ao site ou usando um aplicativo móvel). Com base nessas ações, o [!DNL Device Graph] vincula os dispositivos conhecidos de um [!DNL Device Co-op] membro aos dispositivos contribuídos por outros [!DNL Device Co-op] membros. Esses links podem ser [determinísticos ou probabilísticos](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). Isso beneficia [!DNL Device Co-op] os membros porque eles recebem:

* Mais dados sobre seus dispositivos conhecidos.
* Novas informações sobre outros dispositivos vinculados.

![](assets/known-device.png)

O não [!DNL Device Graph] fornecerá informações sobre clusters de dispositivos que um membro do Device Co-op não viu.

## Metas do Device Co-op {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Três objetivos principais animam o [!DNL Device Co-op]. Eles incluem:

* **Escala:** Compartilhe o número máximo de links possíveis em diversos casos de uso.
* **Equidade:** Garantir que cada membro dos [!DNL Device Co-op] benefícios seja proporcional às suas contribuições.

* **Confiança do consumidor:** Mantenha e consolide a confiança dos consumidores, garantindo que a experiência entre dispositivos dos consumidores envolva marcas que eles já conhecem e confiam.

## Escala e dispositivo conhecido {#section-67f734109762457ca62ec306284ea082}

Os métodos a seguir são as maneiras mais comuns de um dispositivo se qualificar como um dispositivo conhecido. Considerando esses métodos, [!DNL Device Co-op] os membros quase sempre terão pelo menos um dispositivo conhecido. Isto apoia o objetivo de proporcionar uma escala máxima a todos os membros do grupo [!DNL Device Co-op].

**Orgânico**

* Da visita de um cliente ao seu site ou usando seu aplicativo. Esta é a qualificação de dados primários.
* Através de clientes embarcados de um sistema de CRM.

**Marketplace**

* Comprando dados de segmento do Audience Marketplace.
* A partir da compra de dados de um provedor de dados de terceiros.

**Publicidade**

Ao ganhar um inventário em um leilão e servir um anúncio para um dispositivo. O dispositivo se torna um dispositivo conhecido se esse anúncio contiver um [!DNL Audience Manager] pixel.

## Dispositivos conhecidos e casos de uso de equidade {#section-0543188729d845d6b95db70b8b25e9f8}

Os membros do grupo [!DNL Device Co-op] recebem ligações proporcionais às suas contribuições para o [!DNL Device Graph]. Empresas que contribuem com muitos dispositivos para o [!DNL Device Graph] recebem mais links do que membros que contribuem com apenas alguns. Acreditamos que isso ajuda a tornar a [!DNL Device Co-op] justiça para todos os seus membros. Vamos ver como isso funciona com os casos de uso pequeno e grande descritos abaixo.

**Marca A: caso de uso grande**

Neste exemplo, a Marca A tem 100 visitantes de site a cada mês e start uma nova campanha de marca entre dispositivos. Para simplificar, suponha que o [!DNL Device Graph] saiba que todos os visitantes da Marca A estão vinculados a um dispositivo adicional. Isso significa que a Marca A pode atingir outros 100 dispositivos. Além disso, o [!DNL Device Graph] contém cerca de 200 dispositivos vinculados.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Dispositivos conhecidos/mês </th> 
   <th colname="col2" class="entry"> Dispositivos vinculados recebidos do Device Co-op </th> 
   <th colname="col3" class="entry"> Total de dispositivos para Campanha </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Marca B: Caso de uso pequeno**

Neste exemplo, a Marca B tem 100 visitantes do site a cada mês e start uma nova campanha de marca entre dispositivos. Para simplificar, suponha que o [!DNL Device Graph] saiba que todos os visitantes da Marca B estão vinculados a 50 dispositivos adicionais. Isso significa que a Marca B pode atingir 150 dispositivos. Além disso, o [!DNL Device Graph] contém cerca de 1.000 dispositivos vinculados.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Dispositivos conhecidos/mês </th> 
   <th colname="col2" class="entry"> Dispositivos vinculados recebidos do Device Co-op </th> 
   <th colname="col3" class="entry"> Total de dispositivos para Campanha </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [Dispositivos desconhecidos](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

