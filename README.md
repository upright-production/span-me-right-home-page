# 求生相機 · Snap Me Right 支援網站

純 HTML/CSS 網站，提供使用支援、常見問題與繁體中文隱私權政策。不需要安裝依賴或編譯。

## GitHub Pages

此公開 repo 可直接使用 GitHub Pages 架站：

1. 到 repository 的 **Settings → Pages**。
2. 在 **Build and deployment → Source** 選擇 **Deploy from a branch**。
3. Branch 選擇 **main**、資料夾選擇 **/ (root)**，按 Save。
4. 等待 GitHub 完成部署；部署狀態可在 Actions 或 Pages 頁面查看。

GitHub Pages 啟用並完成部署後，預期網址：

- 使用支援：`https://upright-production.github.io/span-me-right-home-page/`
- 隱私權政策：`https://upright-production.github.io/span-me-right-home-page/privacy/`

一般頁面使用相對路徑，可支援 GitHub Pages 的 repo 子目錄。404 頁使用目前 repo 的絕對子路徑，若更換 repo 名稱或使用自訂網域，請同步更新。

## 本機預覽

```sh
python3 -m http.server 8765
```

開啟 `http://localhost:8765/`；隱私政策在 `/privacy/`。

## 內容更新

- `index.html`：客服與常見問題。
- `privacy/index.html`：線上隱私權政策。
- `privacy-policy.json`：同一份政策的結構化原始內容；修改時需同步 HTML。
- `style.css`：共用樣式。
- `app-logo.png`：App Logo。
- `.nojekyll`：停用 Jekyll 處理，直接發布靜態檔案。

客服 Email：`info@uprightproduction.com`。

網站不包含廣告、分析程式或聯絡表單。GitHub Pages 的託管服務可能依其政策處理請求與技術紀錄。

政策更新時，請同步求生相機 App 的 `assets/legal/privacy-policy.json`，並以新版 App 發布。GitHub Pages 網址啟用後，才將 App 與 App Store Connect 的支援／政策網址改成這裡。

© 2026 直立製作設計有限公司。保留所有權利。
