# AGENTS.md

## Text formatting rules

- **No em-dash.** Never use the em-dash character (`—`, U+2014). Use a standard hyphen (`-`), double hyphen (`--`), or en-dash (`–` where appropriate) instead. This applies to all files: Markdown, PHP, JavaScript, CSS, and any other text in this repository.
- Follow the existing conventions in each file. Match indentation, quote style, and comment style of surrounding code.
- **No testimonials or user reviews** in any README or public-facing document. The user has explicitly removed them.

## Repository context

This is the GitHub organization profile repository for **BotBlocker Security** -- a WordPress firewall and bot protection plugin by GLOBUS.studio. The main content is in `profile/README.md`.

### Key URLs

| Resource | URL |
|---|---|
| Product site | https://botblocker.top |
| WordPress.org plugin | https://wordpress.org/plugins/botblocker-security/ |
| Pricing page | https://botblocker.top/pricing/ |
| Documentation | https://botblocker.top/docs/ |
| Community | https://botblocker.top/community/ |
| Contact | https://botblocker.top/contacts/ |
| Support email | support@botblocker.top |

### Authoritative sources

- **wp.org plugin page** is the canonical source for feature claims, stats, and version info. Use `webfetch` to pull the latest data when updating the README.
- **botblocker.top/pricing/** is the canonical source for pricing, tier comparison, and plan features. Always verify against this page before editing the PRO Plans table.
- Never invent features, numbers, or claims. Verify against one of the two authoritative sources above.

## Multilingual README management

The `profile/` directory contains 11 README files -- the English original plus 10 translations:

| File | Language | Active label |
|---|---|---|
| `README.md` | English | `<b>English</b>` |
| `README_de.md` | Deutsch | `<b>Deutsch</b>` |
| `README_es.md` | Español | `<b>Español</b>` |
| `README_fr.md` | Français | `<b>Français</b>` |
| `README_pl.md` | Polski | `<b>Polski</b>` |
| `README_pt.md` | Português | `<b>Português</b>` |
| `README_ru.md` | Русский | `<b>Русский</b>` |
| `README_uk.md` | Українська | `<b>Українська</b>` |
| `README_ar.md` | العربية | `<b>العربية</b>` |
| `README_zh.md` | 中文 | `<b>中文</b>` |
| `README_ja.md` | 日本語 | `<b>日本語</b>` |

### Critical rules for translations

1. **All 11 files must stay in sync.** Any structural or factual change to `README.md` MUST be replicated to all 10 translated files immediately.
2. **Language bar format** — every file has a `<p align="center">` block at the top with the language switcher. The active language uses `<b>Tag</b>` (bold, no link). All other languages use `<a href="./README_xx.md">Tag</a>` with `./` prefix for explicit relative paths.
3. **Arabic (`README_ar.md`)** is RTL — the entire content is wrapped in `<div dir="rtl">...</div>`. Preserve this wrapper.
4. **Do not change the language bar order.** The order is: English, Deutsch, Español, Français, Polski, Português, Русский, Українська, العربية, 中文, 日本語.
5. **Translate meaning, not word-for-word.** Adapt commercial messaging to sound natural in each language while preserving all facts, numbers, and technical terms.
6. **Do not translate** technical identifiers: `wp-config.php`, `MU-plugin`, `FCrDNS`, `TOTP`, `WAF`, `CIDR`, `PTR`, `ASN`, `DB`, `IP`, `IPv4`, `IPv6`, `API`, `HMAC`, `JS`, `RAM`, `CPU`, `CDN`, `TTFB`, `REST`, `XML-RPC`, `GPL-2.0+`, `Freemius`, `GDPR`, `CCPA`.

## HTML / Markdown conventions

- Use `<p align="center">` for centered blocks (banner image, language bar, tagline, link bars, footer).
- Use `<h1 align="center">` for the main title.
- Use standard markdown tables with `|---|---|` separator rows.
- Use `---` for horizontal rules between major sections.
- Links to external sites use full `https://` URLs. Internal links between translations use `./README_xx.md`.
- Bold text uses `**text**` in markdown, `<b>text</b>` in HTML blocks.

## PRO Plans table

The pricing table in the PRO Plans section must match https://botblocker.top/pricing/. When updating:

1. Fetch the latest pricing page with `webfetch`.
2. Update the feature comparison table in `README.md` (English) first.
3. Replicate to all 10 translations.
4. Use the correct tier order: Free, Premium, Pro, Ultimate.
5. Include monthly and annual prices. Annual column shows "includes 1 month free".

Features by tier (verified against pricing page):

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
| Cloud checks/month | — | 25k | 100k | 250k |
| Unlock Addons | — | ✓ | ✓ | ✓ |
| Priority support | — | ✓ | ✓ | ✓ |
| Emergency support (24h) | — | — | — | ✓ |

## Sections that must NOT be in README

- Testimonials / user reviews / ratings
- Changelog / version history
- Installation instructions
- FAQ
- Repositories listing

## File structure

```
profile/
  README.md          (English — main, rendered on org page)
  README_de.md       (Deutsch)
  README_es.md       (Español)
  README_fr.md       (Français)
  README_pl.md       (Polski)
  README_pt.md       (Português)
  README_ru.md       (Русский)
  README_uk.md       (Українська)
  README_ar.md       (العربية, RTL)
  README_zh.md       (中文)
  README_ja.md       (日本語)
AGENTS.md            (this file)
```

## Maintenance workflow

When asked to update the README:

1. Read `profile/README.md` to understand current state.
2. If facts/features/pricing are involved, fetch the authoritative source (wp.org or botblocker.top/pricing).
3. Make the change in the English `README.md` first.
4. Replicate the exact same structural change to all 10 translation files, preserving each language's natural phrasing for the surrounding text.
5. Verify no em-dashes were introduced.
6. Verify the language bar is intact in every file.
