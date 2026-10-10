電費管家 iPhone 主畫面網頁 App（PWA）

功能：
- 台灣住宅累進級距電費試算（夏月/非夏月、單月/雙月）
- 歷史電費紀錄、前後期比較、CSV 匯出
- 冷氣耗電與每月費用估算
- 電費/度數門檻提醒

在 Windows 透過 GitHub Pages 發布：
1. 登入 https://github.com/ 並建立新 repository，名稱可用 electricity-manager，設為 Public。
2. 在 repository 頁面按 Add file > Upload files。
3. 上傳本資料夾內所有檔案（index.html、manifest.json、sw.js、icon-192.png、icon-512.png；README 可選）。請上傳檔案本身，不要只上傳外層資料夾。
4. 按 Commit changes。
5. 進入 Settings > Pages。
6. 在 Build and deployment 選 Deploy from a branch；Branch 選 main，資料夾選 /(root)，按 Save。
7. 等 Pages 發布完成，網址會顯示在 Settings > Pages，格式通常為 https://你的GitHub帳號.github.io/electricity-manager/。
8. 在 iPhone 用 Safari 開啟該 HTTPS 網址。點分享按鈕 > 加入主畫面 > 加入。

注意：
- 網站會公開在網路上，不要放個人敏感資料。
- 歷史紀錄與設定儲存在該 iPhone 的瀏覽器/網頁 App 本機資料中；清除網站資料或刪除網頁 App 可能會遺失，請定期匯出 CSV。
- 電價級距是可修改的參考值，不是即時台電費率；請依台電最新公告調整，實際帳單以台電為準。
- 超支檢查主要在開啟或操作 App 時進行，不能保證像原生 App 一樣在背景即時提醒。
