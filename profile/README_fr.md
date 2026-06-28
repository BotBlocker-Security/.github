<p align="center">
  <img src="https://ps.w.org/botblocker-security/assets/banner-1544x500.png?rev=3405280" alt="BotBlocker Security">
</p>

<p align="center">
  <a href="./README.md">English</a> ·
  <a href="./README_de.md">Deutsch</a> ·
  <a href="./README_es.md">Español</a> ·
  <b>Français</b> ·
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
  <strong>Pare-feu WordPress & Protection Anti-bots</strong><br>
  Arrête les bots, la force brute, le spam et les faux crawlers - avant qu'ils n'atteignent WordPress.
</p>

<p align="center">
  <a href="https://botblocker.top">Site Web</a> ·
  <a href="https://wordpress.org/plugins/botblocker-security/">WordPress.org</a> ·
  <a href="https://botblocker.top/docs/">Documentation</a> ·
  <a href="https://botblocker.top/pricing/">Tarifs</a> ·
  <a href="https://botblocker.top/community/">Communauté</a>
</p>

---

## Qu'est-ce que BotBlocker ?

**BotBlocker Security bloque 99% des attaques automatisées avant même que WordPress ne se charge.** Aucun surpoids, aucun ralentissement, aucun frais mensuel pour la protection de base. Configuration en 60 secondes.

Trois couches d'interception arrêtent le trafic malveillant au niveau de `wp-config.php` (avant WordPress), en phase MU-plugin et au bouclier principal - économisant 30–100ms et 5–20MB de RAM par requête bloquée. Les concurrents réagissent après le démarrage de WordPress ; BotBlocker arrête les menaces à la porte.

**3 000+ installations actives · 8 langues · Conforme RGPD / CCPA · Compatible avec Cloudflare, WP Rocket, LiteSpeed, WooCommerce, Elementor, multisite, IPv6**

---

## Fonctionnalités Clés

### 🛡️ Pare-feu Principal (Gratuit)
- **Pare-feu à trois couches** avec mises à jour des règles WAF en temps réel
- **2 899 signatures User-Agent** - la plus grande liste noire parmi les plugins WordPress
- **Protection contre la force brute** avec verrouillages progressifs et bannissements croissants
- **Anti-spam** pour les commentaires, inscriptions et formulaires de contact
- **Détection des faux crawlers** via FCrDNS - 95% efficace, impossible à usurper
- **Gestion des crawlers LLM / IA** - autoriser ou bloquer GPTBot, ClaudeBot, PerplexityBot, Bytespider
- **Blocage par pays, ASN, plage IP, User-Agent, Referer**
- **Compatible Cloudflare** - résolution IP réelle et protection contre le contournement d'origine
- **Support complet IPv6** - tables et logique séparées pour IPv4 et IPv6
- **Détection automatique DDoS** - reconnaissance des JS-challenges pour DDoS-Guard, Stormwall, Qrator. Le seul plugin WordPress fonctionnant derrière une protection DDoS agressive sans liste blanche manuelle

### 🔒 Sécurité de Connexion & 2FA (Gratuit)
- **Authentification à Deux Facteurs** - standard TOTP (Google Authenticator, Authy, Bitwarden)
- **9 modes CAPTCHA**:
  - **Silent Auto-Verify** -- les vrais utilisateurs passent automatiquement sans clic, les bots voient "Accès refusé"
  - **Shapes CAPTCHA** -- Canvas 60fps avec figures géométriques animées, ~100x plus difficile à craquer pour l'IA que reCAPTCHA
  - **Color CAPTCHA** -- sélectionnez la bonne combinaison de couleurs
  - **Images CAPTCHA** -- défi de reconnaissance visuelle
  - **Digits CAPTCHA** -- vérification numérique
  - **Hold Button CAPTCHA** -- vérification humaine par appui prolongé
  - **Single Button CAPTCHA** -- vérification en un clic
  - **reCAPTCHA v2** -- "Je ne suis pas un robot" de Google
  - **reCAPTCHA v3** -- vérification invisible par score
- **CAPTCHA Hybride** -- combine n'importe quel CAPTCHA interne avec reCAPTCHA v3 pour une défense invisible à deux couches
- **Masquer l'URL de connexion** *(PRO)*

### 💳 Contournement des Passerelles de Paiement (Gratuit)
Détection automatique de plus de 25 plateformes e-commerce et plus de 150 fournisseurs de paiement (Stripe, PayPal, WooCommerce, etc.). Les webhooks et notifications IPN ne sont jamais bloqués.

### 📊 Visibilité & Contrôle (Gratuit)
- Moniteur de trafic en direct avec carte des attaques et 54 codes d'événement uniques
- Jauge Health Score - 42 paramètres, 5 niveaux de sécurité
- 8 langues d'interface - English, Deutsch, Español, Français, Polski, Русский, Українська
- Désinstallation propre - zéro donnée résiduelle

### 🚀 Plans PRO

| Fonctionnalité | Free | Premium | Pro | Ultimate |
|---|---|---|---|---|
| Statistiques visiteurs en temps réel | ✓ | ✓ | ✓ | ✓ |
| Mode MU | ✓ | ✓ | ✓ | ✓ |
| Protection contre la force brute | ✓ | ✓ | ✓ | ✓ |
| Détection de faux crawlers (FCrDNS) | ✓ | ✓ | ✓ | ✓ |
| Blocage local des bots | ✓ | ✓ | ✓ | ✓ |
| Intégration Redis / Memcached | ✓ | ✓ | ✓ | ✓ |
| Mode Early Init | -- | ✓ | ✓ | ✓ |
| Renseignement IP cloud | -- | ✓ | ✓ | ✓ |
| Mises à jour zero-day des botnets | -- | ✓ | ✓ | ✓ |
| 5M+ signatures de bots | -- | ✓ | ✓ | ✓ |
| Moteur d'analyse comportementale | -- | ✓ | ✓ | ✓ |
| Vérifications cloud / mois | -- | 25k | 100k | 250k |
| Débloquer les Addons | -- | ✓ | ✓ | ✓ |
| Support prioritaire | -- | ✓ | ✓ | ✓ |
| Support d'urgence (24h) | -- | -- | -- | ✓ |
| **Prix mensuel** | **Free** | **$12** | **$50** | **$100** |
| **Prix annuel** | **Free** | **$11/mo** | **$45.8/mo** | **$91.6/mo** |

La facturation annuelle inclut 1 mois gratuit. Licence par domaine via Freemius.
[Comparer les plans →](https://botblocker.top/pricing/)

---

## Pourquoi BotBlocker ?

| | BotBlocker | Plugins de sécurité typiques |
|---|---|---|
| **Point d'interception** | Avant le chargement de WordPress | Après le démarrage de WordPress |
| **CPU/RAM par requête bloquée** | 30–100ms / 5–20MB RAM économisés | Pile WordPress complète chargée |
| **Modes CAPTCHA** | 9 (propriétaires + reCAPTCHA) | 1–2 (reCAPTCHA uniquement) |
| **CAPTCHA résistant à l'IA** | Oui -- Shapes ~100x plus difficile à craquer que reCAPTCHA (cassable pour $2-3/1 000) | Non |
| **Limites version gratuite** | Aucune - pare-feu complet, toutes les CAPTCHA, 2FA complet | Fonctions limitées, écrans intrusifs |
| **Confidentialité** | Toutes les données restent sur votre serveur | Télémétrie, appels API externes |
| **Surcharge mesurée** | +3–15ms pour les visiteurs vérifiés | +20–200ms |

---

## Stack Technique

- **PHP** 7.4–8.5
- **WordPress** 5.1–7.0+
- **Plateforme** Linux, Windows, hébergement mutualisé
- **Base de données** Zéro requête DB pour les visiteurs récurrents - 9 fichiers PHP d'exécution pré-générés
- **Cache** Support Redis / Memcached (désactivation automatique en cas d'échec)
- **CDN / DDoS** Compatible avec Cloudflare, Sucuri, StackPath, DDoS-Guard, Stormwall
- **Licence** GPL-2.0+

---

## Liens

- 🌐 [botblocker.top](https://botblocker.top/)
- 🔌 [Plugin WordPress.org](https://wordpress.org/plugins/botblocker-security/)
- 📖 [Documentation](https://botblocker.top/docs/)
- 💰 [Tarifs](https://botblocker.top/pricing/)
- 💬 [Communauté](https://botblocker.top/community/)
- 📧 [Contact](https://botblocker.top/contacts/)

---

<p align="center">
  <sub>Créé par <a href="https://globus.studio">GLOBUS.studio</a> · <a href="https://leonidov.dev">Yevhen Leonidov</a> · Andrii Lukashevych · Aleksandr Kinakh</sub>
</p>
