---
description: デバイスグラフの既知のデバイスについて
seo-description: About known devices in the Device Graph.
seo-title: Known devices
title: 既知のデバイス
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
exl-id: 4eaf104f-022b-447b-8ce2-f0d0d1177cdf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '562'
ht-degree: 1%

---

# 既知のデバイス{#known-devices}

デバイスグラフの既知のデバイスについて

デバイスグラフでは、 *`known device`*. 既知のデバイスとは、顧客がブランドとやり取りする際に使用するデバイスです。

>[!NOTE]
>
>内 [!DNL Adobe Experience Cloud Device Co-op]、などの用語 *`device`*, *`person`*, *`identity`* など 具体的な意味を持つ。 例えば、「デバイス」とは、電話やタブレットなどの物理的なハードウェアや、そのハードウェア上で動作するアプリケーションを指す場合があります。 詳しくは、 [用語集](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) を参照してください。

## 既知のデバイスでのサポート目標 {#section-80deae33660e4280ac65c659ceff5601}

既知のデバイスの概念は、効果的なの作成と保守に不可欠ないくつかの目標をサポートします [!DNL Device Co-op] プログラム。 既知のデバイスは、 [!DNL Device Co-op] メンバーは、消費者との何らかのやり取り（サイト訪問やモバイルアプリの使用など）によって把握しています。 これらのアクションに基づいて、 [!DNL Device Graph] は、 [!DNL Device Co-op] 他の人から寄与された装置のメンバー [!DNL Device Co-op] メンバー。 これらのリンクは [決定論的または確率論的](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). この利点 [!DNL Device Co-op] メンバーは、次を受け取るからです。

* 既知のデバイスに関するより多くのデータ。
* その他のリンクされたデバイスに関する新しい情報。

![](assets/known-device.png)

この [!DNL Device Graph] は、Device Co-op のメンバーが見たことのないデバイスクラスターに関する情報を提供しません。

## Device Co-op の目標 {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

3 つの主な目標は、 [!DNL Device Co-op]. これには、以下が含まれます。

* **スケール：** 様々な使用例で、可能な最大数のリンクを共有します。
* **公平性：** 各メンバーが [!DNL Device Co-op] 貢献に見合った方法での利益

* **消費者の信頼：** 消費者のクロスデバイスエクスペリエンスに、既に知り合い、信頼しているブランドが含まれていることを確認して、消費者の信頼感を維持および構築します。

## スケールと既知のデバイス {#section-67f734109762457ca62ec306284ea082}

デバイスが既知のデバイスと見なされる一般的な方法は、次のとおりです。 これらの方法を考えると、 [!DNL Device Co-op] メンバーには、ほとんどの場合、少なくとも 1 つの既知のデバイスが存在します。 これにより、 [!DNL Device Co-op].

**オーガニック**

* 顧客のサイトへの訪問から、またはアプリを使用して。 これはファーストパーティデータからの認定です。
* CRM システムからの顧客のオンボーディングによって。

**Marketplace**

* セグメントからのセグメントデータのAudience Marketplace。
* サードパーティのデータプロバイダーからのデータ購入から。

**広告**

オークションでインベントリに当選し、広告をデバイスに提供することで。 その広告に [!DNL Audience Manager] ピクセル。

## 既知のデバイスと公平性の使用例 {#section-0543188729d845d6b95db70b8b25e9f8}

のメンバー [!DNL Device Co-op] ～への貢献に見合ったリンクを得る [!DNL Device Graph]. 多くのデバイスをに寄稿する会社 [!DNL Device Graph] 少数の投稿者よりも多くのリンクを受け取ります。 これは、 [!DNL Device Co-op] その会員全員にとって公正な 以下に説明する大規模および小規模の使用例で、これがどのように機能するかを見てみましょう。

**ブランド A:大規模な使用例**

この例では、ブランド A には、毎月 100 人のサイト訪問者がいて、新しいクロスデバイスのブランドキャンペーンを開始します。 簡単にするために、次のように仮定します。 [!DNL Device Graph] は、Brand A へのすべての訪問者が 1 台の追加デバイスにリンクされていることを認識します。 つまり、ブランド A が別の 100 台のデバイスに到達する可能性があります。 また、 [!DNL Device Graph] には、互いにリンクされた約 200 台のデバイスが含まれています。

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 既知のデバイス/月 </th> 
   <th colname="col2" class="entry"> Device Co-op から受信したリンク済みデバイス </th> 
   <th colname="col3" class="entry"> キャンペーンの合計デバイス数 </th> 
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

**ブランド B:小規模な使用例**

この例では、ブランド B には、毎月 100 人のサイト訪問者がいて、新しいクロスデバイスのブランドキャンペーンを開始します。 簡単にするために、次のように仮定します。 [!DNL Device Graph] は、ブランド B へのすべての訪問者が、その他 50 台のデバイスにリンクされていることを認識します。 つまり、ブランド B は 150 台のデバイスに到達できます。 また、 [!DNL Device Graph] には、互いにリンクされた約 1,000 個のデバイスが含まれています。

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 既知のデバイス/月 </th> 
   <th colname="col2" class="entry"> Device Co-op から受信したリンク済みデバイス </th> 
   <th colname="col3" class="entry"> キャンペーンの合計デバイス数 </th> 
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
>* [不明なデバイス](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

