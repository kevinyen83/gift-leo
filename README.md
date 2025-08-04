# RickRoll Prank GitHub Pages Template

這是一套可以放到 GitHub Pages 的惡搞頁面結構：  
掃 QR Code 先到一個偽裝的「解鎖／驗證」landing page，點一下之後跳到播放頁，盡可能在 Chrome 上獲得有聲自動播放體驗。

## 內容
- `landing.html`: 偽裝驗證/載入頁，用來先取得 user gesture。
- `player.html`: 播放頁，會播放 `rickroll.mp4`（需要你自己提供）。
- **你需要自己準備** `rickroll.mp4` 放在同一目錄下（合法來源自行取得影片副本）。

## 如何使用（部署到 GitHub Pages）
1. 建一個 public 的 GitHub repository（例如 `rickroll-prank`）。
2. 把這個資料夾裡的 `landing.html`、`player.html`、`README.md` 上傳到 repo 根目錄。
3. 把你合法取得的 Rick Astley - Never Gonna Give You Up 影片重新命名為 `rickroll.mp4` 並上傳到同一個位置。
4. 到 repo 的 **Settings > Pages**：
   - Source 選 `main` branch，根目錄 (`/`)。
   - Save，等幾分鐘會顯示你的 Pages 網址，例如:
     `https://yourusername.github.io/your-repo/landing.html`
5. 把 `landing.html` 的網址做成 QR Code 發給朋友，掃了後點一次「繼續」，會跳到有聲播放頁。

## 偽裝建議（讓惡搞更有效）
- QR Code 描述寫成：「下載報告」、「檢查你的資料」、「確認身份」之類的。  
- 可以把 `landing.html` 改標題、文字讓它看像公司內部流量、客服驗證、會議資源等。

## 注意
- 影片檔 `rickroll.mp4` **請自行合法取得**。  
- 手機瀏覽器仍可能因瀏覽器策略在第一次沒聲音，需要點一次 fallback 按鈕。
