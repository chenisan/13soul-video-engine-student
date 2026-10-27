# 13SoulMU 一般版（Standard）

Windows 本機影片剪輯與離線字幕工具，供個人學習與創作使用。

## 下載 2.1.1

**[下載 Windows 安裝檔（2.1.1，約 335 MB）](https://github.com/chenisan/13soul-video-engine-student/releases/download/v2.1.1/13SoulMU.Standard.Setup.2.1.1.exe)**

[版本說明與校驗碼](https://github.com/chenisan/13soul-video-engine-student/releases/latest) · [安裝與 MCP 使用說明](INSTALL_ZH-TW.txt)

系統需求：Windows 10／11 x64。安裝後即可剪輯，不需另外安裝 Node.js、Git、FFmpeg、Whisper 或模型。

安裝程式尚未數位簽章，Windows SmartScreen 可能顯示警告。請從本儲存庫的 Releases 下載，並使用發布頁的 SHA256SUMS.txt 核對檔案。

## 2.1.1 新功能

- 對外名稱統一改為「一般版」，保留既有專案與設定。
- 啟動時顯示 13soul 頻道介紹，可勾選「下次不再顯示」，也可從「設定 → 關於」重新開啟。
- 不包含 RVC 變聲、音色轉換、聲音複製及相關聲音模型。
- 設定頁新增「MCP 連線」，可用 Claude Code／Codex 操作剪輯。
- 提供 76 個工具：專案、匯入素材、時間軸、SRT、離線自動字幕與影片輸出。
- 建立專案可指定 16:9、9:16、1:1 等比例。
- AI 修改可即時出現在介面；舊版完整存檔遇到衝突時會被拒絕，避免覆蓋新修改。
- 修正合法素材網址被擋下、導致預覽黑畫面的問題。

## 使用方式

1. 安裝並開啟 13SoulMU Standard。
2. 建立專案、匯入影片與音訊、排時間軸並匯出。
3. 需要字幕時，開啟「字幕」面板並按「自動字幕」。音訊在本機辨識，完成後請自行校對。
4. 使用 MCP 時，到「設定 → MCP 連線」開啟功能，測試連線，再複製對應指令到 PowerShell 執行。
5. 從該 PowerShell 視窗啟動自己的 Claude Code／Codex，並保持一般版開啟。既有用戶端需要重新啟動。

MCP 預設關閉，只接受本機連線；連線金鑰在首次啟用時產生。更新金鑰或連接網址後，請重新設定用戶端。

剪輯與離線字幕不需 API Key。外部 AI 用戶端的網路、帳號與方案需求依各服務規定；執行 MCP 操作前請先儲存介面上的修改。

## 一般版範圍與隱私

一般版不包含配音、變聲、雲端 AI 生圖／生影片、分鏡板、前製或計費功能。離線字幕不會把音訊上傳雲端，專案與輸出保留在使用者電腦。

使用外部 AI 用戶端時，工具請求與回應由該用戶端處理，請依自己的資料保密需求使用；不要分享 mcp.json、連線金鑰或其他個人憑證。

## 授權與第三方元件

13SoulMU Standard 是專有軟體，並非開放原始碼。使用許可請參閱 [LICENSE](LICENSE)；FFmpeg、whisper.cpp 與 Whisper 模型等元件授權與來源請參閱 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。

問題請至 [Issues](https://github.com/chenisan/13soul-video-engine-student/issues) 回報，附上 Windows 版本與重現步驟，避免貼出私人影片或憑證。
