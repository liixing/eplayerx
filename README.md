# EplayerX

简体中文 | [English](README.en.md)

EplayerX 的公开反馈与 macOS 下载仓库。

## macOS 下载

当前版本：[**1.2.22**](https://github.com/liixing/eplayerx/releases/tag/v1.2.22-macos)，需要 **macOS 12.0 或更高版本**。

| Mac 芯片 | 下载 |
| --- | --- |
| Apple Silicon（M 系列） | [下载 Apple Silicon 版](https://github.com/liixing/eplayerx/releases/download/v1.2.22-macos/EplayerX-1.2.22-83-macOS-Apple-Silicon.zip) |
| Intel | [下载 Intel 版](https://github.com/liixing/eplayerx/releases/download/v1.2.22-macos/EplayerX-1.2.22-83-macOS-Intel.zip) |

在屏幕左上角选择 ** → 关于本机**，查看「芯片」或「处理器」，再选择对应版本。

下载并解压 `.zip`，将 EplayerX 拖入「应用程序」，再从「应用程序」启动。安装包已签名并通过 Apple 公证；[Releases](https://github.com/liixing/eplayerx/releases) 提供更新日志和 SHA-256 校验值。

仅提供最新版安装包下载，历史版本保留更新日志和校验值。

### SHA-256 校验值

[下载校验文件](https://github.com/liixing/eplayerx/releases/download/v1.2.22-macos/SHA256SUMS.txt)

| Mac 芯片 | SHA-256 |
| --- | --- |
| Apple Silicon | `fb151b4d6992deb1b994174b694ddf0ccd5d41ba19f1047b0f3f41457d8fab4e` |
| Intel | `545fb8390116b05935992934161f2fa4efa2bc6671c5421703f1914bf372c4ec` |

## 已购用户从商店版切换

已在 Mac App Store 购买或订阅的用户，可以在**同一台 Mac** 上尝试以下方式沿用会员：

1. 安装 Mac App Store 版 EplayerX，使用购买时的 Apple 账户，在应用内点击「恢复购买」，确认会员已生效。
2. 完全退出 EplayerX，保留原有应用数据，不使用清理工具删除数据。
3. 下载上方对应芯片的独立版，解压后拖入「应用程序」，替换原来的 EplayerX。
4. 打开独立版，检查会员状态。

这条路径可能沿用已有的本机会员状态，**目前不能保证成功，也不适用于换机或清空数据后的恢复**。如果会员没有显示，请先回到商店版确认购买状态并[反馈问题](https://github.com/liixing/eplayerx/issues/new?template=bug_report.md)，不要为了排查问题重复购买。

## 问题反馈与功能建议

- [报告问题](https://github.com/liixing/eplayerx/issues/new?template=bug_report.md)
- [提出功能建议](https://github.com/liixing/eplayerx/issues/new?template=feature_request.md)
- [查看已有反馈](https://github.com/liixing/eplayerx/issues)

提交前请先搜索已有反馈。报告问题时，请提供应用版本、系统版本、设备信息和复现步骤；播放问题可补充媒体格式与编码信息。

Issues 和附件公开可见。请勿提交账号密码、访问令牌、带鉴权参数的播放地址或其他隐私信息；日志与截图请先脱敏。

## 版本更新

从 **1.2.2** 起，独立版会自动检查更新。发现新版时，侧边栏 Pro 卡片右侧会显示青绿色下载按钮。点击按钮或应用菜单中的「检查更新…」，即可查看更新日志并下载；准备好重启时选择「安装并重启应用」。后台更新提示不会打断播放，也可在 Sparkle 更新窗口中选择自动安装。

**1.2.1 没有内置更新器，需要先手动下载并安装一次当前版本，之后即可使用应用内更新。**

新版本及中英文更新日志也会发布在 [Releases](https://github.com/liixing/eplayerx/releases)。可通过仓库右上角 **Watch → Custom → Releases** 订阅发布通知。

此仓库用于应用分发和用户反馈，不包含应用源代码。
