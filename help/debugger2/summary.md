---
description: Experience Cloud除錯程式摘要畫面
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: Experience Cloud除錯程式摘要畫面
seo-title: 摘要畫面
title: 摘要畫面
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: tm+mt
source-wordcount: '948'
ht-degree: 98%

---


# 摘要畫面{#summary-screen}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 目前仍在測試階段。文件和功能可能會有所變更。

若要執行 Adobe Experience Platform Debugger，請按一下瀏覽器列上的圖示，然後在瀏覽器中開啟您要檢查的頁面。

![](assets/start-icon.jpg)

Adobe Experience Platform Debugger 的「摘要」畫面會隨即顯示。

![](assets/summary.jpg)

此畫面會顯示各種 Adobe Experience Cloud 解決方案的相關資訊。顯示的資訊會依解決方案而異，但通常包括解決方案程式庫和版本 (例如「AppMeasurement 2.9 版」) 和帳戶 ID (例如 Analytics 報表套裝 ID、Target 用戶端代碼、Audience Manager 合作夥伴 ID 等) 的相關資訊。

## Debugger 中顯示的資訊

以下是 Debugger 會針對各個解決方案顯示的資訊：

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>報表套裝 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/zh_TW/reference/report_suites_admin.html" format="html" scope="external">報表套裝</a>可全面而獨立地定義針對選定網站、一組網站或網頁子集的報告。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>針對頁面定義的 <a href="https://experiencecloud.adobe.com/resources/help/zh_TW/sc/implement/appmeasure_mjs.html" format="html" scope="external">AppMeasurement</a> 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>訪客版本 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/zh_TW/sc/implement/visid_analytics.html" format="html" scope="external">訪客 ID</a> 程式庫的版本。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>頁面名稱 </p> </td> 
   <td colname="col2"> <p>傳送至 Analytics 的 <a href="https://experiencecloud.adobe.com/resources/help/zh_TW/sc/implement/pageName.html" format="html" scope="external">pageName</a> 變數，包含網站的好記名稱。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>模組 </p> </td> 
   <td colname="col2"> <p>Adobe Analytics 載入的模組 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>合作夥伴 </p> </td> 
   <td colname="col2"> <p>DIL 例項的<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external">合作夥伴名稱</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>DIL 例項的<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external">版本號碼</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>與 DIL 例項相關聯的<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external">不重複的使用者 ID</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>名稱 </p> </td> 
   <td colname="col2"> <p>Adobe Launch <a href="https://docs.adobe.com/content/help/zh-Hant/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">屬性</a>名稱 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>Turbine 版本</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>建置日期 </p> </td> 
   <td colname="col2"> <p>Launch<a href="https://docs.adobe.com/content/help/zh-Hant/launch/using/reference/publish/libraries.html" format="https" scope="external"> 程式庫</a>建置日期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>環境 </p> </td> 
   <td colname="col2"> <p>Launch 程式庫使用的<a href="https://docs.adobe.com/content/help/zh-Hant/launch/using/reference/publish/environments.html" format="https" scope="external">環境</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>擴充功能 </p> </td> 
   <td colname="col2"> <p>頁面所使用的擴充功能 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Web SDK**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>程式庫版本 </p> </td> 
   <td colname="col2"> <p>AEB Web SDK <a href="https://docs.adobe.com/content/help/zh-Hant/launch/using/extensions-ref/adobe-extension/aep-extension/overview.html" format="html" scope="external">程式庫版本</a>編號 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>命名空間</p> </td> 
   <td colname="col2"> <p>擴充功能的識別名稱</p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>屬性 ID </p> </td> 
   <td colname="col2"> <p>擴充功能中指定的 Launch 屬性名稱 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>邊緣網域 </p> </td> 
   <td colname="col2"> <p>Adobe Experience Platform 擴充功能傳送及接收資料的網域 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>IMS 組織 ID </p> </td> 
   <td colname="col2"> <p>您要在 Adobe 傳送資料的組織 (如同擴充功能中所指定) </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>啟用記錄功能 </p> </td> 
   <td colname="col2"> <p>指定是否已為此屬性啟用記錄功能</p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID 服務**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience Cloud 組織 ID </p> </td> 
   <td colname="col2"> <p>您的<a href="https://experiencecloud.adobe.com/resources/help/zh_TW/mcvid/" format="https" scope="external">組織 ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p><a href="https://experiencecloud.adobe.com/resources/help/zh_TW/sc/implement/visid_analytics.html" format="html" scope="external">訪客 ID</a> 程式庫版本 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>用戶端代碼 </p> </td> 
   <td colname="col2"> <p>您的 Target <a href="https://docs.adobe.com/content/help/zh-Hant/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external">用戶端代碼</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>您目前的 <a href="https://docs.adobe.com/content/help/zh-Hant/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external">at.js</a> 或 mbox.js 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>全域請求名稱 </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/help/zh-Hant/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">全域 mbox</a> 是指 Target 實作中各網頁頂端所發出的單一伺服器呼叫 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>頁面載入事件 </p> </td> 
   <td colname="col2"> <p>頁面載入時觸發的<a href="https://docs.adobe.com/content/help/zh-Hant/launch/using/extensions-ref/adobe-extension/target-extension/overview.html" format="html" scope="external">事件</a>類型 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>請求名稱 </p> </td> 
   <td colname="col2"> <p>頁面上某個<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">位置</a>周圍的請求名稱。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活動名稱 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hant/target/using/activities/activities.html" format="html" scope="external">促銷活動或活動</a>的名稱。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活動 ID </p> </td> 
   <td colname="col2"> <p>Target 活動 ID。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>體驗名稱 </p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hant/target/using/experiences/experiences.html" format="html" scope="external">體驗</a>的名稱。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>體驗 ID </p> </td> 
   <td colname="col2"> <p>Target 體驗 ID。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>選件名稱</p> </td> 
   <td colname="col2"> <p>Target <a href="https://docs.adobe.com/content/help/zh-Hant/target/using/experiences/offers/manage-content.html" format="html" scope="external">選件</a>的名稱。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>選件 ID </p> </td> 
   <td colname="col2"> <p>Target 選件 ID。只有當您在程式碼或 Tag Manager 中實作 Debugging 事件監聽器，並在 Target UI 中開啟必要的<a href="https://docs.adobe.com/content/help/zh-Hant/target/using/administer/response-tokens.html" format="html" scope="external">回應 Token</a> 時，才能無須驗證即可取得。 </p> </td> 
  </tr> 
 </tbody> 
</table>

