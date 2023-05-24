---
description: Adobe Targetアクティビティで Device Co-op データを使用する方法を説明します。
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - A/B テスト、多変量分析テスト、エクスペリエンスのターゲット設定
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target - A/B テスト、多変量分析テスト、エクスペリエンスのターゲット設定{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Adobe Targetアクティビティで Device Co-op データを使用する方法を説明します。

A/B テスト、多変量分析 (MVT) テスト、エクスペリエンスのターゲット設定アクティビティで、Device Co-op データを使用できます。 「 Device Co-op 」オプションは、 [!DNL Goals & Settings] ページの [!DNL Target] 3 ステップのガイドによるワークフロー

Device Co-op データは、Automated Personalizationアクティビティ、Recommendation アクティビティ、または [!DNL Adobe Analytics] レポートソースとして ( [!DNL Target] および [!DNL Analytics] 統合（A4T とも呼ばれます）。

>[!NOTE]
>
>必要なバージョンの `mbox.js`. 任意のバージョンの `at.js`. 詳しくは、 [メンバーシップ要件](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## デバイスを問わず、関連するコンテンツを配信 {#section-bba8d41e96914c82a6d267a54f776354}

マーケターは、訪問者が現在会社やブランドとやり取りする際に使用しているデバイスに関係なく、各訪問者に最も関連性の高いエクスペリエンスを提供したいと考えています。

ユーザーは、様々なデバイスから同じ会社またはブランドを操作します。仕事用のノートパソコン、ホームコンピューター、iPad、iPhone、様々なブラウザーなど。 別のデバイスやブラウザーでブランドとのやり取りを行った同じ人物が、各特定のデバイスやブラウザーを使用していることが認識できない場合は、その人物に対して一貫したターゲットエクスペリエンスを提供できません。

Device Co-op を使用すると、ユーザーの様々なデバイスを、同じユーザーが使用していると識別できます。 そのユーザーが [!DNL Target] アクティビティ — アクティビティまたはターゲットコンテンツ — [!DNL Target] では、別のデバイスでも確実に同じエクスペリエンスを表示できます。

## 訪問者ではなく担当者による Target アクティビティの分析 {#section-c25cf4f8483942d7836d60756235e62c}

マーケターが分析 [!DNL Target] アクティビティを「訪問者」ではなく「人」で指定する。

各ユーザーは、デバイスやブラウザーをまたいで同じ会社やブランドを操作している可能性が高くなりますが、Device Co-op を使用しない場合、個々のデバイスやブラウザーは、 [!DNL Target] レポート。

個々のデバイスやブラウザーでレポートを表示すると、会社やブランドとやり取りするユーザーの数よりも、「訪問者」の数が多くなります。 これらのユーザーは通常、様々なデバイスやブラウザーで 1 回だけコンバージョンをおこなうので、1 回のコンバージョンでカウントされる「訪問者」の数が増えるので、実際よりもコンバージョン率が低くなります。

Device Co-op を使用すると、コンテンツ配信とレポートは「人」レベルでおこなわれるので、レポートは、アクティビティを閲覧した実際の人数とコンバージョンに至った人数を正確に示します。

Device Co-op のデータがない場合は、特定のアクティビティが勝者であると判断することができます。ただし、Device Co-op ではレポートの精度が高いので、別のアクティビティのコンバージョン率が高く、その結果、勝者になる場合があります。

この概念について詳しくは、 [分析：人物指標](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## アクティビティごとに Device Co-op データを使用 {#section-fb46fae482654023abb1a1e26564db9a}

マーケターは、アクティビティごとに Device Co-op データを使用するよう選択できます。 特定 [!DNL Target] アクティビティは、次のような Device Co-op データには適さない場合があります。

* iPadのユーザーに適した特定のコンテンツ。

   iPadで初めてエクスペリエンスを表示したユーザーは、引き続き自宅のコンピューターでそのエクスペリエンスを表示します。

* 訪問者の厳密なセグメントに対してのみ利用できる金利オファー。
* 特定の状態でのみ広告が許可される製品（例えば、ライセンス制限のある保険証券）。

マーケターが [!DNL Target]に設定されている場合、オーディエンスが Device Co-op のデータが有効なアクティビティに適していない場合に警告が表示されます。 適切なオーディエンスには、すべての訪問者、新規訪問者、再訪問者が含まれます。
