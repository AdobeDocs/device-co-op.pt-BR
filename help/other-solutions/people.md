---
description: A métrica Pessoas é a contagem de pessoas (ou grupos de dispositivos) com base no Gráfico de dispositivos Adobe. Você pode aplicar a métrica Pessoas para identificar visitantes em seus dispositivos na Analysis Workspace.
seo-description: The People metric is the count of people (or groups of devices) based on Adobe's Device Graph. You can apply the People metric to identify visitors across their devices in Analysis Workspace.
seo-title: People metric
title: Métrica de pessoas
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
exl-id: e2e70461-19ab-49db-bd65-a3eb26c2d4a8
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '1374'
ht-degree: 4%

---

# Métrica de pessoas{#people-metric}

A métrica Pessoas é a contagem de pessoas (ou grupos de dispositivos) com base no Gráfico de dispositivos Adobe. Você pode aplicar a métrica Pessoas para identificar visitantes em seus dispositivos na Analysis Workspace.

## Pré-requisitos e considerações da métrica de pessoas {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Pré-requisito ou consideração </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Device Co-op </p> </td> 
   <td colname="col2"> <p> Para usar a métrica Pessoas, torne-se membro da <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Device Co-op da Adobe Experience Cloud</a>. A cooperação identifica os vários dispositivos (ou IDs de Experience Cloud) de uma pessoa. O Analytics aproveita essas informações para obter estatisticamente o número de pessoas que interagem com uma marca. A métrica tem uma precisão de até 5%. </p> <p><b>Regiões</b>: o Device Co-op está disponível somente nos EUA e no Canadá. Portanto, ao avaliar a métrica Pessoas, você deve aplicar um segmento à análise que filtra seus dados somente para os EUA e o Canadá. </p> <p>A cada semana, o Gráfico de dispositivos calcula uma nova versão da cooperação e a publica para uso. Às terças-feiras, o sistema coleta os dados mais recentes e publica uma versão atualizada do gráfico. As soluções Experience Cloud usam a versão mais recente do gráfico. Especificamente para o Analytics, as alterações são lidas às quartas-feiras e o processamento das alterações normalmente leva entre 1 e 2 dias úteis. </p> <p> <p>Importante: quando o gráfico é atualizado semanalmente, ele pode afetar a métrica Pessoas historicamente. Em outras palavras, as contagens históricas de Pessoas podem mudar com o tempo, à medida que o gráfico aprende e é atualizado. Por exemplo, se você executar um relatório hoje que conta Pessoas no mês passado e, em seguida, executar o mesmo relatório em uma semana após a atualização do gráfico, a contagem histórica de Pessoas poderá ser ligeiramente alterada. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Permissões de métrica </td> 
   <td colname="col2"> <p>Você só poderá usar a métrica Pessoas se tiver acesso a ela. Os administradores podem<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> personalizar permissões de métricas</a> nas Ferramentas administrativas. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Mapeamento para a organização IMS </td> 
   <td colname="col2"> <p>A Métrica de pessoas será ativada para todos os conjuntos de relatórios <a href="https://docs.adobe.com/content/help/pt-BR/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"> mapeado para um IMSORG</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ferramentas/Projetos de Análise </p> </td> 
   <td colname="col2"> <p>Usar a métrica Pessoas no <span class="wintitle"> Analysis Workspace</span>, <span class="wintitle"> Ad Hoc Analysis</span>, <span class="wintitle"> Report Builder</span>e por meio da API. Você pode usá-la onde quiser usar a métrica Visitantes únicos, incluindo Métricas calculadas. </p> <p>Por exemplo, crie uma métrica receita por pessoa para substituir uma métrica receita por visitante único. </p> <p>A <a href="https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"> Modelo do projeto Pessoas</a> O está disponível para começar a usar a métrica Pessoas no Analysis Workspace. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ativar regras de bot </p> </td> 
   <td colname="col2"> <p>O Adobe recomenda que você ative <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"> Regras de bot</a>, especialmente ao usar a métrica Pessoas. </p> <p>Quando um bot rastreia o site, ele aumenta artificialmente a contagem de Visitantes únicos. A remoção do tráfego de bot do conjunto de relatórios fornece uma medida mais precisa da atividade nas propriedades digitais, tanto em termos de Visitantes únicos quanto de Pessoas. </p> <p>Para fazer isso, navegue até <span class="uicontrol"> Analytics</span> &gt; <span class="uicontrol"> Admin</span> &gt; <span class="uicontrol"> Conjuntos de relatórios</span>. Selecione o conjunto de relatórios correto e vá para <span class="uicontrol"> Editar configurações</span> &gt; <span class="uicontrol"> Geral</span> &gt; <span class="uicontrol"> Regras de bot</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Considerações de segmentação </p> </td> 
   <td colname="col2"> <p> Ao usar segmentos com a métrica Pessoas, os relatórios de métrica podem ser drasticamente inferiores ao esperado. </p> <p>Consulte <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> Uso da métrica de pessoas com segmentos</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Qual é a métrica de pessoas? {#section-89e2b8f5e80f480391449fc8d1117a6a}

A métrica Pessoas é uma métrica de relatórios do Analytics que ajuda a atribuir dispositivos a pessoas. Ele fornece uma visualização de marketing com base em pessoas, permitindo medir a atividade dos visitantes em todos os dispositivos. Pense nisso como uma versão deduplicada de Visitantes únicos e você pode usar a métrica Pessoas para análise em que usou Visitantes únicos anteriormente.

**Dispositivos São Pessoas**

Antes da métrica de Pessoas ficar disponível, uma pessoa (por exemplo) pode visitar seu site e se envolver com uma campanha ou marca em três dispositivos diferentes e fazer uma compra, mesmo que isso ocorra em minutos. Dependendo da sua implementação, o Analytics pode relatar cada dispositivo como um visitante único e atribuir US$ 10 a três dispositivos em uma compra de US$ 30.

A métrica Pessoas permite atribuir com precisão essa compra de US$ 30 a uma pessoa:

![](assets/people-centric-results.png)

**Maior precisão nos relatórios**

A métrica Pessoas permite que você considere vários dispositivos como uma única entidade. O seguinte projeto do Analysis Workspace mostra comparações de maior precisão entre os relatórios de Visitantes únicos e de Pessoas:

![](assets/people_report.png)

Comparar pessoas e visitantes únicos lado a lado:

![](assets/people-report.png)

**Definições**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Item </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>People </p> </td> 
   <td colname="col2"> <p>A métrica Pessoas é baseada na ideia de que os consumidores interagem com sua marca usando vários dispositivos. Quanto mais você divide ou segmenta seus dados, menor a chance de a mesma pessoa usar vários dispositivos dentro dessa fatia de dados. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visitantes únicos </p> </td> 
   <td colname="col2"> <p>Por exemplo, quanto mais você cortar seus dados por data ou hora, menor será a diferença entre Pessoas e Visitantes únicos. Se você quiser ter uma boa compreensão do impacto geral do Device Co-op, a Adobe recomenda usar um intervalo de datas dos últimos 90 dias </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Compactação </p> </td> 
   <td colname="col2"> <p>Usando uma métrica calculada simples, você pode ver o quão menor a métrica Pessoas é como uma porcentagem de Visitantes únicos. Clique no ícone de informações ao lado de "Compactação" na tabela acima para ver como criar essa métrica. </p> <p>As pessoas podem ser usadas em outras métricas calculadas no lugar de Visitantes únicos. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Como é calculada a métrica de pessoas? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

A imagem a seguir mostra como a métrica Pessoas é calculada e como ela pode diminuir com o tempo para o mesmo intervalo de datas do relatório no passado.

![](assets/people-calculations.png)

Neste exemplo, suponha que haja um conjunto fixo de visitantes. Se você executar um relatório para um período fixo no passado, ele exibirá um conjunto fixo de visitantes. Se o Gráfico de dispositivos gerar os dados mostrados no gráfico à esquerda na semana 1, isso resultará em 90 pessoas. Uma semana depois, após a próxima execução do Gráfico de dispositivos, novas informações são consideradas. Se você executar o mesmo relatório que fez uma semana atrás, o número de pessoas baixou para 84. O histórico foi alterado porque o Gráfico de dispositivos forneceu novas informações sobre quais dispositivos devem ser agrupados.

## Uso da métrica de pessoas com segmentos {#section-d03525420dbe48379fd95b230ef05885}

Ao usar segmentos com a métrica Pessoas, os resultados da métrica podem ser drasticamente inferiores ao esperado. Esse problema ocorre porque, na segmentação, não há *`person`* recipiente. A segmentação usa o contêiner Visitante, que é o contêiner de nível mais alto na definição e se baseia no dispositivo, não na pessoa.

Esse problema ocorre principalmente ao empilhar segmentos com a métrica Pessoas.

![](assets/people-stacked-segments.png)

O empilhamento de segmentos cria um novo segmento que representa a combinação dos segmentos. O empilhamento de segmentos ocorre sempre que você:

* Coloque um segmento sobre outro segmento no Analysis Workspace. (Elas são unidas automaticamente usando o *`And`* operador.)
* Aplique um único segmento que contenha o *`And`* operador.
* Aplique um segmento no nível do projeto e no nível da tabela.
* Use um conjunto de relatórios virtual com outro segmento.

Por exemplo, suponha que você empilhe os seguintes segmentos na métrica Pessoas:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Somente o número de pessoas qualificadas em ambos os segmentos *`using a single device`* são contados. (A métrica Pessoas não exibe o número de pessoas qualificadas em dispositivos.)

Além disso, usando o *`Or`* operador não é recomendado nessa situação. Fazer isso produziria uma contagem de pessoas que viram um ou outro, sem como contar quantas pessoas se qualificam para ambos os segmentos.

Consulte [Construir segmentos](https://docs.adobe.com/content/help/pt-BR/analytics/components/segmentation/segmentation-workflow/seg-build.html) na ajuda Segmentação para obter mais informações.

## Tipos de dispositivo {#section-8ab378c84ff34574b9c20fecb3848a86}

As métricas Device Co-op e People funcionam melhor no Adobe Analytics quando seu conjunto de relatórios contém dados de vários tipos de dispositivos. Por exemplo, combinar dados da Web e do aplicativo no mesmo conjunto de relatórios torna a métrica Pessoas mais eficiente. Quanto mais dispositivos se cruzarem nos dados, maior a chance de vários visitantes únicos serem agrupados como uma única pessoa.

![](assets/people-device-types.png)

## Cobertura do serviço de ID do Experience Cloud {#section-bbf0098cac2e467289e7a644a1dea05c}

O Device Co-op requer que suas propriedades digitais sejam instrumentadas usando o serviço Experience Cloud ID (MCID). Se os dados em seu conjunto de relatórios contiverem um número significativo de visitantes sem um MCID, a eficácia da Device Co-op e da métrica de Pessoas será reduzida.

<!--
mcdc-people-metric-apply.xml
-->

No Analysis Workspace, crie uma [projeto](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html), em seguida, arraste o **[!UICONTROL People]** para a tabela projeto:

![](assets/people-metric.png)
