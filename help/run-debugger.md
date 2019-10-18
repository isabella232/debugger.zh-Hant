---
description: 'null'
keywords: debugger;experience Cloud除錯程式；chrome;extension；摘要；清除；請求；摘要畫面；解決方案；資訊；分析；目標；dtm;audience manager;launch;id服務
seo-description: 'null'
seo-title: 摘要畫面
title: 摘要畫面
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 摘要畫面{#summary-screen}

若要執行Experience Cloud除錯程式，請按一下擴充列中的擴充功能圖示，然後在Chrome中開啟您要檢查的頁面。

![](assets/start-icon.jpg)

此時會出現「Adobe Experience cloud除錯程式摘要」畫面。

![](assets/summary.jpg)

此畫面會顯示頁面的縮圖，以及頁面的URL和標題。 此外，還會顯示每個Adobe Experience cloud解決方案的相關資訊。 顯示的資訊視解決方案而異，但通常包含的資訊包括解決方案程式庫和版本（例如「AppMeasurement v2.9」）和帳戶識別碼（例如Analytics報表套裝ID、Target用戶端代碼、Audience Manager合作夥伴ID等）

視窗頂端標籤旁的藍色數字顯示已進行的伺服器呼叫數。 您可以按一下個別標籤中的「清 **[!UICONTROL 除所有請求]** 」，將這些重設為零。

例如，下圖顯示有關Adobe Target的資訊。 請注意，若要在不進行驗證的情況下公開下列活動詳細資料，您必須在程式碼或標籤管理員中實作「除錯」事件接聽程式，並在Target UI中開啟必 [要的回應](https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html) Token。

![](assets/summary-target2.jpg)

## 在Auditor中運行審計 {#section-82bc57440406461ebf27a16855b71655}

您可以使用Adobe Auditor在您的頁面上執行一連串的稽核。 要運行Auditor，請按一下頂 **[!UICONTROL 部菜單中的]** Auditor ，然後按一下 **[!UICONTROL Audit Page Now]**。 若要開啟Adobe Auditor，請按一 **[!UICONTROL 下「立即執行多頁稽核」]**。

## 除錯程式中顯示的資訊 {#section-88a95ba53dca43d9b96a585e75e5f5cf}

除錯程式會針對每個解決方案顯示下列資訊：

**頁面資訊**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>頁面螢幕擷取 </p> </td> 
   <td colname="col2"> <p>頁面縮圖 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>頁面的URL </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>標題 </p> </td> 
   <td colname="col2"> <p>在&lt;TITLE&gt;標籤中指 <span class="codeph"> 定的名稱</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>報表套裝 </p> </td> 
   <td colname="col2"> <p>A <a href="https://experiencecloud.adobe.com/resources/help/en_US/reference/report_suites_admin.html" format="html" scope="external"> report suite</a> defines the complete, independent reporting on a chosen website, set of websites, or subset of web pages </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>為頁 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/appmeasure_mjs.html" format="html" scope="external"> 面定義的AppMeasurement</a> 版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>訪客版本 </p> </td> 
   <td colname="col2"> <p>訪客ID程式 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> 庫的版本</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>頁面名稱 </p> </td> 
   <td colname="col2"> <p>傳送 <a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/pageName.html" format="html" scope="external"> 至Analytics的pageName</a> 變數，其中包含網站的使用者好記名稱。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>模組 </p> </td> 
   <td colname="col2"> <p>Adobe Analytics載入的模組 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Partner </p> </td> 
   <td colname="col2"> <p>DIL <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_dil_get_partner.html" format="html" scope="external"> 例項的</a> 「合作夥伴名稱」 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>DIL例項的版本號碼<a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/r_api_return_versions_dil.html" format="html" scope="external"></a> （英文） </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>UUID </p> </td> 
   <td colname="col2"> <p>與 <a href="https://experiencecloud.adobe.com/resources/help/en_US/aam/ids-in-aam.html" format="html" scope="external"> DIL例項關聯的</a> 「唯一使用者ID」 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>名稱 </p> </td> 
   <td colname="col2"> <p>Adobe Launch屬性的名 <a href="https://docs.adobelaunch.com/administration/companies-and-properties" format="https" scope="external"> 稱</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>渦輪機的版 <a href="https://developer.adobelaunch.com/guides/extensions/turbine-free-variable/" format="https" scope="external"> 本</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>建置日期 </p> </td> 
   <td colname="col2"> <p>啟動程 <a href="https://docs.adobelaunch.com/publishing/libraries" format="https" scope="external"> 式庫</a> 組建日期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>環境 </p> </td> 
   <td colname="col2"> <p>啟動 <a href="https://docs.adobelaunch.com/administration/environments" format="https" scope="external"> 程式庫</a> (Launch library)所使用的環境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>指令碼目錄 </p> </td> 
   <td colname="col2"> <p>儲存Launch指令碼的目錄 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>資料庫名稱 </p> </td> 
   <td colname="col2"> <p>Adobe DTM程式庫的名稱<a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"></a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>渦輪機版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>建置日期 </p> </td> 
   <td colname="col2"> <p>啟動程 <a href="https://experiencecloud.adobe.com/resources/help/en_US/dtm/library_management.html" format="html" scope="external"> 式庫</a> 組建日期 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>環境 </p> </td> 
   <td colname="col2"> <p>DTM程式庫使用的環境 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>指令碼目錄 </p> </td> 
   <td colname="col2"> <p>儲存DTM指令碼的目錄 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Cloud ID 服務**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Experience cloud組織ID </p> </td> 
   <td colname="col2"> <p>Your <a href="https://experiencecloud.adobe.com/resources/help/en_US/mcvid/" format="https" scope="external"> Organization ID</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>訪客<a href="https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/visid_analytics.html" format="html" scope="external"> ID程式庫的版本</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>用戶端代碼 </p> </td> 
   <td colname="col2"> <p>Your Target <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> Client Code </a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>版本 </p> </td> 
   <td colname="col2"> <p>您目前 <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> 的at.js</a> 或mbox.js版本 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>全域 mbox 名稱 </p> </td> 
   <td colname="col2"> <p>全域<a href="https://docs.adobe.com/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox</a> ，是指在Target實作中每個網頁頂端所做的單一伺服器呼叫 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mbox 名稱 </p> </td> 
   <td colname="col2"> <p>頁面上位置周圍的 <a href="https://docs.adobe.com/content/help/en/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external"> mbox</a> 名稱。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活動名稱 </p> </td> 
   <td colname="col2"> <p>Target促銷活動或活 <a href="https://docs.adobe.com/content/help/en/target/using/activities/activities.html" format="html" scope="external"> 動的名稱</a>。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>活動ID </p> </td> 
   <td colname="col2"> <p>Target活動的ID。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>方式名稱 </p> </td> 
   <td colname="col2"> <p>Target體驗的名 <a href="https://docs.adobe.com/content/help/en/target/using/experiences/experiences.html" format="html" scope="external"> 稱</a>。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>指導方針 ID </p> </td> 
   <td colname="col2"> <p>Target方式的ID。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>選件 </p> </td> 
   <td colname="col2"> <p>Target選件的名 <a href="https://docs.adobe.com/content/help/en/target/using/experiences/offers/manage-content.html" format="html" scope="external"> 稱</a>。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>選件 ID </p> </td> 
   <td colname="col2"> <p>Target選件的ID。 只有在您在程式碼或標籤管理器中實作「除錯」事件接聽程式，並在Target UI中開啟必要的回應Token時，才 <a href="https://docs.adobe.com/content/help/en/target/using/administer/response-tokens.html" format="html" scope="external"> 可在不進行驗證</a> 。 </p> </td> 
  </tr> 
 </tbody> 
</table>

