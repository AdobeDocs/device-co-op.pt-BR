---
description: A métrica de Pessoas é a contagem de pessoas (ou de grupos de dispositivos) com base no Gráfico de dispositivos da Adobe. Você pode aplicar a métrica de Pessoas para identificar os visitantes em seus dispositivos na Analysis Workspace.
seo-description: A métrica de Pessoas é a contagem de pessoas (ou de grupos de dispositivos) com base no Gráfico de dispositivos da Adobe. Você pode aplicar a métrica de Pessoas para identificar os visitantes em seus dispositivos na Analysis Workspace.
seo-title: Métrica de pessoas
title: Métrica de pessoas
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Métrica de pessoas{#people-metric}

A métrica de Pessoas é a contagem de pessoas (ou de grupos de dispositivos) com base no Gráfico de dispositivos da Adobe. Você pode aplicar a métrica de Pessoas para identificar os visitantes em seus dispositivos na Analysis Workspace.

## People Metric Prerequisites and Considerations {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Pré-requisito ou Consideração </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Dispositivo Cooperação </p> </td> 
   <td colname="col2"> <p> To use the People metric, become a member of the <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. A cooperativa identifica vários dispositivos de uma pessoa (ou Experience Cloud IDs). O Analytics utiliza estas informações para calcular estatisticamente o número de pessoas que interagem com uma marca. A métrica tem uma precisão de até 5%. </p> <p><b>Regiões</b>: o Device Co-op está disponível atualmente apenas nos EUA e no Canadá. Portanto, ao avaliar a métrica de Pessoas, você deve aplicar um segmento à sua análise que filtra os dados apenas para os EUA e Canadá. </p> <p>A cada semana, o Gráfico de dispositivos calcula uma nova versão da cooperativa e a publica para uso. Às terças-feiras, o sistema coleta os dados mais recentes e publica uma versão atualizada do gráfico. As soluções da Experience Cloud usam a versão mais recente do gráfico. Especificamente para o Analytics, as alterações são lidas na quarta-feira e o processamento das alterações normalmente leva de 1 a 2 dias úteis. </p> <p> <p>Importante:  Quando o gráfico é atualizado semanalmente, pode afetar historicamente a métrica de Pessoas. Em outras palavras, as contagens históricas de Pessoas podem mudar ao longo do tempo à medida que o gráfico aprende e é atualizado. Por exemplo, se você executar um relatório hoje que conta Pessoas no mês passado e, em seguida, executar o mesmo relatório em uma semana após a atualização do gráfico, a contagem histórica de Pessoas poderá mudar ligeiramente. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Permissões de métrica </td> 
   <td colname="col2"> <p>Você pode usar a métrica de Pessoas somente se tiver acesso a ela. Os administradores podem<a href="https://marketing.adobe.com/resources/help/en_US/reference/groups-metrics.html" format="html" scope="external"> personalizar as permissões</a> de métricas nas Ferramentas administrativas. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Mapeamento para organização IMS </td> 
   <td colname="col2"> <p>A métrica de Pessoas será ativada para todos os conjuntos de relatórios que estão <a href="https://marketing.adobe.com/resources/help/en_US/mcloud/map-report-suite.html" format="html" scope="external"> mapeados para um IMSORG</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ferramentas/projetos de análise </p> </td> 
   <td colname="col2"> <p>Use a métrica de Pessoas no <span class="wintitle">Analysis Workspace</span>, na <span class="wintitle">Análise ad hoc</span>, no <span class="wintitle">Construtor de relatórios</span> e através da API. Você pode usá-lo em qualquer lugar que usaria a métrica de Visitantes exclusivos, incluindo as Métricas calculadas. </p> <p>Por exemplo, crie uma métrica de receita por pessoa para substituir uma métrica de receita por visitante exclusivo. </p> <p>Um <a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html" format="html" scope="external">modelo de projeto de Pessoas</a> está disponível para começar a usar a métrica de Pessoas na Analysis Workspace. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ativar as regras de bots </p> </td> 
   <td colname="col2"> <p>A Adobe recomenda ativar as <a href="https://marketing.adobe.com/resources/help/en_US/reference/bot_rules.html" format="html" scope="external">Regras de bot</a>, especialmente ao utilizar a métrica de Pessoas. </p> <p>Quando um bot rastreia o seu site, ele aumenta artificialmente sua contagem de Visitantes únicos. Remover o tráfego de bot do seu conjunto de relatórios permite uma medição mais precisa da atividade em suas propriedades digitais, em termos de Visitantes únicos e Pessoas. </p> <p>Para fazer isso, navegue para <span class="uicontrol">Analytics</span> &gt; <span class="uicontrol">Admin</span> &gt; <span class="uicontrol">Conjuntos de relatórios</span>. Selecione o conjunto de relatórios correto e vá para <span class="uicontrol">Editar configurações</span> &gt; <span class="uicontrol">Geral</span> &gt; <span class="uicontrol">Regras de bot</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Considerações de segmentação </p> </td> 
   <td colname="col2"> <p> Quando você usa segmentos com a métrica de Pessoas, o relatório da métrica pode ser significativamente menor do que o esperado. </p> <p>Consulte <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local">Usando a métrica de Pessoas com segmentos</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## O que é a métrica de pessoas? {#section-89e2b8f5e80f480391449fc8d1117a6a}

A métrica de Pessoas é uma métrica de relatório do Analytics que ajuda a atribuir dispositivos às pessoas. Ela fornece uma visão de marketing baseada em pessoas, permitindo medir a atividade dos visitantes em todos os seus dispositivos. Pense nisso como uma versão desduplicada de Visitantes únicos; você pode usar a métrica de Pessoas para análises em que utilizou a métrica Visitantes únicos anteriormente.

**Dispositivos são pessoas**

Antes da métrica de Pessoas ser disponibilizada, uma pessoa (por exemplo) podia visitar o seu site e se envolver com uma campanha ou marca em três dispositivos diferentes e fazer uma compra, mesmo em poucos minutos. Dependendo da sua implementação, o Analytics podia relatar cada dispositivo como um visitante único e atribuir $10 a três dispositivos em uma compra de $30.

A métrica de Pessoas permite atribuir com precisão a compra de $30 a uma pessoa:

![](assets/people-centric-results.png)

**Precisão aumentada em relatórios**

A métrica de Pessoas permite considerar vários dispositivos como uma única entidade. O seguinte projeto da Analysis Workspace mostra comparações do aumento de precisão entre os relatórios de Visitantes únicos e os relatórios de Pessoas:

![](assets/people_report.png)

Compare Pessoas e Visitantes únicos lado a lado:

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
   <td colname="col1"> <p>Pessoas </p> </td> 
   <td colname="col2"> <p>A métrica de Pessoas baseia-se na ideia de que os consumidores interagem com a sua marca usando vários dispositivos. Quanto mais você divide ou segmenta os dados, menor será a chance de que uma mesma pessoa utilize vários dispositivos dentro dessa fatia de dados. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visitantes únicos </p> </td> 
   <td colname="col2"> <p>Por exemplo, quanto mais você divide os seus dados por data ou hora, menor será a diferença entre as métricas de Pessoas e Visitantes únicos. Se você quiser ter uma boa compreensão do impacto geral do Device Co-op, a Adobe recomenda usar um intervalo de datas dos últimos 90 dias </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Compactação </p> </td> 
   <td colname="col2"> <p>Usando uma simples métrica calculada você pode ver o quão menor a métrica de Pessoas é como uma porcentagem de Visitantes únicos. Clique no ícone de informações ao lado de “Compressão” na tabela acima para ver como criar essa métrica. </p> <p>A métrica de Pessoas pode ser usados em outras métricas calculadas no lugar de Visitantes únicos. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Como a métrica de Pessoas é calculada? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

A imagem a seguir mostra como a métrica de Pessoas é calculada e como ela pode se reduzir ao longo do tempo para o mesmo intervalo de datas de um relatório no passado.

![](assets/people-calculations.png)

Neste exemplo, suponha que há um conjunto fixo de visitantes. Se você executar um relatório para um período fixo no passado, ele exibirá um conjunto fixo de visitantes. Se o Gráfico de dispositivos exibir os dados mostrados no gráfico à esquerda na semana 1, o resultado seria 90 pessoas. Uma semana depois, após a próxima execução do Gráfico de dispositivos, novas informações são consideradas. Se você executar o mesmo relatório da semana anterior, o número de pessoas diminuirá para 84. O histórico mudou porque o Gráfico de dispositivos forneceu novas informações sobre quais dispositivos devem ser agrupados.

## Usando a métrica de Pessoas com segmentos {#section-d03525420dbe48379fd95b230ef05885}

Quando você usa segmentos com a métrica de Pessoas, os resultados da métrica podem ser significativamente menores do que o esperado. Esse problema ocorre porque não há um *`person`* container. A segmentação utiliza o contêiner Visitante, que é o contêiner de mais alto nível na definição e se baseia no dispositivo, e não na pessoa.

Esse problema ocorre principalmente ao empilhar segmentos com a métrica de Pessoas.

![](assets/people-stacked-segments.png)

O empilhamento de segmentos cria um novo segmento que representa a combinação dos segmentos. O empilhamento de segmentos ocorre sempre que você:

* Coloca um segmento em cima de outro na Analysis Workspace. (Eles são automaticamente associados usando o operador *`And`* operador.)
* Apply a single segment that contains the *`And`* operator.
* Aplica um segmento, em nível de projeto e em nível de tabela.
* Usa um conjunto de relatório virtual com outro segmento.

Por exemplo, suponha que você empilhe os seguintes segmentos sobre a métrica de Pessoas:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Only the number of people who qualify in both segments *`using a single device`* are counted. (A métrica de Pessoas não exibe o número de pessoas qualificadas em todos os dispositivos.)

Além disso, usar o operador *`Or`* não é recomendado nesta situação. Fazer isso produziria uma contagem de pessoas que visualizaram um ou o outro, sem permitir a contagem de pessoas qualificadas para ambos os segmentos.

Consulte [Criação de segmentos](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_build.html) na ajuda de segmentação para obter mais informações.

## Tipos de dispositivo {#section-8ab378c84ff34574b9c20fecb3848a86}

O Device Co-op e a métrica de Pessoas funcionam melhor no Adobe Analytics quando seu conjunto de relatório contém dados de vários tipos de dispositivos. Por exemplo, a combinação de dados da web e de aplicativos no mesmo conjunto de relatório torna a métrica de Pessoas mais potente e eficaz. Quanto maior o cruzamento de dispositivos em seus dados, maior será a chance de que vários visitantes únicos sejam agrupados como uma única pessoa.

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

O Device Co-op exige que suas propriedades digitais sejam instrumentadas usando o serviço da Experience Cloud ID (MCID). Se os dados no conjunto de relatório contiverem um número significativo de visitantes sem uma MCID, a eficácia do Device Co-op e da métrica de Pessoas será reduzida.

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, create a [project](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/t_freeform_project.html), then drag the **[!UICONTROL People]** metric to the project table:

![](assets/people-metric.png)

