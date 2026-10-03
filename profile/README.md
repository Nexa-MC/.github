<div align="center">

<img src="https://avatars.githubusercontent.com/u/304438575?v=4" alt="NexaOrg" width="112" height="112">

# NexaOrg

**连接玩家、创作者与 Minecraft 的更多可能。**

跨平台启动器 · 云端服务 · 开放插件生态

[官方网站](https://pcln.top/) · [使用文档](https://docs.pcln.top/) · [下载启动器](https://github.com/PCL-N-Edition/PCL-N/releases) · [反馈问题](https://github.com/PCL-N-Edition/PCL-N/issues/new/choose)

</div>

## 从这里开始

**NexaOrg** 围绕 Minecraft 构建启动器、账户与在线服务、插件开发工具和文档。我们希望让日常启动更顺手，让创作者更容易把想法做成可用的扩展。

### NexaLauncher

跨平台 Minecraft 启动器，主仓库沿用 **PCL-N**，历史名称为 PCL N Edition。

基于 .NET 10 与 Avalonia，面向 Windows、Linux 和 macOS，提供实例管理、版本安装、Java 选择、账号登录与资源下载等能力。

[查看源码](https://github.com/PCL-N-Edition/PCL-N) · [版本与下载](https://github.com/PCL-N-Edition/PCL-N/releases) · [提交反馈](https://github.com/PCL-N-Edition/PCL-N/issues/new/choose)

### Nexa 云端服务

官网、账户中心与在线服务共同连接启动器和社区。公开项目包括 Web 界面与独立身份服务，分别承担网站交互和账户认证。

[访问官网](https://pcln.top/) · [Web 项目](https://github.com/PCL-N-Edition/PCL-N-Plugin-Center-Web) · [Auth 项目](https://github.com/PCL-N-Edition/PCL-N-Plugin-Center-Auth)

### 插件与开发工具

通过公开 SDK 为启动器编写扩展，或从官方插件和工具项目了解实现方式。

| 项目 | 用途 |
|---|---|
| [Plugin SDK](https://github.com/PCL-N-Edition/PCL-N-Plugin-SDK) | 公开契约、示例、分析器、测试宿主与签名 `.pnp` 打包工具 |
| [Terracotta 陶瓦联机](https://github.com/PCL-N-Edition/PCLN.Terracotta) | Minecraft P2P 联机插件 |
| [Plugin IDE](https://github.com/PCL-N-Edition/PCL-NE-Plugin-IDE) | 插件开发编辑器项目 |
| [PXML Compiler](https://github.com/PCL-N-Edition/PXML-Compiler) | PXML 编译工具链 |
| [Docs](https://github.com/PCL-N-Edition/PCLN-Docs) | 用户文档与插件开发文档 |
| [Patches](https://github.com/PCL-N-Edition/PCL-N-Patches) | 启动器差分更新产物与清单 |

[创建第一个插件](https://docs.pcln.top/plugin-sdk/Getting-Started) · [Manifest 参考](https://docs.pcln.top/plugin-sdk/Plugin-Manifest) · [权限与安全](https://docs.pcln.top/plugin-sdk/Permissions-and-Security) · [示例代码](https://github.com/PCL-N-Edition/PCL-N-Plugin-SDK/tree/main/examples/HelloPlugin)

## 版本与项目状态

- 下载与更新请以各项目的 **Releases、发布说明和实际发布产物**为准
- 开发分支、工具原型与已发布版本可能不同；具体平台支持和已知问题请查阅对应项目
- 插件开发请核对 SDK 与目标启动器版本，使用公开接口，不依赖启动器内部实现
- 历史仓库名和部分文档仍使用 PCL N / PCLN，现有链接可继续使用

## 一起参与

欢迎提交问题、改进文档、测试新版本或贡献代码。

1. 在对应仓库提交 Issue，附上版本、系统、复现步骤与必要日志
2. 提交 Pull Request 前，阅读仓库开发说明，并运行相关构建与测试
3. 分享日志前移除令牌、密钥、账号信息和其他个人数据
4. 安全漏洞请按相关仓库的安全政策，优先通过可用的私密渠道报告

[启动器问题反馈](https://github.com/PCL-N-Edition/PCL-N/issues) · [文档贡献](https://github.com/PCL-N-Edition/PCLN-Docs) · [支持项目](https://ifdian.net/a/pclne)

## 致谢与许可

感谢 [PCL Community](https://github.com/PCL-Community/PCL-CE)、各项目的上游作者、第三方依赖维护者，以及每一位贡献者。PCL-N 保留其与 PCL-CE 的上游关系；本项目的问题请反馈到本组织对应仓库。

各仓库独立采用其声明的许可证，请查阅对应的 `LICENSE`、`NOTICE` 与第三方声明，并保留上游署名。

<div align="center">

<sub>Building tools for Minecraft players and creators.</sub>

</div>
