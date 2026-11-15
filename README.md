# 一首歌的重量｜GitHub Pages 發布版

## 最簡單的發布方法（不需要安裝程式）

1. 登入 GitHub，點右上角「＋」→「New repository」。
2. Repository name 輸入 `song-museum`，選 Public，勾選 Add a README file，點 Create repository。
3. 解壓縮本 ZIP。到新儲存庫點 Add file → Upload files。
4. 將解壓後的 index.html、favicon.svg、assets 資料夾及 exhibits 資料夾全部拖進上傳區。請不要直接上傳 ZIP，也不要多包一層資料夾。README.md 可一併覆蓋。
5. 點 Commit changes。
6. 到 Settings → Pages。在 Build and deployment 選 Deploy from a branch，Branch 選 main，資料夾選 /(root)，點 Save。
7. 等待 Pages 的部署完成。網址會顯示在同一頁；以 GitHub 實際顯示的網址為準。

## 功能與部署

- 這是已完成編譯的靜態網站，可直接放在 GitHub Pages 的專案子路徑。
- 訪客不需登入，網址使用 github.io，不必購買網域。
- 保留大廳、取號、四個展區、音效、倒帶、選曲、跑字試唱與圖片。
- 音樂由 YouTube 提供，部分影片可能受地區或嵌入設定限制。
- 共用留言仍連到既有展覽的公開 API，並非 GitHub 提供的資料庫。因此請保留原展覽服務運作；若未來要完全移除原服務，需另遷資料庫與 API。
- 留言 API：https://weight-of-a-song-1990.kichiaai.chatgpt.site/api/messages
- 僅允許 HTTPS 的 github.io 網站從瀏覽器跨站讀寫留言；沒有內含密碼或金鑰。
- 專輯文字封套為策展視覺設計，文件附圖另行標示。跑字試唱為原創內容。

## 檔案位置

index.html 必須位於儲存庫最外層，與 assets 和 exhibits 資料夾並列。
請完整上傳資料夾內的檔案，避免只上傳 index.html 導致空白畫面。
