# コントリビューションガイド

[日本語](#コントリビューションガイド) | [English](#contributing-guide)

Ether合同会社が公開しているリポジトリ共通の貢献手順です。各リポジトリに独自の `CONTRIBUTING.md` がある場合は、そちらが優先されます。

## 行動規範

参加者は [行動規範](CODE_OF_CONDUCT.md) に従ってください。

## Issue

- バグ報告と機能要望は、各リポジトリの Issue テンプレートを使って作成してください。
- 脆弱性は Issue に書かず、[セキュリティポリシー](SECURITY.md) に従って非公開で報告してください。
- 使い方の質問は [サポート](SUPPORT.md) を参照してください。

## Pull Request

1. `main` から作業ブランチを切ります（例: `fix/…`、`feat/…`、`chore/…`）。
2. 変更は小さく、1 つの目的に絞ります。
3. `main` への直接 push はできません。必ず Pull Request を作成し、CI（ビルドとテスト、コードレビュー）が通ってからマージします。
4. コミットメッセージの 1 行目は変更内容を日本語または英語で簡潔に書きます。
5. `.editorconfig` の設定に従い、各リポジトリのフォーマッタとリンタ（Swift は Xcode の設定、Python は Ruff）を通してください。

## ライセンス

貢献した内容は、各リポジトリの `LICENSE` に記載のライセンスで公開されることに同意したものとみなします。

---

## Contributing guide

These are the shared contribution rules for the public repositories of Ether LLC. A repository's own `CONTRIBUTING.md`, if present, takes precedence.

### Code of conduct

All participants are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

### Issues

- Use the issue templates for bug reports and feature requests.
- Do not file vulnerabilities as issues; follow the [security policy](SECURITY.md) and report privately.
- For usage questions, see [SUPPORT.md](SUPPORT.md).

### Pull requests

1. Branch from `main` (for example `fix/…`, `feat/…`, `chore/…`).
2. Keep changes small and focused on one purpose.
3. Direct pushes to `main` are not allowed. Open a pull request and merge only after CI (build, tests, code review) passes.
4. Write a concise first line in the commit message, in Japanese or English.
5. Follow `.editorconfig` and run the repository's formatter and linter (Xcode settings for Swift, Ruff for Python).

### License

By contributing, you agree that your contribution is released under the license in the repository's `LICENSE` file.
