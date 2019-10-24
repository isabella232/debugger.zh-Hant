---
description: 使用Adobe Debugger中的「解決方案」標籤
keywords: debugger;experience cloud除錯程式；chrome;extension；摘要；clear;requests；解決方案；解決方案；資訊；分析；目標；觀眾管理器；媒體優化器；amo;id服務
seo-description: 使用Adobe Debugger中的「解決方案」標籤
seo-title: Adobe Debugger中的解決方案標籤
title: 解決方案標籤
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 解決方案標籤{#solution-tabs}

按一下解決方案標籤，以檢視特定Adobe Experience cloud解決方案的結果。

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

「Analytics」標籤提供您 [Analytics實作的相](https://experiencecloud.adobe.com/resources/help/en_US/reference/) 關資訊。

**點擊**

依預設，對相同報表套裝進行的所有伺服器呼叫都會收合。

![](assets/analytics-hits.jpg)

**** 下載：以Excel試算表形式下載所有顯示報表套裝的相關資訊。

**** 清除所有請求：從Analytics檢視移除所有顯示的請求。 清除請求後，新請求會在發生時顯示。

按一下報表套裝ID以展開檢視：

![](assets/analytics-hits-expand.jpg)

此畫面顯示除錯程式開啟或清除請求後的所有請求。 預設參數會自動映射至好記名稱。 [如果您使用「連結分析](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) 」功能進行驗證，Prop和eVar變數可以對應至您的自訂好記名稱（例如，「prop1」可顯示為「使用者類型」）。 請求會依序從左至右顯示。

**** 下載：將對報表套裝提出的所有請求儲存為Excel試算表。

**** 清除請求：移除對此報表套裝提出的所有請求。 新請求會在發生時顯示。

**連結帳戶（舊版）**

按一 **[!UICONTROL Link Account]**&#x200B;下，然後輸入要求的資訊，將Analytics帳戶連結至除錯程式。

>[!NOTE]
>
>目前，此功能僅支援舊版Analytics使用者登入憑證。

![](assets/analytics-link-account.jpg)

**擷取後處理的點擊**

如果您想在處理規則執行後查看Analytics點擊的值，請啟用「擷取處理後的點擊」選項。 您必須登入Adobe Experience Cloud，此功能才能運作。

啟用此選項時，會將除錯參數新增至您的Analytics請求。 會像處理任何其他點擊一樣繼續處理點擊。 除錯程式會輪詢Analytics除錯API，以擷取任何具有原始點擊ID的點擊的後處理規則值。 後處理的點擊具有紫色背景，並會顯示在原始點擊旁。

對於大部分的Analytics實作，處理後規則資訊只需幾分鐘即可取得。 Analytics for Target(A4T)實作需要長得多的時間。

## Target {#section-988873ba5ede4317953193bd7ac5474c}

使用「目標」標籤可檢視 [Target請求](https://docs.adobe.com/content/help/en/target/using/target-home.html) 或 [](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) Mbox追蹤回應詳細資訊。

按一 **[!UICONTROL Requests]**&#x200B;下，然後展開環境以檢視有關Target的資訊。

![](assets/target-requests.jpg)

按一 **[!UICONTROL Clear All Requests]** 下以移除目前顯示的請求。 會在發出更多請求時顯示。

您也可以使用「目標」篩選器來啟 [用「MBox追蹤」以用於「目標」除錯](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html)。

您必須有一個開啟的Chrome標籤，該標籤已驗證至Experience cloud中，才能啟用Mbox追蹤。 啟用後，會顯示您的Adobe id使用者名稱。 展開您的使用者名稱，以公開與您有權存取的Experience cloud組織相關的Target用戶端代碼。 按一下您要啟用Mbox追蹤的用戶端代碼，並確認出現綠色核取標籤。 現在會顯示所有含有Mbox追蹤資訊的Target請求，依用戶端代碼分組。 若要探索Mbox追蹤資訊，請展開請求以查看標籤：

* [活動](https://docs.adobe.com/content/help/en/target/using/activities/activities.html) 「活動」標籤顯示與Target請求名稱關聯的所有活動，無論您是否符合活動的資格。 「符合的活動」是您符合資格的活動，其選件是在回應時傳遞的。 您可以展開活動名稱，以確認您所在的體驗，以及哪些對象和定位條件符合您的活動資格。 「評估活動」是評估的所有活動，無論您是否符合資格。 若要疑難排解您未符合「評估」但未符合「符合」活動資格的原因，請展開活動名稱並檢閱「不相符的觀眾」區段。

* 請求

   「 [Mbox追蹤」的「請求](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) 」標籤類似於主要的請求標籤。 除了請求標題外，您還可以檢視Target請求傳遞的所有參數。
* 描述檔

   展開「描述檔快照」區段，以 [查看在Target描述檔資料庫中](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) ，以訪客身分儲存的描述檔資訊。 所有in-mbox和指令碼描述檔都會在此公開，以及部分系統描述檔。 「狀態」列顯示在此請求範圍內更改的配置檔案，以及在請求進入配置檔案系統之前和之後更改的配置檔案值。
* Audience Manager

   「Audience Manager」標籤的「segmentId」和「cachedSegmentIds」區段會公開從Experience cloud共用至Target且您已符合其資格的 [觀眾ID](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) 。 這些對象可能是在Audience Manager、Analytics或People Core service的Audience Builder中建立的對象。 您可以在Audience manager使用者介面中尋找這些ID，以尋找對象名稱。

以下視訊顯示一般Target功能：

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=chi_hant)

下列視訊顯示Mbox追蹤：

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=chi_hant)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

使用「 [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) 」索引標籤來檢視事件的 [詳細資訊](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html)。 按一下組織以展開並顯示資訊。

![](assets/audience-manager.jpg)

按一 **[!UICONTROL Clear All Events]** 下以重設顯示的資訊。 新事件將在發生時顯示。

**ID同步**

ID同步是傳入、非同步資料傳輸程式的第一步。 在此步驟中，Audience manager和廠商會比較並比對其各自網站訪客的ID。

![](assets/aam-idsync.jpg)

如需詳 [細資訊，請參閱Audience manager產品檔案中](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) ，傳入資料傳輸的ID同步化。

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

使用Advertising cloud標籤來檢視Advertising cloud請求。

按一 **[!UICONTROL Requests]**&#x200B;下，然後展開環境以檢視Advertising cloud的相關資訊。

按一 **[!UICONTROL Clear All Requests]** 下以移除目前顯示的請求。 會在發出更多請求時顯示。

## Experience Cloud ID 服務 {#section-a96c32f8e63a4991abb296f6e8ea01cf}

使用「Experience Cloud ID服務」標籤來檢視 [Experience Cloud ID服務請求](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/) 。

按一 **[!UICONTROL Requests]**&#x200B;下，然後展開環境以檢視Experience Cloud ID服務的相關資訊。

按一 **[!UICONTROL Clear All Requests]** 下以移除目前顯示的請求。 會在發出更多請求時顯示。
