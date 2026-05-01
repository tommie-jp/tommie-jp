# README.ja.md 追加候補メモ

2026-05-02

GitHub プロフィール README として強化できる項目を優先度順にまとめたメモ。

## 🔴 高優先 — 見た人の行動を増やす

### 連絡手段の追加

- 現状: GitHub のみ
- 候補: X / Bluesky / Mastodon / Email / LinkedIn のいずれか
- 理由: GitHub だけだと「Issue / DM 経由」になり敷居が高い。複数の入口を用意すると反応率が上がる

### ブログ記事の自動同期

- 現状: ブログサイトへの導線なし
- 方法: `tommie.jp` のブログを **blog-post-workflow** GitHub Action で最新 5 件を自動表示
- 参考: <https://github.com/marketplace/actions/blog-post-workflow>
- 効果: README に「最新の活動」感が出る、更新頻度が見える

## 🟡 中優先 — 差別化

### ヘッダ画像 / バナー

- 名前 + キャッチコピー（例: 「Web 〜 FPGA を横断する個人開発者」）を画像化
- 効果: 視認性向上、第一印象が変わる
- ツール: Canva / Figma / capsule-render など

### Reversi 関連の実績欄

- Reversi プロジェクトが 3 つある（reversi-uart-protocol / Soft-FPGA-Reversi / 関連）
- もし大会戦績やレーティングがあれば追加すると独自性が際立つ
- 例: WOR / Othello Quest / Logistello との対戦結果など

### 「最近やってること / Now」セクション

- 短期的トピック（例: 「Soft-FPGA-TD4 でパイプライン最適化中」）を 2〜3 行
- 動的な README 感が出る
- 月 1 で更新する運用にするのが理想

## 🟢 低優先 — お好みで

### 使用ハードウェア

- Raspberry Pi Pico 2 / アンテナ / オシロ / ロジアナなど
- 効果: 組み込み・電子工作志向の人に刺さる

### 支援ボタン

- GitHub Sponsors / Buy me a coffee 等
- 注意: Buy Me a Coffee は KYC で電話番号公開リスクあり（[github-sponsors-setup.md](./github-sponsors-setup.md) 参照）
- 推奨: GitHub Sponsors のみ

### Pinned リポジトリの調整

- README 本文ではなく GitHub プロフィール側の設定だが、相互補完
- 推奨: `tommie-chat` / `reversi-uart-protocol` / `Soft-FPGA-Reversi` を手動で pin

## トレードオフ

情報を増やすほど「30 秒スキャン性」が落ちる。優先度高の 2 つ（連絡手段 + ブログ自動同期）だけ足すのが現実的。
