---
slug: ja-jp/real-world-development/cloud
title: "GitHub Copilot cloud agent"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot cloud agent](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)** を使うと、GitHub Copilot がクラウドで非同期に作業できます。GitHub で作業を割り当てると、cloud agent はバックグラウンドでリポジトリを調べ、変更を加えて pull request を作成します。その間、別の作業を進められます。

この演習では、cloud agent が従うカスタム指示を追加した後、GitHub issue を割り当てて実装を依頼します。カスタムエージェントを確認して利用し、作業方法を調整します。エージェントのダッシュボードからセッションを監視して指示し、最後にエージェントが作成した pull request をレビューして結果を改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと Codespace を作成します |
| [1. カスタム指示][ex1] | コンテキスト | cloud agent が従うカスタム指示を追加します |
| [2. Cloud Agent][ex2] | 非同期エージェント | GitHub Copilot cloud agent に issue を割り当てます |
| [3. カスタムエージェント][ex3] | 専門エージェント | カスタムエージェントを確認して使用します |
| [4. エージェントの管理][ex4] | 監視 | エージェントセッションを監視して指示します |
| [5. 反復][ex5] | レビュー | PR をレビューし、Copilot の作業を繰り返し改善して、次のステップを選びます |

## 前提条件

このワークショップを始める前に、次のものを用意してください。

- [ ] 有効な **Copilot Student、Pro、Pro+、Business、Enterprise** プランを利用できる GitHub アカウント
- [ ] アカウントまたは組織で GitHub Copilot cloud agent が有効になっていること

> [!TIP]
> 有料プランを利用していませんか？認証済みの学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使うエージェント、MCP、コードレビュー、Copilot CLI の機能が含まれているため、すべての演習を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Cloud agent は **Copilot Student、Pro、Pro+、Business、Enterprise** で利用できます。Copilot Free では利用できません。Copilot Business または Enterprise の場合、管理者が組織で有効にする必要があります。

> [!NOTE]
> この演習では MCP を扱いません。Copilot で MCP サーバーを使う方法については、[CLI ワークショップ][cli]または [VS Code ワークショップ][vscode]を参照してください。

## はじめに

**[演習 0: 前提条件から始める →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
