# ClassBuddy 🌟 班級互動工具箱

ClassBuddy 是一款專為國小/國中資訊課與日常教學設計的免主機、輕量級互動網頁工具。結合 Google Classroom 同步，讓老師在大螢幕上能輕鬆點名、隨機抽籤、小組加分，並進行課堂噪音偵測與分組。

🌐 **線上使用網址 (Demo)**：[https://cagoooo.github.io/classroom-rollcall-picker/](https://cagoooo.github.io/classroom-rollcall-picker/)

---

## ✨ 核心功能特色

1. **🎯 班級抽籤工具**：
   * **幸運大轉盤** 與 **電子拉霸機** 雙模式。
   * 支援「排除已中籤學生」的不重複抽籤機制。
   * **中籤語音朗讀 (TTS)**：自動使用台灣繁中女聲唸出「恭喜林俊傑中籤！」，提升學生專注度，並可與全域音效連動及即時打斷。

2. **📋 線上點名系統**：
   * 智慧統計出席、請假與缺席人數。
   * 支援一鍵全部出席與重置。
   * 提供點名結果一鍵複製文字報告，或匯出 CSV 出席檔案。

3. **🏆 小組積分榮譽榜**：
   * 支援自訂小組名稱與代表色。
   * 支援分數即時加減，並可勾選「根據分數自動排序」。

4. **👥 隨機團隊分組器**：
   * 可設定「固定分組數」或「固定每組人數」。
   * 一鍵將班級名單隨機打散分組。

5. **🔊 教室環境分貝監測**：
   * 趣味泡泡噪音計，音量過大時泡泡會晃動並破裂。
   * 可設定破裂音量閾值與靈敏度，引導班級保持安靜。

6. **🔗 Google Classroom 智慧同步 (零金鑰洩漏設計)**：
   * 老師可貼上自己申請的 Google Client ID，直接在前端與您的 Classroom 帳號安全連結。
   * 一鍵載入您的課程清單與學生名冊，省去手動登打的麻煩。
   * 內建展開式「憑證申請三步圖文指南」與「當前網域來源一鍵複製」功能，大幅降低設定門檻。

---

## 🛠️ 本地開發與運行

本專案採用純前端靜態架構 (Vanilla JS + HTML + CSS)，不需安裝額外的後端伺服器：

1. 複製此專案：
   ```bash
   git clone https://github.com/cagoooo/classroom-rollcall-picker.git
   ```
2. 使用本機 Web 伺服器開啟（例如 Python HTTP 伺服器）：
   ```bash
   cd classroom-rollcall-picker
   python -m http.server 5500
   ```
3. 在瀏覽器打開 [http://localhost:5500](http://localhost:5500) 即可使用。

---

Made with ❤️ by [阿凱老師](https://ipad.smes.tyc.edu.tw)
