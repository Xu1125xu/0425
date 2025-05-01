# Gemini AI 圈圈叉叉遊戲

這是一個可以和 Google Gemini AI 對戰的圈圈叉叉（井字棋）網頁遊戲，支援自動判斷勝負，並可多次重新開始。

## 功能特色
- 玩家（O）對戰 Gemini AI（X）
- AI 會自動思考最佳下一步
- 三個圖案連成一線即結束遊戲，顯示勝負或平手
- 支援重新開始多局遊戲
- 美觀簡潔的介面

## 使用方式
1. 直接用 Chrome 或 Edge 開啟 `tictactoe_ai.html`。
2. 點擊空格下 O，AI 會自動下 X。
3. 只要有三個圖案連成一線，遊戲立即結束。
4. 點擊「重新開始」可再玩一局。

## 注意事項
- 若直接開啟 HTML 檔案遇到 CORS 或 API 連線問題，請改用本地伺服器（如 http-server）開啟。
- 若要自訂 AI 行為或 API 金鑰，請修改檔案開頭的 `API_KEY` 與 `API_URL`。

## 相關檔案
- `tictactoe_ai.html`：主遊戲網頁
- `server.js`（選用）：本地 Gemini Proxy Server（解決 CORS 問題）

---

如有任何問題或想要新增功能，歡迎提出！
