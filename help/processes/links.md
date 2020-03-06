---
description: Device Graphでの決定論的データと確率的データの分析方法により、デバイスを相互にリンクするマップを作成します。
seo-description: Device Graphでの決定論的データと確率的データの分析方法により、デバイスを相互にリンクするマップを作成します。
seo-title: 決定論的リンクと確率的リンク
title: 決定論的リンクと確率的リンク
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Deterministic and probabilistic links{#deterministic-and-probabilistic-links}

Device Graphでの決定論的データと確率的データの分析方法により、デバイスを相互にリンクするマップを作成します。

In the [!DNL Device Graph], internal processes build an identity hierarchy that maps devices and connects them to individual, anonymized people. グラフの出力には、ターゲット設定に使用できるデバイス間のリンクと、一部のExperience Cloudソリューションで公開されたデータが含まれます。 The Adobe solutions that work with [!DNL Device Graph] data include Analytics, Audience Manager, Media Optimizer, and Target.

The [!DNL Device Graph] analyzes deterministic and probabilistic data to build a map that links devices together. 決定論的データは、ハッシュ化されたログイン情報に基づいてデバイスどうしをリンクします。確率論的データは、IP アドレスや他のメタデータなどの情報に基づいてデバイスどうしをリンクします。The [!DNL Device Graph] associates the linked device clusters to an anonymous individual person These connections let digital marketers reach people instead of devices. In the [!DNL Device Graph], the owner of a device is the anonymous representation of a real-life person. 決定論的リンクと確率論的リンクの両方が、ユーザー ID の構造を構築するのに役立ちます。

>[!NOTE]
>
>Adobe Experience Cloud Device Co-opでは、デバイス、人、IDなどの用語 *は*、特 *定の意*&#x200B;味を持 *ち* ます。 For example, *device* can refer to physical hardware such as a phone or tablet and the applications that run on that hardware. 定義については、[用語集](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c)を参照してください。

## What are links? {#section-2df4c6f01eba49369993146df0661f13}

ここで言うリンクとは、[!DNL Experience Cloud] デバイスグラフのコンテキストで使用されるリンクを指します。このコンテキストでは、リンクは、デバイス間の物理的な接続ではありません。様々なデバイスを 1 人の匿名の人物に結び付ける関連付けを指します。例えば、携帯電話とデスクトップブラウザーがあるとします。デバイスグラフによってこれらのデバイスが 1 人の匿名の人物によって使用されていると判定されると、電話とブラウザーは「リンク」されます。以下で説明するとおり、デバイスグラフは、決定論的リンクと確率論的リンクを使用して ID を作成します。そして、デバイスグラフでは、デバイスの所有者は、実在の人物の匿名表現です。

## Deterministic links {#section-33d41e828a674b398e36fe63da20ac09}

決定論的リンクは、認証イベント（デバイスからサイトへのログインアクションなど）に基づいてデバイスを個人に関連付けます。このアクションにより、消費者 ID として知られる、匿名化された ID が作成されます。決定論的リンクがどのように機能するかを見てみましょう。この例では、人物 A はモバイルデバイス上のアプリを使用してニュースサイトにログインします。その日の後になって、人物 A は再度ログインしますが、今回はノートパソコンのブラウザーを使用します。

![](assets/link1.png)

ログイン情報に基づいて、デバイスグラフは、以下のように動作します。

* 携帯電話／アプリとノートパソコン／ブラウザーのデバイスの組み合わせを使用してニュースサイトに認証した人物 A を把握します。
* これらのデバイスを 人物 A にリンクします。
* 匿名の人物に関連付けられたリンク済みデバイスに基づいて ID を作成します。

![](assets/link2.png)

>[!NOTE]
>
>またはは、こ [!DNL Adobe Experience Cloud Device Co-op] のデー [!DNL Device Graph] タの実際の認証情報や個人情報(PII)を受け取ることはありません。 Members of the [!DNL Experience Cloud Device Co-op], pass in cryptographically hashed, unique consumer IDs to the Device Graph. 消費者 ID は、グラフ内で認証済みユーザーを示し、消費者のプライバシーを保護します。

## Probabilistic links {#section-5f5aa755da984f9d851f7cb380262998}

確率論的リンクは、以下の特徴およびメタデータに基づいて、アルゴリズムでデバイスを個人に結び付けます。

* ブラウジング行動
* IP アドレス
* オペレーティングシステム
* IDFA および GAID 識別子

確率論的リンクがどのように機能するかを見てみましょう。この例では、人物 A がタブレットでニュースサイトを閲覧し、その後、デスクトップコンピューターから閲覧します。ブラウジングの間、人物 A は、ニュースサイトにログインしません。それぞれの訪問の間、タブレットとデスクトップは同じ IP アドレスを共有します。

![](assets/link3.png)

Based on this information, the [!DNL Device Graph] evaluates IP address sharing patterns between both devices and links these devices together if the results suggest they belong to Person A. The end result is hierarchy of identity derived from algorithmic probability calculations.

![](assets/link4.png)

この例では、デバイスグラフは、両方のデバイスが同じニュースサイトへのアクセスに使用された後、それらをリンクします。ただし、デバイスがリンクされるには、同じサイトで確認される必要はありません。この点を説明するために、この例の各デバイスがまったく異なる Web サイトを訪問したと仮定します。The [!DNL Device Graph] algorithm can still make a probabilistic link based on their shared IP address and from an analysis of other data. この処理は、確率論的リンクを [!DNL Experience Cloud] Device Co-op のメンバーにとってパワフルなものにするのに役立ちます。

## Both types of data provide value {#section-43d22d8c10634edcb261e7bda6fdf323}

決定論的データと確率論的データは、互いに補完します。決定論的データのみを含むデバイスグラフは、人物を識別できる範囲が限定されます。認証がないと、デバイスグラフは、サイトを参照する他のデバイスおよび人物について判別できません。確率論的データは、それらのつながりを構築でき、未認証デバイス、人物、家族へのリーチに役立ちます。

ただし、決定論的データも重要です。例えば、確率論的シグナルが数多くあり、重複している場所（例：喫茶店、図書館、空港など）で生成された、間違ったリンクを削除することで、確率論的判定を向上できます。

両方のタイプのデータがあれば、デバイスグラフは、どちらかだけの場合に比べて、より包括的に人物を識別できます。

![](assets/link5.png)

