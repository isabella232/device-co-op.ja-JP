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

Device Graphには、*`known device`*&#x200B;という概念があります。 既知のデバイスとは、顧客がブランドとやり取りする際に使用するデバイスです。

>[!NOTE]
>
>[!DNL Adobe Experience Cloud Device Co-op]では、*`device`*、*`person`*、*`identity`*&#x200B;などの用語が 特定の意味を持つ。 例えば、「デバイス」とは、スマートフォンやタブレットなどの物理的なハードウェア、およびそのハードウェア上で実行されるアプリケーションを指します。 定義については、[用語集](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c)を参照してください。

## 既知のデバイス{#section-80deae33660e4280ac65c659ceff5601}を使用したサポート目標

既知のデバイス概念は、効果的な[!DNL Device Co-op]プログラムの作成と保守に不可欠ないくつかの目標をサポートしています。 既知のデバイスとは、[!DNL Device Co-op]メンバーがコンシューマーとの何らかのやり取り（例：サイト訪問、モバイルアプリの使用）から知っているものです。 これらの操作に基づいて、[!DNL Device Graph]は、[!DNL Device Co-op]メンバの既知のデバイスを、他の[!DNL Device Co-op]メンバが貢献したデバイスにリンクします。 これらのリンクは、[決定論的または確率的](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)です。 [!DNL Device Co-op]メンバーは次のようなメンバーを受け取るので、このメリットが得られます。

* 既知のデバイスに関する詳細データ。
* リンクされた他のデバイスに関する新しい情報です。

![](assets/known-device.png)

[!DNL Device Graph]は、Device Co-opメンバーが見ていないデバイスクラスターに関する情報を提供しません。

## Device Co-opの目標{#section-75aea5a102d54733aae2a7c6ee9ec6c7}

3つの主な目標は[!DNL Device Co-op]をアニメートします。 これには、以下が含まれます。

* **スケール：様々な使用例で、可能な最大数のリンクを** 共有します。
* **公平：各メンバーが貢献** に見合う方法で [!DNL Device Co-op] 利益を受けるようにします。

* **消費者信頼：** 消費者のデバイス間のエクスペリエンスに既に知り合いで信頼しているブランドが含まれていることを確認し、消費者信頼感を維持して構築します。

## スケールと既知のデバイス{#section-67f734109762457ca62ec306284ea082}

次の方法は、デバイスが既知のデバイスとして認識される一般的な方法です。 これらのメソッドを使うと、[!DNL Device Co-op]メンバは、ほとんど常に1つ以上の既知のデバイスを持ちます。 これは、[!DNL Device Co-op]のすべてのメンバーに最大スケールを提供する目標をサポートします。

**オーガニック**

* 顧客のサイトへの訪問から、またはアプリを使用して行う。 これは、ファーストパーティデータに基づく資格です。
* CRMシステムのオンボーディング顧客。

**Marketplace**

* Audience Marketplaceからのセグメントデータの購入を参照してください。
* サードパーティのデータプロバイダーからの購入データから取得できます。

**広告**

オークションでインベントリを勝ち取り、広告を装置に提供する。 その広告に[!DNL Audience Manager]ピクセルが含まれる場合、デバイスは既知のデバイスになります。

## 既知のデバイスと公平な使用例{#section-0543188729d845d6b95db70b8b25e9f8}

[!DNL Device Co-op]のメンバーは、[!DNL Device Graph]への貢献度に応じたリンクを取得します。 [!DNL Device Graph]に多くのデバイスを貢献する会社は、ほんの数人の会員よりも多くのリンクを受け取る。 [!DNL Device Co-op]をそのメンバー全員に公平にするのに役立つと思います。 以下に示す大きい使用例と小さい使用例で、この機能がどのように動作するかを見てみましょう。

**ブランドA:大規模な使用事例**

この例では、ブランドAのサイト訪問者は毎月100人で、開始は新しいクロスデバイスのブランドキャンペーンを利用しています。 簡単にするために、[!DNL Device Graph]は、ブランドAに対するすべての訪問者が1つの追加のデバイスにリンクされていることを知っているとします。 これは、ブランドAが別の100台のデバイスに到達できることを意味します。 さらに、[!DNL Device Graph]には約200個のデバイスがリンクされています。

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

この例では、ブランドBのサイト訪問者は毎月100人で、開始は新しいクロスデバイスのブランドキャンペーンを使用しています。 簡単にするために、[!DNL Device Graph]は、ブランドBへのすべての訪問者が50台の追加デバイスにリンクされていることを知っているとします。 これは、ブランドBが150台のデバイスに到達できることを意味します。 さらに、[!DNL Device Graph]には約1,000個のデバイスがリンクされています。

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

