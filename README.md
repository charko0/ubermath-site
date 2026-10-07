# Übermath 網上版

- 網址：https://ubermath.pages.dev（學生）、https://ubermath.pages.dev/teacher.html（老師後台）
- `site/`：Cloudflare Pages 發佈的網站檔案（Build output directory = `site`）。Push 到 `main` 後自動更新。
- 原始碼和建置程式在 Claude 交接壓縮檔（`web/build_web.py` 產生 `site/` 的內容）。
- 後端：Supabase 項目 tniqkwtaxrzwhjqrsiqg（`config.js` 內只有 publishable key，可公開；secret key 不可放進這裏）。
