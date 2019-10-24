---
description: 'null'
keywords: debugger;experience Cloud除錯程式；chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: 工具
title: 工具
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 工具{#tools}

在「工具」畫面上，您可以啟用或停用已安裝解決方案的各種工具。 例如，您可以開啟Target的主控台除錯陳述式，或使用DTM測試程式庫。 這些工具僅在您的頁面上安裝了Target和DTM時才可用。

![](assets/tools.jpg)

您可以在任何頁面上動態插入啟動或DTM，以測試未安裝啟動或DTM的頁面上的內容。 按一下 **[!UICONTROL Embed Code]** 圖示，然後輸入您 [的內嵌代碼](https://experiencecloud.adobe.com/resources/help/en_US/dtm/deployment.html) ，然後按一下 **[!UICONTROL Save]**。

![](assets/tools-embedcode.jpg)

## DTM資訊 {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 工具 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM控制台記錄 </p> </td> 
   <td colname="col2"> <p>此工具會將DTM專用的除錯陳述式公開至瀏覽器主控台。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用測試程式庫 </p> </td> 
   <td colname="col2"> <p>此工具使用「測試程式庫」來取得DTM除錯資訊。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>停用DTM </p> </td> 
   <td colname="col2"> <p>此工具會封鎖DTM資訊，以免被檢查。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 動態插入DTM </p> </td> 
   <td colname="col2"> <p> 此工具會在您的頁面上插入DTM程式碼。 使用內嵌代碼編輯器編輯插入的代碼。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 目標資訊 {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 工具 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>目標控制台記錄 </p> </td> 
   <td colname="col2"> <p><span class="codeph"> 此工具會將Target特定除錯陳述式公開至瀏覽器主控台，全部從 </span> AT開始：前置詞，將名為 <span class="codeph"> mboxDebug=true的Cookie新增至您的瀏覽器</span> 。 目前，控制台語句不會出現在「除錯程式記錄檔」畫面中，但會顯示在瀏覽器的原生除錯主控台中。 </p> <p> 此工具需要at.js 0.9.6+。 如果您使用舊版at.js，可將 <span class="codeph"> ?mboxDebug=true</span> 查詢字串參數新增至URL，以開啟主控台記錄。 如果您使用mbox.js，可以新增 <span class="codeph"> ?_AT_Debug=console</span> 參數，以開啟僅限Visual Experience Composer活動的主控台記錄。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 啟用Mbox追蹤 </p> </td> 
   <td colname="col2"> <p>此工具會將詳細資訊新增至Target回應，您可在除錯程式的 <span class="uicontrol"></span> Target&gt;Mbox追蹤畫面中加以探索。 </p> <p> 您必須登入Experience cloud的其中一個Chrome標籤，才能啟用此工具。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>停用目標 </p> </td> 
   <td colname="col2"> <p>此工具會新增名為mboxDisable=true的Cookie至您的瀏覽器，以停用 <span class="codeph"> 所有Target請求</span> 。 </p> <p> 此工具需要at.js 0.9.6+。 如果您使用舊版，可將 <span class="codeph"> ?mboxDisable=true查詢字串參 </span>數新增至URL以停用mbox。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox反白顯示 </p> </td> 
   <td colname="col2"> <p> 此工具會在舊版包裝樣式的mbox周圍繪製一個紅色方塊。 </p> </td> 
  </tr> 
 </tbody> 
</table>

以下影片說明如何搭配Adobe Target使用除錯程式擴充功能。

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=chi_hant)
