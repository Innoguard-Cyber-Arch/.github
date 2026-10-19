# .github（組織公開首頁）

> [!WARNING]
> **請勿直接修改本 repo，也不要開 issue 或 PR。** 這裡的所有檔案都是發布結果，下次發布會整份覆蓋。

- **來源**：組織內部的來源 repo；組織成員可在成員首頁的「關於本頁」找到位置與修改方式。
- **同步方式**：維護者在本機執行發布腳本 `publish.sh --push`（不是 GitHub Actions，也沒有排程），腳本產生內容並通過發布前檢查後，整份覆蓋本 repo 並推送。

GitHub 從本 repo 的 `profile/README.md` 顯示組織公開首頁。
