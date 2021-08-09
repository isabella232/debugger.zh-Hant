---
description: Experience Platform Debugger 網路畫面
keywords: Debugger；Experience Platform Debugger 擴充功能；Chrome；擴充功能；網路；資訊
seo-description: Experience Platform Debugger 網路畫面
seo-title: 網路資訊
title: 網路資訊
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
exl-id: ed0579ef-ec26-43df-9453-a395c105038a
source-git-commit: 8672a623442e5a0daa10597a4a93631131221fec
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 100%

---

# 網路{#network}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger 目前仍在測試階段。文件和功能可能會有所變更。

若要檢視網路資訊，請按一下「**[!UICONTROL Network]**」。

網路畫面會彙總頁面上發出的所有 Adobe Experience Cloud 解決方案呼叫，並由左到右依序顯示。標準參數會自動加上好記名稱的標示，並將相同角色的常見參數編排為分組顯示。

![](assets/network.jpg)

若要比較不同點擊數的索引鍵值組，此畫面相當實用。您可確認整合時所使用的參數 (例如 Experience Cloud 訪客 ID 或補充資料 ID)，在各整合作業之間是否一致。

>[!NOTE]
>
>目前並非解決方案呼叫中傳遞的所有參數 (例如 Analytics 內容變數、Target 自訂參數或 Experience Cloud ID 服務客戶 ID) 都會顯示在網路畫面中。

若要依解決方案變更資訊，請從左側導覽的清單中選取您要檢視的解決方案。篩選下列範例以僅顯示 Analytics：

![](assets/network-analytics.jpg)

若要返回顯示所有解決方案，請按一下「**[!UICONTROL Network]**」

按一下網路檢視中的項目以查看其展開檢視。從展開的視圖視窗中，您可以將顯示的資訊複製到剪貼簿。

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

若要清除清單，請按一下「**[!UICONTROL Remove Events]**」。

若要下載包含此螢幕上資訊的 Excel 檔案，請按一下「**[!UICONTROL Download]**」。
