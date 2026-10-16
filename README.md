# ChainScope · AI 供應鏈股票追蹤（股市探針）

以台股 AI 供應鏈為主軸的股票追蹤：依技術主題看產業地圖、即時行情、基本面與 AI 分析。

**線上使用**：https://kftseng2oo1.github.io/stock/

## 主要功能
- 技術主題：CoWoS、CoPoS、矽光子、AI 伺服器、HBM 記憶體
- 產業層級：上游材料／設備、中游製造代工、下游系統整合
- 三種檢視：⬡ 產業地圖、▤ 股票列表、◈ 技術路線圖
- 個股：即時股價（自動刷新）、基本面、題材與近期消息，以及 AI 解讀
- 手機版有獨立的選單與個股頁

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- 後端：`twinklehub.kftseng2oo1.workers.dev`（`/twse-proxy` 行情、`/goodinfo-proxy` 基本面、`/claude` AI 分析）

## 備註
- 資料與 AI 分析僅供參考，不構成投資建議。
