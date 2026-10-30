# korean-daily-reading｜每日韓語跟讀

粉彩卡通風格、簡約版網站與課程庫，全部內容放在同一個倉庫裡。

## 倉庫結構

- `index.html`：網站首頁，今天的跟讀 + 全部課程列表
- `style.css`：粉彩圓角卡片風格
- `lessons/`：每課的完整內容（韓文會話、繁體翻譯、文法、詞彙）
  - `cafe-ordering.md`：咖啡店點餐
  - `lunch-with-friend.md`：和朋友約午飯
- `audio/`：跟讀音頻（MP3）
  - `cafe-vanessa.mp3`：咖啡店課，慢速女聲 Vanessa
  - `lunch-female.mp3`：午飯課，慢速女聲

之後每天的新課按「一課一檔案」加到 `lessons/`，音頻加到 `audio/`，首頁同步加一個卡片即可。

## 本地預覽

直接用瀏覽器打開 `index.html` 即可。

## GitHub Pages

本倉庫為靜態網站，推到 GitHub 後在 Settings → Pages → Branch 選 `main`、資料夾 `/ (root)`，儲存後即可用 `https://<用戶名>.github.io/korean-daily-reading/` 訪問。

## 音頻說明

網站裡的 `<audio>` 指向 `audio/` 裡的 MP3。
由於 GitHub MCP 快照推送不支援二進位檔案，這兩個 MP3 需要另外上傳：到 GitHub 網頁版倉庫裡，點 Add file → Upload files，把本地 `audio/` 裡的兩個 MP3 拖進去即可，之後音頻播放就會正常。
在上傳之前，頁面上的「瀏覽器朗讀（備用）」按鈕可以用瀏覽器自帶的韓語語音朗讀課文。
