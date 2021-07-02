---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op；提供終了
title: Device Co-opの提供終了に関するFAQ
description: Device Co-opの提供終了プランについて説明します。
exl-id: 015ba95c-0c8d-415e-969c-b8670494de98
source-git-commit: c19e8425d5d6c2498186c19929907d2ee5327b31
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 4%

---

# Device Co-opの提供終了に関するFAQ

このドキュメントでは、Adobe Experience Cloud Device Co-opの提供終了(EOL)プランに関するよくある質問に対する回答を示します。 この計画が実施されると、Adobeは、[Experience Cloudリリースノート](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=ja)と[Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html)に詳細な通知を提供します。

## FAQ

以下は、[!DNL Device Co-op] EOL計画に関するよくある質問に対する回答のリストです。

## [!DNL Device Co-op]が廃止されるのはなぜですか？

AdTech環境での今後の変更は、今後数年間で[!DNL Device Co-op]が古いソリューションになると予想されます。 [!DNL Device Co-op] は主にサードパーティCookieで構成されてお [!DNL Google's] り、2022年までにサードパーティCookieをブロックする [!DNL Google Chrome] とのお知らせにより、の効果が低下し [!DNL Device Co-op]ます。[!DNL Chrome] には、ブラウザー市場でのシェアの約65%と、その他の主要なブラウザーでは、既にサードパーティcookieのブロック機能が実装されています。[!DNL Chrome]がサードパーティCookieをブロックすると、サードパーティCookieの大部分はブロックされ、[!DNL Device Co-op]は古くなります。

## Adobeが[!DNL Device Co-op]サインアップを終了する理由

サインアップは、サードパーティCookieに関する業界の変更が今後おこなわれるので、顧客の期待に応えないリスクを防ぐために終わります。 [!DNL Device Co-op] サービスから価値を引き出すのに数ヶ月かかり、さらに数ヶ月かかります。この時点でこれ以上サインアップすると、ブランドで[!DNL Device Co-op]の完全な値が得られない可能性があります。

## 新規顧客は新規登録できますか？

2021年6月11日以降、Adobeは[!DNL Device Co-op]への新規登録を受け付けなくなります。

## 既存の契約は更新されていますか。

2021年6月11日以降、Adobeは[!DNL Device Co-op]契約を更新しなくなります。 [!DNL Device Co-op]サービスを引き続き使用する場合は、プログラムが終了するまで、現在のライセンス条項に従って引き続き使用することができます。

## [!DNL Device Co-op]プログラムの正確な終了日は？

[!DNL Device Co-op]プログラムは2022年に終了します。 特定のタイミングと日付は、 [!DNL Google]がサードパーティCookieのブロックを開始するタイミングによって異なります。

## Device Co-opの提供終了によって影響を受けるアプリケーションはどれですか。

以下のアプリケーションは、[!DNL Device Co-op]提供終了の手順の影響を受けます。

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## [!DNL Device Co-op]の代替手段として、どのような選択肢がありますか？

### [!DNL Analytics]

[!DNL Analytics] [クロスデバイス分析(CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html?lang=ja)機能は、Adobe Experience Platform IDサービス[プライベートグラフ](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en)と[フィールドベースのステッチ](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en)の両方をサポートしているので、使用できます。

### [!DNL Audience Manager]

[!DNL Audience Manager] は、やを含むサードパーティデバイスグラフパートナーとの統合を維持しま [!DNL LiveRamp] す [!DNL Tapad]。ただし、を活用するには、グラフパートナーとの商業関係を直接確立する必要があり [!DNL Audience Manager]ます。

### [!DNL Real-time Customer Data Platform]

現在の[!DNL Audience Manager Data Management Platform](DMP)を変更する予定はありません。 ただし、サードパーティCookieの廃止により、ほとんどのDMPユーザーにとってスケール上の課題が生じる可能性があります。 お客様がデータ管理の慣行を発展させるために、Adobeでは、来年に制限を受けるIDに対する依存関係を減らすことを推奨しています。 マーケティングチームは、個人を特定できる情報(PII)を含む永続的な識別子に焦点を当てたファーストパーティのデータ戦略を構築する必要があります。PIIは[!DNL Real-time Customer Data Platform]（リアルタイムCDP）で解決できます。

[!DNL Real-time CDP] は、オーディエンス作成に使用できる識別子のセットをPIIを含めるように拡張することで、サードパーティCookieとデバイスIDとの依存関係を減らします。[!DNL Real-time CDP]の基礎となるのはリアルタイム顧客プロファイルで、個人の属性データと行動データをリアルタイムで統合し、マーケターは特許取得済みのデータガバナンスコントロールを使用して豊富なオーディエンスセグメントを作成できます。 [!DNL Audience Manager]と同様に、[!DNL Real-time CDP]はインサイトやパーソナライゼーションの使用例を強化し、より詳細な個人レベルのインサイトを生み出し、有料メディア、ソーシャルメディア、電子メール、顧客システムなど、広告技術やマーケティング技術にまたがる幅広い宛先にオーディエンスをアクティブ化できます。

[!DNL Real-time CDP] また、には [Adobe Experience Platform Segment Match（アルファ）](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)へのアクセスも含まれます。これにより、ブランドはパートナーシップを通じて自社のファーストパーティデータセットを拡張し、インサイトとパーソナライゼーションを向上させることができます。

### [!DNL Target]

[!DNL Target]には、現在、[!DNL Target]がAdobeの顧客IDと同様に機能する、決定論的なクロスデバイスIDステッチ機能(`mbox3rdPartyId`)を提供しているので、に代替手段はありません。 この機能を使用すると、[!DNL Target]のお客様は、インバウンドチャネルでおこなわれる[!DNL Target]テストとパーソナライゼーション全体で、プロファイルとアクティビティのパーティシペーションを結合できます。

### Adobe Advertising Cloud

[!DNL Advertising Cloud] をご利用のお客様は、クロスデバイスオーディエンスのタ [!DNL Device Co-op] ーゲティングと測定にを使用できなくなります。[!DNL Advertising Cloud]では、[!DNL LiveRamp]とのAdobeの[!DNL Device Graph]パートナーシップを活用して、[!DNL LiveRamp’s]の能力と規模に応じて、引き続きこれらの機能を実行できます。 [!DNL Device Co-op]を使用しているキャンペーンを終了することを許可して、[!DNL LiveRamp]デバイスグラフプロバイダーに切り替えるか、ユーザーベースのターゲティングを利用しなくする必要があります。

## cookieのない将来に備えるのに役立つ既存の機能と実装は何ですか？

既存の訪問者IDサービスの実装により、Analyticsの[CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html)が強化されます。 既存の宣言済みIDがハッシュ化された電子メールである場合は、これを使用して次の機能を強化できます。

- [!DNL Audience Manager] [People-Based Destinations](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html?lang=ja).
- [Experience Platformセグメントの一致（アルファ） ](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en)を参照してください。

## [!DNL Device Co-op]からデータを保持することはできますか？

[!DNL Audience Manager]と[!DNL Advertising Cloud]ユーザーの場合、[!DNL Device Co-op]のデータをサードパーティのグラフに転送することはできません。 [!DNL Device Co-op] データは、CDAを使用し、フィールドベ [!DNL Analytics Ultimate] ースのステッチに切り替え [!DNL Device Co-op] る場合にのみ移行されます。その他のすべてのソリューションは、データを移行しません。

## 他の機能の採用は必須ですか？

他のAdobe機能の採用は必須ではありませんが、[!DNL Device Co-op]の廃止に先立って、他の機能の実装を可能な限り早く開始し、時間と適切な調整を行う必要があります。

## 私が選択した場合、いつまでに代替ソリューションを採用する必要がありますか？

その他の機能の採用は必須ではありません。 [!DNL Device Co-op]が対処した使用例のアドレス指定を続行する場合にのみお勧めします。 他の機能を採用する場合は、[!DNL Device Co-op]プログラムが終了する前に、2022年までに（発表予定の正確なタイミングで）採用する必要があります。

## 養子縁組にはどのくらい時間がかかりますか？

これは、機能によって異なります。 例えば、クロスデバイス分析と[!DNL Device Co-op]を使用しているAnalytics Ultimateのお客様が、リアルタイムプライベートデバイスグラフまたはフィールドベースのステッチに移行する必要がある場合、導入にはしばらく時間がかかります。
