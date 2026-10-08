# 春豬工作室｜前台與後台設計示範

獨立新專案，不會修改原網站。

- 前台：https://ninthlab99-netizen.github.io/harui-studio-design/
- 後台：https://ninthlab99-netizen.github.io/harui-studio-design/admin/
- 示範密碼：123456

後台修改僅儲存於操作的瀏覽器，不會同步所有訪客。請勿存放機密資料。

## 來源與發布

完整原始碼保存在 harui-source.zip（不含 Git 記錄或本機暫存）。GitHub Actions 會解開來源、執行測試，再以原本的 Node 靜態產生器建置和發布 GitHub Pages。

修改時先解壓縮，編輯 content、src/assets 或 admin；本機 node build.mjs 後可預覽。將更新後的來源打包替換 harui-source.zip，即可重新發布。品牌設計說明見壓縮包內 DESIGN.md。
