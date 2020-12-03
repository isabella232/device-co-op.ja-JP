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

これは、Adobe Experience Cloud・デバイス協同組合の異なるメンバーと、決定論的なリンクと確率的なリンクを [!DNL Device Graph] 共有しています。 リンクの共有は、非常に強力な [!DNL Device Co-op] 要素です。 匿名の人に関連付けられた装置について各会員が知っている範囲を拡張します。ただし、その匿名の人の装置の少なくとも1つを見たことがある場合に限ります。

## Device Graphの概要の確認 {#section-7858e9f61b5644c981ffb53626fcc19d}

始める前に、の [!DNL Device Graph] 動作を確認します。 にデータを [!DNL Device Co-op] 送信するメンバ [!DNL Device Graph]。 このデータ [!DNL Device Graph] を使って、デバイス間の [決定論的なリンクと確率的なリンク](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) 。 参加者として、これらのリンクは、認証済みユーザー、他のユーザーおよびそのデバイスとの関係に関するインサイトを提供します。 [!DNL Device Co-op] 次の節で、これがどのように機能するかを見てみましょう。

## リンクの共有の例 {#section-cb410d827cf14f76bc9b0bd4d31ed767}

次の例は、Device Co-opでのリンク共有の機能を示しています。 この例では、ニュース会社と金融会社の2つの架空の会社があります。 両方の会社は、のメンバー [!DNL Device Co-op]です。 個人Aは、複数のデバイスにログオンしたり、各会社のWebサイトを閲覧したりする消費者です。

![](assets/share1.png)

個人Aは携帯電話とタブレットでニュースサイトに対して認証を行っているので、ニュース会社は消費者IDでユーザーを識別します。 そのIDは、暗号化ハッシュ [!DNL Device Graph] としてに送信されます。 金融会社はこれらのデバイスを以前に見たことがありますが、個人Aはサイトにログオンしていません。 したがって、金融会社は、これらのデバイスが相互に関連し合っているか、どのように関連しているか、または、個人Aとどのように関連付けられているかを知りません。

![](assets/share2.png)

消費者IDの暗号化ハッシュを与えると、は、これらのデバイスが互いに関連していて特定の人物が関連していることを [!DNL Device Graph] 認識する。 これらのサイトに参加しない会社への訪問は、別々のランダムなデバイスから来ている [!DNL Device Co-op] ように見えます。 いずれにしても、ハッシュ化されたID [!DNL Device Graph] を持つユーザーは、次の操作を実行します。

* 携帯電話とノートパソコンがリンクされていることを知っています。
* Finance会社が携帯電話とラップトップがリンクされているかどうかを知りたがっていることを認識します。

これらの条件を考慮して、では、ニュース会社用にこれらのデバイスを接続するリンクを金融会社と共有しています。 [!DNL Device Graph] このプロセス中、 [!DNL Device Graph] 重複は、協力メンバー間のリンクを共有します。

![](assets/share3.png)

この時点で、は、その役割を正常に [!DNL Device Graph] 実行しました。 ニュース会社と金融会社は共に、明確なアイデンティティを持っています。 ユーザーは、すべてのデバイスを通して、ユーザーAに正確に連絡できます。

## プライバシーとリンクの共有 {#section-7b566018b3304420a4b3e4c079826110}

ユーザーのプライバシーとメンバーのデータの整合性を維持することは、リンク共有プロセス全体で重要で [!DNL Device Co-op] す。 この顧客の識別およびリンクの共有プロセス中、次の操作は行わ [!DNL Device Graph] れませんでした。

* 金融会社に、リンクがニュース会社から来たことを伝えます。
* あるメンバーが使用する顧客IDを別の [!DNL Device Co-op] メンバーと共有します。
* モバイルデバイスとノートブックパソコンが共通のリンクを共有する情報以外の情報を入力します。

## 次の手順 {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

ID、リンク、およびリンク共有に関するドキュメントを読むと、データが内部的にどのようにアセンブルされるかをよく理解できるはずです。 [!DNL Device Graph] 次のステップとして、デバイス間のリンクをDevice Co-opメンバーに *`known device`* 提供するという概念について説明したドキュメントを見ることをお勧めします。 「 [既知のデバイス](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) 」および「 [不明なデバイス](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)」を参照してください。
