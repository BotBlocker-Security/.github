<p align="center">
  <img src="https://ps.w.org/botblocker-security/assets/banner-1544x500.png?rev=3405280" alt="BotBlocker Security">
</p>

<p align="center">
  <b>English</b> ·
  <a href="./README_de.md">Deutsch</a> ·
  <a href="./README_es.md">Español</a> ·
  <a href="./README_fr.md">Français</a> ·
  <a href="./README_pl.md">Polski</a> ·
  <a href="./README_pt.md">Português</a> ·
  <a href="./README_ru.md">Русский</a> ·
  <a href="./README_uk.md">Українська</a> ·
  <a href="./README_ar.md">العربية</a> ·
  <a href="./README_zh.md">中文</a> ·
  <a href="./README_ja.md">日本語</a>
</p>

<h1 align="center">BotBlocker Security</h1>

<p align="center">
  <strong>WordPress Firewall & Bot Protection</strong><br>
  Stop bots, brute force, spam, and fake crawlers - before they reach WordPress.
</p>

<p align="center">
  <a href="https://botblocker.top">Website</a> ·
  <a href="https://wordpress.org/plugins/botblocker-security/">WordPress.org</a> ·
  <a href="https://botblocker.top/docs/">Documentation</a> ·
  <a href="https://botblocker.top/pricing/">Pricing</a> ·
  <a href="https://botblocker.top/community/">Community</a>
</p>

---

## What is BotBlocker?

**BotBlocker Security blocks 99% of automated attacks before WordPress even loads.** No bloat, no slowdowns, no monthly fees for core protection. Setup in 60 seconds.

Three interception layers stop bad traffic at `wp-config.php` (before WordPress), MU-plugin phase, and the main shield - saving 30–100ms and 5–20MB RAM per blocked request. Competitors react after WordPress boots; BotBlocker stops threats at the door.

**3,000+ active installations · 8 languages · GDPR / CCPA compliant · Works with Cloudflare, WP Rocket, LiteSpeed, WooCommerce, Elementor, multisite, IPv6**

---

## Key Features

### 🛡️ Core Firewall (Free)
- **Three-layer firewall** with real-time WAF rule updates
- **2,899 User-Agent signatures** - largest blacklist among WordPress plugins
- **Brute force protection** with progressive lockouts and escalating bans
- **Anti-spam** for comments, registration, and contact forms
- **Fake crawler detection** via FCrDNS - 95% effective, impossible to spoof
- **LLM / AI crawler management** - allow or block GPTBot, ClaudeBot, PerplexityBot, Bytespider
- **Country, ASN, IP range, User-Agent, Referer** blocking rules
- **Cloudflare-aware** real-IP resolution and origin bypass protection
- **Full IPv6 support** - separate tables and logic for IPv4 and IPv6
- **DDoS protection auto-detection** - JS-challenge recognition for DDoS-Guard, Stormwall, Qrator. The only WordPress plugin that works behind aggressive DDoS protection without manual whitelisting

### 🔒 Login Security & 2FA (Free)
- **Two-Factor Authentication** - TOTP standard (Google Authenticator, Authy, Bitwarden)
- **9 CAPTCHA modes** - Silent Auto-Verify, Shapes (60fps Canvas), Colors, Images, Digits, Hold Button, Single Button, reCAPTCHA v2/v3
- **Hybrid CAPTCHA** - combine internal CAPTCHA with reCAPTCHA v3 for two-layer defense
- **Hide login URL** *(PRO)*

### 💳 Payment Gateway Bypass (Free)
Auto-detects 25+ e-commerce platforms and 150+ payment providers (Stripe, PayPal, WooCommerce, etc.). Webhooks and IPN callbacks never get blocked.

### 📊 Visibility & Control (Free)
- Live traffic monitor with attack map and 54 unique event codes
- Health Score gauge - 42 parameters, 5 security levels
- 8 interface languages - English, Deutsch, Español, Français, Polski, Русский, Українська
- Clean uninstall - zero leftover data

### 🚀 PRO Plans

| Feature | Free | Premium | Pro | Ultimate |
|---|---|---|---|---|
| Real-time visitor statistics | ✓ | ✓ | ✓ | ✓ |
| MU-Mode | ✓ | ✓ | ✓ | ✓ |
| Brute-force protection | ✓ | ✓ | ✓ | ✓ |
| Fake crawler detection (FCrDNS) | ✓ | ✓ | ✓ | ✓ |
| Local bot blocking | ✓ | ✓ | ✓ | ✓ |
| Redis / Memcached integration | ✓ | ✓ | ✓ | ✓ |
| Early Init Mode | — | ✓ | ✓ | ✓ |
| Cloud IP intelligence | — | ✓ | ✓ | ✓ |
| Zero-day botnet updates | — | ✓ | ✓ | ✓ |
| 5M+ bots signatures | — | ✓ | ✓ | ✓ |
| Behavioral analysis engine | — | ✓ | ✓ | ✓ |
| Cloud checks / month | — | 25k | 100k | 250k |
| Unlock Addons | — | ✓ | ✓ | ✓ |
| Priority support | — | ✓ | ✓ | ✓ |
| Emergency support (24h) | — | — | — | ✓ |
| **Monthly price** | **Free** | **$12** | **$50** | **$100** |
| **Annual price** | **Free** | **$11/mo** | **$45.8/mo** | **$91.6/mo** |

Annual billing includes 1 month free. Licensed per domain via Freemius.
[Compare plans →](https://botblocker.top/pricing/)

---

## Why BotBlocker?

| | BotBlocker | Typical security plugins |
|---|---|---|
| **Interception point** | Before WordPress loads | After WordPress boots |
| **CPU/RAM per blocked request** | 30–100ms / 5–20MB RAM saved | Full WordPress stack loaded |
| **CAPTCHA modes** | 9 (proprietary + reCAPTCHA) | 1–2 (reCAPTCHA only) |
| **AI-resistant CAPTCHA** | Yes -- Shapes ~100x harder to crack than reCAPTCHA (crackable for $2-3/1,000) | No |
| **Free tier limits** | None - full firewall, all CAPTCHAs, full 2FA | Crippled features, nag screens |
| **Privacy** | All data stays on your server | Telemetry, external API calls |
| **Measured overhead** | +3–15ms for verified visitors | +20–200ms |

---

## Tech Stack

- **PHP** 7.4–8.5
- **WordPress** 5.1–7.0+
- **Platform** Linux, Windows, shared hosting
- **Database** Zero DB queries for returning visitors - 9 pre-generated PHP runtime files
- **Cache** Redis / Memcached support (auto-disable on failure)
- **CDN / DDoS** Cloudflare, Sucuri, StackPath, DDoS-Guard, Stormwall compatible
- **License** GPL-2.0+

---

## Repositories

| Repository | Description |
|---|---|
| `botblocker-security` | WordPress plugin - core firewall, CAPTCHA, 2FA, traffic monitor |
| *(more coming)* | |

---

## Links

- 🌐 [botblocker.top](https://botblocker.top/)
- 🔌 [WordPress.org Plugin](https://wordpress.org/plugins/botblocker-security/)
- 📖 [Documentation](https://botblocker.top/docs/)
- 💰 [Pricing](https://botblocker.top/pricing/)
- 💬 [Community](https://botblocker.top/community/)
- 📧 [Contact](https://botblocker.top/contacts/)

---

<p align="center">
  <sub>Built by <a href="https://globus.studio">GLOBUS.studio</a> · <a href="https://leonidov.dev">Yevhen Leonidov</a> · Andrii Lukashevych · Aleksandr Kinakh</sub>
</p>
