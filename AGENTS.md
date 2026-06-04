# 教育最前線 — AGENTS.md

## 專案入口

專案名稱：教育最前線
專案用途：教育相關事宜
主要工作目錄：`C:\Users\tolkien\Downloads\opencode\edu`
GitHub repo：`https://github.com/tolkien-eng/edu--01`
預設 branch：`main`

## Obsidian 對應筆記

Obsidian vault：`C:\Users\tolkien\Documents\Secondbrain`
專案駕駛艙：`教育最前線/專案工作流程.md`

## 工作桌 + 三個家

- 工作桌：`C:\Users\tolkien\Downloads\opencode\edu`
- GitHub：`https://github.com/tolkien-eng/edu--01`
- Obsidian：`C:\Users\tolkien\Documents\Secondbrain` → `教育最前線/專案工作流程.md`

## 同步規則

開工時：
- 使用 `startup-sync` 流程
- 讀本檔
- 讀 Obsidian 駕駛艙
- 檢查 Git 狀態
- 不自動 pull / commit / push

收工時：
- 使用 `shutdown-sync` 流程
- 更新 Obsidian 駕駛艙
- 如規則、路徑、專案邊界改變才更新本檔
- 需要時 commit + push GitHub

新專案初始化時：
- 使用 `project-init-sync` 流程

## 主要檔案

入口檔：待開發
設定檔：待開發
部署位置：GitHub Pages（`https://tolkien-eng.github.io/edu--01`）

## 不要做

- 不要把每日進度寫進 AGENTS.md
- 不要自動納入無關 git 變更
- 不要把 API key、token、密碼寫進 repo
- 不要儲存學生姓名；正式資料只用座號與班級代號
