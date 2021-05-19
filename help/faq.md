---
description: Device Co-op（Identity Services CooperativeとIdentity Graph）に関するよくある質問と、その回答を示します。
title: Device Co-op FAQ
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# FAQ{#faq}

IDサービス協同組合とIDグラフに関してよく寄せられる質問の説明と回答です。

**何が [!DNL Device Co-op]?**

Device Co-opは、複数のデバイスにわたって消費者をより良く識別するために、Adobe Experience Cloudのお客様と協力し合うためのデジタル協力会社です。

**Device Co-opで使用されているテクノロジー**

Device Co-opは、次の2つのテクノロジーで構成されています。

* **Experience CloudIDサービス：** Adobe Experience Cloudのこのコアサービスは、ソリューション、チャネル、エクスペリエンスおよびデバイス全体で一貫した消費者を識別するための共通のIDを提供します。
* **Adobe Experience Cloudデバイス協力会：** この技術は、消費者や家庭で使用される様々なデバイスをリンクします。

**どうやって [!DNL Device Co-op] 働く？**

ブランドは、匿名ログインやサイト訪問によってクロスデバイスパズルのピースにピッチを与えるので、Adobeはこのデータを処理して、未知の人が使用するデバイスのグループを表すデバイスクラスターを形成します。 これらのデバイスクラスターは、Device Co-opのメンバーに提供され、ユーザーに対してより優れた一貫性のあるデバイス間のエクスペリエンスを提供するために使用されます。

**リン [!DNL Device Co-op] クデバイスの動作**

「[決定論的リンクと確率的リンク](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)」を参照してください。

**参加者はどのようなデータを提供し [!DNL Adobe]ますか。**

[コンシューマーオプトアウトツール、プライバシー、デバイスグラフ](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)を参照してください。

**メン [!DNL Device Co-op] バー間で共有されるデータは何ですか。**

「Device Graph」の「[リンクの共有](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf)」を参照してください。

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**メン [!DNL Device Co-op] バーは、これまで見たことのないデバイスへのリンクを表示できますか。**

いいえ。Device Co-opのメンバーは、自社ブランドのWebプロパティの1つを訪問したデバイスに基づくデータのみを取得できます。 「[既知のデバイス](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)」および「[不明なデバイス](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)」を参照してください。

**会社のマーケティング情報を共有する必要がありますか。**

いいえ。ブランドは、匿名デバイスデータのみをAdobeに提供します。

**に個人 [!DNL Adobe] 識別情報(PII)を使用しま [!DNL Device Co-op]すか。**

いいえ。個人を特定できる情報はすべて、Adobeシステムに取り込まれる前にハッシュ化されるので、顧客の情報がAdobeシステムに転送されることはありません。

**Device Co-opに対するデバイスデータの寄与が少ない小規模ブランドは、大規模ブランドに比べて、より多くの価値を得られるか。**

いいえ。組合の全メンバーは、入力内容に対する値を取得します。 例えば、ブランドが10,000個のデバイスに貢献する場合、それらの10,000に関連付けられた追加のリンクされたデバイス情報を受け取ることができます。 全体像を見ると、この貢献は最小限に見えるかもしれません。しかし、様々な規模のブランドが加わるにつれて、集計貢献度は重要なものとなり、他の多くの大きなブランドが探し求めている多くのデバイスには、リンクがなくなるでしょう。 [公正と既知のデバイス](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)を参照してください。

**一部の国でIPアドレスを個人情報と見なす場合、IPアドレスはどのように [!DNL Adobe] 管理しますか。**

Device Co-opは、IPアドレスが個人情報ではない米国およびカナダで最初にリリースされます。 IPアドレスが個人情報と見なされる国で協同組合がリリースされた場合、そのIPアドレスは使用されません。
