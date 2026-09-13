# Jacob Mod Manager Community

[English](#english) · [简体中文](#简体中文)

## English

Jacob Mod Manager is a native macOS tool for importing, analyzing, converting,
organizing, installing, and safely removing compatible game Mods. It was
previously named **Mac Mod Manager** and was renamed to meet Apple's App Store
naming requirements. The first validated game module is **Resident Evil 4**
for macOS.

This repository is the public home for Community Edition downloads, release
notes, known issues, the support roadmap, and issue reports. It does **not**
contain CAPCOM game files, official artwork, third-party Mods, license-server
code, or the proprietary application source.

### Current release

- **0.1.0 (build 10)** is the first supported public release.
- Download it from [jacobmodmanager.app](https://jacobmodmanager.app/en/) or the matching GitHub Release.
- The DMG is Developer ID signed, Apple notarized, and stapled.
- Verify the DMG against the SHA-256 published in both release channels.

Community Edition supports every game module that has been officially released,
but allows one imported top-level Mod package per game at a time. Optional
components inside that package remain part of the same Mod. Paid licenses unlock
batch import and full multi-Mod management for the licensed game scope.

### Get help

- General software bug: use the **Software bug** issue form.
- A Mod cannot be imported, converted, or installed: use the **Mod compatibility**
  issue form.
- License, payment, refund, privacy, or a report containing personal data:
  email [support@jacobmodmanager.app](mailto:support@jacobmodmanager.app) instead of
  opening a public issue.
- Security vulnerability: follow [SECURITY.md](SECURITY.md).

Never upload game files, complete Mods, license keys, payment records, diagnostic
archives, or screenshots containing personal paths to a public issue.

### Repository status

Community Edition is free to use, but this repository is not currently an
open-source release of the application. No source-code license is granted merely
because the repository is public. See [NOTICE.md](NOTICE.md).

## 简体中文

Jacob Mod Manager 是一款原生 macOS Mod 管理工具，用于导入、分析、转换、
整理、安装和安全移除兼容的游戏 Mod。软件原名 **Mac Mod Manager**，为符合
Apple App Store 的软件命名规范，现已更名为 Jacob Mod Manager。首个完成验证的
游戏模块是 macOS 版 **《生化危机 4》**。

本仓库是社区版下载、更新日志、已知问题、支持路线图和问题反馈的公开入口。
仓库不会包含 CAPCOM 游戏文件、官方素材、第三方 Mod、许可证服务代码或软件
商业源码。

### 当前版本

- **0.1.0（build 10）** 是首个受支持的公开版本。
- 请从 [jacobmodmanager.app](https://jacobmodmanager.app/zh/) 或对应的 GitHub Release 下载。
- DMG 已通过 Developer ID 签名、Apple 公证并装订公证票据。
- 请使用 GitHub Release 与官网下载页同时公布的 SHA-256 校验 DMG。

社区版支持所有已经正式发布的游戏模块，但每款游戏同一时间只允许使用一个已
导入的顶层 Mod 包；该包中的可选组件仍视为同一个 Mod。收费许可证会按购买的
游戏范围解锁批量导入和完整多 Mod 管理。

### 获取帮助

- 普通软件错误：使用 **软件错误 / Software bug** 表单。
- Mod 无法导入、转换或安装：使用 **Mod 兼容问题 / Mod compatibility** 表单。
- 许可证、付款、退款、隐私，或包含个人信息的报告：请发送邮件到
  [support@jacobmodmanager.app](mailto:support@jacobmodmanager.app)，不要提交公开 Issue。
- 安全漏洞：请遵循 [SECURITY.md](SECURITY.md)。

请勿在公开 Issue 上传游戏文件、完整 Mod、许可证密钥、付款记录、诊断压缩包，
或包含个人路径的截图。

### 仓库性质

社区版可以免费使用，但本仓库目前不代表应用程序已经开源。仓库公开不会自动
授予任何源代码许可证，详情见 [NOTICE.md](NOTICE.md)。

## Documentation / 文档

- [Installation guide](docs/INSTALLATION.md) · [安装指南](docs/INSTALLATION.zh-CN.md)
- [Known issues](docs/KNOWN_ISSUES.md) · [已知问题](docs/KNOWN_ISSUES.zh-CN.md)
- [Roadmap / 支持路线图](docs/ROADMAP.md)
- [Changelog / 更新日志](CHANGELOG.md)
- [Contributing / 参与反馈](CONTRIBUTING.md)

> Existing repository paths, bundle identifiers, and older release artifact
> filenames may retain `mac-mod-manager` or `Mac-Mod-Manager` for compatibility.
> They still belong to Jacob Mod Manager.
