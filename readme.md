# Release workflow test

main ブランチへの push (PR のマージも含む) から Release を作成するワークフローのテスト

## 使用方法

コミットメッセージに以下のタグを含めることで動作します

- `[release major]`
- `[release minor]`
- `[release patch]`

バージョンの増やし方は [Semantic Versioning 2.0](https://semver.org/lang/ja/) に準拠します。
