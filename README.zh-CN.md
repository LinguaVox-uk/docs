<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI 语音听写 Chrome 扩展" />
</p>

<h3 align="center">LinguaVox — 说你的语言，输出21种以上文字</h3>

<p align="center">
  按住快捷键 · 说话 · 松开 · 文字在3秒内出现在任意网页输入框<br>
  OpenAI Whisper · 21种以上输出语言 · 6种AI增强模式 · 无需API密钥 · Slack、Gmail、Notion、Jira
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/许可证-MIT-blue.svg" alt="许可证" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/网站-linguavox-brightgreen" alt="网站" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20应用商店-免费安装-blue?logo=googlechrome" alt="Chrome应用商店" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/控制台-打开-orange" alt="控制台" /></a>
  <img src="https://img.shields.io/badge/版本-2.8-green" alt="版本" />
</p>

---

## 什么是 LinguaVox？

LinguaVox 是一款基于 AI 的 Chrome 语音听写和翻译扩展。按住 Ctrl+Space，说话，松开——转录文字立即出现在任何活动的文本框中：聊天框、邮件编辑器、搜索框、CRM 表单、代码编辑器。扩展使用 OpenAI Whisper 实现 95%+ 精度转录，并通过 GPT-4o-mini 提供可选的 AI 增强功能：语法修正、风格改写、翻译。

与大多数语音听写工具不同，LinguaVox 不需要用户自己提供 OpenAI API 密钥。免费用户每天可获得 100 次请求，使用共享密钥池，零配置即可使用。高级用户和团队可接入自己的密钥实现无限使用。

## 工作原理

**使用前：** 打开独立应用 → 录音 → 复制 → 切换到浏览器 → 粘贴  
**使用后：**

```
1. 点击任意输入框（Slack、Gmail、Notion、Jira…）
2. 按住  Ctrl+Space  →  说话
3. 松开  →  文字在 ~3 秒内出现  ✓
```

无需复制粘贴。无需切换应用。适用于任何网站。

## 支持平台

| 平台 | 状态 | 备注 |
|------|------|------|
| Slack（浏览器） | ✅ | 浏览器级快捷键，绕过 Slack 键盘拦截 |
| Gmail | ✅ | 撰写和回复框 |
| Notion | ✅ | 所有 `contenteditable` 块 |
| Jira | ✅ | 任务字段、评论、描述 |
| Asana | ✅ | 任务和评论字段 |
| Salesforce | ✅ | CRM 输入字段 |
| 任何 `<input>` / `<textarea>` | ✅ | 通用——任何网站 |
| 任何 `contenteditable` | ✅ | 兼容 React、Draft.js、Quill |
| Google 文档 | ⚠️ | 有限支持——自定义画布编辑器 |

## 核心功能

- **无需 API 密钥** — 免费每日 100 次，共享密钥池，零配置
- **自带密钥（BYOK）** — 以 OpenAI 费率无限使用（典型月费不足 $0.50）
- **组织账户** — 团队共享密钥池、成员管理、使用分析
- **21 种以上语言** — 一步完成转录和翻译
- **6 种 AI 增强模式** — 语法修正、商务风格、学术风格、口语风格、创意风格、智能润色
- **隐私优先** — 音频从不存储，实时处理后立即丢弃
- **3 秒内完成** — 从说话到文字插入端到端
- **95%+ 精度** — OpenAI Whisper large-v2

## AI 增强模式

| 模式 | 功能 |
|------|------|
| 智能润色 | 修正语法、提升表达清晰度、保留原意 |
| 商务风格 | 改写为专业商务语言 |
| 语法修正 | 仅修正语法和拼写 |
| 创意风格 | 生动有趣的表达 |
| 口语风格 | 友好、自然的对话语气 |
| 学术风格 | 正式的学术语言 |

## 价格

| 套餐 | 请求次数 | 设置要求 |
|------|----------|----------|
| 免费 | 100次/天 | 仅需 Google 登录 |
| 自带密钥 | 无限 | 您的 OpenAI API 密钥 |
| 组织 | 无限 | 团队共享密钥 + 分析 |

## 常见问题

### LinguaVox 支持 Slack 吗？
支持。Slack 在页面级拦截键盘事件。LinguaVox 通过 `chrome.commands.onCommand` 在浏览器级注册快捷键，绕过 Slack 的拦截。适用于 Slack 所有消息输入框。

### 需要 OpenAI API 密钥吗？
不需要。免费用户每天获得 100 次共享池请求。在控制台添加自己的密钥可无限使用。

### 我的声音会被录制或存储吗？
不会。音频由 Whisper 实时处理，处理后立即丢弃。任何地方都不会存储声音数据。

### 支持哪些语言？
21 种以上：英语、乌克兰语、俄语、西班牙语、法语、德语、日语、韩语、中文（普通话）、阿拉伯语、葡萄牙语、意大利语、波兰语、荷兰语、土耳其语、瑞典语、罗马尼亚语、希腊语等。

## 链接

| | |
|--|--|
| 🌐 网站 | https://linguavox.uk |
| 📊 控制台 | https://linguavox.uk/login |
| 🎤 语音翻译 | https://linguavox.uk/voice-translation |
| ✨ AI语音增强 | https://linguavox.uk/ai-voice-enhancement |
| 🌍 非母语人士 | https://linguavox.uk/for-non-native-speakers |
| 👤 关于作者 | https://linguavox.uk/about |
| 🔒 隐私政策 | https://linguavox.uk/privacy/ |
| 💬 支持 | https://linguavox.uk/support/ |

## 社区与支持

| | |
|--|--|
| 📺 YouTube | [演示视频和教程](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox 社区频道](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [加入 linguavox.slack.com](https://linguavox.slack.com) |

## 演示视频

| 使用场景 | 观看 |
|---------|------|
| Gmail — 用语音撰写邮件 | [▶ 观看](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — 语音消息 | [▶ 观看](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — 语音听写 | [▶ 观看](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — 用语音写帖子 | [▶ 观看](https://youtube.com/watch?v=3WX9EmYNYjk) |
| 会议模式 — 实时字幕 | [▶ 观看](https://youtube.com/watch?v=agcMJVPKlxE) |

## 许可证

MIT — 查看 [LICENSE](LICENSE)