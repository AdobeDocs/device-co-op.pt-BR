---
description: A métrica de Pessoas é a contagem de pessoas (ou grupos de dispositivos) com base no Gráfico de dispositivos Adobe. Você pode aplicar a métrica de Pessoas para identificar visitantes em seus dispositivos no Analysis Workspace.
seo-description: A métrica de Pessoas é a contagem de pessoas (ou grupos de dispositivos) com base no Gráfico de dispositivos Adobe. Você pode aplicar a métrica de Pessoas para identificar visitantes em seus dispositivos no Analysis Workspace.
seo-title: Métrica de pessoas
title: Métrica de pessoas
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c
workflow-type: tm+mt
source-wordcount: '1408'
ht-degree: 3%

---


# Métrica de pessoas{#people-metric}

A métrica de Pessoas é a contagem de pessoas (ou grupos de dispositivos) com base no Gráfico de dispositivos Adobe. Você pode aplicar a métrica de Pessoas para identificar visitantes em seus dispositivos no Analysis Workspace.

## Pré-requisitos e considerações da métrica de Pessoas {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Pré-requisito ou Consideração </th> 
   <th colname="col2" class="entry"> Descrição </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Device Co-op </p> </td> 
   <td colname="col2"> <p> Para usar a métrica de Pessoas, torne-se um membro do <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. A cooperativa identifica vários dispositivos (ou IDs de Experience Cloud) de uma pessoa. O Analytics utiliza essas informações para calcular estatisticamente o número de pessoas que interagem com uma marca. A métrica tem uma precisão de até 5%. </p> <p><b>Regiões</b>: O Device Co-op está disponível atualmente apenas nos EUA e Canadá. Portanto, ao avaliar a métrica de Pessoas, você deve aplicar um segmento à sua análise que filtros seus dados somente para os EUA e Canadá. </p> <p>Toda semana, o Gráfico de dispositivos calcula uma nova versão da cooperativa e a publica para uso. Às terças-feiras, o sistema coleta os dados mais recentes e publica uma versão atualizada do gráfico. As soluções de Experience Cloud usam a versão mais recente do gráfico. Especificamente para o Analytics, as alterações são lidas na quarta-feira e o processamento das alterações normalmente leva de 1 a 2 dias úteis. </p> <p> <p>Importante:  Quando o gráfico é atualizado semanalmente, pode afetar historicamente a métrica de Pessoas. Em outras palavras, as contagens históricas de Pessoas podem mudar ao longo do tempo à medida que o gráfico aprende e é atualizado. Por exemplo, se você executar um relatório hoje que conta Pessoas no mês passado e, em seguida, executar o mesmo relatório em uma semana após a atualização do gráfico, a contagem histórica de Pessoas poderá mudar ligeiramente. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Permissões de métrica </td> 
   <td colname="col2"> <p>Você pode usar a métrica de Pessoas somente se tiver acesso a ela. Os administradores podem<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> personalizar as permissões</a> de métricas nas Ferramentas administrativas. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Mapeamento para organização IMS </td> 
   <td colname="col2"> <p>A métrica de Pessoas será ativada para todos os conjuntos de relatórios que estão <a href="https://docs.adobe.com/content/help/pt-BR/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"> mapeados para um IMSORG</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Projetos/ferramentas de análise </p> </td> 
   <td colname="col2"> <p>Use a métrica de Pessoas no <span class="wintitle"> Analysis Workspace</span>, <span class="wintitle"> Ad Hoc Analysis</span>, <span class="wintitle"> Report Builder</span>e por meio da API. Você pode usá-la em qualquer lugar que usasse a métrica Visitantes únicos, incluindo Métricas calculadas. </p> <p>Por exemplo, crie uma métrica de receita por pessoa para substituir uma métrica de receita por visitante exclusivo. </p> <p>Um modelo <a href="https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"> de projeto de</a> Pessoas está disponível para começar a usar a métrica de Pessoas no Analysis Workspace. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ativar regras de bots </p> </td> 
   <td colname="col2"> <p>O Adobe recomenda ativar as Regras <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"> do</a>robô, especialmente ao usar a métrica de Pessoas. </p> <p>Quando um bot rastreia seu site, ele aumenta artificialmente sua contagem de Visitantes únicos. A remoção do tráfego de robô de seu conjunto de relatórios fornece uma medição mais precisa da atividade em suas propriedades digitais, tanto em termos de Visitantes únicos quanto de Pessoas. </p> <p>Para fazer isso, navegue até <span class="uicontrol"> Analytics</span> &gt; <span class="uicontrol"> Administrador</span> &gt; <span class="uicontrol"> Report Suites</span>. Select the correct report suite, and then go to <span class="uicontrol"> Edit Settings</span> &gt; <span class="uicontrol"> General</span> &gt; <span class="uicontrol"> Bot Rules</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Considerações de segmentação </p> </td> 
   <td colname="col2"> <p> Quando você usa segmentos com a métrica de Pessoas, o relatórios da métrica pode ser consideravelmente menor do que o esperado. </p> <p>Consulte <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> Uso da métrica de Pessoas com segmentos</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## O que é a métrica de Pessoas? {#section-89e2b8f5e80f480391449fc8d1117a6a}

A métrica de Pessoas é uma métrica de relatórios do Analytics que ajuda a atribuir dispositivos a pessoas. Ele oferece uma visualização de marketing baseada em pessoas, permitindo que você meça a atividade de visitantes em todos os seus dispositivos. Considere-o como uma versão deduplicada de Visitantes únicos, e você pode usar a métrica de Pessoas para análises em que usou Visitantes únicos anteriormente.

**Dispositivos são pessoas**

Antes de a métrica de Pessoas ser disponibilizada, uma pessoa (por exemplo) pode visitar seu site e se envolver com uma campanha ou marca em três dispositivos diferentes e fazer uma compra, mesmo em minutos. Dependendo da sua implementação, o Analytics pode relatar cada dispositivo como um visitante exclusivo e atribuir $10 a três dispositivos em uma compra de $30.

A métrica de Pessoas permite atribuir com precisão a compra de $30 a uma pessoa:

![](assets/people-centric-results.png)

**Precisão aumentada em relatórios**

A métrica de Pessoas permite que você considere vários dispositivos como uma única entidade. O projeto do Analysis Workspace a seguir mostra comparações de precisão aumentadas entre o relatórios Visitantes únicos e o relatórios de pessoas:

![](assets/people_report.png)

Comparar pessoas e Visitantes únicos lado a lado:

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
   <td colname="col2"> <p>A métrica de Pessoas é baseada na ideia de que os consumidores interagem com a sua marca usando vários dispositivos. Quanto mais você divide ou segmenta seus dados, menor será a chance de a mesma pessoa usar vários dispositivos dentro dessa fatia de dados. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visitantes únicos </p> </td> 
   <td colname="col2"> <p>Por exemplo, quanto mais você divide seus dados por data ou hora, menor será a diferença entre Pessoas e visitantes únicos. Se você quiser entender melhor o impacto geral do Device Co-op, o Adobe recomenda usar um intervalo de datas dos últimos 90 dias </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Compactação </p> </td> 
   <td colname="col2"> <p>Usando uma métrica calculada simples, você pode ver o quão menor a métrica de Pessoas é como uma porcentagem de Visitantes únicos. Clique no ícone de informações ao lado de "Compactação" na tabela acima para ver como criar essa métrica. </p> <p>As pessoas podem ser usadas em outras métricas calculadas no lugar de Visitantes únicos. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Como a métrica de Pessoas é calculada? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

A imagem a seguir mostra como a métrica de Pessoas é calculada e como ela pode diminuir ao longo do tempo para o mesmo intervalo de datas do relatório no passado.

![](assets/people-calculations.png)

Neste exemplo, suponha que haja um conjunto fixo de visitantes. Se você executar um relatório para um período fixo no passado, ele exibirá um conjunto fixo de visitantes. Se o Gráfico de dispositivos exibir os dados mostrados no gráfico esquerdo na semana 1, isso resultará em 90 pessoas. Uma semana depois, após a próxima execução do Gráfico de dispositivos, novas informações serão levadas em conta. Se você executar o mesmo relatório que fez há uma semana, o número de pessoas diminuiu para 84. O histórico mudou porque o Gráfico de dispositivos forneceu novas informações sobre quais dispositivos devem ser agrupados.

## Uso da métrica de Pessoas com segmentos {#section-d03525420dbe48379fd95b230ef05885}

Quando você usa segmentos com a métrica de Pessoas, os resultados da métrica podem ser significativamente menores do que o esperado. Esse problema ocorre porque, na segmentação, não há *`person`* container. A segmentação usa o container do Visitante, que é o container de mais alto nível na definição e se baseia no dispositivo, não na pessoa.

Esse problema ocorre principalmente ao empilhar segmentos com a métrica de Pessoas.

![](assets/people-stacked-segments.png)

O empilhamento de segmentos cria um novo segmento que representa a combinação dos segmentos. O empilhamento de segmentos ocorre sempre que você:

* Coloque um segmento sobre outro no Analysis Workspace. (Eles são automaticamente unidos usando o *`And`* operador.)
* Aplique um único segmento que contenha o *`And`* operador.
* Aplique um segmento no nível do projeto e da tabela.
* Use um conjunto de relatórios virtual com outro segmento.

Por exemplo, suponha que você empilhe os seguintes segmentos na métrica de Pessoas:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Somente o número de pessoas que se qualificam em ambos os segmentos *`using a single device`* é contado. (A métrica de Pessoas não exibe o número de pessoas qualificadas em todos os dispositivos.)

Além disso, não é recomendado usar o *`Or`* operador nesta situação. Fazer isso produziria uma contagem de pessoas que viram um ou outro, sem nenhuma forma de contar quantas pessoas se qualificam para ambos os segmentos.

Consulte [Construção de segmentos](https://docs.adobe.com/content/help/pt-BR/analytics/components/segmentation/segmentation-workflow/seg-build.html) na ajuda Segmentação para obter mais informações.

## Tipos de dispositivo {#section-8ab378c84ff34574b9c20fecb3848a86}

O Device Co-op e a métrica de Pessoas funcionam melhor no Adobe Analytics quando seu conjunto de relatórios contém dados de vários tipos de dispositivos. Por exemplo, combinar dados da Web e do aplicativo no mesmo conjunto de relatórios torna a métrica de Pessoas mais poderosa e eficaz. Quanto maior o cruzamento de dispositivos em seus dados, maior a chance de que vários visitantes únicos sejam agrupados como uma única pessoa.

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

O Device Co-op exige que suas propriedades digitais sejam instrumentadas usando o serviço Experience Cloud ID (MCID). Se os dados em seu conjunto de relatórios contiverem um número significativo de visitantes sem uma MCID, a eficácia do Device Co-op e da métrica de Pessoas será reduzida.

<!--
mcdc-people-metric-apply.xml
-->

No Analysis Workspace, crie um [projeto](https://docs.adobe.com/content/help/pt-BR/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html)e arraste a **[!UICONTROL People]** métrica para a tabela do projeto:

![](assets/people-metric.png)

