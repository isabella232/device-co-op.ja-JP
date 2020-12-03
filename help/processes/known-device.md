---
description: Device Graphの既知のデバイスについて
seo-description: Device Graphの既知のデバイスについて
seo-title: 既知のデバイス
title: 既知のデバイス
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '571'
ht-degree: 1%

---


# 既知のデバイス{#known-devices}

Device Graphの既知のデバイスについて

Device Graphには、の概念があり *`known device`*&#x200B;ます。 既知のデバイスとは、顧客がブランドとやり取りする際に使用するデバイスです。

>[!NOTE]
>
>で [!DNL Adobe Experience Cloud Device Co-op]は、 *`device`*、 *`person`**`identity`* などの用語 特定の意味を持つ。 例えば、「デバイス」とは、スマートフォンやタブレットなどの物理的なハードウェア、およびそのハードウェア上で実行されるアプリケーションを指します。 定義については、 [用語集](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) を参照してください。

## 既知のデバイスを使用したサポート目標 {#section-80deae33660e4280ac65c659ceff5601}

既知のデバイス概念は、効果的な [!DNL Device Co-op] プログラムの作成と保守に不可欠ないくつかの目標をサポートしています。 既知のデバイスとは、 [!DNL Device Co-op] 会員が消費者との何らかのやりとりから（例えば、サイト訪問やモバイルアプリを使用して）知っているものです。 これらの操作に基づいて、メンバーの既知のデバイスを、他のメンバーが貢献したデバイスに [!DNL Device Graph] リンクし [!DNL Device Co-op] ま [!DNL Device Co-op] す。 これらのリンクは、 [決定論的にも確率的にもあり得ます](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)。 メンバーには次のようなメリットがあり [!DNL Device Co-op] ます。

* 既知のデバイスに関する詳細データ。
* リンクされた他のデバイスに関する新しい情報です。

![](assets/known-device.png)

は、Device Co-opメンバー [!DNL Device Graph] が見ていないデバイスクラスターに関する情報を提供しません。

## Device Co-opの目標 {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

3つの主な目標は、をアニメートし [!DNL Device Co-op]ます。 これには、以下が含まれます。

* **スケール：** 様々な使用例で、可能なリンクの最大数を共有します。
* **公平：** 各メンバーの貢献度に応じた方法でメリット [!DNL Device Co-op] を得る。

* **消費者信頼：** 消費者のデバイス間のエクスペリエンスに既に知り合いで信頼しているブランドが含まれていることを確認し、消費者の信頼感を維持して構築します。

## スケールと既知のデバイス {#section-67f734109762457ca62ec306284ea082}

次の方法は、デバイスが既知のデバイスとして認識される一般的な方法です。 これらのメソッドを使用すると、 [!DNL Device Co-op] メンバーにはほとんど常に少なくとも1つの既知のデバイスが存在します。 これは、のすべてのメンバに最大スケールを指定する目標をサポートし [!DNL Device Co-op]ます。

**オーガニック**

* 顧客のサイトへの訪問から、またはアプリを使用して行う。 これは、ファーストパーティデータに基づく資格です。
* CRMシステムのオンボーディング顧客。

**Marketplace**

* Audience Marketplaceからのセグメントデータの購入を参照してください。
* サードパーティのデータプロバイダーからの購入データから取得できます。

**広告**

オークションでインベントリを勝ち取り、広告を装置に提供する。 その広告に [!DNL Audience Manager] ピクセルが含まれる場合、デバイスは既知のデバイスになります。

## 既知のデバイスと公平な使用例 {#section-0543188729d845d6b95db70b8b25e9f8}

のメンバーは、に対する貢献度に応じたリンクを [!DNL Device Co-op] 取得 [!DNL Device Graph]します。 多くのデバイスに貢献する会社は、ほんの数人のデバイスに貢献する会員よりも多くのリンクを [!DNL Device Graph] 受け取る。 これは全会員の [!DNL Device Co-op] 公正さを助けると信じています。 以下に示す大きい使用例と小さい使用例で、この機能がどのように動作するかを見てみましょう。

**ブランドA:大規模な使用事例**

この例では、ブランドAのサイト訪問者は毎月100人で、開始は新しいクロスデバイスのブランドキャンペーンを利用しています。 簡単にするために、ブランドAへのすべての訪問者が1つの追加のデバイスにリンクされていることを知っているとします。 [!DNL Device Graph] これは、ブランドAが別の100台のデバイスに到達できることを意味します。 また、には約200台のデバイスがリンクされ [!DNL Device Graph] ています。

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 既知のデバイス/月 </th> 
   <th colname="col2" class="entry"> Device Co-opから受信したリンクされたデバイス </th> 
   <th colname="col3" class="entry"> キャンペーン用の合計デバイス数 </th> 
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

**ブランドB:小さな使用例**

この例では、ブランドBのサイト訪問者は毎月100人で、開始は新しいクロスデバイスのブランドキャンペーンを使用しています。 簡単にするために、ブランドBへのすべての訪問者が50台の追加のデバイスにリンクされていることを知っているとします。 [!DNL Device Graph] これは、ブランドBが150台のデバイスに到達できることを意味します。 また、には約1,000台のデバイスがリンクされて [!DNL Device Graph] います。

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 既知のデバイス/月 </th> 
   <th colname="col2" class="entry"> Device Co-opから受信したリンクされたデバイス </th> 
   <th colname="col3" class="entry"> キャンペーン用の合計デバイス数 </th> 
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

