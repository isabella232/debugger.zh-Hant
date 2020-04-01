---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: 工具
title: 工具
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: tm+mt
source-git-commit: 9bb030d94db1a1e70ecda3d62caf542d7f750317

---


# 工具{#tools}

在工具畫面上，您可以啟用或停用已安裝解決方案的各種工具。例如，您可以開啟 Target 的主控台除錯陳述式或使用 DTM 中繼程式庫。只有在頁面上已安裝 Target 和 DTM 時，才能使用這些工具。

![](assets/tools.jpg)

您可以在任何頁面上動態插入 Launch 或 DTM，以測試頁面上未安裝 Launch 或 DTM 的某個項目。按一下「**[!UICONTROL Embed Code]**」圖示，然後輸入您的[內嵌程式碼](https://docs.adobe.com/content/help/en/dtm/using/client-side/deployment.html)，並按一下「**[!UICONTROL Save]**」。

![](assets/tools-embedcode.jpg)

## DTM 資訊 {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 工具 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> DTM 主控台記錄 </p> </td> 
   <td colname="col2"> <p>此工具會向瀏覽器主控台顯示 DTM 專用除錯陳述式。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>使用中繼程式庫 </p> </td> 
   <td colname="col2"> <p>此工具會使用中繼程式庫取得 DTM 除錯資訊。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>停用 DTM </p> </td> 
   <td colname="col2"> <p>此工具會封鎖 DTM 資訊以避免進行檢查。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 動態插入 DTM </p> </td> 
   <td colname="col2"> <p> 此工具會在頁面上插入 DTM 程式碼。使用內嵌程式碼編輯器來編輯已插入的程式碼。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## Target 資訊 {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 工具 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Target 主控台記錄 </p> </td> 
   <td colname="col2"> <p>此工具會將名稱為 <span class="codeph">mboxDebug=true</span> 的 Cookie 新增至瀏覽器，以向瀏覽器主控台顯示 Target 專用除錯陳述式，且開頭一律顯示 <span class="codeph">AT:</span> 前置詞。目前主控台陳述式不會出現在 Debugger 記錄檔畫面內，但會顯示在瀏覽器的原生除錯主控台中。 </p> <p> 此工具需要使用 at.js 0.9.6+。如果您使用的是舊版 at.js，您可以將 <span class="codeph">?mboxDebug=true</span> 查詢字串參數新增至 URL 以開啟主控台記錄。如果您使用的是 mbox.js，您可以新增 <span class="codeph">?_AT_Debug=console</span> 參數以開啟限定於 Visual Experience Composer 活動的主控台記錄。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 啟用 Mbox 追蹤 </p> </td> 
   <td colname="col2"> <p>此工具會將詳細資訊新增至 Target 回應，您可在 Debugger 的 <span class="uicontrol">Target &gt; Mbox 追蹤</span>畫面中探索相關資訊。 </p> <p> 您必須先在其中一個 Chrome 分頁中登入 Experience Cloud 才能啟用此工具。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>停用 Target </p> </td> 
   <td colname="col2"> <p>此工具會將名稱為 <span class="codeph">mboxDisable=true</span> 的 Cookie 新增至瀏覽器，以停用所有 Target 請求。 </p> <p> 此工具需要使用 at.js 0.9.6+。如果您使用的是舊版，您可以將 <span class="codeph">?mboxDisable=true</span> 查詢字串參數新增至 URL 以停用 mbox。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Mbox 強調顯示 </p> </td> 
   <td colname="col2"> <p> 此工具會在舊版包裝樣式的 mbox 周圍顯示紅色方塊。 </p> </td> 
  </tr> 
 </tbody> 
</table>

以下影片說明如何將 Debugger 擴充功能與 Adobe Target 搭配使用。

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/)
