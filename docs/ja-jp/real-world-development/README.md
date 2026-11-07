---
slug: ja-jp/real-world-development
title: "実践的な開発"
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を活用します。変更の計画、コードの作成、動作のテスト、プルリクエストのレビュー、エージェントを使った作業の管理を繰り返しながら進めます。

## シナリオ

あなたは、開発者をテーマにしたボードゲームのクラウドファンディングを提供する架空の会社、Tailspin Toys に入社したばかりの開発者です。チームのバックログは GitHub issue として登録されており、すぐに取り組めます。フィルターやページネーションなどの機能開発に加え、アクセシビリティやコーディング標準などの品質改善も含まれています。

## 環境を選ぶ

GitHub Copilot は、どこで作業していても利用できます。自分の開発方法に合った環境を選んでください。各ワークショップは個別のセットアップから始まり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使います。Plan モードと Autopilot モード、指示、スキル、カスタム エージェント、Playwright MCP、Agent Merge、便利なスラッシュ コマンドを活用します。

### [GitHub Copilot アプリ][app]

複数のエージェント セッションを並行して実行し、セッション モードを切り替え、キャンバスで共同作業し、デスクトップ アプリから GitHub issue とプルリクエストを管理します。

### [GitHub Copilot cloud agent][cloud]

GitHub issue を非同期エージェントに割り当て、作業を案内して進捗を監視し、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使います。エディターを離れずに、Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを活用します。

[cli]: cli/
[app]: app/
[cloud]: cloud/
[vscode]: vscode/
