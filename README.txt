【GitHub Pages 專屬網站包 使用說明書】

為了解決直接拖曳資料夾會找不到檔案的 Bug，這個壓縮檔已經過特殊設計。
解壓縮後，您會看到以下檔案與一個名為 assets 的空資料夾：

  ├── index.html       (已經寫好精美排版與所有程式碼，免改 Code)
  └── assets/          (專門存放媒體成果檔案的資料夾)

請依照以下步驟把真實檔案放進去並上傳：

第一步、放置真實檔案
請將您手邊的真實成果檔案「重新命名」為下方對應的檔名，並放進 `assets/` 資料夾內：
1. 完整研究報告 ── 改名為 `完整研究.pdf`
2. 10頁PPT簡報   ── 改名為 `PPT.pdf`
3. Podcast音檔   ── 改名為 `學校午餐比宅配有機菜好賺 (mp3cut.net).mp3`
4. Podcast逐字稿 ── 改名為 `逐字稿.pdf`
5. 教學影片      ── 改名為 `clideo_editor_ed8759b6c68d4782a7c212b4ea258b6b.mp4`

第二步、如何上傳到 GitHub（完美避開資料夾 Bug 的兩種方法）

【方法 A：最推薦、最不會出錯！使用 GitHub 網頁手動建立】
1. 登入您的 GitHub 專案儲存庫 (Repository)。
2. 先把外層的 `index.html` 直接拖曳進去儲存庫根目錄並 Commit 儲存。
3. 點擊網頁右上角的「Add file」 -> 「Create new file」。
4. 在輸入檔名的地方，輸入 `assets/README.txt`（當你打完 assets/ 時，GitHub 就會自動在根目錄幫你建好名為 assets 的資料夾了！）。
5. 點最底下的 Commit 儲存。
6. 點回 GitHub 首頁，點擊剛剛自動產生出來的 `assets` 資料夾進入內部。
7. 點擊右上角「Add file」 -> 「Upload files」，把你第一步改好檔名的 5 個真實研究成果檔案，一次全選拖曳進來上傳。大功告成！

【方法 B：使用 GitHub Desktop 電腦版軟體】
1. 將本壓縮檔解壓出來的所有檔案（index.html 和 assets 資料夾），直接複製到你電腦上與 GitHub 連動的本地專案資料夾。
2. 將重新命名好的 5 個成果檔案放進 assets 資料夾中。
3. 打開 GitHub Desktop 軟體，左下角會自動偵測到所有新檔案，點擊「Commit to main」，再點擊右上角的「Push origin」同步上傳。大功告成！
