# 13SoulMU Student

13SoulMU Student 是給學生與個人學習使用的 Windows 本機影片剪輯工具。安裝後不需登入，也不需輸入 API Key。

## 下載

請到 [Releases](https://github.com/chenisan/13soul-video-engine-student/releases/latest) 下載最新版：

- `13SoulMU Student Setup 2.0.3.exe`
- 系統需求：Windows 10／11 x64

> 目前安裝程式尚未購買程式碼簽章憑證。Windows SmartScreen 可能顯示「Windows 已保護您的電腦」。請只從本 repository 的 Releases 下載，並用發布頁提供的 SHA-256 核對檔案。

## 使用方式

1. 執行安裝程式並完成安裝。
2. 開啟 13SoulMU Student。
3. 建立專案，匯入影片或音訊。
4. 如需字幕，開啟「字幕」面板並按「自動字幕」。辨識在本機離線執行，不必另外安裝 FFmpeg、Whisper 或模型。
5. 自動字幕可能有錯字，完成後請自行校對。處理時間依影片長度和電腦效能而異。

## 學生版範圍

學生版不包含配音、變聲、雲端 AI 生圖／生影片、分鏡板與前製功能。

## 隱私

學生版的離線字幕不會把音訊上傳到雲端。專案素材與輸出保留在使用者的電腦上。

## 授權與第三方元件

13SoulMU Student 是專有軟體，並非開放原始碼。個人與教育用途的使用許可請參閱 [LICENSE](LICENSE)。內含 FFmpeg、whisper.cpp 與 OpenAI Whisper 模型等第三方元件；相關授權及來源請參閱 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。

## 問題回報

請使用本 repository 的 [Issues](https://github.com/chenisan/13soul-video-engine-student/issues) 回報問題，並附上 Windows 版本、操作步驟與錯誤畫面。請勿貼出私人影片、API Key 或其他敏感資訊。
