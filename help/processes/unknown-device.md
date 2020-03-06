---
description: ある人物がブランドとのやり取りに使用したことのないデバイスを持っている場合、そのデバイスは未知のデバイスと呼ばれます。
seo-description: ある人物がブランドとのやり取りに使用したことのないデバイスを持っている場合、そのデバイスは未知のデバイスと呼ばれます。
seo-title: 不明なデバイス
title: 不明なデバイス
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Unknown devices{#unknown-devices}

ある人物がブランドとのやり取りに使用したことのないデバイスを持っている場合、そのデバイスは未知のデバイスと呼ばれます。

## Unknown device categories {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

デバイスは、いくつかの条件下で「未知」であると見なされます。これには、以下が含まれます。

* **ファーストパーティの他の メンバーへの訪問：**&#x200B;他の [!DNL Device Co-op]Device Co-op メンバーサイトへの訪問やデバイスへの広告掲載だけで、デバイスが既知のものとなることはありません。

* **追跡されていない広告インベントリ：**&#x200B;広告インベントリが利用可能な状態ではあるものの、まだ提供されていない、または取り込まれていない場合、デバイスは既知のものにはなりません。
* **消費者のオプトアウト：**&#x200B;消費者の要求を尊重するために、オプトアウトされたデバイスは、既知のデバイスとは見なされません。

既知のデバイスとは異なり、未知のデバイスが他のデバイスにリンクされたり、個人に関連付けられたりすることはありません。

## Rules for setting known/unknown status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

The [!DNL Device Graph] tries to be inclusive as possible when classifying devices as known compared to unknown. 未知／既知のステータスの判定を支援するルールは、以下に示す優先順位（1 が最高）で機能します。

* **ルール 1：**&#x200B;デバイスがオプトアウトされているかどうか。該当する場合、デバイスは未知になります。
* **ルール 2：**&#x200B;デバイスが任意の方法で把握されているかどうか。**&#x200B;該当する場合、デバイスは既知になります。

* **ルール3:**前のバージョンが適用されない場合、デバイスは不明です。

>[!MORELIKETHIS]
>
>* [既知のデバイス](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

