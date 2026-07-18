# GitHub Pages 靜態暫停頁

這是一個可直接部署到 GitHub Pages 的靜態網站，內容為「網站建置中，近期上線」。

## 檔案

- `index.html`：首頁
- `styles.css`：版面與響應式樣式
- `script.js`：自動更新頁尾年份
- `404.html`：GitHub Pages 找不到頁面時顯示相同暫停訊息
- `.nojekyll`：避免 GitHub Pages 使用 Jekyll 處理靜態檔案

## 部署到 GitHub Pages

1. 將此資料夾內的檔案放到 GitHub repository 根目錄，或放到 `docs/` 資料夾。
2. 到 repository 的 `Settings` > `Pages`。
3. `Source` 選擇 `Deploy from a branch`。
4. 如果檔案放在根目錄，選擇 `main` / `/root`；如果放在 `docs/`，選擇 `main` / `/docs`。
5. 儲存後等待 GitHub Pages 完成部署。

部署完成後，網站網址通常會是：

```text
https://你的帳號.github.io/你的repository名稱/
```
