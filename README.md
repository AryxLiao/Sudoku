# 🧩 數獨大師 Sudoku Master  
一款以 JavaScript/TailwindCSS 製作的高質感數獨 Web App，支援唯一解生成、每日挑戰、深色模式、PWA、筆記模式、錯誤限制、遊玩紀錄、動畫特效等完整功能。

---

## 🚀 功能特色

### 🎯 核心數獨功能
- 自動生成「唯一解」數獨盤面  
- 四種難度：簡單 / 中等 / 困難 / 專家  
- 電腦與手機介面自適應  
- 筆記模式（快速切換）  
- Undo 歷史復原  
- 三次錯誤即遊戲失敗  
- 盤面動畫與互動式高亮

### 📅 每日挑戰 Daily Mode
- 以當天日期產生固定種子（Seeded Random）  
- 每天題目不變  
- 完成後記錄於 localStorage  
- 顯示每日連勝（Streak）

### 📊 遊戲紀錄系統
- 最近 50 筆遊玩記錄  
- 包含：時間、難度、錯誤次數、結果  
- 可一鍵清除  
- 以 localStorage 儲存

### 🌓 深色模式 / 自動偵測
- 可手動切換  
- 也會自動依系統亮 / 暗切換  
- Tailwind + `dark:` class 全面支援

### 📱 PWA 支援
- iOS / Android 可安裝成獨立 App  
- 支援安全區域（Safe Area）  
- 無邊框、沉浸體驗

### 🧩 Sudoku 引擎特點
- 使用 Backtracking + 隨機化數列產生完整盤面  
- 自動嘗試挖空至符合目標線索數  
- 限制解數搜尋（只找 2 個解即可判定非唯一解）  
- 解題器可於毫秒級完成（8×8 DFS）

---

## 🛠 技術使用

- **HTML5 / JavaScript ES6**
- **TailwindCSS**
- **PWA / Manifest**
- **localStorage**
- **Responsive Web Design**
- **Seeded Random Generator**
- **Custom Sudoku Solver / Generator**

---

## 📂 專案結構

