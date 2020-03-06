---
description: 人物指標は、アドビのデバイスグラフに基づく人物（またはデバイスのグループ）の数です。Analysis Workspace で、デバイスをまたいで訪問者を識別するための人物指標を適用できます。
seo-description: 人物指標は、アドビのデバイスグラフに基づく人物（またはデバイスのグループ）の数です。Analysis Workspace で、デバイスをまたいで訪問者を識別するための人物指標を適用できます。
seo-title: 人物指標
title: 人物指標
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# 人物指標{#people-metric}

人物指標は、アドビのデバイスグラフに基づく人物（またはデバイスのグループ）の数です。Analysis Workspace で、デバイスをまたいで訪問者を識別するための人物指標を適用できます。

## People Metric Prerequisites and Considerations {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 前提条件または検討事項 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>デバイス Co-op </p> </td> 
   <td colname="col2"> <p> To use the People metric, become a member of the <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. Co-opは、個人の複数のデバイス（またはExperience Cloud ID）を識別します。 Analytics は、この情報を利用して、ブランドとやり取りする人の数を統計的に導きます。指標の正確さは5%以内です。 </p> <p><b>地域</b>：Device Co-op は、現在、米国およびカナダでのみ使用できます。そのため、人物指標を評価する場合、米国およびカナダのみのデータをフィルターする分析にセグメントを適用する必要があります。 </p> <p>毎週、デバイスグラフは、Co-op の新しいバージョンを計算して、使用するために公開します。火曜日に、システムは最新データを収集し、グラフの更新バージョンを公開します。その後、Experience Cloudソリューションは最新バージョンのグラフを使用します。 特に、Analyticsの場合、変更は水曜日に読み取られ、変更の処理には通常1 ～ 2営業日かかります。 </p> <p> <p>重要： グラフが週単位で更新されると、人物指標に過去に影響を与える可能性があります。 つまり、過去の訪問者数は、グラフが学習し、更新されるにつれて、時間の経過と共に変化する可能性があります。 例えば、先月の人数をカウントする今日のレポートを実行し、グラフの更新後1週間で同じレポートを実行した場合、過去の人数は少し変わる可能性があります。 </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> 指標の権限 </td> 
   <td colname="col2"> <p>人物指標は、その指標へのアクセス権を付与されている場合にのみ使用できます。 管理者は<a href="https://marketing.adobe.com/resources/help/en_US/reference/groups-metrics.html" format="html" scope="external"> 、管理ツールで指標の権限をカスタマイズできます</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> IMS組織へのマッピング </td> 
   <td colname="col2"> <p>人物指標は、IMSORGにマッピングされるすべてのレポートスイ <a href="https://marketing.adobe.com/resources/help/en_US/mcloud/map-report-suite.html" format="html" scope="external"> ートで有効になります</a>。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>分析プロジェクト／ツール </p> </td> 
   <td colname="col2"> <p><span class="wintitle">Analysis Workspace</span>、<span class="wintitle">Ad Hoc Analysis</span>、<span class="wintitle">Report Builder</span> および API から、人物指標を使用します。計算指標など、実訪問者数の指標が使用されている場所ならどこでも、人物指標を使用することができます。 </p> <p>例えば、1 人あたりの収益指標を作成して、実訪問者あたりの収益指標を置き換えます。 </p> <p><a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html" format="html" scope="external">人物プロジェクトテンプレート</a>を使用して、Analysis Workspace で人物指標を使い始めることができます。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ボットルールを有効にする </p> </td> 
   <td colname="col2"> <p>アドビでは、特に人物指標を使用する場合、<a href="https://marketing.adobe.com/resources/help/en_US/reference/bot_rules.html" format="html" scope="external">ボットルール</a>を有効にすることをお勧めします。 </p> <p>ボットが Web サイトをクロールすると、実訪問者の数が人工的に増加されます。レポートスイートからボットトラフィックを削除することで、実訪問者と人物の両方で、デジタルプロパティに関するアクティビティのより正確な指標が提供されます。 </p> <p>そのためには、<span class="uicontrol">Analytics</span>／<span class="uicontrol">管理者</span>／<span class="uicontrol">レポートスイート</span>に移動します。適切なレポートスイートを選択し、<span class="uicontrol">設定を編集</span>／<span class="uicontrol">一般</span>／<span class="uicontrol">ボットルール</span>に移動します。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>セグメント化の考慮事項 </p> </td> 
   <td colname="col2"> <p> 人物指標でセグメントを使用する場合、指標レポートは、想定よりも大幅に低くなる可能性があります。 </p> <p><a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local">セグメントでの人物指標の使用</a>を参照してください。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 人物指標とは{#section-89e2b8f5e80f480391449fc8d1117a6a}

人物指標は、デバイスを人に結び付けるのに役立つ、Analytics レポート指標です。ユーザーベースのマーケティングの視点を提供し、すべてのデバイスにまたがる訪問者のアクティビティを測定できます。実訪問者の重複排除されたバージョンと考えてください。以前、実訪問者を使用した分析で人物指標を使用できます。

**デバイスは人物**

人物指標が有効になる前に、（例えば）ある人物がサイトを訪問し、3 つの異なるデバイスでキャンペーンやブランドに関与して、購入する可能性があります。それがわずか数分の間におこなわれることもあります。実装に応じて、Analytics は、各デバイスを実訪問者としてレポートし、30 ドルの購入で 10 ドルを 3 つのデバイスによるものとします。

人物指標を使用すると、30 ドルの購入を正確に 1 人の人物によるものとできます。

![](assets/people-centric-results.png)

**レポートでの正確性の向上**

人物指標を使用すると、複数のデバイスを単一のエンティティと考えることができます。以下の Analysis Workspace プロジェクトは、向上した正確性を実訪問者数レポートと人物レポートの間で比較しています。

![](assets/people_report.png)

人物と実訪問者を横に並べて比較します。

![](assets/people-report.png)

**定義**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 項目 </th> 
   <th colname="col2" class="entry"> 説明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>People </p> </td> 
   <td colname="col2"> <p>人物指標は、消費者が複数のデバイスを使用してブランドとやり取りするという考えに基づいています。データをスライスまたはセグメント化すればするほど、データのスライス内で同じ人物が複数のデバイスを使用する可能性が少なくなります。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>実訪問者数 </p> </td> 
   <td colname="col2"> <p>例えば、日付または時間でデータをスライスすればするほど、人物と実訪問者の違いは少なくなります。Device Co-opの全体的な影響を十分に理解したい場合は、過去90日間の日付範囲を使用することをお勧めします。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>圧縮 </p> </td> 
   <td colname="col2"> <p>シンプルな計算指標を作成することで、人物指標によってどれほどの人数が除外されたかを実訪問者の割合として確認することができます。前述の表の「圧縮」の隣にある情報アイコンをクリックして、この指標の作成方法を確認します。 </p> <p>他の計算指標で、実訪問者の代わりに人物を使用できます。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 人物指標の計算方法 {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

以下の図に、人物指標の計算方法と、過去の同じ日付範囲に対するレポートで時間の経過と共に人物の数がどのように減少するかを示します。

![](assets/people-calculations.png)

この例では、訪問者数が固定されていると想定しています。過去の一定期間、レポートを実行した場合、一定の訪問者数が表示されます。デバイスグラフが左の図に示されている第 1 週のデータを出力すると、レポートでは人物の数が 90 人と報告されます。1 週間後、デバイスグラフが再度実行され、新しい情報が考慮されます。1 週間前と同じレポートを実行すると、人数が 84 に減少します。これは、デバイスグラフによってどのデバイスをグループ化すべきかに関する新しい情報が提供されたためです。

## セグメントでの人物指標の使用 {#section-d03525420dbe48379fd95b230ef05885}

人物指標でセグメントを使用する場合、指標の結果は、想定よりも大幅に低くなる可能性があります。セグメント化で *`person`* container. セグメント化では、訪問者コンテナを使用します。訪問者コンテナは、定義の最高レベルのコンテナであり、人ではなくデバイスに基づいています。

この問題は、主に、人物指標でセグメントを積み重ねる場合に発生します。

![](assets/people-stacked-segments.png)

セグメントを積み重ねると、そのセグメントの組み合わせを表す新しいセグメントが作成されます。セグメントの積み重ねは、以下の場合に発生します。

* Analysis Workspace で、別のセグメントの上にセグメントを配置する（これらは、*`And`* 演算子を使用して自動的に結合されます）。
* Apply a single segment that contains the *`And`* operator.
* プロジェクトレベルおよびテーブルレベルの両方でセグメントを適用する。
* 別のセグメントと共に仮想レポートスイートを使用する。

例えば、人物指標の上に以下のセグメントを積み重ねるとします。

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Only the number of people who qualify in both segments *`using a single device`* are counted. （人物指標は、デバイスをまたいで適合する人数は表示しません）。

また、この状況では、*`Or`* 演算子の使用は、お勧めしません。Or 演算子を使用すると、どちらか一方に適合する人数がカウントされ、両方のセグメントに適合する人数はカウントされません。

詳しくは、セグメントのヘルプの[セグメントの作成](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_build.html)を参照してください。

## デバイスタイプ {#section-8ab378c84ff34574b9c20fecb3848a86}

Device Co-op および人物指標は、レポートスイートが複数のデバイスタイプからのデータを含んでいる場合に、Adobe Analytics で最も適切に機能します。例えば、同じレポートスイートの Web およびアプリデータを組み合わせると、人物指標はよりパワフルで効果的になります。より多くのデバイスに関するデータを収集できれば、複数の実訪問者を 1 人の人物としてグループ化できる可能性が高くなります。

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-opでは、Experience Cloud ID(MCID)サービスを使用してデジタルプロパティを実装する必要があります。 レポートスイートのデータに MCID を持たない大量の訪問者が含まれている場合、Device Co-op および人物指標の有効性は減少します。

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, create a [project](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/t_freeform_project.html), then drag the **[!UICONTROL People]** metric to the project table:

![](assets/people-metric.png)

