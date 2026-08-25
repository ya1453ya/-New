請把 index.html 原本「旅遊資訊」整個區塊替換成 travel-info-4cards-force.html 的全部內容。

這次使用獨立 pq-travel-info class，並在 grid 上使用 !important：
grid-template-columns: repeat(4,minmax(0,1fr)) !important;

因此桌機不會再被你原本網站的 CSS 改成兩排。
只有螢幕寬度 600px 以下的手機才會改成一欄。

上傳後：
1. Commit changes
2. 等 GitHub Pages 綠色部署完成
3. 網頁按 Ctrl + F5 強制重新整理
