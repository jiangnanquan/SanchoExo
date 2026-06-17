<div align="right">
  <a href="./README.md">简体中文</a> |
  <a href="./README.zh-TW.md">繁體中文</a> |
  <a href="./README.en.md">English</a> |
  <a href="./README.ja.md">日本語</a> |
  <a href="./README.ko.md">한국어</a> |
  <a href="./README.es.md">Español</a> |
  <a href="./README.fr.md">Français</a> |
  <a href="./README.de.md">Deutsch</a> |
  <a href="./README.ru.md">Русский</a> |
  <a href="./README.pt-BR.md">Português</a> |
  <a href="./README.ar.md">العربية</a> |
  <a href="./README.hi.md">हिन्दी</a> |
  <a href="./README.id.md">Bahasa Indonesia</a> |
  <a href="./README.th.md">ไทย</a> |
  <a href="./README.vi.md">Tiếng Việt</a> |
  <a href="./README.tr.md">Türkçe</a> |
  <a href="./README.pl.md">Polski</a> |
  <a href="./README.he.md">עברית</a>
</div>

<div align="center">

# SanchoExo

**本地 AI 數據研判工作台 (Local AI Data Operating Room)**

將可執行模板、智能 AI、DuckDB OLAP、可審計 Cell、結構化視覺化語言和巡檢飛輪融入精緻安全的桌面軟體，讓數據研判在本地爆發性能。

[官方網站 (sanchoexo.com)](https://sanchoexo.com) · [下載](#下載) · [功能](#打破聊天框侷限重塑本地數據研判) · [反饋](https://github.com/jiangnanquan/SanchoExo/issues)

<img src="./website/img/app-portal-page.png" alt="SanchoExo Portal" width="100%">

</div>

---

## 極客的核心堅持

- **100% 本地存儲（隱私極客）** — 數據絕對不出本地，為您的隱私與機密安全負責，打造絕對安全的個人數據堡壘。
- **零配置 開箱即用（部署體驗）** — 無需繁雜的部署服務，內置 Python 環境、DuckDB 計算引擎，下載即刻投入高密度研判。
- **Harness Engineering（全鏈路駕馭）** — 摒棄浮於表面的聊天框。大模型被深度編排進數據平面的每一環，在受控、可審計的鏈路下主導節點巡檢與報告生成。

---

## 打破聊天框侷限，重塑本地數據研判

數據研判需要嚴謹的計算推理與可復用的經驗。SanchoExo 將分析過程轉變為可執行、可追溯、可沉澱的本地有機系統。

### 01 / PROCESS SYSTEM - 可執行模板系統
SanchoExo 的模板是研判經驗的可執行封裝。它搭起包含章節結構、口徑約束和檢查點的骨架，AI 沿著骨架編寫 Cell 計算，實現方法論的直接落地，告別從零開始的迷茫。

### 02 / AGENT INTEGRATION - 智能輔助研判
Queen 能全面理解項目、筆記本 Cell 單元、本地知識庫和工具，支持連續追問、深層巡檢與複雜數據報告的生成。

<img src="./website/img/app-notebook-dark.png" alt="Unified Notebook" width="100%">

### 03 / PERFORMANCE CORE - 極速 DuckDB OLAP
內置輕量級列式計算核心。本地百萬級 CSV、Excel 和數據庫直連無需部署服務，極速響應，杜絕數據搬運成本。

### 04 / EXPERIENCE RECYCLE - 分析經驗回流飛輪
Notebook Cell、數據脈絡、巡檢異常與視覺化偏好在分析中自動沉澱。高價值方法論被不斷蒸餾並回流到模板，讓軟體越用越聰明，越來越理解您的研判習慣。

<img src="./website/img/app-data-inspection.png" alt="Data Inspection" width="100%">

### 05 / VISUAL LANGUAGE - SanchoVis 視覺化
利用結構化指令，Cell 能夠以極其穩定的預期生成圖表，自動交給 SanchoVis 渲染器，完美復現專業分析口徑。

### 06 / DESKTOP COMPACT - 一鍵即跑環境
開箱即用。Python 依賴、SQL 執行器、瀏覽器自動化代理和知識庫處理運行時深度整合打包，告別繁重環境搭建。

### 07 / GLOBAL REACH - 原生多語言體驗
原生支持全球 18 種語言介面無縫切換，無論您身處何地，都能在最熟悉的母語語境下流暢開展深層研判。
支持的語言包括：簡體中文、繁體中文、English (英語)、日本語 (日語)、한국어 (韓語)、Español (西班牙語)、Français (法語)、Deutsch (德語)、Русский (俄語)、Português (葡萄牙語)、العربية (阿拉伯語)、हिन्दी (印地語)、Bahasa Indonesia (印尼語)、ไทย (泰語)、Tiếng Việt (越南語)、Türkçe (土耳其語)、Polski (波蘭語) 以及 עברית (希伯來語)。

---

## 研判故事鏈路

絕大多數工具僅切入局部分析環節。SanchoExo 將導入、計算、視覺化、巡檢追問與沉澱分享，無縫咬合在同一條本地流水線上。

1. **數據平滑接入**：本地 Excel、CSV 報表、外部業務數據庫以及網頁結構化抽取，100% 留在本地，零延遲進入同一安全分析空間。
2. **極限關聯計算**：Cell 直接充當計算單元，由 DuckDB 提供極速支撐，中間體結果源源不斷且高度安全地流向下一計算環節。
3. **精準意圖表達**：SanchoVis 視覺化指令高度規範圖表渲染，拋棄浮躁，具備極高可讀性與確定性的口徑對齊能力。
4. **主動巡檢追問**：AI 引擎根據節點與鏈路拓撲圖譜自動巡檢數據異常，主動提出核心洞察，徹底追蹤回放推理過程。
5. **閉環經驗蒸餾**：高價值結論以 Notebook 的形式持久存留，重複研判流程被不斷提煉並回灌飛輪，轉化為下次任務的墊腳石。

---

## 下載

支持 macOS、Windows、Linux 三平臺。

| 平臺    | 架構                        | 下載                |
| ------- | --------------------------- | ------------------- |
| macOS   | Apple Silicon (M1/M2/M3/M4) | [下載 .dmg](#)      |
| Windows | x64                         | [下載 .exe](#)      |
| Linux   | x64                         | [下載 .AppImage](#) |

> 系統要求：macOS 12+、Windows 10+、Ubuntu 20.04+
>
> AI 功能需要您自己的 API Key（支持 DeepSeek、通義千問、Kimi、MiniMax、Anthropic、Gemini、OpenAI 等）

---

## 反饋與支持

- **Bug 反饋**：[GitHub Issues](https://github.com/jiangnanquan/SanchoExo/issues)
- **功能建議**：[GitHub Discussions](https://github.com/jiangnanquan/SanchoExo/discussions)
- **郵箱**：jiangnanquan@gmail.com

---

<div align="center">

**SanchoExo** — 100%本地存儲 | 零配置開箱即用的 AI 研判台

Copyright &copy; 2024-2026 JNQ (江南泉). All rights reserved.

</div>
