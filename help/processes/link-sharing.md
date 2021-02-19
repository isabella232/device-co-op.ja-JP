---
description: Device Graphでのリンクの共有について
seo-description: Device Graphでのリンクの共有について
seo-title: Device Graphでのリンクの共有
title: Device Graphでのリンクの共有
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '557'
ht-degree: 0%

---


# Device Graphでのリンクの共有{#link-sharing-in-the-device-graph}

Device Graphでのリンクの共有について

[!DNL Device Graph]は、Adobe Experience Cloud・デバイスCo-opの異なるメンバーと確定的および確率的なリンクを共有しています。 [!DNL Device Co-op]を強力にするのは、リンクの共有です。 匿名の人に関連付けられた装置について各会員が知っている範囲を拡張します。ただし、その匿名の人の装置の少なくとも1つを見たことがある場合に限ります。

## Device Graphの概要{#section-7858e9f61b5644c981ffb53626fcc19d}

始める前に、[!DNL Device Graph]の仕組みを少し見てみましょう。 [!DNL Device Co-op]のメンバーは、[!DNL Device Graph]にデータを送信します。 [!DNL Device Graph]はこのデータを使って、デバイス間の[決定論的および確率的なリンク](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)から人のアイデンティティを構築する。 [!DNL Device Co-op]参加者として、これらのリンクは、認証済みユーザー、他のユーザー、およびそのデバイスとの関係に関するインサイトを提供します。 次の節で、これがどのように機能するかを見てみましょう。

## リンク共有の例{#section-cb410d827cf14f76bc9b0bd4d31ed767}

次の例は、Device Co-opでのリンク共有の機能を示しています。 この例では、ニュース会社と金融会社の2つの架空の会社があります。 両方の会社は[!DNL Device Co-op]のメンバです。 個人Aは、複数のデバイスにログオンしたり、各会社のWebサイトを閲覧したりする消費者です。

![](assets/share1.png)

個人Aは携帯電話とタブレットでニュースサイトに対して認証を行っているので、ニュース会社は消費者IDでユーザーを識別します。 このIDを[!DNL Device Graph]に暗号化ハッシュとして送信します。 金融会社はこれらのデバイスを以前に見たことがありますが、個人Aはサイトにログオンしていません。 したがって、金融会社は、これらのデバイスが相互に関連し合っているか、どのように関連しているか、または、個人Aとどのように関連付けられているかを知りません。

![](assets/share2.png)

コンシューマIDの暗号化ハッシュを指定すると、[!DNL Device Graph]は、これらのデバイスが互いに関連していて、特定の人物が関連していることを認識します。 [!DNL Device Co-op]に参加しない会社にとって、これらのサイトへの訪問は、別々のランダムなデバイスから来ているように見えます。 いずれにせよ、[!DNL Device Graph]がハッシュ化されたIDを持つと、次のようになります。

* 携帯電話とノートパソコンがリンクされていることを知っています。
* Finance会社が携帯電話とラップトップがリンクされているかどうかを知りたがっていることを認識します。

これらの条件を満たすと、[!DNL Device Graph]は、News会社用にこれらのデバイスを接続するリンクをFinance会社と共有します。 このプロセス中、[!DNL Device Graph]重複は、協力メンバー間でリンクを共有します。

![](assets/share3.png)

この時点で、[!DNL Device Graph]は正常にその役割を果たしました。 ニュース会社と金融会社は共に、明確なアイデンティティを持っています。 ユーザーは、すべてのデバイスを通して、ユーザーAに正確に連絡できます。

## プライバシーとリンクの共有{#section-7b566018b3304420a4b3e4c079826110}

[!DNL Device Co-op]メンバーのプライバシーとデータの整合性を維持することは、リンク共有プロセス全体で重要です。 この顧客の識別とリンクの共有プロセス中、[!DNL Device Graph]は次の操作を行いませんでした。

* 金融会社に、リンクがニュース会社から来たことを伝えます。
* ある[!DNL Device Co-op]メンバが使用する顧客IDを別のメンバと共有します。
* モバイルデバイスとノートブックパソコンが共通のリンクを共有する情報以外の情報を入力します。

## 次の手順 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

ID、リンク、リンクの共有に関するドキュメントを読むと、[!DNL Device Graph]がデータを内部的に組み立てる方法を正しく理解できるはずです。 次のステップとして、*`known device`*&#x200B;の概念がDevice Co-opメンバーにデバイス間のリンクを提供する方法を説明したドキュメントを見てみることをお勧めします。 「[既知のデバイス](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)」および「[不明なデバイス](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)」を参照してください。
