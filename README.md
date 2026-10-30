# korean-daily-reading｜每日韓語跟讀

粉彩卡通模板網站。首頁是課程列表，點一張卡片就進入那一天的獨立課程頁面，每課配一張場景圖和一段音頻。

## 倉庫結構

- `index.html`：首頁，課程卡片列表（圖 + 場景 + 標題 + 進入連結）
- `style.css`：粉彩圓角卡片模板
- `lessons/*.html`：每天的獨立課程頁面（會話、翻譯、文法、詞彙、問題）
  - `lessons/cafe.html`：第 1 課 · 咖啡店點餐
  - `lessons/lunch.html`：第 2 課 · 和朋友約午飯
- `lessons/*.md`：課程的文字底稿
- `assets/*.jpg`：每課的場景圖
  - `assets/cafe.jpg`：咖啡店場景
  - `assets/lunch.jpg`：拌飯午飯場景
- `audio/*.mp3`：每課的跟讀音頻
  - `audio/cafe-vanessa.mp3`：咖啡店課，慢速女聲 Vanessa
  - `audio/lunch-female.mp3`：午飯課，慢速女聲

## 新增一天的課程（模板用法）

1. 在 `lessons/` 裡複製一課的 HTML，改成新一天的會話、翻譯、文法、詞彙和問題，圖片和音頻路徑改成新的檔名。
2. 在 `assets/` 裡放一張該場景的卡通圖，在 `audio/` 裡放一段該課的音頻。
3. 在 `index.html` 的課程列表裡加一張新卡片，連結到新課頁面。

## 本地預覽

直接用瀏覽器打開 `index.html` 即可，點卡片進入各課頁面。

## GitHub Pages

靜態網站，分支 `main`、資料夾 `/ (root)`，網址：https://joshuawalden1225.github.io/korean-daily-reading/

## 音頻和圖片說明

文字檔案用 GitHub MCP 快照推送；MP3 和 JPG 是二進位檔案，不能用快照推送，需要用 GitHub 網頁版上傳到對應資料夾（`audio/`、`assets/`），上傳完播放和圖片就都正常。在上傳之前，各課頁面上的「瀏覽器朗讀（備用）」按鈕可以用瀏覽器自帶的韓語語音朗讀課文。
