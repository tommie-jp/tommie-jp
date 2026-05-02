# CLAUDE.md

GitHub プロフィール用リポジトリ ([tommie-jp/tommie-jp](https://github.com/tommie-jp/tommie-jp)) — `github.com/tommie-jp` のプロフィールページに `README.md` がそのまま表示される。

## このリポジトリの構成

- [README.md](README.md) — 英語版 (デフォルト表示)
- [README.ja.md](README.ja.md) — 日本語版
- [doc/](doc/) — 改善案・運用メモ (公開リポジトリなので機密情報は書かない)

## 編集ルール

- **二言語を同期する**: `README.md` を更新したら `README.ja.md` も同等の内容にすること (片方だけ進めない)。
- **更新日を直す**: ヘッダの `Updated: YYYY-MM-DD` を編集ごとに今日の日付へ更新する。
- **リンクを壊さない**: 外部 URL とリポジトリリンクは編集後に必ず確認する (過去に `tommie-chat` / `reversi-uart-protocol` の URL が間違っていた前科あり)。
- **バッジの体裁**: shields.io の形式・色・logo 指定を既存と揃える。

## やらないこと

- 個人情報・連絡先の追加 (公開する分は既に README にある)
- HTML コメントでセットアップ手順を残す (過去に削除済み)
- README に実装詳細を書く (詳細は各プロジェクトの repo 側へ)

## コミット

`<type>: <description>` 形式 (feat / fix / docs / chore / refactor)。本文は省略可。
