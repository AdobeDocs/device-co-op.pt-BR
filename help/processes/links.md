---
description: Como o Gráfico de dispositivos analisa dados determinísticos e probabilísticos para criar um mapa que vincula dispositivos.
seo-description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-title: Deterministic and probabilistic links
title: Vínculos determinísticos e probabilísticos
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
exl-id: e9bd2b7a-7d39-425d-adbb-298944009fcc
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '845'
ht-degree: 0%

---

# Vínculos determinísticos e probabilísticos{#deterministic-and-probabilistic-links}

Como o Gráfico de dispositivos analisa dados determinísticos e probabilísticos para criar um mapa que vincula dispositivos.

No [!DNL Device Graph], os processos internos criam uma hierarquia de identidade que mapeia dispositivos e os conecta a pessoas individuais e anônimas. A saída do gráfico inclui links entre dispositivos que você pode usar para direcionamento junto com dados expostos em determinadas soluções de Experience Cloud. As soluções de Adobe que funcionam com [!DNL Device Graph] Os dados incluem Analytics, Audience Manager, Media Otimizer e Target.

A variável [!DNL Device Graph] O analisa dados determinísticos e probabilísticos para criar um mapa que vincule dispositivos. Dados determinísticos vinculam dispositivos com base em informações de logon com hash. Os dados probabilísticos vinculam dispositivos com base em informações como endereços IP e outros metadados. A variável [!DNL Device Graph] associa os clusters de dispositivos vinculados a uma pessoa individual anônima. Essas conexões permitem que os profissionais de marketing digital cheguem às pessoas em vez de dispositivos. No [!DNL Device Graph], o proprietário de um dispositivo é a representação anônima de uma pessoa real. Links determinísticos e probabilísticos ajudam a construir uma estrutura de identidade do usuário.

>[!NOTE]
>
>No Device Co-op da Adobe Experience Cloud, termos como *dispositivo*, *pessoa*, e *identidade* têm significados específicos. Por exemplo, *dispositivo* pode se referir a hardware físico, como um telefone ou tablet e aos aplicativos executados nesse hardware. Consulte a [glossário](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) para definições.

## O que são links? {#section-2df4c6f01eba49369993146df0661f13}

Quando falamos sobre links, é importante ter em mente o que eles realmente são no contexto do [!DNL Experience Cloud] Gráfico de dispositivos. Neste contexto, os links não são conexões físicas entre dispositivos. Em vez disso, um link é a forma como o Gráfico de dispositivos associa diferentes dispositivos à mesma pessoa desconhecida. Por exemplo, digamos que tenhamos um celular e um navegador de desktop. O telefone e o navegador podem ser considerados &quot;vinculados&quot; assim que o Gráfico de dispositivos determinar que esses dispositivos são usados pela mesma pessoa desconhecida. Como você lerá abaixo, o Gráfico de dispositivos cria identidades com links determinísticos e probabilísticos. E, no Gráfico de dispositivos, o proprietário de um dispositivo é a representação anônima de uma pessoa real.

## Links determinísticos {#section-33d41e828a674b398e36fe63da20ac09}

Links determinísticos associam um dispositivo a uma pessoa com base em um evento de autenticação (por exemplo, uma ação de logon em um site a partir de um dispositivo). Essa ação cria um identificador anônimo conhecido como ID do consumidor. Vamos dar uma olhada em como a vinculação determinística funciona. Neste exemplo, a Pessoa A faz logon em um site de notícias por meio de um aplicativo em seu dispositivo móvel. Mais tarde naquele dia, a Pessoa A faz logon novamente, mas dessa vez por meio de um navegador em seu laptop.

![](assets/link1.png)

Com base nas informações de logon, o Gráfico de dispositivos:

* Sabe que a Pessoa A está autenticada no site de notícias com uma combinação de telefone celular/aplicativo e laptop/navegador.
* Vincula esses dispositivos à Pessoa A.
* Cria uma identidade com base em dispositivos vinculados associados a uma pessoa anônima.

![](assets/link2.png)

>[!NOTE]
>
>Nem o [!DNL Adobe Experience Cloud Device Co-op] ou o [!DNL Device Graph] O recebe informações de autenticação reais ou informações de identificação pessoal (PII) nesses dados. Membros da [!DNL Experience Cloud Device Co-op], transmitem IDs de consumidor exclusivas, com hash criptográfico, para o Gráfico de dispositivos. A ID do consumidor representa um usuário autenticado no gráfico e protege a privacidade do consumidor.

## Vínculos probabilísticos {#section-5f5aa755da984f9d851f7cb380262998}

Links probabilísticos conectam um dispositivo a uma pessoa de forma algorítmica, com base em características e metadados como:

* Comportamento de navegação
* Endereços IP
* Sistemas operacionais
* Identificadores IDFA e GAID

Vamos dar uma olhada em como o link probabilístico funciona. Neste exemplo, a Pessoa A navega até um site de notícias em seu tablet e, posteriormente, a partir de um computador desktop. Durante a navegação, a Pessoa A não faz logon no site de notícias. Durante cada visita separada, o tablet e o desktop compartilham o mesmo endereço IP.

![](assets/link3.png)

Com base nessas informações, a [!DNL Device Graph] O avalia os padrões de compartilhamento de endereços IP entre os dois dispositivos e os vincula se os resultados sugerirem que eles pertencem à Pessoa A. O resultado final é a hierarquia de identidade derivada dos cálculos de probabilidade algorítmica.

![](assets/link4.png)

Neste exemplo, o Gráfico de dispositivos vinculou ambos os dispositivos depois de serem usados para acessar o mesmo site de notícias. Porém, os dispositivos não precisam ser vistos no mesmo site para serem vinculados. Para ilustrar este ponto, digamos que cada dispositivo neste exemplo visite sites completamente diferentes. A variável [!DNL Device Graph] O algoritmo ainda pode fazer um link probabilístico com base em seu endereço IP compartilhado e em uma análise de outros dados. Esse processo é o que ajuda a tornar a vinculação probabilística tão poderosa para os membros da [!DNL Experience Cloud] Device Co-op.

## Ambos os tipos de dados fornecem valor {#section-43d22d8c10634edcb261e7bda6fdf323}

Dados determinísticos e probabilísticos complementam-se. Por outro lado, um gráfico de dispositivos que inclui apenas dados determinísticos fornece uma visualização limitada da identidade de uma pessoa. Sem autenticação, um gráfico de dispositivos não pode informar sobre outros dispositivos e pessoas que navegam no seu site. Dados probabilísticos podem fazer essas conexões e ajudá-lo a alcançar dispositivos não autenticados, pessoas e residências.

No entanto, dados determinísticos também são importantes. Pode, por exemplo, melhorar a tomada de decisões probabilísticas, eliminando ligações falsas geradas em locais onde os sinais probabilísticos são abundantes e se sobrepõem (por exemplo, cafés, bibliotecas, aeroportos, etc.).

Com ambos os tipos de dados, o Gráfico de dispositivos fornece uma imagem mais abrangente da identidade de uma pessoa do que com qualquer um dos tipos isoladamente.

![](assets/link5.png)
