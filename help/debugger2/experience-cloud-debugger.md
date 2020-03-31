---
description: Debugger 會檢視您的網頁，並協助您找出 Experience Cloud 解決方案實作方式的相關問題
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: Adobe Experience Cloud Debugger 2.0 Chrome 與 Firefox 擴充功能技術文件 - 檢視您的網頁，並瞭解 Experience Cloud 解決方案實施的相關問題
seo-title: Adobe Experience Platform Debugger Chrome和Firefox Extension
title: Adobe Experience Platform Debugger Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: dc723f0848c56794e9a1a6eda405de2f4ea6b8fa

---


# （測試版）Adobe Experience Platform Debugger 2.0 {#adobe-experience-platform-debugger}

> [!IMPORTANT]
>
> Adobe Experience Cloud Debugger 2.0目前正在測試中。 說明檔案和功能可能會有所變更。

The [Adobe Experience Platform Debugger for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

將Adobe Experience Platform Debugger與其他Adobe啟動解決方案搭配使用，以進行類似下列的工作流程：

1. 使用 [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) 或 [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html)，插入會在您的頁面上啟用 [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) 解決方案的程式碼。

1. 使用 [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) 測試您的實作成果。
1. 使用Adobe Experience Platform Debugger對Auditor發現的問題進行除錯，或檢查您實作的其他資訊。

上述步驟不一定需要按照該順序執行，但這是常見的程序。

雖然您可以在任何網頁上執行 Debugger，只有當您已在其中一個已開啟 Chrome 分頁中通過 Experience Cloud 驗證時，才會顯示擴充功能中的任何非公開資料。

## 使用案例 {#section-9fcd0583ed184943a8f0c2d3c00658e0}

使用 Debugger，收集可協助您瞭解 Experience Cloud 解決方案實作方式的相關資訊。例如：

* **啟動：** 查看頁面上部署了哪些屬性、環境和構建。
* **Target**：查看您符合或不符合哪些活動的資格及其原因。
