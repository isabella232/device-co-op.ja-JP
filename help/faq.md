---
description: Device Co-op（ID サービス協業および ID グラフ）に関するよくある質問への回答。
title: Device Co-op に関する FAQ
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# FAQ{#faq}

ID サービス協業および ID グラフに関するよくある質問への説明と回答。

**概要 [!DNL Device Co-op]?**

Device Co-op は、Adobe Experience Cloudの顧客が連携して複数のデバイスをまたいで消費者をより正確に識別できるようにするためのデジタル協業です。

**Device Co-op ではどのようなテクノロジーが使用されていますか。**

Device Co-op は、次の 2 つのテクノロジーで構成されます。

* **Experience CloudID サービス：** Adobe Experience Cloudのこのコアサービスは、ソリューション、チャネル、エクスペリエンスおよびデバイスをまたいで一貫した消費者を識別するための共通の ID を提供します。
* **Adobe Experience Cloud Device Co-op:** この技術は、消費者や世帯が使用する様々なデバイスをリンクします。

**は [!DNL Device Co-op] 仕事？**

ブランドは、匿名化されたログインやサイト訪問を通じてクロスデバイスパズルの一部にピッチを持つので、Adobeはこのデータを処理して、不明な人が使用するデバイスのグループを表すデバイスクラスターを形成します。 これらのデバイスクラスターは、Device Co-op のメンバーに提供され、消費者に対して、より高品質で一貫性のあるクロスデバイスエクスペリエンスを提供するために使用されます。

**は [!DNL Device Co-op] デバイスをリンクしますか？**

詳しくは、 [決定論的リンクと確率論的リンク](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**参加者が提供するデータ [!DNL Adobe]?**

詳しくは、 [消費者のオプトアウトツール、プライバシーおよびデバイスグラフ](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**データの共有先 [!DNL Device Co-op] メンバー？**

詳しくは、 [デバイスグラフでのリンク共有](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**使用可能な [!DNL Device Co-op] メンバーは、これまでに見たことのないデバイスへのリンクを表示しますか？**

いいえ。Device Co-op のメンバーは、ブランドの Web プロパティの 1 つを訪問したデバイスに基づいてのみデータを取得できます。 詳しくは、 [既知のデバイス](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) および [不明なデバイス](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**会社のマーケティング情報を共有する必要がありますか？**

いいえ。ブランドは匿名デバイスデータのみをAdobeに提供します。

**実行 [!DNL Adobe] 個人を特定できる情報 (PII) を [!DNL Device Co-op]?**

いいえ。個人を特定できる情報はすべて、Adobeシステムに取り込まれる前にハッシュ化されるので、お客様の情報はAdobeシステムに転送されません。

**Device Co-op に貢献するデバイスデータの量が少ない小規模ブランドは、大規模なブランドと比べて、提供されるデバイスデータの量よりも多くの価値を得られますか。**

いいえ。協業の全てのメンバーは、入力した内容に対する価値を取り戻します。 例えば、ブランドが 10,000 台のデバイスに貢献する場合、10,000 台のデバイスに関連付けられた、リンクされた追加のデバイス情報を受け取ることができます。 全体像を見ると、この貢献は最小限にしか見えない。しかし、あらゆる規模のブランドがますます多く結びつくにつれ、集計的な貢献度は大きく、他の多くの、おそらくは大きなブランドが探している多くのデバイスの欠落リンクを提供します。 詳しくは、 [公平性と既知のデバイス](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**方法 [!DNL Adobe] 一部の国で IP アドレスを個人情報と見なす場合、IP アドレスを管理しますか？**

Device Co-op は、IP アドレスが個人情報と見なされない米国およびカナダで最初にリリースされます。 IP アドレスが個人情報と見なされる国で協業がリリースされた場合、IP アドレスは使用されません。
