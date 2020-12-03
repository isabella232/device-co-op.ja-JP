---
description: 会社Device Co-opを使用して開始を行うには、Experience Cloudがこれらの最小基準を満たしている必要があります。
seo-description: 会社Device Co-opを使用して開始を行うには、Experience Cloudがこれらの最小基準を満たしている必要があります。
seo-title: メンバーシップ要件
title: メンバーシップ要件
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 15%

---


# Membership requirements{#membership-requirements}

会社Device Co-opを使用して開始を行うには、Experience Cloudがこれらの最小基準を満たしている必要があります。

## 要件 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

お話し [!DNL Adobe representative to get started]。 Adobeの担当者がいない場合は、 [Device Co-opメンバーシップポータルにアクセスし](http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html) 、オンラインフォームに記入します。

Adobeは、見込み客のDevice Co-opへの参加が(1)適用法に違反するとAdobeが判断した場合、Experience CloudDevice Co-opへの参加を見込み客に拒否する権利を留保します。(2)Adobe又はその顧客の安全又は運用に重大なリスクを与える。

## Experience Cloud要件 {#section-76218a50385d43e6b9323e49f598394a}

Co-opに参加するには、を有効にし、次のソリューション [!DNL Adobe Experience Cloud] とサービスを使用する必要があります。

**ソリューション**

申込者は、次のいずれかの [!DNL Adobe]解決策を使用する必要があります。

* [Analytics](http://www.adobe.com/jp/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/jp/marketing-cloud/data-management-platform.html)
* [Media Manager](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/jp/marketing-cloud/testing-targeting.html)

**コアサービス**

Applicants must implement the [Experience Cloud ID Service](https://docs.adobe.com/content/help/ja-JP/id-service/using/home.html).

## Adobeコードライブラリの要件 {#section-931a3fca1ce54afd90b88ba032e75f05}

次の表に、様々なソリューションやサービスで使用されるコードライブラリまたはSDKの最小バージョンを示し [!DNL Experience Cloud] ます。 このコードのいずれかを使用し、Device Co-opに参加する場合は、以下の最小要件を満たしていることを確認してください。

>[!TIP]
>
>ベストプラクティスとして、必要な最小コードではなく、最新のコードバージョンを使用することをお勧めします。

**AppMeasurement(Flash)**

バージョン4.1が必要です。AppMeasurement forFlash、 [Flex、AIRを参照してください](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md)。

**AppMeasurement(JavaScript)**

バージョン1.5.4が必要です。 [AppMeasurement forFlash、Flex、AIRを参照してください](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/js/migrate-from-hcode.html)。

**モバイル SDK**

モバイルSDKの最小要件：

* Android バージョン 4.8.3.
* iOS バージョン 4.8.5.

Your SDK code must be enabled for the [!DNL Experience Cloud] ID service. [AdobeのMobile Servicesアカウントで、各アプリの最新のSDKコードを有効にしてダウンロードします](https://mobilemarketing.adobe.com/) 。 See [Configure SDK Visitor ID Service Options](https://docs.adobe.com/content/help/ja-JP/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

SDKごとに、ニーズに合った適切な `visitorSyncIdentifier` 方法を使用します。 以下を参照してください。

* [AndroidExperience CloudIDサービスのメソッド](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOSExperience CloudIDサービスのメソッド](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

バージョン1.5.4が必要です。

[!DNL Analytics] お客様は、からVisitorAPI.jsライブラリをダウンロードでき [!DNL Code Manager]ます。 このファイルは、JavaScript（新規）ファイルまたはJavaScript（レガシー）ファイルにあります。 へのアクセス権がない場合は、 [カスタマーケア](https://helpx.adobe.com/jp/marketing-cloud/contact-support.html) にお問い合わせくだ [!DNL Code Manager]さい。

**ターゲットライブラリ**

次のJavaScriptライブラリのいずれかが必要です。 [!DNL Target]

* at.js（任意のバージョン）
* mbox.jsバージョン58以降

