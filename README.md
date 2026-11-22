# 執行長辦公室｜禮品庫存管理

依據「執行長辦公室_酒類與送禮庫存資料.xlsx」製作的禮品庫存管理網頁。

## 內容

- `index.html`：主頁面（酒類庫存、收藏酒、禮盒、大謙堂禮盒、收禮記錄、送禮名單、已送出品項、酒櫃照片）

（照片與 Excel 資料都已內嵌在 index.html 裡，只有這一個檔案。）

## 用 GitHub Pages 開啟

1. 把這個資料夾的所有檔案上傳到 repository 根目錄
2. 到 **Settings → Pages**，Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾 `/ (root)`
3. 等一兩分鐘，網址會是 `https://<你的帳號>.github.io/<repo 名稱>/`

## 注意

- 在 GitHub Pages 上，修改的資料會存在**各自瀏覽器**（localStorage），不會跨電腦同步。請用右上角「匯出資料」定期備份成 JSON，換電腦時再「匯入資料」。
- 若 repository 是公開的，任何人都看得到裡面的送禮對象與金額，建議設為 **Private**（私有 repo 使用 Pages 需付費方案），或確認內容可以公開。
