# NotebookLM キーワード分析 RooCode ルール

## 📋 概要
NotebookLMに関連するキーワードを収集・分析し、効果的なブログ記事作成のための RooCode ルールセットです。

## 🗂️ ディレクトリ構造
```bash
.roo/                   # RooCodeルール
├── .roomodes           # カスタムモード設定
├── rules-keyword/      # キーワード処理ルール
│   ├── 01-raw-import.mdc    # 生データ整形ルール
│   ├── 02-keyword-check.mdc # バリデーションルール
│   └── 03-batch-processing.mdc # バッチ処理ルール
├── rules-persona/      # ペルソナ生成ルール
│   └── 01-persona-template.mdc
├── rules-outline/      # アウトライン生成ルール
│   ├── 01-outline-AIDA.mdc
│   └── 02-outline-PREP.mdc
└── rules-title/        # タイトル最適化ルール
    └── 01-title-style.mdc
```

## 🔧 カスタムモード
- **keyword-processor**: キーワードデータの処理と最適化
- **batch-orchestrator**: 大規模データのバッチ処理管理
- **debug-analyzer**: エラー分析と解決策提案
- **persona**: ペルソナ生成
- **outline**: アウトライン作成
- **title-writer**: タイトル最適化

## 📝 ルール説明

### キーワード処理ルール
1. **01-raw-import.mdc**
   - 生データの読み込みと正規化
   - 重複排除と前処理
   - カテゴリ分類（Primary/Secondary/Support）

2. **02-keyword-check.mdc**
   - 重複・類似度チェック
   - フォーマット検証
   - ノイズフィルタリング

3. **03-batch-processing.mdc**
   - 大規模データの分割処理
   - エラーハンドリング
   - 結果の統合

### ペルソナ生成ルール
- **01-persona-template.mdc**
  - 検索意図の分析
  - ユーザー属性の定義
  - 課題とゴールの設定

### アウトライン生成ルール
- **01-outline-AIDA.mdc**: Attention→Interest→Desire→Action
- **02-outline-PREP.mdc**: Point→Reason→Example→Point

### タイトル最適化ルール
- **01-title-style.mdc**
  - SEO最適化
  - 文字数制限
  - キーワード配置

## 🚀 使用方法
1. `.roo`ディレクトリをプロジェクトにコピー
2. `.roomodes`の設定を確認
3. 必要に応じてルールをカスタマイズ

## ⚙️ 必要な環境
- RooCode拡張機能
- Claude 3.7 Sonnet（推奨）

## 📄 ライセンス
MITライセンス 