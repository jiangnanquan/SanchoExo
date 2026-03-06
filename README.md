<div align="center">

# SanchoExo

**AI 驱动的个人数据工作台**

用一个界面完成数据查询、分析、可视化和自动化。
AI 不是附加功能，而是核心体验。

[下载](#下载) · [功能](#功能) · [购买授权](#购买授权) · [反馈](https://github.com/jiangnanquan/SanchoExo/issues)

<!--
  TODO: 添加产品主截图
  建议：深色主题下的 Dashboard 或 DB Query 页面全屏截图
  尺寸：1920x1080，JPEG 格式，放在 screenshots/ 目录

  ![SanchoExo](./screenshots/hero.jpg)
-->

</div>

---

## 为什么

数字鸿沟正在扩大。程序员在 IDE 中享受 AI 协作和多工具整合，普通人却被困在广告弹窗和碎片化工具中。

AI 时代不缺模型能力，缺的是**把 AI 接入真实业务的管道**。

SanchoExo 的解法：让 AI 当翻译——把人类意图翻译成工具操作。你不需要懂 SQL，只需要说"把这堆报价单整理一下"。

### 设计哲学

- **零噪音** — 每个像素都有意义，没有广告、弹窗、无关信息
- **AI 原生** — 人类负责决策，AI 负责执行
- **整合而非分散** — 一个界面，所有工具，统一交互
- **本地优先** — 你的数据在你自己的机器上，不上传任何云端

---

## 功能

### 数据查询

内嵌 DuckDB 引擎，毫秒级查询。Notebook 式 SQL 编辑器，写完即跑，结果即时呈现。

支持 CSV、Excel、Parquet 等多种数据源直接查询，无需导入流程。

<!-- ![数据查询](./screenshots/db-query.jpg) -->

### AI 全能助手

Queen AI 拥有 60+ 工具，能感知你当前的页面、理解你的数据、操作你的工作流。

- 自然语言查询数据
- 自动生成 SQL 和 Python 代码
- 页面感知与智能操作
- 知识库语义搜索
- 兼容 DeepSeek、通义千问、Kimi、OpenAI 等主流 AI 服务商

<!-- ![AI 助手](./screenshots/queen-ai.jpg) -->

### Python 笔记本

AI 原生的 Python 开发环境。持久化会话、变量共享、环境管理。

SQL 查询结果一键送入 Python 做深度分析，Python 处理结果一键回写数据库。

<!-- ![Python 笔记本](./screenshots/python-notebook.jpg) -->

### 知识库

导入 PDF、Word、网页、Markdown，自动分块和向量化。

全文搜索、语义搜索、混合搜索三种模式。AI 对话时自动检索相关知识，不需要手动粘贴上下文。

<!-- ![知识库](./screenshots/knowledge-base.jpg) -->

### 数据管道

从杂乱到有序的完整链路：

```
多源数据导入 → DuckDB 统一入库 → Python 分析 → 知识库沉淀 → AI 关联扫描
```

AI 自动识别表头和数据类型，多文件合并入库。分析结论自动存入知识库，下次可搜索复用。

### 心流舱笔记

Markdown 编辑器 + 思维导图双视图。写笔记的同时自动生成导图，笔记内容自动同步到知识库。

### 浏览器自动化

内置 Playwright 引擎，支持网页操作自动化。AI 可以直接操控浏览器完成重复性工作。

### 更多

- **MCP 协议支持** — 接入外部工具，扩展 AI 能力边界
- **VS Code 主题兼容** — 支持 VS Code 主题市场，一键切换
- **中英文双语界面** — 完整的国际化支持
- **文件守卫** — 自动快照备份，AI 操作可回滚

---

## 下载

支持 macOS、Windows、Linux 三平台。

| 平台    | 架构                        | 下载                |
| ------- | --------------------------- | ------------------- |
| macOS   | Apple Silicon (M1/M2/M3/M4) | [下载 .dmg](https://github.com/jiangnanquan/SanchoExo/releases/download/v1.2.0-dev.125/SanchoExo-1.2.0-dev.125-arm64.dmg)      |
| macOS   | Intel                       | [下载 .dmg](https://github.com/jiangnanquan/SanchoExo/releases/download/v1.2.0-dev.125/SanchoExo-1.2.0-dev.125.dmg)      |
| Windows | x64                         | [下载 .exe](https://github.com/jiangnanquan/SanchoExo/releases/download/v1.2.0-dev.125/SanchoExo%20Setup%201.2.0-dev.125.exe)      |
| Linux   | x64                         | [下载 .AppImage](https://github.com/jiangnanquan/SanchoExo/releases/download/v1.2.0-dev.125/SanchoExo-1.2.0-dev.125.AppImage) |

> 系统要求：macOS 12+、Windows 10+、Ubuntu 20.04+
>
> AI 功能需要您自己的 API Key（支持 DeepSeek、通义千问、Kimi、OpenAI 等）

---

## 购买授权

SanchoExo 提供 14 天全功能免费试用。

|              | 价格   | 说明                       |
| ------------ | ------ | -------------------------- |
| **永久买断** | ¥198   | 含 1 年免费更新            |
| **更新续费** | ¥98/年 | 不续费仍可继续使用已有版本 |

每份授权绑定一台设备。

<!-- [立即购买](#) -->

---

## 反馈与支持

- **Bug 反馈**：[GitHub Issues](https://github.com/jiangnanquan/SanchoExo/issues)
- **功能建议**：[GitHub Discussions](https://github.com/jiangnanquan/SanchoExo/discussions)
- **邮箱**：jiangnanquan@gmail.com

---

<div align="center">

**SanchoExo** — 让 AI 成为你的数据工作搭档

Copyright &copy; 2024-2026 JNQ (江南泉). All rights reserved.

</div>
