---
description: ID サービス協業および ID グラフに関するよくある質問に対する説明と回答です。
seo-description: ID サービス協業および ID グラフに関するよくある質問に対する説明と回答です。
seo-title: FAQ
title: FAQ
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# FAQ{#faq}

ID サービス協業および ID グラフに関するよくある質問に対する説明と回答です。

**何だ[!DNL Device Co-op]?**

Device Co-opは、Adobe Experience Cloudの顧客と協力して、複数のデバイスにわたって消費者をより良く識別するための協力を行うデジタル協力会社です。

**Device Co-op ではどのようなテクノロジーが使用されますか。**

Device Co-op は、以下の 2 つのテクノロジーで構成されます。

* **Experience Cloud IDサービス：** Adobe Experience Cloudのこのコアサービスは、ソリューション、チャネル、エクスペリエンスおよびデバイス全体で消費者を一貫して識別するための共通のIDを提供します。
* **Adobe Experience Cloud Device Co-op:** この技術は、消費者や家庭で使用される様々なデバイスをリンクします。

**どうやっ[!DNL Device Co-op]て？**

アドビは、企業から提供される匿名化されたログインおよびサイト訪問のデータを処理して、デバイス間の関係を特定し、1 人の匿名の人物によって使用されるデバイスのグループ（デバイスクラスター）を形成します。これらのデバイスクラスターは、Device Co-op メンバーに提供され、より一貫した、優れたクロスデバイスエクスペリエンスを消費者に提供するために使用されます。

**リンクデバイスはど[!DNL Device Co-op]のようにしますか。**

See [Deterministic and Probabilistic Links](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**参加者はどのようなデータを提供しま[!DNL Adobe]すか。**

[消費者のオプトアウトツール、プライバシーおよびデバイスグラフ](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be)を参照してください。

**メンバー間で共有されるデータ[!DNL Device Co-op]は何か。**

See [Link Sharing in the Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**[!DNL Device Co-op]メンバーは、それまで認識したことのないデバイスへのリンクを確認できますか。**

いいえ。Device Co-op の各メンバーが入手できるのは、自社の Web プロパティの 1 つにアクセスしたデバイスに関連するデータのみです。詳しくは、 既知のデ [バイス](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) と不明 [なデバイス](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。

**会社のマーケティング情報のいずれかを共有する必要はありますか。**

いいえ。ブランドは、匿名デバイスデータのみをアドビに提供します。

**に個人[!DNL Adobe]を特定できる情報(PII)を使用します[!DNL Device Co-op]か。**

いいえ。すべての個人情報は、アドビのシステムに組み込まれる前にハッシュ化されているので、顧客の情報は、アドビのシステムに転送されることはありません。

**大規模のブランドと比較して、より少ないデバイスデータを Device Co-op に提供する小規模のブランドは、提供したもの以上の価値を得るのではありませんか。**

いいえ。協業のすべてのメンバーは、提供したものに応じた価値を得ます。例えば、あるブランドが 10,000 個のデバイスデータを提供する場合、それらの 10,000 個にリンクされる追加のデバイス情報を受け取ることができます。全体から判断すると、このブランドの貢献は小さなものに見えるかもしれませんが、あらゆる規模のブランドの参加によってデータの集約が進めば、大規模なブランドを含む多くのメンバーが自社のデータのみでは特定できなかったデバイス間のリンクを識別できるようになります。公正と [既知のデバイスを参照](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)。

**一部の国でIPア[!DNL Adobe]ドレスを個人情報と見なす場合、IPアドレスはどのように管理しますか。**

Device Co-op は、IP アドレスが個人情報とは見なされない米国およびカナダで最初にリリースされます。この協業が IP アドレスを個人情報と見なす国でリリースされる場合、IP アドレスは使用されません。
