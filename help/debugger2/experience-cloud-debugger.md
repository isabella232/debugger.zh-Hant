---
description: Debugger 會檢視您的網頁，並協助您找出 Experience Cloud 解決方案實作方式的相關問題
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger 2.0 Chrome 與 Firefox 擴充功能技術文件 - 檢視您的網頁，並了解 Experience Cloud 解決方案實作的相關問題
seo-title: Adobe Experience Platform Debugger Chrome 與 Firefox 擴充功能
title: Adobe Experience Platform Debugger 擴充功能
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: ht
source-git-commit: 3dc1876c0516b7a81f68a207c6a1651bc95b17ab

---


# (Beta) Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Cloud Debugger 2.0 目前仍在測試階段。文件和功能可能會有所變更。

適用於 [Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) 與 [Firefox](https://addons.mozilla.org/zh-TW/firefox/addon/adobe-experience-platform-dbg/) 的 Adobe Experience Platform Debugger 會檢查您的網頁，協助您找出 Experience Cloud 解決方案實作方面的相關問題。

將 Adobe Experience Platform Debugger 與其他 Adobe 啟用解決方案搭配使用，以執行類似以下的工作流程：

1. 使用 [Launch](https://docs.adobe.com/content/help/zh-Hant/launch/using/overview.html) 或 [DTM](https://docs.adobe.com/content/help/zh-Hant/dtm/using/dtm-home.html)，插入會在您的頁面上啟用 [Adobe Experience Cloud](https://docs.adobe.com/content/help/zh-Hant/core-services/interface/experience-cloud.html) 解決方案的程式碼。

1. 使用 [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) 測試您的實作成果。
1. 使用 Adobe Experience Platform Debugger 對 Auditor 發現的問題偵錯，或檢查實作的其他相關資訊。

上述步驟不一定需要按照該順序執行，但這是常見的程序。

雖然您可以在任何網頁上執行 Debugger，只有當您已在其中一個已開啟 Chrome 分頁中通過 Experience Cloud 驗證時，才會顯示擴充功能中的任何非公開資料。

## 使用案例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

使用 Debugger，收集可協助您了解 Experience Cloud 解決方案實作的相關資訊。例如：

* **Launch**：查看頁面上部署了哪些屬性、環境和版本。
* **Target**：查看您符合或不符合哪些活動的資格及其原因。
