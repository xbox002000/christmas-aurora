# 這個專案的規矩

- 成品是**單一檔案** `index.html`。不要拆成多檔、不要引入建置流程、不要加 `package.json` 或 `node_modules`。
- Three.js 從 CDN 載入，用 `<script type="importmap">` + ES module，版本固定（例如 `three@0.169.0`），不要用 `latest`。
- 不要依賴任何外部模型檔（`.glb`/`.gltf`/貼圖）；所有幾何、材質、粒子都用程式生成。
- 預覽方式：直接用瀏覽器開 `index.html`（需要網路載 CDN）。
- 提交前自己檢查：HTML 開頭有 `<!DOCTYPE html>`、`<meta name="viewport">`、canvas 撐滿視窗、`resize` 有處理、`requestAnimationFrame` 迴圈有在跑。
- commit 訊息用 `feat:` / `fix:` / `docs:` 前綴，一行說清楚改了什麼。