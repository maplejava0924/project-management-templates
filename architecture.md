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

## Testing Strategy

- Unit：
- Integration：
- API：
- E2E：
- Manual UX：

## Cost and Constraints

- [費用、性能、可用性、運用上の制約]

## Future Extensions

- [将来拡張]
