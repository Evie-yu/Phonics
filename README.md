# 🌈 Phonics 發音遊樂園

適合兒童的互動式 Phonics 網頁。

## GitHub Pages 上線方法

1. 登入 GitHub，新增公開 repository，名稱建議為 `phonics-playground`。
2. 將本 ZIP 的 `index.html`、`.nojekyll` 和 `README.md` 上傳到 repository **根目錄**（不要直接上傳 ZIP）。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**，Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
5. 等 GitHub Pages 部署完成，造訪 `https://你的帳號.github.io/phonics-playground/`。

## 使用注意

- 單字朗讀使用瀏覽器內建語音合成（Web Speech API），必須由使用者點擊才播放。
- Microsoft Jenny Online (Natural) 只有在裝置／瀏覽器實際提供時才可選用，GitHub Pages 不會額外提供這個聲音。
- 語音合成與音質因裝置和瀏覽器而異，建議以 Chrome、Edge、Safari 測試。
- 獨立音素沒有加入未經驗證的模擬音檔。
