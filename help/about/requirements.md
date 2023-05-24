---
description: Device Co-op の使用を開始する前に、お客様の会社がこれらの最小基準を満たしている必要があります。
seo-description: Your company must meet these minimum standards before you can start using the Experience Cloud Device Co-op.
seo-title: Membership requirements
title: メンバーシップ要件
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
exl-id: 923ce9c5-7716-4c5a-95f2-05a81a05c9cf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 17%

---

# メンバーシップ要件{#membership-requirements}

Device Co-op の使用を開始する前に、お客様の会社がこれらの最小基準を満たしている必要があります。

## 要件 {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

お問い合わせ [!DNL Adobe representative to get started]. Adobeは、Device Co-op への見込みExperience Cloudの参加が適用法に違反するとAdobeが判断した場合、Device Device Co-op への見込み顧客メンバーシップを拒否する権利を留保します。または (2)Adobeまたはその顧客のセキュリティや操作に重大なリスクを引き起こす。

## Experience Cloud要件 {#section-76218a50385d43e6b9323e49f598394a}

を有効にする必要があります。 [!DNL Adobe Experience Cloud] 次のソリューションおよびサービスを使用して co-op に参加します。

**ソリューション**

申請者は、次のうち少なくとも 1 つを使用する必要があります [!DNL Adobe]ソリューション：

* [Analytics](http://www.adobe.com/jp/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/jp/marketing-cloud/data-management-platform.html)
* [Media Manager](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/jp/marketing-cloud/testing-targeting.html)

**コアサービス**

申請者は、 [Experience CloudID サービス](https://docs.adobe.com/content/help/ja-JP/id-service/using/home.html).

## Adobeコードライブラリの要件 {#section-931a3fca1ce54afd90b88ba032e75f05}

次の表に、様々なコードライブラリまたは SDK で使用される最小バージョンを示します [!DNL Experience Cloud] ソリューションとサービス このコードのいずれかを使用し、Device Co-op に参加する場合は、次の最小要件を満たしていることを確認してください。

>[!TIP]
>
>ベストプラクティスとして、必要最小限ではなく、最新のコードバージョンを使用することをお勧めします。

**AppMeasurement (Flash)**

バージョン 4.1 が必要です。詳しくは、 [Flash、FlexおよびAIR向けの AppMeasurement](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

バージョン 1.5.4 が必要です。詳しくは、 [Flash、FlexおよびAIR向けの AppMeasurement](https://docs.adobe.com/content/help/ja-JP/analytics/implementation/js/migrate-from-hcode.html).

**モバイル SDK**

モバイル SDK の最小要件：

* Android バージョン 4.8.3.
* iOS バージョン 4.8.5.

に対して SDK コードを有効にする必要があります。 [!DNL Experience Cloud] ID サービス。 の各アプリ用の最新 SDK コードを有効にして、ダウンロードします [AdobeMobile Services](https://mobilemarketing.adobe.com/) アカウント 詳しくは、 [SDK 訪問者 ID サービスの設定](https://docs.adobe.com/content/help/ja-JP/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

SDK ごとに、適切な `visitorSyncIdentifier` 必要に応じてメソッドを使用できます。 参照：

* [AndroidExperience CloudID サービスメソッド](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOSExperience CloudID サービスメソッド](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

バージョン 1.5.4 が必要です。

[!DNL Analytics] のお客様は、 VisitorAPI.js ライブラリを [!DNL Code Manager]. JavaScript（新規）または JavaScript（レガシー）ファイルにあります。 連絡先 [カスタマーケア](https://helpx.adobe.com/jp/marketing-cloud/contact-support.html) アクセス権がない場合 [!DNL Code Manager].

**ターゲットライブラリ**

次のいずれかが必要です [!DNL Target] JavaScript ライブラリ：

* at.js （任意のバージョン）
* mbox.js バージョン 58 以降
