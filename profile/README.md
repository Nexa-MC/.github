<div align="center">

# PCL N Edition

**跨平台 Minecraft 启动器与开放插件生态**

基于 .NET 10 与 Avalonia，面向 Windows、Linux 和 macOS。

[官方网站与文档](https://docs.pcln.top/) · [下载启动器](https://github.com/PCL-N-Edition/PCL-N/releases/latest) · [反馈问题](https://github.com/PCL-N-Edition/PCL-N/issues/new/choose) · [插件 SDK](https://github.com/PCL-N-Edition/PCL-N-Plugin-SDK)

</div>

## 关于我们

PCL N Edition（Plain Craft Launcher N Edition）致力于打造现代、跨平台、可扩展的 Minecraft 启动体验。项目以模块化架构连接启动器、公开插件 SDK、插件中心、文档站与官方插件，在保持安全边界的同时为玩家和开发者提供一致的体验。

- **跨平台**：支持 Windows、Linux、macOS 的 x64 与 ARM64
- **现代技术栈**：使用 .NET 10、Avalonia 12，并提供多平台自动化构建
- **完整启动能力**：覆盖实例管理、Java 选择、版本安装、资源下载与多种账号体系
- **开放插件生态**：通过签名 `.pnp` 包、权限声明、隔离加载与公开 SDK 扩展启动器
- **安全发布链路**：支持 OpenPGP 开发者签名、市场签名、包扫描和在线完整性验证

## 核心项目

| 项目 | 说明 |
|---|---|
| [PCL-N](https://github.com/PCL-N-Edition/PCL-N) | PCL N 跨平台 Minecraft 启动器主仓库 |
| [PCL-N-Plugin-SDK](https://github.com/PCL-N-Edition/PCL-N-Plugin-SDK) | 第三方插件公开契约、分析器、测试宿主与 `.pnp` 构建工具 |
| [PCLN-Docs](https://github.com/PCL-N-Edition/PCLN-Docs) | 用户文档与插件开发文档，发布于 [docs.pcln.top](https://docs.pcln.top/) |
| [PCLN.Terracotta](https://github.com/PCL-N-Edition/PCLN.Terracotta) | 官方 Minecraft P2P 联机插件“陶瓦联机” |
| [PCL-N-Plugin-Center-Web](https://github.com/PCL-N-Edition/PCL-N-Plugin-Center-Web) | 插件中心、发布者工作台与管理界面 |
| [PCL-N-Plugin-Center-Server](https://github.com/PCL-N-Edition/PCL-N-Plugin-Center-Server) | 插件发布、审核、扫描与市场分发服务 |
| [PCL-N-Patches](https://github.com/PCL-N-Edition/PCL-N-Patches) | 启动器版本间二进制差分与更新清单 |

## 插件开发

PCL N Plugin SDK 提供稳定的公开 ABI、Manifest Schema、权限与服务协商、本地化、宿主原生 UI、Avalonia 页面、测试工具以及可复现的签名 `.pnp` 打包流程。

当前 SDK 版本为 **0.2.0**。从以下资源开始：

- [插件开发入门](https://docs.pcln.top/plugin-sdk/Getting-Started)
- [完整 Manifest 参考](https://docs.pcln.top/plugin-sdk/Plugin-Manifest)
- [权限与安全](https://docs.pcln.top/plugin-sdk/Permissions-and-Security)
- [示例插件](https://github.com/PCL-N-Edition/PCL-N-Plugin-SDK/tree/main/examples/HelloPlugin)

## 参与贡献

欢迎通过 Issue 和 Pull Request 参与。提交前请阅读目标仓库的 README、开发说明与许可证，并确保：

1. 问题提交到对应项目，而不是其他 PCL 分支或上游仓库；
2. 代码改动通过该仓库的格式检查、构建和测试；
3. 不在 Issue、日志、配置或提交中公开密钥、令牌及个人信息；
4. 插件只依赖公开 SDK，不引用启动器私有程序集。

## 许可与安全

各仓库按其自身许可证发布；核心项目通常采用 Apache License 2.0，部分 Web 项目沿用 MIT License。请以对应仓库中的 `LICENSE` 和第三方声明为准。

发现安全问题时，请优先使用相关仓库的私密安全报告渠道，避免在公开 Issue 中披露可利用细节。

<div align="center">

让 Minecraft 启动体验更现代、更开放，也更可靠。

</div>
