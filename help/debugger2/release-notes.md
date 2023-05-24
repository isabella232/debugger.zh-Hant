---
title: 發行說明
description: Adobe Experience Platform Debugger 的最新發行說明。
keywords: Debugger；Experience Platform Debugger 擴充功能；Chrome；擴充功能；發行說明
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 7%

---

# 發行說明

## 1.3.0版 — 2022年1月28日

* 新增「關於」連結以顯示最新版本和說明。
* 新增切換功能，可檢視Analytics請求的處理後點選。 Analytics區段提供此切換選項。
* 修正在偵錯工具外部關閉工作階段時的遠端偵錯工作階段問題。
* 修正Web SDK Edge Transactions索引標籤中顯示的錯誤通知。
* 修正偵錯工具存取_satellite物件時，頁面出現棄用警告的Adobe標籤。
* 修正在頁面上找不到AppMeasurement例項的一些情況。
* 修正第一次開啟偵錯工具視窗時發生的頁面連線問題。

## 1.2.0版 — 2021年10月26日

* 顯示網路檢視中所有瀏覽器標籤的事件。 若只要檢視目前標籤中的事件，請選取Debugger右下角的鎖定圖示。
* 更新品牌。

## 1.1.0版 — 2021年10月5日

* 遠端偵錯視覺效果 — 在「Adobe Experience Platform Web SDK >邊緣交易」區段中，將遠端偵錯事件組織成視覺流程圖。
* 啟動新的遠端偵錯工作階段時，需要頁面上使用的Adobe Experience Platform Web SDK IMS組織符合登入組織。
* 僅顯示已連線標籤的邊緣交易。 Target追蹤記錄仍可在「記錄> Edge」區段中取得。
* 允許頁面上每個Adobe Experience Platform Web SDK執行個體的個別資料串流ID設定覆寫。 新增偵錯已啟用切換。
* 修正Adobe Target追蹤權杖不一定會與Adobe Experience Platform Web SDK的遠端偵錯工作階段一起傳送的問題。

## 1.0.0版（2021年5月5日）

* Experience Platform Debugger的第一個主要版本。 旨在取代Experience Cloud Debugger。
