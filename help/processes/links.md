---
description: Como o Gráfico de dispositivos analisa dados determinísticos e probabilísticos para criar um mapa que vincula dispositivos.
seo-description: Como o Gráfico de dispositivos analisa dados determinísticos e probabilísticos para criar um mapa que vincula dispositivos.
seo-title: Links determinísticos e probabilísticos
title: Links determinísticos e probabilísticos
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '866'
ht-degree: 0%

---


# Links determinísticos e probabilísticos{#deterministic-and-probabilistic-links}

Como o Gráfico de dispositivos analisa dados determinísticos e probabilísticos para criar um mapa que vincula dispositivos.

No [!DNL Device Graph], os processos internos criam uma hierarquia de identidade que mapeia dispositivos e os conecta a pessoas individuais anônimas. A saída do gráfico inclui links entre dispositivos que podem ser usados para definição de metas juntamente com dados expostos em soluções Experience Cloud selecionadas. As soluções de Adobe que funcionam com [!DNL Device Graph] dados incluem Analytics, Audience Manager, Media Otimizer e Público alvo.

A [!DNL Device Graph] analisa dados determinísticos e probabilísticos para criar um mapa que vincula dispositivos. Os dados determinísticos vinculam os dispositivos com base em informações de logon em hash. Dados probabilísticos vinculam dispositivos com base em informações como endereços IP e outros metadados. O [!DNL Device Graph] associa os grupos de dispositivos vinculados a uma pessoa individual anônima Essas conexões permitem que profissionais de marketing digital cheguem às pessoas em vez de dispositivos. No [!DNL Device Graph]caso, o proprietário de um dispositivo é a representação anônima de uma pessoa real. Ambos os links determinísticos e probabilísticos ajudam a construir uma estrutura de identidade do usuário.

>[!NOTE]
>
>No Adobe Experience Cloud Device Co-op, termos como *dispositivo*, *pessoa* e *identidade* têm significados específicos. Por exemplo, o *dispositivo* pode se referir ao hardware físico, como um telefone ou tablet e os aplicativos que são executados nesse hardware. Consulte o [glossário](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) para ver as definições.

## O que são links? {#section-2df4c6f01eba49369993146df0661f13}

Quando falamos de links, é importante ter em mente o que eles realmente são no contexto do Gráfico de [!DNL Experience Cloud] dispositivos. Neste contexto, os links não são conexões físicas entre dispositivos. Em vez disso, um link é como o Gráfico de dispositivos associa diferentes dispositivos à mesma pessoa desconhecida. Por exemplo, digamos que temos um celular e um navegador de desktop. O telefone e o navegador podem ser considerados &quot;vinculados&quot; assim que o Gráfico de dispositivos determinar que esses dispositivos são usados pela mesma pessoa desconhecida. Como você lerá abaixo, o Gráfico de dispositivos cria identidades com links determinísticos e probabilísticos. E, no Gráfico de dispositivos, o proprietário de um dispositivo é a representação anônima de uma pessoa real.

## Links determinísticos {#section-33d41e828a674b398e36fe63da20ac09}

Links determinísticos associam um dispositivo a uma pessoa com base em um evento de autenticação (por exemplo, uma ação de logon em um site a partir de um dispositivo). Esta ação cria um identificador anônimo conhecido como uma ID do consumidor. Vejamos como os links determinísticos funcionam. Neste exemplo, a Pessoa A faz logon em um site de notícias por meio de um aplicativo em seu dispositivo móvel. Mais tarde nesse dia, a Pessoa A faz login novamente, mas desta vez através de um navegador em seu laptop.

![](assets/link1.png)

Com base nas informações de logon, o Gráfico de dispositivos:

* Sabe que a Pessoa A foi autenticada no site de notícias com uma combinação de telefone/aplicativo móvel e laptop/navegador.
* Vincula esses dispositivos à Pessoa A.
* Cria uma identidade com base em dispositivos vinculados associados a uma pessoa anônima.

![](assets/link2.png)

>[!NOTE]
>
>Nem o usuário [!DNL Adobe Experience Cloud Device Co-op] ou o [!DNL Device Graph] recebe informações de autenticação reais ou informações de identificação pessoal (PII) nesses dados. Membros do [!DNL Experience Cloud Device Co-op], transmitam IDs de consumidor exclusivas e criptografadas com hash ao Gráfico de dispositivos. A ID do consumidor representa um usuário autenticado no gráfico e protege a privacidade do consumidor.

## Links probabilísticos {#section-5f5aa755da984f9d851f7cb380262998}

Links probabilísticos conectam um dispositivo a uma pessoa de forma algorítmica, com base em características e metadados como:

* Comportamento de navegação
* Endereços IP
* Sistemas operacionais
* Identificadores IDFA e GAID

Vejamos como os links probabilísticos funcionam. Neste exemplo, a Pessoa A navega até um site de notícias em seu tablet e depois de um computador desktop. Durante a navegação, a Pessoa A não faz logon no site de notícias. Durante cada visita separada, o tablet e a área de trabalho compartilham o mesmo endereço IP.

![](assets/link3.png)

Com base nessas informações, o [!DNL Device Graph] avalia os padrões de compartilhamento de endereços IP entre ambos os dispositivos e os vincula se os resultados sugerirem que eles pertencem à Pessoa A. O resultado final é a hierarquia de identidade derivada de cálculos de probabilidade algorítmicos.

![](assets/link4.png)

Neste exemplo, o Gráfico de dispositivos vinculou ambos os dispositivos depois que foram usados para acessar o mesmo site de notícias. Mas os dispositivos não precisam ser vistos no mesmo site para serem vinculados. Para ilustrar este ponto, digamos que cada dispositivo neste exemplo visite sites completamente diferentes. O [!DNL Device Graph] algoritmo ainda pode criar um link probabilístico com base em seu endereço IP compartilhado e em uma análise de outros dados. Esse processo é o que ajuda a tornar os links probabilísticos tão poderosos para os membros do [!DNL Experience Cloud] Device Co-op.

## Ambos os tipos de dados fornecem valor {#section-43d22d8c10634edcb261e7bda6fdf323}

Os dados determinísticos e probabilísticos complementam-se uns aos outros. Por outro lado, um gráfico de dispositivos que inclui apenas dados determinísticos fornece uma visualização limitada da identidade de uma pessoa. Sem autenticação, um gráfico de dispositivo não pode informá-lo sobre outros dispositivos e pessoas que navegam em seu site. Dados probabilísticos podem fazer essas conexões e ajudar você a alcançar dispositivos não autenticados, pessoas e residências.

No entanto, os dados determinísticos também são importantes. Pode, por exemplo, melhorar a tomada de decisões probabilísticas através da remoção de ligações falsas geradas em locais onde os sinais probabilísticos são abundantes e sobrepostos (por exemplo, cafeterias, bibliotecas, aeroportos, etc.).

Com ambos os tipos de dados, o Gráfico de dispositivos fornece uma imagem mais abrangente da identidade de uma pessoa do que com qualquer um dos tipos individualmente.

![](assets/link5.png)

