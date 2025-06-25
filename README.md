# Issue Templates

再利用可能なGitHubイシューテンプレート集です。

## 📋 含まれているテンプレート

### 基本テンプレート
- **Bug Report** - バグレポート用
- **Feature Request** - 機能要求用
- **Question** - 質問用
- **Documentation** - ドキュメント関連
- **Performance** - パフォーマンス問題用

## 🚀 使用方法

### 1. テンプレートファイルをコピー

他のリポジトリで使用する場合は、必要なテンプレートファイルを `.github/ISSUE_TEMPLATE/` ディレクトリにコピーしてください。

```bash
# 例: bug_report.mdをコピー
cp .github/ISSUE_TEMPLATE/bug_report.md /path/to/your/repo/.github/ISSUE_TEMPLATE/
```

### 2. プロジェクトに合わせてカスタマイズ

各テンプレートは汎用的に作られていますが、プロジェクトの特性に合わせて以下をカスタマイズしてください：

- **タイトルプレフィックス**: `[BUG]`, `[FEATURE]` など
- **ラベル**: プロジェクトのラベル体系に合わせて変更
- **担当者**: デフォルトの担当者を設定
- **質問項目**: プロジェクト固有の情報を追加

### 3. config.ymlの設定

`config.yml` ファイルも忘れずにコピーし、連絡先情報を更新してください：

```yaml
contact_links:
  - name: 💬 Discussions
    url: https://github.com/your-username/your-repo/discussions
    about: For general questions and discussions
  - name: 🔒 Security Issues
    url: mailto:your-security@example.com
    about: Please report security vulnerabilities privately
```

## 📚 テンプレートの詳細

### Bug Report
- 再現手順
- 期待される動作
- 実際の動作
- 環境情報
- スクリーンショット

### Feature Request
- 問題の説明
- 提案する解決策
- 代替案
- 使用例
- 実装アイデア

### Question
- 質問内容
- コンテキスト
- 試したこと
- 関連ドキュメント

### Documentation
- ドキュメントの種類
- 場所
- 現在の内容
- 改善提案

### Performance
- パフォーマンス問題
- 測定データ
- 環境情報
- 改善提案

## 🔧 カスタマイズのヒント

### プロジェクト固有の情報を追加
- 特定のツールやフレームワークのバージョン情報
- プロジェクト固有の設定情報
- 関連するログファイルの場所

### ラベルの統一
各テンプレートで使用するラベルを、プロジェクトのラベル体系に合わせて統一してください。

### 多言語対応
必要に応じて、英語版と日本語版の両方を用意することもできます。

## 🤝 貢献

新しいテンプレートの追加や既存テンプレートの改善案があれば、イシューやプルリクエストでお知らせください。

## 📄 ライセンス

このテンプレート集は自由に使用・改変していただけます。

---

**使用例**
- [他のリポジトリでの使用例](https://github.com/kur00/issue-templates/issues)
- [カスタマイズ例](https://github.com/kur00/issue-templates/wiki)
