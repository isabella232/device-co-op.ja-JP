---
description: Adobe TargetアクティビティでDevice Co-opデータを使用する方法を説明します。
seo-description: Adobe TargetアクティビティでDevice Co-opデータを使用する方法を説明します。
seo-title: Target - A/Bテスト、多変量分析テスト、エクスペリエンスのターゲット設定
title: Target - A/Bテスト、多変量分析テスト、エクスペリエンスのターゲット設定
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Adobe TargetアクティビティでDevice Co-opデータを使用する方法を説明します。

Device Co-opデータは、A/Bテスト、多変量分析(MVT)テストおよびエクスペリエンスのターゲット設定アクティビティで使用できます。 The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

自動パーソナライゼーションアクティビティ、レコメンデーションアクティビティまたは [!DNL Adobe Analytics] をレポートソースとして使用するアクティビティ（A4T とも呼ばれる、[!DNL Target] と [!DNL Analytics] の統合）では、Device Co-op データは使用できません。

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. `at.js` は、すべてのバージョンを使用できます。詳しくは、「メンバーシップ要件」を [参照してくださ](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43)い。

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

マーケティング担当者は、訪問者が会社やブランドとやり取りをするために現在使用しているデバイスにかかわらず、各訪問者に最も関連性のあるエクスペリエンスを配信したいと考えます。

ユーザーは、会社のノートパソコン、家のコンピューター、iPad、iPhone、様々なブラウザーなど、多くの異なるデバイスから、同じ会社やブランドとやり取りします。特定のデバイスやブラウザーが、以前、別のデバイスやブラウザーでブランドとやり取りした同じ人物によって使用されていると認識できない場合、ターゲット設定された一貫したエクスペリエンスを配信することはできません。

Device Co-op を使用すると、ユーザーの様々なデバイスが同じユーザーによって使用されていると特定できます。そのユーザーが [!DNL Target] アクティビティ（いずれかのアクティビティまたはターゲット化されたコンテンツ）を含むページを表示すると、[!DNL Target] は、以前に別のデバイスでユーザーに提供したものと一貫したエクスペリエンスを提供します。

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

マーケティング担当者は、「訪問者」ではなく「人物」で [!DNL Target] アクティビティを分析したいと考えます。

各人は、複数のデバイスやブラウザーから同じ会社やブランドにアクセスする傾向がありますが、Device Co-op を使用しなければ、個々のデバイスやブラウザーは [!DNL Target] レポートで個別の「訪問者」と見なされます。

デバイス別やブラウザー別にレポートを作成すると、会社やブランドに接触した実際の人数よりも「訪問者」の数が多くカウントされます。複数のデバイスやブラウザーを使用していても 1 人の人物がコンバージョンをおこなうのは通常 1 回のみであるため、1 回のコンバージョンに対して多くの「訪問者」がカウントされれば、それだけコンバージョン率は実際より低くなります。

Device Co-op を使用すると、コンテンツ配信やレポートは「人物」レベルでおこなわれるので、レポートには、実際に何人がアクティビティを表示し、その内の何人がコンバージョンに達したかが正確に表示されます。

Device Co-op データがなくても、特定のアクティビティを勝者と判定することはできますが、Device Co-op があればレポートはより正確になるので、実際には別のアクティビティがより高いコンバージョン率を獲得し、その結果勝者になる可能性があります。

この概念について詳しくは、 [解析：人物指標](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)。

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

マーケティング担当者は、アクティビティごとに Device Co-op データを使用することを選択できます。以下のように、[!DNL Target] アクティビティによっては、Device Co-op データの使用が適切ではない場合があります。

* iPad のユーザーに適した専用のコンテンツ。

   最初に iPad で提供されるエクスペリエンスが、その後、家のコンピューターでも提供されることになります。

* 訪問者の限定されたセグメントでのみ利用可能な金利オファー。
* 特定の状態でのみ宣伝が許可された商品（例えば、ライセンスで制限された保険証券）。

マーケティング担当者が [!DNL Target] でオーディエンスを作成する場合、そのオーディエンスが Device Co-op データを有効にしたアクティビティにとって適切でない場合に警告が表示されます。適切なオーディエンスには、すべての訪問者、新しい訪問者および再訪問者が含まれます。
