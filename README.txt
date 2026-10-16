慢慢存｜個人記帳 PWA

檔案：
- index.html
- styles.css
- app.js
- manifest.json
- service-worker.js

部署方式：把以上檔案放到 GitHub Pages 專案根目錄後等待發布，再用 Safari 開啟網站。
資料保存：本機瀏覽器 localStorage；不同網域/不同瀏覽器不會自動同步。請使用 App 內的「匯出備份檔」定期備份。
注意：此版本使用獨立的資料鍵 slowmoney_v1，不會自動讀取舊版資料，也不會主動刪除舊版資料。請先將新版部署在另一個 GitHub repository / Pages 網址測試，勿直接覆蓋舊版直到確認功能與資料轉移需求。
