<div align="center">

<!-- 终端窗口抬头：文件在你自己的仓库里，字体用系统等宽栈，不依赖任何外部服务。
     SVG 通过 <img> 加载时内部的 prefers-color-scheme 不生效（实测），所以出明暗两份用 <picture> 切。
     用绝对地址而不是相对路径：原生 HTML <img> 的相对路径在 README 里不保证被解析 -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sakurawwwxh/sakurawwwxh/main/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sakurawwwxh/sakurawwwxh/main/header-light.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/sakurawwwxh/sakurawwwxh/main/header-light.svg" alt="tomato@sakurawwwxh" />
</picture>

</div>

做的东西基本是给自己用的：单进程、SQLite、systemd、零外部依赖 —— 装上就能放着不管，才算做完。

## 主要在做

**[qq-agent-plus](https://github.com/sakurawwwxh/qq-agent-plus)** · `Node.js`

![星](https://img.shields.io/github/stars/sakurawwwxh/qq-agent-plus?style=flat-square&color=1F6FEB&label=%E6%98%9F) ![最近提交](https://img.shields.io/github/last-commit/sakurawwwxh/qq-agent-plus?style=flat-square&color=1F6FEB&label=%E6%9C%80%E8%BF%91%E6%8F%90%E4%BA%A4) ![最新版本](https://img.shields.io/github/v/release/sakurawwwxh/qq-agent-plus?style=flat-square&color=1F6FEB&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)

跑在 Linux QQ（NapCat）上的群聊 Agent，走 OneBot v11 协议。分条发言、贴纸系统、主动发言、内置运维命令 —— 单进程 + SQLite + systemd，装上就能放着不管。

**[opencode-go-panel](https://github.com/sakurawwwxh/opencode-go-panel)** · `PowerShell`

![最近提交](https://img.shields.io/github/last-commit/sakurawwwxh/opencode-go-panel?style=flat-square&color=1F6FEB&label=%E6%9C%80%E8%BF%91%E6%8F%90%E4%BA%A4)

撬开 opencode.ai 控制台的 RPC，把用量做成 Windows 桌面悬浮窗。不想为了看一眼额度就开网页。

## 其他项目

| 项目 | 说明 | 技术 |
| :--- | :--- | :--- |
| [**ai-mcp-gateway**](https://github.com/sakurawwwxh/ai-mcp-gateway) | MCP 网关 | `Java` |
| [**ai-agent-scaffold**](https://github.com/sakurawwwxh/ai-agent-scaffold) | AI Agent 脚手架工程 | `Java` |
| [**AI-interview**](https://github.com/sakurawwwxh/AI-interview) | 基于 Spring AI 的简历分析 + 模拟面试系统 | `Java` |
| [**ptmsystem**](https://github.com/sakurawwwxh/ptmsystem) | 个人任务管理系统 | `TypeScript` |

## 技术栈

<div align="center">

<img src="https://skillicons.dev/icons?i=nodejs,java,typescript,powershell,linux,sqlite,docker,git&theme=dark" alt="技术栈" />

</div>
