# 驗證截圖（PR #2 / Issue #1）

這是「極光下的漂浮聖誕樹」（`index.html`）的驗證截圖，放在獨立分支 `agent/aurora-tree-scene-57ead0ea0826-screenshots`，不影響 `main` 的成品。截圖由無頭 Chrome（CDP + SwiftShader 軟體算圖）實際載入 `file://` 版本的 `index.html` 取得。

| 檔案 | 內容 | 視窗 | 版本 |
| --- | --- | --- | --- |
| `before.png` | 改動前的 `main`（repo 只有 `README.md`，還沒有 `index.html`，所以瀏覽器呈現的是 README 文字頁） | 1200×675 | `af96833`（PR 建立時的 `main`） |
| `after.png`、`after-desktop.png` | 改動後的場景：夜空的極光光幕、漂浮聖誕樹與浮島、結冰湖面反射、雪花、HUD | 1200×675 | `b59d2a0`（PR #2 head） |
| `after-click.png` | 點擊樹上的裝飾球：該球爆亮，並噴出金色粒子，同時有暖色光暈 | 1200×675 | `b59d2a0` |
| `after-mobile.png` | 手機直向版面，整棵樹與浮島都在畫面內 | 390×844 | `b59d2a0` |

所有截圖都是同一場景、同一主題（深色夜間風格）、相同相機初始角度，差別只在於改動前後的版本與視窗大小。
