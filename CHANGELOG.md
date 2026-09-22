# Changelog / 更新日志

## 0.2.0 — 2026-09-21

Major update:

- RE2 Mod conversion currently supports Mods made for the PC non-RT version
  only. RT-version Mods are not supported yet.
- Added the Resident Evil 2 game module for macOS, including safe import,
  analysis, conversion, library management, patch deployment, removal and
  rollback.
- Added RE2 collection and optional-component handling while keeping the
  Community Edition limit at one active top-level Mod package per game.
- Expanded fail-closed conversion coverage for RE Engine models, materials,
  textures, prefabs, scenes, motion and physics resources.
- Improved storage safety, interrupted-operation recovery, library migration,
  diagnostics and compatibility reporting.
- Simplified game and license settings, with consistent action buttons and
  automatic game-status refresh after selecting an installation.
- Renamed the distributed application to Jacob Mod Manager and retained the
  existing license/update migration path.

RE2 conversion coverage is broad, but runtime behavior still varies by Mod.
Some newly convertible packages have not completed game-play verification; see
Known Issues and report exact Mod/version details if a result is incorrect.

---

重点更新：

- RE2 Mod 转换目前仅支持 PC 非 RT 版 Mod；RT 版 Mod 暂不支持；
- 新增 macOS《生化危机 2》游戏模块，支持安全导入、分析、转换、资料库管理、
  补丁部署、移除与回滚；
- 新增 RE2 集合与可选组件管理；社区版仍保持每款游戏同时启用一个顶层 Mod 包；
- 扩展 RE Engine 模型、材质、贴图、预制体、场景、动作与物理资源的失败关闭转换；
- 改进存储安全、中断恢复、资料库迁移、诊断和兼容问题反馈；
- 简化游戏与许可证设置，统一操作按钮，并在选择游戏安装位置后自动刷新状态；
- 发布应用名称更新为 Jacob Mod Manager，并保留现有许可证与更新迁移路径。

RE2 已具备广泛转换覆盖，但具体 Mod 的游戏内表现仍可能不同；部分新近可转换包
尚未完成实机验证。请查看已知问题，遇到异常时提供准确的 Mod 名称和版本。

## 0.1.0 (build 10) — 2026-09-06

First supported public release of Mac Mod Manager.

Initial scope:

- Native English and Simplified Chinese macOS interface.
- Resident Evil 4 module with import, analysis, supported resource conversion, conflict reporting, patch build, verification and removal.
- Community Edition one-package-per-game workflow and license-based paid feature unlocking in the same application.
- In-app software bug and Mod compatibility report preparation.
- Developer ID signed, Apple notarized and stapled DMG.

Compatibility varies by Mod and game update. Check the live compatibility catalog and known issues before relying on a result; an unlisted Mod is not automatically incompatible.

---

Mac Mod Manager 首个受支持的公开版本。

首发范围：

- 原生英文和简体中文 macOS 界面；
- 《生化危机 4》模块：导入、分析、已支持资源转换、冲突提示、补丁构建、验证和移除；
- 同一应用内的社区版单包流程和许可证解锁收费功能；
- 软件问题与 Mod 兼容问题报告准备。
- 通过 Developer ID 签名、Apple 公证并装订公证票据的 DMG。

Mod 兼容性会随具体 Mod 和游戏更新而变化。使用前请查看实时兼容清单与已知问题；未列入清单并不等于不兼容。
