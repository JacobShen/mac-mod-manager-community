# Changelog / 更新日志

## 0.2.2 — 2026-10-06

### 中文

- 改进【里昂改版】狂战士（Berserker）的原始包转换、软件应用及旧缓存更新，已验证第 10 章请求场景。
- 扩展部分 RE4 转换与组合规则，包括 Definitive Playable Ada、Shermie、Ada 旗袍／礼服及 Ashley 女仆／Princess；未验证组合仍以兼容检查为准。
- 合入【艾达改版】女武神（Valkyrie）的阶段性代码，仍在开发中。
- 优化导入进度、错误提示和写入失败恢复；修复资料库移动后的重启引用及失效缓存恢复。

更新后旧 Mod 若仍不兼容或效果异常，可重新导入原始包并重新应用。不保证所有章节、存档或组合完全兼容；RE2 仍仅支持 PC 非 RT 版 Mod。此前狂战士的大部分章节反馈来自独立研究候选，不是 0.2.1 软件原始包转换流程的完整验证。

### English

- Improved original-package conversion, software application and legacy-cache updates for the Leon-campaign Berserker overhaul, with the requested chapter10 scenario verified.
- Extended some RE4 conversion and combination rules, including Definitive Playable Ada, Shermie, Ada cheongsam/evening dresses, and Ashley maid/Princess; unverified combinations remain subject to compatibility checks.
- Included ongoing code for the Ada-campaign Valkyrie overhaul, which remains in development.
- Improved import progress, error messages and write-failure recovery; fixed library references after moving and restarting, and improved missing-cache recovery.

If an older import remains incompatible or behaves unexpectedly, re-import the original archive and apply it again. Not every chapter, save or combination is fully compatible; RE2 still supports PC non-RT Mods only. Earlier multi-chapter Berserker feedback came from a separate research candidate, not complete validation of the 0.2.1 original-package software workflow.

## 0.2.1 — 2026-10-03

## 中文

- 改进 RE4 纹理、服装和音频转换，修复 Definitive Playable Ada 已验证的图鉴服装、自定义头发及模型界面声音，以及 black suit 去耳环、Shermie 剧情／佣兵模式相关兼容问题。
- 修复 Ada Wong Voice Mod – The Definitive Edition（Ada Voice）及 Leon to Ada Voice Replacement 的已验证语音转换问题。
- 纳入 【里昂改版】狂战士（Berserker） 的阶段性兼容改进：大部分章节经用户测试暂未发现明显问题，尚未确认所有章节完全无异常。
- 纳入 【艾达改版】女武神（Valkyrie） 的阶段性转换改进；适配仍在开发中，尚未完成全章节验证。
- 改进排队应用 Mod 变更的可靠性，统一新版软件和官网图标。
- App Store 0.2.1 同期修复了游戏目录授权和反复出现权限提示的问题；已有购买权益保持不变。官网版和 App Store 版使用各自独立的购买与授权渠道。

更新后若旧 Mod 仍显示不兼容或效果异常，可尝试重新导入原始 Mod 包，让软件按新规则重新转换。上述兼容改进覆盖已验证的原包和场景，不代表所有 Mod、语言、存档或全部章节都已验证。

RE2 Mod 转换仍仅支持 PC 非 RT 版 Mod，RT 版暂不支持。

## English

- Improved RE4 texture, costume, and audio conversion, including verified fixes for Definitive Playable Ada gallery outfits, authored hair, and model-viewer audio; black suit earring removal; and Shermie story/Mercenaries compatibility.
- Fixed verified voice conversion issues in Ada Wong Voice Mod – The Definitive Edition (Ada Voice) and Leon to Ada Voice Replacement.
- Included ongoing compatibility improvements for the Leon-campaign Berserker overhaul. The user has tested most chapters without obvious issues; every chapter has not been confirmed to be issue-free.
- Included ongoing conversion improvements for the Ada-campaign Valkyrie overhaul. Its adaptation remains in development and has not been verified across every chapter.
- Improved reliability when applying queued Mod changes and unified the updated app and website icons.
- The corresponding App Store 0.2.1 update also fixes game-folder authorization and repeated permission prompts. Existing purchases remain valid. Website and App Store editions retain separate purchase and authorization channels.

If a previously imported Mod still appears incompatible or behaves unexpectedly after updating, try re-importing the original Mod archive to use the latest conversion rules. These improvements cover verified original packages and scenarios, not every Mod, language, save, or chapter.

RE2 Mod conversion continues to support PC non-RT Mods only. RT-version Mods are not supported yet.

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
