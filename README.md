# BillSync Public Portfolio Site

BillSync／固定支出管家的公開作品介紹頁。這是一個獨立、純靜態的網站，不包含 BillSync 私有應用程式原始碼、憑證或使用者資料。

## Local preview

在此目錄執行：

```bash
python -m http.server 8080
```

接著開啟：

```text
http://localhost:8080/
```

## Files

- `index.html`：單頁內容與語意結構
- `styles.css`：設計 tokens、響應式布局與視覺樣式
- `.gitignore`：排除本機、機密與 QA 暫存檔

網站不需要 Node.js、bundler、JavaScript framework、backend 或 database。

## Intended publication

- Repository: `R901111/billsync-site`
- Visibility: Public
- GitHub Pages URL: `https://R901111.github.io/billsync-site/`

目前只準備本機版本。請在內容與視覺驗收後，才建立公開 repository 並啟用 GitHub Pages。

## Publication checklist

1. 確認頁面沒有 secrets、token、私人資料或本機絕對路徑。
2. 確認沒有連到私有 BillSync repository。
3. 重新執行 Desktop 與 375px browser validation。
4. 建立空的 public `R901111/billsync-site` repository。
5. 將這個已準備好的本機 Git repository 加入新的 `origin`，再 push 到 `main`。
6. 在 GitHub Pages 設定中選擇由 `main` branch root 發布。
