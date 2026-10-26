---
slug: ja-jp/real-world-development/cloud
title: "GitHub Copilot クラウド エージェント"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot クラウド エージェント](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)** を使うと、GitHub Copilot がクラウドで非同期に作業できます。GitHub で作業を割り当てると、クラウド エージェントはバックグラウンドでリポジトリを調査して変更を加え、プル リクエストを作成します。その間、ユーザーは別の作業を続けられます。

各演習では、まずクラウド エージェントが従うカスタム指示を追加し、次に GitHub issue を割り当てて作業を実装させます。カスタム エージェントを確認してアプローチを調整し、エージェント ダッシュボードからセッションを監視して指示を出します。最後に、エージェントが作成したプル リクエストをレビューし、結果を改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと codespace を作成する |
| [1. カスタム指示][ex1] | コンテキスト | クラウド エージェントが従うカスタム指示を追加する |
| [2. クラウド エージェント][ex2] | 非同期エージェント | GitHub Copilot クラウド エージェントに issue を割り当てる |
| [3. カスタム エージェント][ex3] | 専門エージェント | カスタム エージェントを確認して使用する |
| [4. エージェントを管理する][ex4] | 監視 | エージェント セッションを監視して指示を出す |
| [5. 繰り返し改善する][ex5] | レビュー | PR をレビューし、Copilot の作業を改善して次のステップを選ぶ |

## 前提条件

このワークショップに参加する前に、次の項目を用意してください。

- [ ] **Copilot Student、Pro、Pro+、Business、Enterprise** のいずれかが有効な GitHub アカウント
- [ ] アカウントまたは組織で有効になっている Copilot クラウド エージェント

> [!TIP]
> 有料プランがありませんか？認証済みの学生は[GitHub Education][callout-student-plan-education]を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使用するエージェント、MCP、コード レビュー、Copilot CLI の機能が含まれているため、すべての環境で演習を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> クラウド エージェントは **Copilot Student、Pro、Pro+、Business、Enterprise** で利用できます。Copilot Free を除くすべてのプランが対象です。Copilot Business または Enterprise では、管理者が組織で有効にする必要があります。

> [!NOTE]
> この環境では MCP を扱いません。Copilot で MCP サーバーを使用する方法については、[CLI 環境][cli]または [VS Code 環境][vscode]を参照してください。

## 開始する

**[演習 0: 前提条件から開始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
