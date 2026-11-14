---
slug: zh-cn/real-world-development/cloud
title: "GitHub Copilot cloud agent"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot cloud agent](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)** 可让 GitHub Copilot 在云端异步工作。你在 GitHub 上分配任务后，cloud agent 会在后台处理：探索仓库、进行更改并创建拉取请求；与此同时，你可以处理其他事情。

在这些练习中，你将添加 cloud agent 要遵循的自定义指令，然后分配一个 GitHub 议题，让它实现相应工作。你将查看并使用自定义代理来引导其工作方式，通过代理仪表板监控并指导会话，最后审查代理创建的拉取请求并迭代改进结果。

## 练习

| 练习 | 主题 | 说明 |
|----------|-------|-------------|
| [0. 先决条件][ex0] | 设置 | 创建仓库和 Codespace |
| [1. 自定义指令][ex1] | 上下文 | 添加 cloud agent 要遵循的自定义指令 |
| [2. Cloud Agent][ex2] | 异步代理 | 将议题分配给 GitHub Copilot cloud agent |
| [3. 自定义代理][ex3] | 专用代理 | 查看并使用自定义代理 |
| [4. 管理代理][ex4] | 监控 | 监控并指导代理会话 |
| [5. 迭代改进][ex5] | 审查 | 审查拉取请求、迭代改进 Copilot 的工作并选择后续步骤 |

## 先决条件

参加本研讨会前，请确保具备以下条件：

- [ ] 拥有有效的 **Copilot Student、Pro、Pro+、Business 或 Enterprise** 计划的 GitHub 帐户
- [ ] 已为你的帐户或组织启用 GitHub Copilot cloud agent

> [!TIP]
> 没有付费计划？通过验证的学生可以从 [GitHub Education][callout-student-plan-education] 免费获取 GitHub Copilot。**Copilot Student** 计划包含本研讨会使用的代理、MCP、代码审查和 Copilot CLI 功能，因此你可以完成所有练习。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Cloud agent 适用于 **Copilot Student、Pro、Pro+、Business 和 Enterprise** 计划，Copilot Free 除外。使用 Copilot Business 或 Enterprise 时，管理员必须为组织启用该功能。

> [!NOTE]
> 本练习路径不涉及 MCP。若要了解如何在 Copilot 中使用 MCP 服务器，请参阅 [CLI 练习路径][cli]或 [VS Code 练习路径][vscode]。

## 开始

**[从练习 0：先决条件开始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
