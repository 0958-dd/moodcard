
# MoodCard 心情小卡

這是一個簡易的網頁應用程式，讓使用者可以每天記錄自己的心情，並透過圖表統計視覺化呈現。
使用 Google 登入功能以儲存每位使用者獨立的紀錄。

## 🔐 功能說明

- Google 帳號登入（OAuth 2.0 驗證）
- 每日心情紀錄：開心、焦慮、疲憊、沮喪
- 圖表顯示最近統計
- 可下載心情小卡 PNG
- 本地儲存區分使用者資料

## 🚀 使用方式

### 1. 部署到 GitHub Pages
1. 建立 GitHub Repository，命名如 `moodcard`
2. 上傳本專案的所有檔案（至少包含 `index.html`）
3. 到 `Settings > Pages` 啟用 GitHub Pages，來源選擇 `main` 分支的 `/root`
4. 網址會是：`https://0958-dd.github.io/moodcard`

### 2. 設定 Google OAuth
1. 前往 [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
2. 編輯 OAuth 2.0 用戶端，新增以下授權網域：
   - `https://0958-dd.github.io`
3. 儲存即可

### 3. 使用
- 使用者使用 Google 登入後，即可開始使用 MoodCard，資料將依照 Email 自動儲存

## 🧑‍💻 開發技術
- HTML5 + JavaScript
- Chart.js 圖表
- Google Identity Services (GIS) 登入套件

## 📄 授權
MIT License
