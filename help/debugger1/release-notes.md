---
description: Experience Cloud Debugger 發行說明
keywords: Debugger；Experience Cloud Debugger 擴充功能；Chrome；擴充功能；發行說明
title: 發行說明Experience Cloud Debugger
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 1c81a0f2-81ae-4f29-8c48-45e755cabb07
source-git-commit: 2778ba78de3350ed1da01d452e303476b04c0303
workflow-type: tm+mt
source-wordcount: '727'
ht-degree: 99%

---

# 發行說明{#release-notes}

## 發行說明 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## 0.0.817 版 (2019 年 5 月 17 日)  {#topic-5dc9026cac864330b04361b1da8309a8}

## 新功能 {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>擷取處理後點擊資料 </p> </td> 
   <td colname="col2"> <p> 新增<a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local">執行處理規則後檢視 Analytics 點擊上的值</a>的功能。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 0.0.810 版 (2019 年 3 月 6 日)  {#topic-83bb7ddd68594177be9fd7826b650b80}

## 新功能 {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Adobe Experience Platform Auditor 測試 </p> </td> 
   <td colname="col2"> <p> 為 Experience Cloud Debugger 新增 <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local">Platform Auditor 測試</a> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Experience Cloud Debugger 現在會顯示 AAM 回應 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 錯誤修正 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* 修正頁尾隱藏頁面底部內容的問題

* 更新 Experience Cloud Debugger 頁尾
* 修正用於 Target 的過時術語問題

## 0.0.809 版 (2019 年 2 月 28 日)  {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## 新功能 {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>內嵌程式碼函數 </p> </td> 
   <td colname="col2"> <p> 區隔取代和插入內嵌程式碼函數。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改進項目 {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* 修正未淨化使用者輸入內容所導致的潛在漏洞。

## 錯誤修正 {#section-556417ff055848c1bf037354dd43cbd0}

* 修正 AAM 標籤中未擷取到 AAM DIL 事件的問題

* 修正動態插入 Launch 中使用者介面似乎對映至不同內嵌程式碼 (但事實上並非如此) 的問題
* 修正動態插入 Launch 中繼續顯示不正確 URL 的問題
* 修正 Experience Cloud Debugger 在 Experience Cloud Debugger 視窗已關閉時仍繼續取代內嵌程式碼的問題

## 0.0.806 版 (2018 年 9 月 10 日)  {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## 新功能 {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>工具標籤上的 Analytics 連結 </p> </td> 
   <td colname="col2"> <p>透過經由 IMS 登入的 Analytics API 顯示 Evar/Prop 的好記名稱。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>動態插入 Launch </p> </td> 
   <td colname="col2"> <p>「工具」標籤可讓您在任何頁面上動態插入 Adobe Experience Platform Launch，以測試頁面上未安裝 Platform Launch 的某個項目。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target 增強功能 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">新增 Target 請求的效能計時功能。 </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">擷取 adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改進項目 {#section-56003a12c32f4998bf1cf2a25a518592}

* 改善網路標籤的顯示內容，避免因表格高度太大而讓使用者必須先垂直捲動才能水平捲動。之前捲動列會顯示在表格底部。因為表格可能會變得很大，使用者必須一直垂直向下捲動才能看到內容。
* 更新工具標籤中的 ObservePoint 連結。

## 錯誤修正 {#section-d9231f5c77254d0888347e5f569a8b1d}

* 修正 Experience Cloud 標籤未更新的問題

* 修正網路標籤的解決方案列顯示「Media Optimizer」(而不是目前的「Advertising Cloud」名稱) 的問題
* 修正導致 Experience Cloud Debugger 在所有頁面上插入 _satellite 的問題

## 0.0.803 版 (2018 年 8 月 10 日)  {#topic-d2901fb70ce04a5586f6c7a994fce875}

0.0.803 版不包含任何供客戶使用的變更。

## 0.0.802 版 (2018 年 8 月 1 日)  {#topic-b93cd396af5e49dc97cd86264871aeb4}

## 新功能 {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>「工具」標籤上的 Platform Auditor 連結 </p> </td> 
   <td colname="col2"> <p>新增從 Experience Cloud Debugger 指向 Platform Auditor 的連結 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>已收合的標籤 </p> </td> 
   <td colname="col2"> <p>已收合的標籤會持續顯示於摘要和工具標籤 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>按一下即可檢視 </p> </td> 
   <td colname="col2"> <p> 對所有標籤新增按一下即可檢視功能 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改進項目 {#section-0e7090e3e6a645f085d4553b983ecff8}

* 將 Media Optimizer 名稱變更為 Advertising Cloud
* 移除網路標籤中找不到的解決方案

## 錯誤修正 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* 修正未更新「按一下儲存格即可檢視」功能的問題
* 修正 AAM 標籤未顯示 AAM 點擊的問題

## 0.0.798 版 (2018 年 6 月 14 日)  {#topic-3b2d44277f2f4c0295d82724c34bf467}

## 新功能 {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Excel 匯出選項 </p> </td> 
   <td colname="col2"> <p>新增 Excel 匯出選項至網路標籤。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>改善外觀 </p> </td> 
   <td colname="col2"> <p>將 Chrome 擴充功能字型更新為 Adobe Clean。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 觸控板滑動功能 </p> </td> 
   <td colname="col2"> <p>停用向前/向後觸控板滑動功能。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>原始伺服器呼叫指標 </p> </td> 
   <td colname="col2"> <p>新增已複製原始伺服器呼叫字串的指標。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>清除記錄檔標籤 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">如果在記錄檔中找不到解決方案的條列項目，則會隱藏解決方案篩選器中的解決方案。 </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">如果找不到任何 DTM 呼叫，則會隱藏層級篩選器，因為這只適用於 DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">變更層級欄中顯示的圖示，讓您在按一下但未發生任何回應時，看起來不像可點選的狀態 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">標準化 DTM 條列項目上「顯示程式碼」的格式 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>更新頁尾的說明連結 </p> </td> 
   <td colname="col2"> <p>將頁尾中的說明連結更新至 <a href="https://docs.adobe.com/content/help/zh-Hant/debugger/using/experience-cloud-debugger.html" format="https" scope="external">https://docs.adobe.com/content/help/zh-Hant/debugger/using/experience-cloud-debugger.html</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 錯誤修正 {#section-c292cf7dcb17463bb1928de73bd55121}

* 修正未清除徽章編號的問題
* 修正客戶回報摘要詳細資料空白的問題

## 0.0.797 版 (2018 年 5 月 25 日)  {#topic-51490f4f42aa40eb879663fad9d62916}

## 新功能 {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Mbox 切換 </p> </td> 
   <td colname="col2"> <p>新增 Mbox 切換至 Target 標籤 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>篩選設定現在是嚴格篩選 </p> </td> 
   <td colname="col2"> <p>篩選設定現在已固定至網路和記錄檔標籤的畫面頂端。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>檢視並複製網路值 </p> </td> 
   <td colname="col2"> <p>您可以在網路標籤中檢視詳細資料並複製任何儲存格的值。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>法律頁尾連結和版權 </p> </td> 
   <td colname="col2"> <p>新增法律頁尾連結和版權資訊至使用者介面。 </p> </td> 
  </tr> 
 </tbody> 
</table>
