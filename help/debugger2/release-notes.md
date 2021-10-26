---
description: Experience Platform Debugger 發行說明
keywords: Debugger；Experience Platform Debugger 擴充功能；Chrome；擴充功能；發行說明
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: 發行說明
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 026ce852ded530e89f36bb01274d7481e07731c0
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 14%

---

# 發行說明{#release-notes}

## 發行說明 {#topic-a92c3eb799b74e7fa404af8af5efb215}

## 1.2.0版（2021年10月26日）

## 新功能

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> 功能 </th>
   <th colname="col2" class="entry"> 說明 </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> 網路檢視中可見的所有瀏覽器分頁的事件 </p> </td>
   <td colname="col2"> <p> 在網路檢視中顯示來自所有瀏覽器標籤的事件。 若只要查看目前索引標籤中的事件，請按一下除錯工具右下角的鎖定圖示。</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> 品牌變更 </p> </td>
   <td colname="col2"> <p> AEP Web SDK會變成Adobe Experience Platform Web SDK，而Launch會變成Adobe Experience Platform標籤。</p> </td>
  </tr>
 </tbody>
</table>

## 1.1.0版（2021年10月5日）

## 新功能

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> 功能 </th>
   <th colname="col2" class="entry"> 說明 </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> 遠端除錯視覺效果 </p> </td>
   <td colname="col2"> <p> 在Adobe Experience Platform Web SDK &gt;邊緣交易區段中，將遠端除錯事件整理至視覺化流程圖。 此外，需要頁面上使用的Adobe Experience Platform Web SDK IMS組織，才能在開始新的遠端除錯工作階段時符合登入的組織。 通過連接的頁簽篩選邊緣事務。</p> <p> <b>注意：</b> Target追蹤記錄仍可在「記錄&gt; Edge」區段中使用。</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Adobe Experience Platform Web SDK設定章節改良 </p> </td>
   <td colname="col2"> <p> 為頁面上的每個例項允許個別的資料流ID設定覆寫。 新增已啟用除錯的切換按鈕。</p> </td>
  </tr>
 </tbody>
</table>

## 錯誤修正

* 修正Adobe Target追蹤Token未一律與Adobe Experience Platform Web SDK的遠端除錯工作階段一起傳送的問題。

## 1.0.0版（2021年5月5日）

## 新功能

<table id="table_7EFCAF456B14404FAF3715FC56519AAF">
 <thead>
  <tr>
   <th colname="col1" class="entry"> 功能 </th>
   <th colname="col2" class="entry"> 說明 </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> 首次發行 </p> </td>
   <td colname="col2"> <p> Experience Platform偵錯工具的第一個主要版本。 意在取代Experience Cloud Debugger。 </p> </td>
  </tr>
 </tbody>
</table>
