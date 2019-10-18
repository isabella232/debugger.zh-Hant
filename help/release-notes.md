---
description: 'null'
keywords: debugger;experience cloud調試器擴展；chrome;extension；發行說明
seo-description: 'null'
seo-title: 發行說明
title: 發行說明
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# 發行說明 {#release-notes}

## 發行說明 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Version 0.0.817 May 17, 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## 新特性 {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>後處理點擊資料 </p> </td> 
   <td colname="col2"> <p> 新增在處理規 <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> 則執行後，可檢視Analytics點擊值的能力</a>。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 版本0.0.810 2019年3月6日 {#topic-83bb7ddd68594177be9fd7826b650b80}

## 新特性 {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Auditor測試 </p> </td> 
   <td colname="col2"> <p> 已將 <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> Auditor測試新增至</a> Debugger </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>除錯程式現在會顯示AAM回應 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 錯誤修正 {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* 修正頁尾隱藏頁面底部內容的問題

* 更新除錯程式頁尾
* 修正Target使用過時術語的問題

## 版本0.0.809 2019年2月28日 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## 新特性 {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>內嵌程式碼函式 </p> </td> 
   <td colname="col2"> <p> 分割取代和插入內嵌代碼函式。 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改良功能 {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* 修正未淨化的使用者輸入所造成的潛在弱點。

## 錯誤修正 {#section-556417ff055848c1bf037354dd43cbd0}

* 修正AAM DIL事件未在AAM標籤中擷取的問題

* 修正動態插入啟動中，使用者介面在未對應至其他內嵌代碼時，似乎會對應至其他內嵌代碼的問題
* 修正動態插入啟動中繼續顯示錯誤URL的問題
* 修正即使關閉「除錯程式」視窗，除錯程式仍會繼續取代內嵌代碼的問題

## 版本0.0.806 2018年9月10日 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## 新特性 {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>「工具」標籤上的Analytics連結 </p> </td> 
   <td colname="col2"> <p>透過IMS登入，透過Analytics API顯示evar/prop的好記名稱。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>動態插入啟動 </p> </td> 
   <td colname="col2"> <p>從「工具」標籤，您可以在任何頁面上動態插入「啟動」，以測試未安裝「啟動」的頁面上的內容。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Target增強功能 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">已新增Target請求的效能計時。 </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Capture adobe.target.trackEvent </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改良功能 {#section-56003a12c32f4998bf1cf2a25a518592}

* 已改善「網路」索引標籤的顯示，使表格的高度不會過高，並強制使用者在水準捲動之前先垂直捲動。 以前，捲動條會出現在表的底部。 由於表格可能會變大，使用者必須垂直向下捲動所有表格才能看到。
* 已從「工具」標籤更新ObservePoint的連結。

## 錯誤修正 {#section-d9231f5c77254d0888347e5f569a8b1d}

* 修正Experience cloud標籤無法更新的問題

* 修正「網路」標籤的「解決方案」列中顯示「Media Optimizer」，而非目前「Advertising Cloud」名稱的問題
* 修正導致除錯程式在每個頁面上插入_satellite的問題

## 版本0.0.803 2018年8月10日 {#topic-d2901fb70ce04a5586f6c7a994fce875}

0.0.803版不包含任何客戶對應的變更。

## 版本0.0.802 2018年8月1日 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## 新特性 {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>「工具」頁籤上的Auditor連結 </p> </td> 
   <td colname="col2"> <p>從偵錯器新增Auditor的連結 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>收合的標籤 </p> </td> 
   <td colname="col2"> <p>收合的標籤會持續存在「摘要」和「工具」標籤上 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>按一下以檢視 </p> </td> 
   <td colname="col2"> <p> 新增點按檢視功能至所有標籤 </p> </td> 
  </tr> 
 </tbody> 
</table>

## 改良功能 {#section-0e7090e3e6a645f085d4553b983ecff8}

* 將Media Optimizer的名稱變更為Advertising Cloud
* 如果找不到，則從「網路」頁籤中刪除解決方案

## 錯誤修正 {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* 修正「按一下儲存格以檢視」功能未更新的問題
* 修正AAM標籤上未顯示AAM點擊的問題

## 版本0.0.798 2018年6月14日 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## 新特性 {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Excel匯出選項 </p> </td> 
   <td colname="col2"> <p>新增Excel匯出選項至「網路」索引標籤。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>改善外觀 </p> </td> 
   <td colname="col2"> <p>已將Chrome擴充功能字型更新為Adobe Clean。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> 軌跡板滑動功能 </p> </td> 
   <td colname="col2"> <p>已停用前向／後向軌跡板滑動功能。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>原始伺服器呼叫指示器 </p> </td> 
   <td colname="col2"> <p>已新增原始伺服器呼叫字串已複製的指標。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>「清除日誌」頁籤 </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">如果日誌中未找到該解決方案的明細項目，請在「解決方案篩選」中隱藏解決方案 </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">如果找不到DTM呼叫，則隱藏「層級篩選」，因為它僅適用於DTM </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">變更「層級」欄中顯示的圖示，當您按一下時，這些圖示看起來不可點選 </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">標準化DTM行項目的「顯示程式碼」格式 </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>更新頁尾中的說明連結 </p> </td> 
   <td colname="col2"> <p>將頁尾中的說明連結更新至 <a href="https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/" format="https" scope="external"> https://marketing.adobe.com/resources/help/en_US/experience-cloud-debugger/</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## 錯誤修正 {#section-c292cf7dcb17463bb1928de73bd55121}

* 修正徽章編號未清除的問題
* 修正客戶回報空白摘要詳細資訊的問題

## Version 0.0.797 May 25, 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## 新特性 {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 功能 </th> 
   <th colname="col2" class="entry"> 說明 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>mbox 切換 </p> </td> 
   <td colname="col2"> <p>mbox切換已新增至「目標」索引標籤 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>篩選設定現在會嚴格 </p> </td> 
   <td colname="col2"> <p>篩選器設定現在會停留在網路螢幕的頂端，並記錄標籤。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>查看和複製網路值 </p> </td> 
   <td colname="col2"> <p>您可以查看詳細資訊並複製網路頁籤中任何單元格的值。 </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>合法頁尾連結與版權 </p> </td> 
   <td colname="col2"> <p>新增法律頁尾連結和版權資訊至使用者介面。 </p> </td> 
  </tr> 
 </tbody> 
</table>

