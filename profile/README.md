<div align="center">
  
# OShin Team

</div>

<div align="center">

![OShinTeam Banner](../banner.png)

### 下一代桌面客户端 | Next-Generation Desktop Client

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.en.html)
[![GitHub Stars](https://img.shields.io/github/stars/OShinTeam/OShin?style=flat-square)](https://github.com/OShinTeam/OShin/stargazers)
[![Telegram Group](https://img.shields.io/badge/Telegram-Join%20Us-blue?logo=telegram)](https://t.me/kinhweb)

</div>

---

## 🎯 关于我们

**OShinTeam** 是一个专注于**功能聚合**、**代码解耦**的开源组织，致力于打造下一代桌面客户端程序。

我们的核心理念：
- 🔌 **插件化架构** - 灵活可扩展的设计
- 🌐 **多功能支持** - 统一管理多个服务
- 💻 **原生体验** - 跨平台桌面应用，性能优异
- 🤖 **AI 赋能** - 智能文件管理与自动化

---

## 📦 核心项目

<div align="center">

| 项目 | 描述 | 语言 |
|:---:|:---|:---:|
| [OShin](https://github.com/OShinTeam/OShin) | 多网盘聚合桌面客户端 | Wails |
| [OShinC](https://github.com/OShinTeam/OShinC) | Go + Lua 安全沙箱执行引擎 | Go |
| [OShinD](https://github.com/OShinTeam/OShinD) | 轻量级多协议多线程下载工具 | Go |
| [OShinHub](https://github.com/OShinTeam/OShinHub) | OShin 官方插件市场 | Lua |

</div>

---

## ✨ 项目详情

### 🖥️ OShin - 多网盘聚合客户端

> 采用 Wails v2 + React + Go 构建的高性能桌面应用

- 🔌 可按需选择的插件化设计
- 🌐 全功能的本地化使用体验
- ⚡ 性能表现贴近原生桌面应用
- 🤖 支持接入 AI 实现文件管理功能

### 🛡️ OShinC - Lua 脚本执行引擎

> Go 编写的安全沙箱环境，支持 CLI 和 FFI 两种接入方式

- 🔒 **双层安全机制**：AST 静态检测 + 运行时权限控制
- 🎯 **精细权限管理**：exec / network / file_read / file_write / system
- 🔗 **多种接入方式**：CLI 直接调用 / FFI 共享库嵌入
- 📦 **丰富内置函数**：JSON、编码哈希、网络请求、文件操作

### 📥 OShinD - 多协议下载工具

> Go 编写的轻量级多线程下载器，支持 HTTP/HTTPS/FTP/SFTP

- 🚀 **高速多线程**：最多 64 并发连接
- ⏸️ **断点续传**：意外中断后可无缝继续
- 🔄 **多源 CDN**：同时从多个 CDN 下载加速
- ✅ **文件校验**：自动验证 MD5/SHA256 完整性

---

## 🛠️ 技术栈

<div align="center">

```
┌─────────────────────────────────────────────────────┐
│  Frontend          │  Backend          │  Mobile   │
├─────────────────────────────────────────────────────┤
│  React             │  Go               │  Wails v2 │
│  TypeScript        │  gopher-lua       │           │
│  Wails v2          │  Protocol Buffers │           │
└─────────────────────────────────────────────────────┘
```

</div>

---

## 🤝 参与贡献

欢迎所有开发者参与 OShinTeam 的建设！

1. 🍴 Fork 您感兴趣的项目
2. 🌿 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 🔨 进行开发并提交更改
4. 📝 提交 Pull Request

> 💬 如需加入开发讨论，请联系 Telegram 群组：[@KinhWeb](https://t.me/kinhweb)

---

## 📄 开源协议

| 项目 | 协议 |
|:---|:---|
| OShin | [AGPL-3.0](https://github.com/OShinTeam/OShin/blob/release/LICENSE) |
| OShinC | [AGPL-3.0](https://github.com/OShinTeam/OShinC/blob/release/LICENSE) |
| OShinD | [AGPL-3.0](https://github.com/OShinTeam/OShinD/blob/release/LICENSE) |
| OShinHub | [MIT](https://github.com/OShinTeam/OShinHub/blob/main/LICENSE) |

---

<div align="center">

**Made with ❤️ by OShinTeam**  
**© 2026 OShinTeam. All rights reserved.**

</div>
