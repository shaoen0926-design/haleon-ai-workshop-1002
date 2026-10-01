# Haleon AI 職場實作課
課程日期：2026-10-02

- 網站：https://shaoen0926-design.github.io/haleon-ai-workshop-1002/
- 下載區：https://shaoen0926-design.github.io/haleon-ai-workshop-1002/#downloads
- 投影 QR Code：https://shaoen0926-design.github.io/haleon-ai-workshop-1002/qr.html
- 學員素材整包：https://shaoen0926-design.github.io/haleon-ai-workshop-1002/downloads/course-materials.zip

## 發布結構
- index.html：唯一的主要實作頁，包含所有練習與複製提詞。
- downloads/excel：內勤、外勤各一份共用 Excel。
- downloads/materials：M-01 至 M-20 與外勤診所清單文字備份。
- downloads/prompts：各單元與全課提詞，按目前網頁匯出。
- downloads/research：兩篇原始研究 PDF；授權見 SOURCES.txt。
- downloads/handouts：原始學員參考附件，部分題號較舊，以網頁為準。
- downloads/course-materials.zip：學員全部素材。
- assets/course-qr.png、assets/course-qr.svg、qr.html：分享與投影用 QR Code。
- downloads/manifest.json：素材檔案大小及 SHA-256 校驗值。

## GitHub Pages
使用 main 分支根目錄發布。保留 .nojekyll，避免教材目錄被 Jekyll 處理。
網站、下載檔案及 QR Code 均由同一個 GitHub Pages 網站提供，不依賴雲端硬碟。

目前目錄中的舊版 HTML 與歷史頁面透過 .gitignore 排除；講師教案和解答卡保留於原始課程資料夾，不在學員公開包內。
更新網頁時同步更新 downloads/prompts 與素材 ZIP；Excel 同名檔案可直接替換。

教學虛構素材與外部研究分開標示。兩篇研究依 CC BY 4.0 保留原檔與來源署名。
