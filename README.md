<!--
  README 多语言维护提示：
  根目录只保留 GitHub 首页展示用的简体中文 README.md。
  其他语言版本统一放在 docs/readme/，更新首页文案时请同步维护该目录和下面的语言导航。
-->

<div align="right">
  <a href="./README.md">简体中文</a> |
  <a href="./docs/readme/README.zh-TW.md">繁體中文</a> |
  <a href="./docs/readme/README.en.md">English</a> |
  <a href="./docs/readme/README.ja.md">日本語</a> |
  <a href="./docs/readme/README.ko.md">한국어</a> |
  <a href="./docs/readme/README.es.md">Español</a> |
  <a href="./docs/readme/README.fr.md">Français</a> |
  <a href="./docs/readme/README.de.md">Deutsch</a> |
  <a href="./docs/readme/README.ru.md">Русский</a> |
  <a href="./docs/readme/README.pt-BR.md">Português</a> |
  <a href="./docs/readme/README.ar.md">العربية</a> |
  <a href="./docs/readme/README.hi.md">हिन्दी</a> |
  <a href="./docs/readme/README.id.md">Bahasa Indonesia</a> |
  <a href="./docs/readme/README.th.md">ไทย</a> |
  <a href="./docs/readme/README.vi.md">Tiếng Việt</a> |
  <a href="./docs/readme/README.tr.md">Türkçe</a> |
  <a href="./docs/readme/README.pl.md">Polski</a> |
  <a href="./docs/readme/README.he.md">עברית</a>
</div>

<div align="center">

# SanchoExo

**本地 AI 数据研判工作台 (Local AI Data Operating Room)**

将可执行模板、智能 AI、DuckDB OLAP、可审计 Cell、结构化可视化语言和巡检飞轮融入精致安全的桌面软件，让数据研判在本地爆发性能。

[官方网站 (sanchoexo.com)](https://sanchoexo.com) · [下载](#下载) · [功能](#打破聊天框局限重塑本地数据研判) · [反馈](https://github.com/jiangnanquan/SanchoExo/issues)

<img src="./website/img/app-portal-page.png" alt="SanchoExo Portal" width="100%">

</div>

---

## 极客的核心坚持

- **100% 本地存储（隐私极客）** — 数据绝对不出本地，为您的隐私与机密安全负责，打造绝对安全的个人数据堡垒。
- **零配置 开箱即用（部署体验）** — 无需繁杂的部署服务，内置 Python 环境、DuckDB 计算引擎，下载即刻投入高密度研判。
- **Harness Engineering（全链路驾驭）** — 摒弃浮于表面的聊天框。大模型被深度编排进数据平面的每一环，在受控、可审计的链路下主导节点巡检与报告生成。

---

## 打破聊天框局限，重塑本地数据研判

数据研判需要严谨的计算推理与可复用的经验。SanchoExo 将分析过程转变为可执行、可追溯、可沉淀的本地有机系统。

### 01 / PROCESS SYSTEM - 可执行模板系统
SanchoExo 的模板是研判经验的可执行封装。它搭起包含章节结构、口径约束和检查点的骨架，AI 沿着骨架编写 Cell 计算，实现方法论的直接落地，告别从零开始的迷茫。

### 02 / AGENT INTEGRATION - 智能辅助研判
Queen 能全面理解项目、笔记本 Cell 单元、本地知识库和工具，支持连续追问、深层巡检与复杂数据报告的生成。

<img src="./website/img/app-notebook-dark.png" alt="Unified Notebook" width="100%">

### 03 / PERFORMANCE CORE - 极速 DuckDB OLAP
内置轻量级列式计算核心。本地百万级 CSV、Excel 和数据库直连无需部署服务，极速响应，杜绝数据搬运成本。

### 04 / EXPERIENCE RECYCLE - 分析经验回流飞轮
Notebook Cell、数据脉络、巡检异常与可视化偏好在分析中自动沉淀。高价值方法论被不断蒸馏并回流到模板，让软件越用越聪明，越来越理解你的研判习惯。

<img src="./website/img/app-data-inspection.png" alt="Data Inspection" width="100%">

### 05 / VISUAL LANGUAGE - SanchoVis 可视化
利用结构化指令，Cell 能够以极其稳定的预期生成图表，自动交给 SanchoVis 渲染器，完美复现专业分析口径。

### 06 / DESKTOP COMPACT - 一键即跑环境
开箱即用。Python 依赖、SQL 执行器、浏览器自动化代理和知识库处理运行时深度整合打包，告别繁重环境搭建。

### 07 / GLOBAL REACH - 原生多语言体验
原生支持全球 18 种语言界面无缝切换，无论您身处何地，都能在最熟悉的母语语境下流畅开展深层研判。
支持的语言包括：简体中文、繁體中文、English (英语)、日本語 (日语)、한국어 (韩语)、Español (西班牙语)、Français (法语)、Deutsch (德语)、Русский (俄语)、Português (葡萄牙语)、العربية (阿拉伯语)、हिन्दी (印地语)、Bahasa Indonesia (印尼语)、ไทย (泰语)、Tiếng Việt (越南语)、Türkçe (土耳其语)、Polski (波兰语) 以及 עברית (希伯来语)。

---

## 研判故事链路

绝大多数工具仅切入局部分析环节。SanchoExo 将导入、计算、可视化、巡检追问与沉淀分享，无缝咬合在同一条本地流水线上。

1. **数据平滑接入**：本地 Excel、CSV 报表、外部业务数据库以及网页结构化抽取，100% 留存在本地，零延迟进入同一安全分析空间。
2. **极限关联计算**：Cell 直接充当计算单元，由 DuckDB 提供极速支撑，中间体结果源源不断且高度安全地流向下一计算环节。
3. **精准意图表达**：SanchoVis 可视化指令高度规范图表渲染，抛弃浮躁，具备极高可读性与确定性的口径对齐能力。
4. **主动巡检追问**：AI 引擎根据节点与链路拓扑图谱自动巡检数据异常，主动提出核心洞察，彻底追踪回放推理过程。
5. **闭环经验蒸馏**：高价值结论以 Notebook 的形式持久存留，重复研判流程被不断提炼并回灌飞轮，转化为下次任务的垫脚石。

---

## 下载

支持 macOS、Windows、Linux 三平台。

| 平台    | 架构                        | 下载                |
| ------- | --------------------------- | ------------------- |
| macOS   | Apple Silicon (M1/M2/M3/M4) | [下载 .dmg](#)      |
| Windows | x64                         | [下载 .exe](#)      |
| Linux   | x64                         | [下载 .AppImage](#) |

> 系统要求：macOS 12+、Windows 10+、Ubuntu 20.04+
>
> AI 功能需要您自己的 API Key（支持 DeepSeek、通义千问、Kimi、MiniMax、Anthropic、Gemini、OpenAI 等）

---

## 反馈与支持

- **Bug 反馈**：[GitHub Issues](https://github.com/jiangnanquan/SanchoExo/issues)
- **功能建议**：[GitHub Discussions](https://github.com/jiangnanquan/SanchoExo/discussions)
- **邮箱**：jiangnanquan@gmail.com

---

<div align="center">

**SanchoExo** — 100%本地存储 | 零配置开箱即用的 AI 研判台

Copyright &copy; 2024-2026 JNQ (江南泉). All rights reserved.

</div>
