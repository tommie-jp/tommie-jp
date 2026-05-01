# GitHub Sponsors アカウント作成メモ

2026-05-02

## 前提条件

- GitHub アカウント作成から 30 日以上経過
- 2 要素認証 (2FA) 有効化済み
- コミュニティガイドライン違反なし

## 作成手順

1. **申請開始** — <https://github.com/sponsors> にアクセス → "Join the waitlist" / "Get started"
2. **基本情報入力**
   - 居住国（日本）
   - 自己紹介・Sponsors を始める理由
3. **本人確認 (KYC)** — Stripe Connect 経由
   - 政府発行 ID（運転免許証 / マイナンバーカード / パスポートのいずれか）
   - 住所
   - 電話番号
   - 銀行口座（日本の銀行で OK、Stripe が直接振込）
4. **税務情報** — 日本居住者は **W-8BEN** を提出
   - 目的: 米国源泉税の免除申請（日米租税条約による軽減）
5. **Sponsorship 階層 (tier) 設定**
   - 月額 $1 / $5 / $10 など複数階層を設定可能
   - 各階層に特典をつけてもよい（任意）
6. **プロフィールカスタマイズ**
   - Sponsorship 目標（例: 月 $100 達成で〜）
   - 自己紹介文・画像
7. **GitHub 審査** — 通常 1〜2 週間
8. **承認後** — プロフィールページに `Sponsor` ボタンが表示される

## 公開される情報 vs 非公開

| 項目 | 公開? |
| --- | --- |
| GitHub ユーザー名 | ✅ 公開 |
| 表示名（GitHub プロフィールで設定したもの） | ✅ 公開 |
| Sponsorship 階層・金額 | ✅ 公開 |
| 自己紹介文・目標 | ✅ 公開 |
| **住所** | ❌ 非公開（Stripe 内のみ） |
| **電話番号** | ❌ 非公開（Stripe 内のみ） |
| **政府発行 ID** | ❌ 非公開（Stripe 内のみ） |
| **銀行口座** | ❌ 非公開（Stripe 内のみ） |
| 税務情報（W-8BEN 等） | ❌ 非公開 |

## ポイント

- Buy Me a Coffee と違い、profile に商業情報（電話番号等）を載せる義務がない
- KYC 情報は規制対応目的のみで、Stripe / GitHub 内に閉じる
- 日本での所得税申告は別途必要（年 20 万円超で **確定申告**）

## 参考リンク

- 公式: <https://github.com/sponsors>
- ヘルプ: <https://docs.github.com/en/sponsors>
- Stripe Connect (本人確認の仕組み): <https://stripe.com/connect>
