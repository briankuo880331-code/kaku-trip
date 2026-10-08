# kaku trip ・ 2026 名古屋・岐阜・伊勢志摩 8 天 7 夜

單一 `index.html`，沒有任何建置步驟，直接用 GitHub Pages 就能上線。

## 本機預覽
直接用瀏覽器打開 `index.html` 即可。

## 修改行程
行程資料都在 `index.html` 最下方 `<script>` 裡的 `DAYS` 陣列，每一筆：
- `t` 時間（`"HH:MM-HH:MM"`）
- `c` 類別：transport / sight / food / hotel / shop（決定顏色）
- `i` emoji、`k` 類別文字、`n` 名稱
- `note` 補充說明（選填）
- `m` Google Maps 搜尋關鍵字（選填，有填才會出現地圖按鈕）
- `w` 官網網址（選填）
- `b` 標籤：`["ok","預約完成"]`、`["warn","現場排隊"]`、`["star","行程重點"]`（選填）

備註、花費、完成狀態、購物清單都存在瀏覽器 localStorage，不會上傳任何地方。
