# [プロジェクト名] Architecture

## Summary

[システム全体の構成と主要な技術選定。]

```text
[Client] → [API] → [Database / External Services]
```

## Hosting and Environments

| 環境 | 用途 | 配置先 | 主要設定 |
|---|---|---|---|
| Local | 開発 | [場所] | [設定] |
| Preview | 検証 | [場所] | [設定] |
| Production | 公開 | [場所] | [設定] |

## Repository Structure

```text
[project-root]/
├── [directory]/
└── [directory]/
```

## Responsibilities

| コンポーネント | 責務 |
|---|---|
| [コンポーネント] | [責務] |

## Data Model

### [Entity]

| フィールド | 型 | 必須 | 説明 |
|---|---|---|---|
| [field] | [type] | [yes/no] | [説明] |

## API Design

| Method | Path | 認証 | 入力 | 出力 | エラー |
|---|---|---|---|---|---|
| [GET/POST] | `/[path]` | [要否] | [概要] | [概要] | [概要] |

## External Services and AI Integration

- サービス： [サービス名]
- 用途： [用途]
- 認証情報の保管場所： [環境変数・Secret管理]
- 障害時の挙動： [再試行・フォールバック・停止]
- 費用・利用上限： [条件]

## Security and Operations

- 認証・認可：
- データ分離：
- 秘密情報：
- ログ・監視：
- バックアップ・復旧：

## Technical Risks and POC

本実装前に成立性を確認すべき技術的不確実性を記録する。ここには現在の技術採用方針・採用状態を記載する。検証結果・判断の経緯と証拠は`development-log.md`、成功条件は`test-plan.md`、実施タスクと現在状態は`tasks.md`を正とする。重要なアーキテクチャ採用・変更は、POCの技術的完了とは別にユーザー承認を必要とする。

| ID | 技術的不確実性 | 失敗時の影響 | POC要否 | 成功条件・テストID | 現在の採用方針 |
|---|---|---|---|---|---|
| [POC-001] | [確認したい技術要素] | [設計変更・MVP変更など] | [要/不要] | [POC-TEST-ID] | [未決定/採用/不採用/条件付き採用、判断記録への参照] |

POCが必要な要素は、成功または代替方針の確定まで、依存する本実装の前提条件としない。

## Testing Strategy

- Feasibility / POC：
- Unit：
- Integration：
- API：
- E2E：
- Manual UX：

## Cost and Constraints

- [費用、性能、可用性、運用上の制約]

## Future Extensions

- [将来拡張]
