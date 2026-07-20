<div align="center">

# MoneyPrinterTurbo 💸

### 一站式 AI 短视频生成工具

只需提供视频<b>主题</b>或<b>关键词</b>，即可自动生成视频脚本、匹配素材、生成字幕和背景音乐，并合成高清短视频。

[![Version](https://img.shields.io/github/v/release/webb-videos/MoneyPrinterTurbo?color=blue&label=version)](https://gitee.com/webb-videos/MoneyPrinterTurbo/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://gitee.com/webb-videos/MoneyPrinterTurbo/releases/latest)
[![Python](https://img.shields.io/badge/python-3.11%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Downloads](https://img.shields.io/github/downloads/webb-videos/MoneyPrinterTurbo/total)](https://gitee.com/webb-videos/MoneyPrinterTurbo/releases/latest)

简体中文 | [English](README-en.md) | [版本发布](https://gitee.com/webb-videos/MoneyPrinterTurbo/releases) | [问题反馈](https://gitee.com/webb-videos/MoneyPrinterTurbo/issues)

</div>

---

## 📋 目录

- [界面预览](#界面预览-️)
- [功能特性](#功能特性-)
- [配置要求](#配置要求-)
- [快速开始](#快速开始-)
- [安装部署](#安装部署-)
- [语音合成](#语音合成-)
- [字幕生成](#字幕生成-)
- [背景音乐](#背景音乐-)
- [常见问题](#常见问题-)
- [反馈建议](#反馈建议-)
- [许可证](#许可证-)

---

## 界面预览 🖥️

### WebUI 界面

![](docs/webui.jpg)

### API 接口界面

![](docs/api.jpg)

---

## 功能特性 🎯

### 核心功能

<table>
<tr>
<td width="50%">
<h4>🎬 视频生成</h4>
<ul>
<li>✅ AI 自动生成视频脚本</li>
<li>✅ 支持自定义脚本</li>
<li>✅ 批量视频生成</li>
<li>✅ 多种视频尺寸支持</li>
</ul>
</td>
<td width="50%">
<h4>🎨 视频格式</h4>
<ul>
<li>✅ 竖屏 9:16 (1080x1920)</li>
<li>✅ 横屏 16:9 (1920x1080)</li>
<li>✅ 可调节片段时长</li>
<li>✅ 高清视频输出</li>
</ul>
</td>
</tr>
<tr>
<td width="50%">
<h4>🗣️ 语音合成</h4>
<ul>
<li>✅ Edge TTS (免费)</li>
<li>✅ Azure Speech</li>
<li>✅ Google Gemini TTS</li>
<li>✅ ElevenLabs TTS</li>
</ul>
</td>
<td width="50%">
<h4>📜 字幕生成</h4>
<ul>
<li>✅ 自动字幕生成</li>
<li>✅ 可调整字体、位置</li>
<li>✅ 自定义颜色、大小</li>
<li>✅ 多种样式选择</li>
</ul>
</td>
</tr>
<tr>
<td width="50%">
<h4>🎵 背景音乐</h4>
<ul>
<li>✅ 随机音乐选择</li>
<li>✅ 自定义音乐</li>
<li>✅ 音量调节</li>
<li>✅ 多格式支持</li>
</ul>
</td>
<td width="50%">
<h4>🖼️ 素材来源</h4>
<ul>
<li>✅ 本地素材</li>
<li>✅ Pexels 图库</li>
<li>✅ Pixabay 图库</li>
<li>✅ Coverr 视频</li>
</ul>
</td>
</tr>
</table>

### 使用方式

```
┌─────────────────────────────────────────────────────┐
│                  MoneyPrinterTurbo                  │
├─────────────────────────────────────────────────────┤
│                                                     │
│   🤖 AI Agent      → 智能对话式视频生成           │
│   🖥️ WebUI         → 图形化界面，直观易用         │
│   🔌 API           → 程序化接口，集成灵活         │
│   ⌨️ CLI           → 命令行工具，自动化批处理     │
│                                                     │
└─────────────────────────────────────────────────────┘
```

### 支持的大模型

| 提供商 | 模型特点 | 推荐指数 |
|--------|---------|---------|
| **Kimi / Moonshot AI** | 长文本理解，中文优化 | ⭐⭐⭐⭐⭐ |
| **OpenAI** | GPT系列，综合能力强 | ⭐⭐⭐⭐⭐ |
| **Google Gemini** | 多模态，免费额度大 | ⭐⭐⭐⭐ |
| **DeepSeek** | 国产模型，性价比高 | ⭐⭐⭐⭐ |
| **阿里云通义千问** | 中文场景优化 | ⭐⭐⭐⭐ |
| **Microsoft Azure OpenAI** | 企业级服务 | ⭐⭐⭐⭐ |
| **火山引擎方舟** | 豆包系列模型 | ⭐⭐⭐ |
| **xAI Grok** | 马斯克旗下模型 | ⭐⭐⭐ |
| **MiniMax** | 自研大模型 | ⭐⭐⭐ |
| **小米 MiMo** | 小米AI模型 | ⭐⭐⭐ |

### 一键发布平台

```
📤 自动发布到
├─ 🎵 TikTok
├─ 📸 Instagram
└─ ▶️ YouTube Shorts
```

---

## 配置要求 📦

### 系统要求

| 项目 | 最低配置 | 推荐配置 | 理想配置 |
|------|---------|---------|---------|
| **系统** | Windows 10 / macOS 11.0 / Linux | Windows 11 / macOS 12+ / Linux | 最新稳定版系统 |
| **CPU** | 4核 | 6-8核 | 8核及以上 |
| **内存** | 4GB | 8GB | 16GB及以上 |
| **GPU** | 非必须 | 4GB显存 | 8GB显存及以上 |
| **Python** | 3.11 | 3.11 | 3.11 |

### 📊 性能对比图

```
视频生成速度对比（相同配置下）

┌─────────────────────────────────────────────────┐
│                                                 │
│   无GPU ████████████████████ 120s              │
│   4GB GPU ████████████ 90s                     │
│   8GB GPU ████████ 70s                          │
│                                                 │
└─────────────────────────────────────────────────┘
```

---

## 快速开始 🚀

### 使用方式推荐

| 使用场景 | 推荐方式 | 优势 |
|---------|---------|------|
| 🚫 不想安装配置 | AI Agent | 零配置，智能生成 |
| 🪟 Windows用户 | 一键启动包 | 解压即用，快速体验 |
| 🍎 macOS/Linux用户 | uv部署 | 轻量快速，依赖管理好 |
| 🐳 需要隔离环境 | Docker部署 | 环境隔离，易于迁移 |

### 方式一：使用 AI Agent 生成视频

如果你的 AI Agent 支持读取 Skill 文档并操作本地终端，可以直接发送下面这段话：

```text
使用这个 Skill：https://gitee.com/webb-videos/MoneyPrinterTurbo/raw/main/docs/skill/SKILL.md
帮我生成一个主题为"人工智能如何改变普通人的日常生活"的视频。
```

### 方式二：Google Colab 在线运行

免去本地环境配置，点击直接在 Google Colab 中快速体验：

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/webb-videos/MoneyPrinterTurbo/blob/main/docs/MoneyPrinterTurbo.ipynb)

### 方式三：Windows 一键启动包

下载地址：[Gitee Releases](https://gitee.com/webb-videos/MoneyPrinterTurbo/releases/latest)

使用步骤：
1. 下载并解压（路径不要有中文、特殊字符、空格）
2. 双击执行 `update.bat` 更新到最新代码
3. 双击 `start.bat` 启动

---

## 安装部署 📥

### 前提条件

- ✅ Python 3.11 或更高版本
- ✅ Windows用户避免中文/特殊字符/空格路径

### Docker 部署 🐳

#### 步骤一：克隆项目

```shell
git clone https://gitee.com/webb-videos/MoneyPrinterTurbo.git
cd MoneyPrinterTurbo
```

#### 步骤二：启动 Docker

```shell
docker compose -f docker-compose.release.yml up
```

#### 步骤三：访问界面

- **WebUI**: http://127.0.0.1:8501
- **API文档**: http://127.0.0.1:8080/docs

### 手动部署 📦

#### 步骤一：克隆代码

```shell
git clone https://gitee.com/webb-videos/MoneyPrinterTurbo.git
cd MoneyPrinterTurbo
```

#### 步骤二：创建虚拟环境（推荐使用 uv）

```shell
uv python install 3.11
uv sync --frozen
```

#### 步骤三：启动 WebUI

**Windows:**
```powershell
.\webui.bat
```

**macOS / Linux:**
```shell
sh webui.sh
```

#### 步骤四：启动 API 服务（可选）

```shell
uv run python main.py
```

#### 步骤五：纯命令行方式（无浏览器）

```shell
# 生成视频
uv run python cli.py --video-subject "人工智能如何改变日常生活"

# 查看帮助
uv run python cli.py --help
```

---

## 语音合成 🗣

### 支持的语音服务

| 服务 | 特点 | 是否需要API Key |
|------|------|---------------|
| **Edge TTS** | 免费，微软云端服务 | ❌ 不需要 |
| **Azure TTS V2** | 高质量，多语言 | ✅ 需要 |
| **SiliconFlow TTS** | 国产服务 | ✅ 需要 |
| **Google Gemini TTS** | 免费额度大 | ✅ 需要 |
| **小米 MiMo TTS** | 小米AI服务 | ✅ 需要 |
| **ElevenLabs TTS** | 高质量英文 | ✅ 需要 |

> 💡 **提示**: 默认使用免费的 Edge TTS，在 WebUI 中显示为 Azure TTS V1

---

## 字幕生成 📜

### 两种字幕模式

```
┌─────────────────────────────────────────────┐
│  模式一：edge (推荐)                        │
│  ├─ 使用 TTS 时间戳生成                     │
│  ├─ 速度快，不需要 GPU                      │
│  └─ 适合大多数场景                          │
├─────────────────────────────────────────────┤
│  模式二：whisper                            │
│  ├─ 使用 faster-whisper 转写音频           │
│  ├─ 更准确的字幕时间轴                      │
│  └─ 需要 GPU 加速（可选）                   │
└─────────────────────────────────────────────┘
```

### 配置方式

在 `config.toml` 中修改：

```toml
[app]
subtitle_provider = "whisper"

[whisper]
model_size = "large-v3-turbo"  # 约1.6GB，更快更小
# model_size = "large-v3"      # 约3GB，更准确
```

---

## 背景音乐 🎵

音乐文件位于项目的 `resource/songs` 目录下，你可以：

- ✅ 使用默认音乐
- ✅ 添加自己的音乐文件
- ✅ 在 WebUI 中选择音乐
- ✅ 调节音乐音量

> ⚠️ **注意**: 默认音乐来自YouTube视频，仅供学习使用，商业用途请替换为自己的音乐

---

## 常见问题 🤔

<details>
<summary><b>❓ 如何发布到 TikTok、Instagram 或 YouTube Shorts？</b></summary>

注册 [Upload-Post](https://upload-post.com/) 账号并获取 API Key，然后在 `config.toml` 中添加配置：

```toml
[app]
upload_post_enabled = true
upload_post_api_key = "your-api-key"
upload_post_username = "your-username"
upload_post_platforms = ["tiktok", "instagram", "youtube"]
upload_post_auto_upload = true
upload_post_youtube_privacy_status = "public"
```

</details>

<details>
<summary><b>❓ RuntimeError: No ffmpeg exe could be found</b></summary>

从 https://www.gyan.dev/ffmpeg/builds/ 下载ffmpeg，解压后在 `config.toml` 中设置路径：

```toml
[app]
ffmpeg_path = "C:\\Users\\webb\\Downloads\\ffmpeg.exe"
```

</details>

<details>
<summary><b>❓ OSError: [Errno 24] Too many open files</b></summary>

这是系统文件打开数限制问题，解决方案：

```shell
# 查看当前限制
ulimit -n

# 调高限制
ulimit -n 10240
```

</details>

<details>
<summary><b>❓ Whisper 模型下载失败怎么办？</b></summary>

从 [Hugging Face](https://huggingface.co/Systran/faster-whisper-large-v3) 手动下载模型，解压后放到：

```
MoneyPrinterTurbo
  ├─models
  │   └─whisper-large-v3
  │          config.json
  │          model.bin
  │          preprocessor_config.json
  │          tokenizer.json
  │          vocabulary.json
```

</details>

---

## 项目架构 🏗️

```
MoneyPrinterTurbo/
├── 📁 app/                    # 应用核心代码
│   ├── 📁 config/             # 配置管理
│   ├── 📁 controllers/        # 控制器层
│   ├── 📁 models/             # 数据模型
│   ├── 📁 services/           # 业务服务
│   └── 📁 utils/              # 工具函数
├── 📁 webui/                  # Web界面
├── 📁 docs/                   # 文档
├── 📁 resource/               # 资源文件
│   ├── 📁 fonts/              # 字体文件
│   ├── 📁 songs/              # 背景音乐
│   └── 📁 public/             # 公共资源
├── 📄 main.py                 # API服务入口
├── 📄 cli.py                  # 命令行工具
└── 📄 webui.bat/sh            # WebUI启动脚本
```

---

## 技术栈 🔧

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 反馈建议 📢

- 📝 提交 [Issue](https://gitee.com/webb-videos/MoneyPrinterTurbo/issues)
- 🔀 提交 [Pull Request](https://gitee.com/webb-videos/MoneyPrinterTurbo/pulls)

---

## 许可证 📝

本项目采用 MIT 许可证，详见 [LICENSE](LICENSE) 文件

---

<div align="center">

### 🌟 如果这个项目对你有帮助，请给一个 Star ⭐

**Made with ❤️ by webb**

</div>