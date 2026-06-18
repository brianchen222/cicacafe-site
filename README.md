# CICACAFE 官方網站（GitHub Pages 部署）

本資料夾為可直接部署的靜態網站，結構：
- index.html（首頁）
- img/（首頁銀河系列主視覺：mars / venus / orion）
- .nojekyll（讓 GitHub Pages 原樣輸出）

## 部署到 GitHub Pages（最簡單：網頁上傳）
1. 到 https://github.com/new 建立新 repo（建議名稱 `cicacafe-site`，設為 Public）。
2. 進入新 repo →「Add file」→「Upload files」→ 把本資料夾內 index.html、img 整個資料夾、.nojekyll 一起拖進去 →「Commit changes」。
3. repo → Settings → Pages → Build and deployment：Source 選「Deploy from a branch」，Branch 選 `main`、資料夾 `/ (root)` → Save。
4. 等 1–2 分鐘，頁面上方會出現網址：`https://<你的帳號>.github.io/cicacafe-site/`

## 想用自己的網域名（username.github.io）
把 repo 命名為 `<你的帳號>.github.io`，上傳同樣檔案，Pages 自動啟用，網址為 `https://<你的帳號>.github.io/`。
