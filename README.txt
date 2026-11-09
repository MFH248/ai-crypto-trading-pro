# AI Crypto Trading Pro — iPhone PWA 原型

## 這是什麼
這是一個可在 iPhone Safari 使用、部署到 HTTPS 網址後可加入主畫面的 PWA 網頁 APP。無需 Mac、Xcode 或 App Store。

## 目前功能
- Bitget 公開 API 讀取 BTCUSDT / ETHUSDT USDT 永續合約行情
- 15m / 30m / 1h K 線資料
- EMA20/EMA50 趨勢、RSI、MACD、成交量、ATR 規則評分
- 參考進場、ATR 停損與風險報酬比停利價
- 本機訊號紀錄與風險設定
- 60 秒更新

## 重要限制
- 這是早期原型，尚未完成策略回測、正式訊號驗證或交易績效統計。
- 訊號評分不是勝率，也不代表獲利機率。
- 使用最新 K 線，可能包含未收盤 K 線；不要直接以此下單。
- 沒有自動下單、背景監控或推播通知。
- 僅使用 Bitget 公開行情端點，不需要 API Key。
- 必須部署在 HTTPS 網站，才能可靠地以 PWA 方式加入 iPhone 主畫面。

## 部署方式（可用 iPhone 操作）
1. 將本 ZIP 解壓縮。
2. 將資料夾內所有檔案上傳到支援 HTTPS 靜態網站的主機（例如 GitHub Pages）。
3. 開啟網站 HTTPS 網址，在 iPhone Safari 點「分享」>「加入主畫面」。
4. 從主畫面圖示啟動。

如果只把 index.html 存在手機「檔案」中直接開啟，仍可當一般網頁測試，但 PWA 安裝、快取等功能不保證正常。
