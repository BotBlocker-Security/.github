<p align="center">
  <img src="https://ps.w.org/botblocker-security/assets/banner-1544x500.png?rev=3405280" alt="BotBlocker Security">
</p>

<p align="center">
  <a href="./README.md">English</a> ·
  <a href="./README_de.md">Deutsch</a> ·
  <a href="./README_es.md">Español</a> ·
  <a href="./README_fr.md">Français</a> ·
  <a href="./README_pl.md">Polski</a> ·
  <a href="./README_pt.md">Português</a> ·
  <a href="./README_ru.md">Русский</a> ·
  <a href="./README_uk.md">Українська</a> ·
  <a href="./README_ar.md">العربية</a> ·
  <a href="./README_zh.md">中文</a> ·
  <b>日本語</b>
</p>

<h1 align="center">BotBlocker Security</h1>

<p align="center">
  <strong>WordPress ファイアウォール & ボット対策</strong><br>
  ボット、ブルートフォース、スパム、偽クローラーをWordPressに到達する前に阻止します。
</p>

<p align="center">
  <a href="https://botblocker.top">公式サイト</a> ·
  <a href="https://wordpress.org/plugins/botblocker-security/">WordPress.org</a> ·
  <a href="https://botblocker.top/docs/">ドキュメント</a> ·
  <a href="https://botblocker.top/pricing/">料金</a> ·
  <a href="https://botblocker.top/community/">コミュニティ</a>
</p>

---

## BotBlocker とは？

**BotBlocker Security は、WordPressが読み込まれる前に99%の自動化攻撃をブロックします。** 肥大化なし、速度低下なし、コア保護に月額料金なし。60秒でセットアップ完了。

3層のインターセプトが `wp-config.php`（WordPress以前）、MU-pluginフェーズ、メインシールドで悪意あるトラフィックを阻止 - ブロックされたリクエストごとに30～100msと5～20MBのRAMを節約。競合製品はWordPress起動後に対応しますが、BotBlockerは脅威を入り口で阻止します。

**3,000以上のアクティブインストール · 8言語対応 · GDPR / CCPA準拠 · Cloudflare、WP Rocket、LiteSpeed、WooCommerce、Elementor、マルチサイト、IPv6対応**

---

## 主な機能

### 🛡️ コアファイアウォール（無料）
- **3層ファイアウォール**、リアルタイムWAFルール更新
- **2,899のUser-Agentシグネチャ** - WordPressプラグイン最大のブラックリスト
- **ブルートフォース対策**、段階的ロックアウトとエスカレーションバン
- **アンチスパム** - コメント、登録、お問い合わせフォーム対応
- **偽クローラー検出** FCrDNS経由 - 95%有効、偽装不可能
- **LLM / AIクローラー管理** - GPTBot、ClaudeBot、PerplexityBot、Bytespiderを許可またはブロック
- **国、ASN、IP範囲、User-Agent、Refererによるブロック**
- **Cloudflare対応** - 実IP解決とオリジンバイパス保護
- **完全IPv6サポート** - IPv4とIPv6で個別のテーブルとロジック
- **DDoS保護の自動検出** - DDoS-Guard、Stormwall、QratorのJSチャレンジを認識。手動ホワイトリストなしで強力なDDoS保護の背後で動作する唯一のWordPressプラグイン

### 🔒 ログインセキュリティ & 2FA（無料）
- **二要素認証** - TOTP標準（Google Authenticator、Authy、Bitwarden対応）
- **9種類のCAPTCHAモード** - サイレント自動検証、Shapes（60fps Canvas）、色、画像、数字、長押しボタン、シングルボタン、reCAPTCHA v2/v3
- **ハイブリッドCAPTCHA** - 内部CAPTCHAとreCAPTCHA v3の組み合わせで2層防御
- **ログインURLの非表示** *(PRO)*

### 💳 決済ゲートウェイバイパス（無料）
25以上のECプラットフォームと150以上の決済プロバイダー（Stripe、PayPal、WooCommerceなど）を自動検出。WebhookやIPN通知がブロックされることはありません。

### 📊 可視性とコントロール（無料）
- 攻撃マップと54のユニークなイベントコードを備えたライブトラフィックモニター
- ヘルススコアゲージ - 42パラメータ、5段階のセキュリティレベル
- 8つのインターフェース言語 - English、Deutsch、Español、Français、Polski、Русский、Українська、日本語
- クリーンアンインストール - 残留データゼロ

### 🚀 PROプラン

| 機能 | Free | Premium | Pro | Ultimate |
|---|---|---|---|---|
| リアルタイム訪問者統計 | ✓ | ✓ | ✓ | ✓ |
| MU-Mode | ✓ | ✓ | ✓ | ✓ |
| ブルートフォース対策 | ✓ | ✓ | ✓ | ✓ |
| 偽クローラー検出 (FCrDNS) | ✓ | ✓ | ✓ | ✓ |
| ローカルボットブロック | ✓ | ✓ | ✓ | ✓ |
| Redis / Memcached 統合 | ✓ | ✓ | ✓ | ✓ |
| Early Init モード | — | ✓ | ✓ | ✓ |
| クラウドIPインテリジェンス | — | ✓ | ✓ | ✓ |
| ゼロデイボットネット更新 | — | ✓ | ✓ | ✓ |
| 500万以上のボットシグネチャ | — | ✓ | ✓ | ✓ |
| 行動分析エンジン | — | ✓ | ✓ | ✓ |
| クラウドチェック / 月 | — | 25k | 100k | 250k |
| アドオン解除 | — | ✓ | ✓ | ✓ |
| 優先サポート | — | ✓ | ✓ | ✓ |
| 緊急サポート (24時間) | — | — | — | ✓ |
| **月額料金** | **Free** | **$12** | **$50** | **$100** |
| **年額料金** | **Free** | **$11/mo** | **$45.8/mo** | **$91.6/mo** |

年額請求には1ヶ月無料が含まれます。Freemiusによるドメイン単位ライセンス。
[プランを比較 →](https://botblocker.top/pricing/)

---

## BotBlockerを選ぶ理由

| | BotBlocker | 一般的なセキュリティプラグイン |
|---|---|---|
| **インターセプトポイント** | WordPress読み込み前 | WordPress起動後 |
| **ブロックされたリクエストあたりのCPU/RAM** | 30～100ms / 5～20MB RAM節約 | WordPressスタック全体を読み込み |
| **CAPTCHAモード** | 9（独自 + reCAPTCHA） | 1～2（reCAPTCHAのみ） |
| **AI耐性CAPTCHA** | あり -- ShapesはreCAPTCHAより約100倍解読困難（reCAPTCHAは$2-3/1,000で解読可能） | なし |
| **無料版の制限** | なし - 完全なファイアウォール、全CAPTCHA、完全な2FA | 機能制限、迷惑な通知画面 |
| **プライバシー** | 全データがサーバー上に保持されます | テレメトリ、外部API呼び出し |
| **実測オーバーヘッド** | 検証済み訪問者で +3～15ms | +20～200ms |

---

## 技術スタック

- **PHP** 7.4～8.5
- **WordPress** 5.1～7.0+
- **プラットフォーム** Linux、Windows、共有ホスティング
- **データベース** リピーター訪問者にDBクエリゼロ - 事前生成された9つのPHPランタイムファイル
- **キャッシュ** Redis / Memcached対応（障害時に自動無効化）
- **CDN / DDoS** Cloudflare、Sucuri、StackPath、DDoS-Guard、Stormwall対応
- **ライセンス** GPL-2.0+

---

## リポジトリ

| リポジトリ | 説明 |
|---|---|
| `botblocker-security` | WordPressプラグイン - コアファイアウォール、CAPTCHA、2FA、トラフィックモニター |
| *(近日公開)* | |

---

## リンク

- 🌐 [botblocker.top](https://botblocker.top/)
- 🔌 [WordPress.org プラグイン](https://wordpress.org/plugins/botblocker-security/)
- 📖 [ドキュメント](https://botblocker.top/docs/)
- 💰 [料金](https://botblocker.top/pricing/)
- 💬 [コミュニティ](https://botblocker.top/community/)
- 📧 [お問い合わせ](https://botblocker.top/contacts/)

---

<p align="center">
  <sub><a href="https://globus.studio">GLOBUS.studio</a> · <a href="https://leonidov.dev">Yevhen Leonidov</a> · Andrii Lukashevych · Aleksandr Kinakh により開発</sub>
</p>
