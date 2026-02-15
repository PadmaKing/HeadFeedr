# Casper's HeadFeedr 🚀

A minimalist, immersive creative writing studio designed for novelists and screenwriters. It combines distraction-free writing with a robust, multi-provider AI co-pilot that lives entirely in your browser.

👉 **[Click here to launch the App](https://padmaking.github.io/HeadFeedr/)** 👈

## ✨ What's New in v20.1?

* **🛡️ AI Auto-Failover System**: No more "Rate Limit" interruptions. Configure multiple AI providers (DeepSeek, Gemini, OpenAI). If one API fails or hits a quota limit, the app **automatically and instantly switches** to the next available provider to finish your request.
* **💾 Persistent AI Config**: API keys and model settings are saved independently for each provider.

## 🌟 Key Features

### 🧠 Intelligent Brainstorming
* **Auto-Fill Loglines**: Stuck on an idea? Let AI auto-complete your setting, protagonist, goal, and obstacle.
* **Smart Character Generation**: Generate detailed character profiles (with fatal flaws) directly from your logline's context.
* **Magic Outline Expansion**: Click the `✨` wand to automatically generate plot points for Act 1, 2, or 3.

### ✍️ Production-Ready Writing
* **Insert Outline to Draft**: One-click import of your structured outline into the main editor as a writing skeleton.
* **Contextual Chat**: Discuss your story with an AI that reads your current draft in real-time.

### 🛡️ Safety & Management
* **⏰ Time Machine**: A built-in version control system. Create snapshots manually or let the auto-backup save your work every 5 minutes. Restore any version instantly.
* **📚 Bookshelf**: Manage multiple novels or projects in one place.
* **🔒 Privacy First**: All data (texts, keys, settings) is stored locally in your browser's **IndexedDB**. Nothing is sent to our servers.
* **📦 Full Archive**: One-click export/import of your entire library (including all projects and history) as a JSON file.

## 🛠️ Supported AI Providers

HeadFeedr supports a generic OpenAI-compatible interface, making it compatible with:
* **DeepSeek** (V3/R1)
* **Google Gemini** (via OpenAI compatibility layer)
* **OpenAI** (GPT-4o/mini)
* **Custom / Local LLMs** (LM Studio, Ollama)

## 🚀 How to Use

1.  Open the [Web App Link](https://padmaking.github.io/HeadFeedr/).
2.  **(Recommended)** Add to Home Screen on iOS/Android for a fullscreen App experience.
3.  Go to **Settings (⚙️ AI)**.
4.  Select a provider (e.g., Gemini), enter your API Key, and click Save.
5.  (Optional) Configure a second provider (e.g., DeepSeek) as a backup.
6.  Start writing!

## ❤️ About

This tool is a single-file HTML application (SPA). It requires no backend and runs entirely on client-side technology.
If you have any suggestions, feel free to open an Issue.

# Casper's HeadFeedr 🚀

**当前版本：v20.0 (Auto-Failover 自动灾备版)**

这是一个专为小说家和编剧设计的极简、沉浸式创意写作工作室。它将无干扰的纯粹写作环境与强大的、支持多服务商轮询的 AI 助手完美结合，且所有程序逻辑完全运行在你的浏览器中。

👉 **[点击这里直接使用 App](https://padmaking.github.io/HeadFeedr/)** 👈

---

## ✨ v20.1 更新亮点

* **🛡️ AI 自动灾备系统 (Auto-Failover)**：告别 API 报错和限流中断。你可以同时配置多个 AI 服务商（如 DeepSeek, Gemini, OpenAI）。当首选服务商报错或额度耗尽时，App 会**自动、瞬间**切换到下一个备用服务商继续完成任务。
* **💾 AI 配置独立记忆**：每个服务商的 API Key 和模型设置都会被独立保存，切换时无需重新输入。

## 🌟 核心功能

### 🧠 智能灵感激发
* **Logline 自动填空**：卡在构思阶段？输入一点点想法，让 AI 自动补全背景、主角、目标和阻碍。
* **角色智能生成**：根据你的故事梗概，一键生成带有性格缺陷 (Fatal Flaw) 的详细角色卡片。
* **大纲魔法扩充**：点击 `✨` 魔法棒，自动为第一幕、第二幕或第三幕生成剧情节点建议。

### ✍️ 生产力写作工具
* **大纲植入正文**：一键将你排列好的结构化大纲转换为文本骨架，插入编辑器中，对着大纲填肉。
* **沉浸式 AI 对话**：在写作界面直接与 AI 讨论剧情，AI 会实时读取你的正文草稿作为上下文，拒绝瞎编。

### 🛡️ 安全与管理
* **⏰ 时光机 (Time Machine)**：内置强大的版本控制系统。支持手动快照或每 5 分钟自动备份。随时可以“穿越”回任何一个历史版本。
* **📚 个人书架**：在一个地方管理你的多部小说或剧本企划。
* **🔒 隐私优先**：**数据绝对安全**。所有的文章、大纲、API Key 都只存储在你浏览器的本地数据库 (**IndexedDB**) 中，绝不上传任何服务器。
* **📦 全库归档**：支持一键导出/导入整个书架（包含所有项目和历史记录），生成 JSON 备份文件。

## 🛠️ 支持的 AI 服务商

HeadFeedr 采用通用的 OpenAI 接口标准，完美支持：
* **DeepSeek** (V3/R1)
* **Google Gemini** (通过兼容层)
* **OpenAI** (GPT-4o/mini)
* **自定义 / 本地模型** (如 LM Studio, Ollama)

## 🚀 如何使用

1.  点击上方的 [Web App 链接](https://padmaking.github.io/HeadFeedr/) 打开网页。
2.  **(推荐)** 在手机/平板浏览器点击分享，选择 **“添加到主屏幕”**，获得全屏原生 App 体验。
3.  进入 **设置 (⚙️ AI)**。
4.  选择一个服务商 (如 Gemini)，填入 API Key 并保存。
5.  (可选) 配置第二个服务商 (如 DeepSeek) 作为备用。
6.  开始创作！

## ❤️ 关于本项目

这是一个单文件 HTML 应用 (SPA)。它不需要后端服务器，完全基于客户端技术运行，轻量、快速且永久免费。
如有建议，欢迎提交 Issue。
