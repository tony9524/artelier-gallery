
# Artelier｜藝境典藏

探索世界名畫與背後故事的靜態線上美術館。依照 `AGENTS.md` 開發，可持續新增畫作頁面。

## 技術
HTML5、CSS3、GitHub Pages。無資料庫、無建置步驟。

## 頁面
- `index.html`：首頁、名畫卡片、網站介紹。
- `artworks/starry-night.html`：《星夜》。
- `artworks/girl-with-pearl-earring.html`：《戴珍珠耳環的少女》。
- `artworks/night-watch.html`：《夜巡》。
- `style.css`：全站共用樣式。
- `AGENTS.md`：AI 新增、修改內容時應遵守的規範。

## 本機瀏覽
直接用瀏覽器開啟 `index.html`，或使用 VS Code Live Server。

## GitHub Pages
將本資料夾**內的所有檔案與資料夾**放在 Repository 根目錄，Settings → Pages → Deploy from a branch → main / (root)。等候部署後測試公開網址。

## 圖片與授權
本版本使用 Wikimedia Commons `Special:FilePath` 遠端圖片網址，未將圖片檔打包；因此瀏覽器需連網，且若 Commons 變更網址或限制連線，圖片可能無法顯示。`images/` 已預留供日後改用本機圖片。要改成本機圖片，先從下列來源下載**合適授權及尺寸**的圖片，放入 `images/`，並把首頁路徑改成 `images/檔名.jpg`、詳細頁路徑改成 `../images/檔名.jpg`。

- 《星夜》：https://commons.wikimedia.org/wiki/File:VanGogh-starry_night.jpg
- 《戴珍珠耳環的少女》：https://commons.wikimedia.org/wiki/File:Girl_with_a_Pearl_Earring.jpg
- 《夜巡》：https://commons.wikimedia.org/wiki/File:The_Night_Watch.jpg

請依各檔案說明頁確認再利用條款。作品歷史資料參考 MoMA、Mauritshuis、Rijksmuseum 官方介紹（詳見各頁底部）。

## AI 新增作品流程
先閱讀 `AGENTS.md` → 參考現有 `artworks/*.html` → 新增同結構頁面 → 更新首頁卡片 → 檢查圖片、路徑、手機版與資料來源。

## 開發工具
由 ChatGPT（GPT-6）輔助產生程式碼；提交作業前請自行測試實際 GitHub Pages 網站。
