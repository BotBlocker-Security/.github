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
  <b>Українська</b> ·
  <a href="./README_ar.md">العربية</a> ·
  <a href="./README_zh.md">中文</a> ·
  <a href="./README_ja.md">日本語</a>
</p>

<h1 align="center">BotBlocker Security</h1>

<p align="center">
  <strong>WordPress Firewall & Захист від ботів</strong><br>
  Зупиняє ботів, брутфорс, спам і підроблених краулерів - до того, як вони досягнуть WordPress.
</p>

<p align="center">
  <a href="https://botblocker.top">Сайт</a> ·
  <a href="https://wordpress.org/plugins/botblocker-security/">WordPress.org</a> ·
  <a href="https://botblocker.top/docs/">Документація</a> ·
  <a href="https://botblocker.top/pricing/">Ціни</a> ·
  <a href="https://botblocker.top/community/">Спільнота</a>
</p>

---

## Що таке BotBlocker?

**BotBlocker Security блокує 99% автоматичних атак ще до завантаження WordPress.** Жодного роздування, жодних сповільнень, жодної щомісячної плати за базовий захист. Налаштування за 60 секунд.

Три рівні перехоплення зупиняють шкідливий трафік на рівні `wp-config.php` (до WordPress), у фазі MU-plugin і на основному щиті - заощаджуючи 30–100ms і 5–20MB RAM на кожен заблокований запит. Конкуренти реагують після завантаження WordPress; BotBlocker зупиняє загрози на вході.

**3 000+ активних встановлень · 8 мов · GDPR / CCPA compliant · Сумісний з Cloudflare, WP Rocket, LiteSpeed, WooCommerce, Elementor, мультисайт, IPv6**

---

## Ключові можливості

### 🛡️ Основний Firewall (Безкоштовно)
- **Трирівневий firewall** з оновленнями WAF-правил у реальному часі
- **2 899 сигнатур User-Agent** - найбільший чорний список серед плагінів WordPress
- **Захист від брутфорсу** з прогресивними блокуваннями та ескалацією банів
- **Анти-спам** для коментарів, реєстрацій і контактних форм
- **Виявлення підроблених краулерів** через FCrDNS - ефективність 95%, неможливо підробити
- **Керування LLM / AI краулерами** - дозволити або заблокувати GPTBot, ClaudeBot, PerplexityBot, Bytespider
- **Блокування за країною, ASN, діапазоном IP, User-Agent, Referer**
- **Підтримка Cloudflare** - визначення реального IP і захист від обходу origin
- **Повна підтримка IPv6** - окремі таблиці та логіка для IPv4 і IPv6
- **Авто-виявлення DDoS-захисту** - розпізнавання JS-челенджів DDoS-Guard, Stormwall, Qrator. Єдиний WordPress плагін, що працює за агресивним DDoS-захистом без ручного вайтлістингу

### 🔒 Безпека входу та 2FA (Безкоштовно)
- **Двофакторна аутентифікація** - стандарт TOTP (Google Authenticator, Authy, Bitwarden)
- **9 режимів CAPTCHA** - Silent Auto-Verify, Shapes (60fps Canvas), Colors, Images, Digits, Hold Button, Single Button, reCAPTCHA v2/v3
- **Гібридна CAPTCHA** - комбінація внутрішньої CAPTCHA з reCAPTCHA v3 для дворівневого захисту
- **Прихований URL входу** *(PRO)*

### 💳 Обхід платіжних шлюзів (Безкоштовно)
Авто-визначення 25+ e-commerce платформ і 150+ платіжних провайдерів (Stripe, PayPal, WooCommerce та ін.). Webhook'и та IPN-сповіщення ніколи не блокуються.

### 📊 Видимість і контроль (Безкоштовно)
- Живий моніторинг трафіку з картою атак і 54 унікальними кодами подій
- Індикатор Health Score - 42 параметри, 5 рівнів безпеки
- 8 мов інтерфейсу - English, Deutsch, Español, Français, Polski, Русский, Українська
- Чисте видалення - нуль залишкових даних

### 🚀 PRO Тарифи

| Функція | Free | Premium | Pro | Ultimate |
|---|---|---|---|---|
| Статистика відвідувачів у реальному часі | ✓ | ✓ | ✓ | ✓ |
| Режим MU-Mode | ✓ | ✓ | ✓ | ✓ |
| Захист від брутфорсу | ✓ | ✓ | ✓ | ✓ |
| Виявлення підроблених краулерів (FCrDNS) | ✓ | ✓ | ✓ | ✓ |
| Локальне блокування ботів | ✓ | ✓ | ✓ | ✓ |
| Інтеграція з Redis / Memcached | ✓ | ✓ | ✓ | ✓ |
| Режим Early Init | — | ✓ | ✓ | ✓ |
| Хмарна розвідка IP | — | ✓ | ✓ | ✓ |
| Zero-day оновлення ботнетів | — | ✓ | ✓ | ✓ |
| 5M+ сигнатур ботів | — | ✓ | ✓ | ✓ |
| Аналіз поведінки | — | ✓ | ✓ | ✓ |
| Хмарних перевірок / міс | — | 25k | 100k | 250k |
| Розблокування аддонів | — | ✓ | ✓ | ✓ |
| Пріоритетна підтримка | — | ✓ | ✓ | ✓ |
| Екстрена підтримка (24г) | — | — | — | ✓ |
| **Ціна за місяць** | **Free** | **$12** | **$50** | **$100** |
| **Ціна за рік** | **Free** | **$11/mo** | **$45.8/mo** | **$91.6/mo** |

При річній оплаті 1 місяць безкоштовно. Ліцензія на домен через Freemius.
[Порівняти тарифи →](https://botblocker.top/pricing/)

---

## Чому BotBlocker?

| | BotBlocker | Звичайні плагіни безпеки |
|---|---|---|
| **Точка перехоплення** | До завантаження WordPress | Після завантаження WordPress |
| **CPU/RAM на заблокований запит** | 30–100ms / 5–20MB RAM зекономлено | Повний стек WordPress завантажено |
| **Режими CAPTCHA** | 9 (пропрієтарні + reCAPTCHA) | 1–2 (тільки reCAPTCHA) |
| **AI-стійка CAPTCHA** | Так -- Shapes ~у 100 разів складніше зламати, ніж reCAPTCHA (зламується за $2-3/1 000) | Ні |
| **Обмеження безкоштовної версії** | Немає - повний firewall, всі CAPTCHA, повний 2FA | Урізані функції, нав'язливі екрани |
| **Приватність** | Всі дані залишаються на вашому сервері | Телеметрія, зовнішні API-виклики |
| **Виміряні накладні витрати** | +3–15ms для верифікованих відвідувачів | +20–200ms |

---

## Технологічний стек

- **PHP** 7.4–8.5
- **WordPress** 5.1–7.0+
- **Платформа** Linux, Windows, shared hosting
- **База даних** Нуль запитів до БД для постійних відвідувачів - 9 попередньо згенерованих PHP-файлів
- **Кеш** Підтримка Redis / Memcached (авто-відключення при збої)
- **CDN / DDoS** Сумісний з Cloudflare, Sucuri, StackPath, DDoS-Guard, Stormwall
- **Ліцензія** GPL-2.0+

---

## Репозиторії

| Репозиторій | Опис |
|---|---|
| `botblocker-security` | Плагін WordPress - основний firewall, CAPTCHA, 2FA, моніторинг трафіку |
| *(скоро)* | |

---

## Посилання

- 🌐 [botblocker.top](https://botblocker.top/)
- 🔌 [Плагін на WordPress.org](https://wordpress.org/plugins/botblocker-security/)
- 📖 [Документація](https://botblocker.top/docs/)
- 💰 [Ціни](https://botblocker.top/pricing/)
- 💬 [Спільнота](https://botblocker.top/community/)
- 📧 [Контакти](https://botblocker.top/contacts/)

---

<p align="center">
  <sub>Розроблено <a href="https://globus.studio">GLOBUS.studio</a> · <a href="https://leonidov.dev">Yevhen Leonidov</a> · Andrii Lukashevych · Aleksandr Kinakh</sub>
</p>
