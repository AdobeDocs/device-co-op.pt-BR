---
description: Sobre dispositivos conhecidos no Gráfico de dispositivos.
seo-description: Sobre dispositivos conhecidos no Gráfico de dispositivos.
seo-title: Dispositivos conhecidos
title: Dispositivos conhecidos
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Known devices{#known-devices}

Sobre dispositivos conhecidos no Gráfico de dispositivos.

No Gráfico de dispositivos, temos o conceito de um *`known device`*. Um dispositivo conhecido é um dispositivo que um cliente usa para interagir com a sua marca.

>[!NOTE]
>
>No [!DNL Adobe Experience Cloud Device Co-op], termos como *`device`*, *`person`*, *`identity`* etc. têm significados específicos. Por exemplo, &quot;dispositivo&quot; pode se referir a um hardware físico, como um telefone ou tablet e os aplicativos executados em tal hardware. Consulte o [glossário](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) para obter as definições.

## Supporting goals with the known device {#section-80deae33660e4280ac65c659ceff5601}

O conceito de dispositivo conhecido apoia algumas metas essenciais para a criação e manutenção de um programa de [!DNL Device Co-op] eficiente. Um dispositivo conhecido é aquele que se torna conhecido por um membro do [!DNL Device Co-op] através de alguma interação com o consumidor (por exemplo, uma visita ao site ou utilização de um aplicativo móvel). Based on these actions, the [!DNL Device Graph] links the known devices of a [!DNL Device Co-op] member to devices contributed by other [!DNL Device Co-op] members. Esses links podem ser [determinísticos ou probabilísticos](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). This benefits [!DNL Device Co-op] members because they receive:

* Mais dados sobre seus dispositivos conhecidos.
* Novas informações sobre outros dispositivos vinculados.

![](assets/known-device.png)

The [!DNL Device Graph] will not provide information about device-clusters that a Device Co-op member has not seen.

## Device Co-op goals {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Three main goals animate the [!DNL Device Co-op]. Elas incluem:

* **Escala:** compartilhar o maior número de links possível em uma variedade de casos de uso.
* **Equidade:** assegurar que cada membro do [!DNL Device Co-op] se beneficie de forma compatível com suas contribuições.

* **Confiança do consumidor:** manter e reforçar a confiança do consumidor, garantido que a experiência do consumidor entre dispositivos envolva as marcas que já conhecem e confiam.

## Scale and the known device {#section-67f734109762457ca62ec306284ea082}

Os métodos a seguir são as maneiras mais comuns de um dispositivo se qualificar como um dispositivo conhecido. Considerando estes métodos, os membros do [!DNL Device Co-op] quase sempre terão, pelo menos, um dispositivo conhecido. Isso apoia a meta de proporcionar a maior escala a todos os membros do [!DNL Device Co-op].

**Fundamental**

* Através de uma visita de um cliente ao seu site ou utilização do seu aplicativo. Esta é a qualificação de dados primários.
* Ao adicionar clientes de um sistema de CRM.

**Marketplace**

* Aquisição de dados de segmento do Audience Marketplace.
* Através da aquisição de dados de um provedor de dados terceirizado.

**Propaganda**

Ao vencer um inventário em um leilão e exibir um anúncio em um dispositivo. O dispositivo se torna um dispositivo conhecido se tal anúncio contiver um pixel do [!DNL Audience Manager].

## Known devices and fairness use cases {#section-0543188729d845d6b95db70b8b25e9f8}

Members of the [!DNL Device Co-op] get links commensurate with their contributions to the [!DNL Device Graph]. Companies that contribute a lot of devices to the [!DNL Device Graph] receive more links than members who contribute just a few. Acreditamos que isso ajuda a tornar o [!DNL Device Co-op] justo para todos os seus membros. Vejamos como isso funciona com os casos de uso pequenos e grandes descritos abaixo.

**Marca A: caso de uso grande**

Neste exemplo, a Marca A tem 100 visitantes ao site a cada mês e inicia uma nova campanha de marca entre dispositivos. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand A are linked to 1 additional device. Isso significa que a Marca A pode atingir outros 100 dispositivos. Additionally, the [!DNL Device Graph] contains about 200 devices linked together.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Dispositivos conhecidos/mês </th> 
   <th colname="col2" class="entry"> Dispositivos vinculados recebidos do Device Co-op </th> 
   <th colname="col3" class="entry"> Total de dispositivos para a campanha </th> 
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

**Marca B: caso de uso pequeno**

Neste exemplo, a Marca B tem 100 visitantes ao site a cada mês e inicia uma nova campanha de marca entre dispositivos. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand B are linked to 50 additional devices. Isso significa que a Marca B pode atingir 150 dispositivos. Additionally, the [!DNL Device Graph] contains about 1,000 devices linked together.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Dispositivos conhecidos/mês </th> 
   <th colname="col2" class="entry"> Dispositivos vinculados recebidos do Device Co-op </th> 
   <th colname="col3" class="entry"> Total de dispositivos para a campanha </th> 
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

