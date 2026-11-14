---
title: "レッスン 12 - GitHub Pages でサイトをデプロイする"
description: "GitHub Copilot app を使って Pages ワークフローを構成し、その pull request をレビューして公開された Space Quiz を確認します。"
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Space Quiz を GitHub Pages でデプロイし、誰でもアクセスできる場所に公開します。Copilot はワークフローを準備してデプロイを案内できますが、変更をレビューし、サイトが公開されたことを確認するのは自身の責任です。

このレッスンでは、次の操作を行います。

- Copilot に GitHub Pages へのデプロイを構成するよう依頼します。
- マージする前にワークフローと pull request をレビューします。
- デプロイの進行状況を確認し、公開されたサイトを検証します。

## シナリオ

Space Quiz はすでに GitHub リポジトリにありますが、手軽に試せる方法が必要です。単一ファイルのサイトを GitHub Pages で公開すると、サーバーやランタイム依存関係を追加せずに、公開 URL からアクセスできるようになります。

## Copilot にデプロイの準備を依頼する

> [!WARNING]
> pull request を作成すると、コードがコミットおよびプッシュされる場合があります。この prompt を送信する前に、承認設定と送信先リポジトリを確認してください。**Approve all** が選択されている場合、別途確認を求められないことがあります。

`space-quiz` の Copilot app セッションで、次の prompt を送信します。

```plaintext
Prepare a GitHub Pages deployment for this repository. Create a GitHub Actions workflow that builds the website if needed and deploys it to GitHub Pages after changes reach the default branch. Add a README describing the app and how to run it locally if one does not already exist. Create a pull request with these changes and report its link and any required Pages settings or permissions. Do not merge, enable auto-merge, change Pages settings, or deploy. Stop and wait for my review.
```

## ワークフローと pull request をレビューする

1. README が、リポジトリにまだ存在しない場合にのみ追加されていることを確認します。
2. ワークフローのビルドおよびデプロイ手順、トリガー、権限など、pull request の変更をレビューします。
3. ワークフローが、未マージの pull request ではなくデフォルトブランチからデプロイすることを確認します。
4. 必要な修正を依頼し、更新された diff をレビューします。マージを許可する前に、pull request の必須チェックが成功するまで待ちます。

## マージとデプロイを許可する

> [!WARNING]
> 次の prompt は、レビュー済みの pull request のマージ、リポジトリの Pages 設定の変更、およびサイトの公開をエージェントに許可します。レビューを完了し、リポジトリと pull request を確認してから送信してください。承認設定によっては、追加の確認なしにこれらの操作が実行されます。

`<PR_NUMBER>` をレビューした pull request の番号に置き換え、この prompt を別途送信します。

```plaintext
I have reviewed pull request <PR_NUMBER> in this repository and authorize its merge and deployment. Enable GitHub Pages using GitHub Actions, merge that pull request only after required checks pass, and monitor the deployment until it succeeds. Report the final URL of the live website. If you lack permission to enable Pages or merge, tell me exactly what I need to approve or do; do not report success until the site is live.
```

![3 段階の図: マージ済みの space-quiz pull request、Build website、Upload artifact、Deploy to Pages の各手順が成功した GitHub Actions の Deploy website 実行、yourname.github.io/space-quiz/ で公開された Space Quiz。](../../../_images/first-steps-app-pages-deploy.svg)

## デプロイを確認する

1. GitHub Actions のデプロイ実行が成功するまで確認します。
2. 報告された URL を開き、Space Quiz が表示されることを確認します。

エージェントが Pages の有効化や pull request のマージを実行できない場合は、エージェントが示す具体的な手順に従います。デプロイが成功し、公開サイトが読み込まれるまで、タスクを完了したと見なさないでください。

## まとめと次のステップ

Space Quiz が公開され、エージェントの報告に頼るのではなく、自分でデプロイを確認できました。[レッスン 13: 振り返りと次のステップ][next-lesson]に進みます。

[next-lesson]: ../13-review/
