# 智慧圖書館資料管理系統 (Smart Library Management System)

這是一個基於 **Java Spring Boot** 開發的後端 RESTful API 專案，旨在模擬圖書館資源管理流程。本專案展現了對資料一致性與系統穩定性的追求。

## 🚀 技術棧 (Tech Stack)

* **核心框架**: Spring Boot 3.x
* **資料庫**: MySQL
* **開發工具**: Maven, IntelliJ IDEA
* **架構風格**: RESTful API 設計

## 🛠️ 核心功能

* **書籍管理 (Book Management)**: 完整實作 CRUD 功能（新增、查詢、修改、刪除）。
* **借閱流程邏輯**: 處理書籍狀態變更，確保資料在併發存取下的正確性。
* **例外處理 (Exception Handling)**: 建立全域錯誤處理機制，確保系統在異常輸入下仍能穩定運作並回饋明確訊息。
