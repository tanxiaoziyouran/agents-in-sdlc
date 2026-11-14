---
title: "练习 0：先决条件"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

开始 GitHub Copilot cloud agent 练习前，需要完成准备工作。你将创建一份 Tailspin Toys 仓库副本，并启动一个 [Codespace][codespaces]，用于编辑指令文件和审查 cloud agent 完成的工作。

## 设置练习仓库

要为后续编写的代码创建仓库副本，请基于[模板仓库][template-repository]创建一个实例。新实例包含练习所需的全部文件，你将在整个练习过程中使用它。

1. 在新的浏览器窗口中，转到 [Tailspin Toys 模板][tailspin-template]。
2. 在练习仓库页面上选择 **Use this template** 按钮，以创建自己的仓库副本。然后选择 **Create a new repository**。

    ![Use this template 按钮](../../../_images/ex0-use-template.png)

3. 如果你正在参加由 GitHub 或 Microsoft 主办的活动，请遵循导师提供的说明。否则，可以在你有权使用 GitHub Copilot 的组织中创建新仓库。

    ![输入仓库模板设置](../../../_images/ex0-repository-settings.png)

4. 记下你创建的仓库路径（**organization-or-user-name/repository-name**），稍后会在练习中用到。

## 创建 Codespace

接下来，你将使用 Codespace 完成练习。

[GitHub Codespaces][codespaces] 是一种基于云的开发环境，可让你直接在浏览器中编写、运行和调试代码。它提供功能完善的 IDE，并支持多种编程语言、扩展和工具。

1. 转到刚创建的仓库。
2. 选择绿色的 **Code** 按钮。

    ![选择 Code 按钮](../../../_images/ex0-code-button.png)

3. 选择 **Codespaces** 选项卡，然后选择 **+** 按钮来创建 Codespace。

    ![创建新的 Codespace](../../../_images/ex0-create-codespace.png)

创建 Codespace 需要几分钟，但仍比手动安装所有服务快得多。等待期间，你可以探索 GitHub Copilot 的其他功能，接下来我们会介绍这些功能。

> [!CAUTION]
> 你将在后续练习中返回 Codespace。现在请将它保留在浏览器标签页中。

> [!NOTE]
> 本研讨会旨在 Codespace 或本地[开发容器][dev-containers]中运行。两者都已安装顺利完成练习所需的全部先决条件。如果你想在本地运行，请在 VS Code 中打开克隆的仓库，并在出现提示时选择 **Reopen in Container**。VS Code 将构建与 Codespace 相同的开发容器。

[codespaces]: https://github.com/features/codespaces
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers

## 总结

恭喜你，已创建练习仓库的副本！你也已开始创建 Codespace，后续将使用它与 GitHub Copilot cloud agent 协作。

## 下一步

现在为 cloud agent 添加它需要遵循的自定义指令。继续学习[练习 1：自定义指令][next-lesson]。

## 资源

- [GitHub Codespaces 概述][codespaces]
- [从模板创建仓库][template-repository]
- [开始使用 Codespaces][codespaces-quickstart]

[tailspin-template]: https://github.com/github-samples/tailspin-toys
[template-repository]: https://docs.github.com/repositories/creating-and-managing-repositories/creating-a-template-repository
[codespaces-quickstart]: https://docs.github.com/codespaces/getting-started/quickstart
[next-lesson]: ../1-custom-instructions/
