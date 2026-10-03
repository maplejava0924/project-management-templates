# [プロジェクト名] Test Plan

## Purpose

このドキュメントを、[プロジェクト名]のテストと受け入れ条件に関するSingle Source of Truthとする。

各ドキュメントの役割、参照順、更新ルールは`AGENTS.md`で管理する。

## Test Levels

- Unit Test：純粋なロジック
- Integration Test：外部サービスやデータストアとの接続
- API Test：エンドポイント、認証、エラー形式
- E2E Test：主要導線
- Responsive Test：対象端末・画面幅
- Manual UX Test：操作性、表示、アクセシビリティ

## Test ID Conventions

- `[DOMAIN]-*`： [領域]
- `AUTH-*`：認証・権限
- `ERROR-*`：エラー・再試行
- `E2E-*`：受け入れシナリオ
- `RELEASE-*`：公開準備

## Test Case Template

### [TEST-ID]：[テスト名]

- 対象：
- 前提条件：
- 入力：
- 操作：
- 期待結果：
- エラー条件：
- 証拠：

## Acceptance Scenarios

### [E2E-ID]：[シナリオ名]

1. [操作]
2. [操作]
3. [操作]

期待結果：[受け入れ条件]

## Evidence Rules

- 実行日時を記録する
- 実行環境、URL、コマンド、テスト結果を記録する
- 手動確認では入力、操作、期待結果、実結果を記録する
- スクリーンショット、ログ、デプロイURLなど再確認できる証拠を残す
- 失敗時は原因、影響、再試行条件を記録する
