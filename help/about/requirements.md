---
description: 会社Device Co-opを使用して開始を行うには、Experience Cloudがこれらの最小基準を満たしている必要があります。
seo-description: 会社Device Co-opを使用して開始を行うには、Experience Cloudがこれらの最小基準を満たしている必要があります。
seo-title: メンバーシップ要件
title: メンバーシップ要件
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 1ab7be570ea63645c6d6065341d31bf170f79715
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 16%

---


# メンバーシップ要件{#membership-requirements}

会社Device Co-opを使用して開始を行うには、Experience Cloudがこれらの最小基準を満たしている必要があります。

## 要件 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

[!DNL Adobe representative to get started]にお問い合わせください。 Adobeは、見込み客のDevice Co-opへの参加が(1)適用法に違反するとAdobeが判断した場合、Experience CloudDevice Co-opへの参加を見込み客に拒否する権利を留保します。(2)Adobe又はその顧客の安全又は運用に重大なリスクを与える。

## Experience Cloud要件{#section-76218a50385d43e6b9323e49f598394a}

[!DNL Adobe Experience Cloud]を有効にし、次のソリューションとサービスを使用してco-opに参加する必要があります。

**ソリューション**

申込者は、次の[!DNL Adobe]ソリューションの少なくとも1つを使用する必要があります。

* [Analytics](http://www.adobe.com/jp/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/jp/marketing-cloud/data-management-platform.html)
* [Media Manager](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/marketing-cloud/testing-targeting.html)

**コアサービス**

申込者は、[Experience CloudIDサービス](https://docs.adobe.com/content/help/ja-JP/id-service/using/home.html)を導入する必要があります。

## Adobeコードライブラリの要件{#section-931a3fca1ce54afd90b88ba032e75f05}

次の表に、様々な[!DNL Experience Cloud]ソリューションおよびサービスで使用されるコードライブラリまたはSDKの最小バージョンを示します。 このコードのいずれかを使用し、Device Co-opに参加する場合は、以下の最小要件を満たしていることを確認してください。

>[!TIP]
>
>ベストプラクティスとして、必要な最小コードではなく、最新のコードバージョンを使用することをお勧めします。

**AppMeasurement(Flash)**

バージョン4.1が必要です。[AppMeasurement forFlash、Flex、AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md)を参照してください。

**AppMeasurement(JavaScript)**

バージョン1.5.4が必要です。[AppMeasurement forFlash、Flex、AIR](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/js/migrate-from-hcode.html)を参照してください。

**モバイル SDK**

モバイルSDKの最小要件：

* Android バージョン 4.8.3.
* iOS バージョン 4.8.5.

[!DNL Experience Cloud] IDサービスに対してSDKコードを有効にする必要があります。 [AdobeMobile Services](https://mobilemarketing.adobe.com/)アカウントの各アプリ用に、最新のSDKコードを有効にしてダウンロードします。 「[SDK訪問者IDサービスの設定](https://docs.adobe.com/content/help/ja-JP/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html)」を参照してください。

SDKごとに、ニーズに合った適切な`visitorSyncIdentifier`メソッドを使用します。 以下を参照してください。

* [AndroidExperience CloudIDサービスのメソッド](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOSExperience CloudIDサービスのメソッド](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

バージョン1.5.4が必要です。

[!DNL Analytics] お客様は、からVisitorAPI.jsライブラリをダウンロードでき [!DNL Code Manager]ます。このファイルは、JavaScript（新規）ファイルまたはJavaScript（レガシー）ファイルにあります。 [カスタマーケア](https://helpx.adobe.com/jp/marketing-cloud/contact-support.html)にお問い合わせください（お客様が[!DNL Code Manager]にアクセスできない場合）。

**ターゲットライブラリ**

次の[!DNL Target] JavaScriptライブラリのいずれかが必要です。

* at.js（任意のバージョン）
* mbox.jsバージョン58以降

