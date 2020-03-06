---
description: Device Graphでのリンクの共有についてを参照してください。
seo-description: Device Graphでのリンクの共有についてを参照してください。
seo-title: Device Graphでのリンク共有
title: Device Graphでのリンク共有
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Link sharing in the Device Graph{#link-sharing-in-the-device-graph}

Device Graphでのリンクの共有についてを参照してください。

The [!DNL Device Graph] shares deterministic and probabilistic links with different members of the Adobe Experience Cloud Device Co-op. Link sharing is what makes the [!DNL Device Co-op] so powerful. リンク共有により、匿名の人物に関連付けられたデバイスについて各メンバーが把握しているデータが強化されます。ただし、新たなデータが得られるのは、ブランド側でその匿名の人物のデバイスが少なくとも 1 つ認識されている場合に限られます。

## Device Graph summary review {#section-7858e9f61b5644c981ffb53626fcc19d}

Before getting started, let&#39;s take a moment to review how the [!DNL Device Graph] works. にデータを送 [!DNL Device Co-op] 信するのメンバ [!DNL Device Graph]ー。 このデ [!DNL Device Graph] ータを使用して、デバイス間の決定的なリンクと確率的なリ [ンクから人のアイデンティティ](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) を構築します。 [!DNL Device Co-op] の参加者は、これらのリンクから、認証済みユーザーまたは他のユーザーとデバイスとの関係に関するインサイトを得ることができます。以下の節で、これらがどのように機能するかを見てみましょう。

## Link sharing example {#section-cb410d827cf14f76bc9b0bd4d31ed767}

以下の例で、Device Co-op のリンク共有がどのように力を発揮するかを示します。この例では、ニュース会社と金融会社の 2 つの架空の会社があるとします。Both companies are members of the [!DNL Device Co-op]. 人物 A は、複数のデバイスから各会社の Web サイトにログオンまたは閲覧する消費者です。

![](assets/share1.png)

人物 A は、携帯電話およびタブレットを使用してニュースサイトに対して認証済みなので、ニュース会社は、消費者 ID で識別しています。It sends that ID to the [!DNL Device Graph] as a cryptographic hash. 金融会社は、以前、これらのデバイスを確認していますが、人物 A はこのサイトにログオンしたことがありません。したがって、金融会社は、これらのデバイスが互いに関連しているかどうかやその方法、またはそれらがどのように人物 A と関連付けられているかを把握していません。

![](assets/share2.png)

Given the cryptographic hash of the consumer ID, the [!DNL Device Graph] recognizes that these devices are related to each other and a particular person. [!DNL Device Co-op] に参加していない会社にとって、これらのサイト訪問は、別の、ランダムなデバイスからのもののように見えます。In any case, once the [!DNL Device Graph] has the hashed ID it:

* 携帯電話とノートパソコンがリンクされていることを把握します。
* 携帯電話とノートパソコンがリンクされているかどうか、金融会社が知りたがっていることを認識します。

Given these conditions, the [!DNL Device Graph] now shares the link connecting these devices for the News Company with the Finance Company. During this process, the [!DNL Device Graph] duplicates and shares the link from one co-op member to another.

![](assets/share3.png)

At this point, the [!DNL Device Graph] performed its role successfully. ニュース会社と金融会社は両方とも、ID を明確に把握しています。すべてのデバイスで人物 A に正確にリーチできます。

## Privacy and link sharing {#section-7b566018b3304420a4b3e4c079826110}

リンク共有処理の間、消費者のプライバシーと [!DNL Device Co-op] メンバーのデータの整合性を維持することが非常に重要です。During this customer identification and link sharing process the [!DNL Device Graph] did not:

* 金融会社に、リンクがニュース会社から来たものであることを伝える。
* ある [!DNL Device Co-op] メンバーによって使用された顧客 ID を他のメンバーと共有する。
* モバイルデバイスおよびノートパソコンが共通のリンクを共有していること以外の情報を提供する。

## 次の手順 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Reading the documentation on identity, linking, and link sharing should give you a good sense of how the [!DNL Device Graph] assembles data internally. 次のステップとして、デバイス間のリンクをDevice Co-opメンバーに提供するという概念を説明するドキュメ *`known device`* ントを見てみることをお勧めします。 「既知のデ [バイス](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 」および「不明なデ [バイス」を参照してください](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)。
