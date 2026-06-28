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
  <b>Русский</b> ·
  <a href="./README_uk.md">Українська</a> ·
  <a href="./README_ar.md">العربية</a> ·
  <a href="./README_zh.md">中文</a> ·
  <a href="./README_ja.md">日本語</a>
</p>

<h1 align="center">BotBlocker Security</h1>

<p align="center">
  <strong>WordPress Firewall & Защита от ботов</strong><br>
  Останавливает ботов, брутфорс, спам и поддельных краулеров - до того как они достигнут WordPress.
</p>

<p align="center">
  <a href="https://botblocker.top">Сайт</a> ·
  <a href="https://wordpress.org/plugins/botblocker-security/">WordPress.org</a> ·
  <a href="https://botblocker.top/docs/">Документация</a> ·
  <a href="https://botblocker.top/pricing/">Цены</a> ·
  <a href="https://botblocker.top/community/">Сообщество</a>
</p>

---

## Что такое BotBlocker?

**BotBlocker Security блокирует 99% автоматических атак ещё до загрузки WordPress.** Никакого раздувания, никаких замедлений, никакой ежемесячной платы за базовую защиту. Настройка за 60 секунд.

Три уровня перехвата останавливают вредоносный трафик на уровне `wp-config.php` (до WordPress), в фазе MU-plugin и на основном щите - экономя 30–100ms и 5–20MB RAM на каждый заблокированный запрос. Конкуренты реагируют после загрузки WordPress; BotBlocker останавливает угрозы на входе.

**3 000+ активных установок · 8 языков · GDPR / CCPA compliant · Совместим с Cloudflare, WP Rocket, LiteSpeed, WooCommerce, Elementor, мультисайт, IPv6**

---

## Ключевые возможности

### 🛡️ Основной Firewall (Бесплатно)
- **Трёхуровневый firewall** с обновлениями WAF-правил в реальном времени
- **2 899 сигнатур User-Agent** - крупнейший чёрный список среди плагинов WordPress
- **Защита от брутфорса** с прогрессивными блокировками и эскалацией банов
- **Анти-спам** для комментариев, регистраций и контактных форм
- **Обнаружение поддельных краулеров** через FCrDNS - эффективность 95%, невозможно подделать
- **Управление LLM / AI краулерами** - разрешить или заблокировать GPTBot, ClaudeBot, PerplexityBot, Bytespider
- **Блокировка по стране, ASN, диапазону IP, User-Agent, Referer**
- **Поддержка Cloudflare** - определение реального IP и защита от обхода origin
- **Полная поддержка IPv6** - отдельные таблицы и логика для IPv4 и IPv6
- **Авто-обнаружение DDoS-защиты** - распознавание JS-челленджей DDoS-Guard, Stormwall, Qrator. Единственный WordPress плагин, работающий за агрессивной DDoS-защитой без ручного вайтлистинга

### 🔒 Безопасность входа и 2FA (Бесплатно)
- **Двухфакторная аутентификация** - стандарт TOTP (Google Authenticator, Authy, Bitwarden)
- **9 режимов CAPTCHA**:
  - **Silent Auto-Verify** -- реальные пользователи проходят автоматически, без единого клика; боты видят "Доступ запрещён"
  - **Shapes CAPTCHA** -- 60fps Canvas с движущимися геометрическими фигурами, ~в 100 раз сложнее для ИИ-взлома, чем reCAPTCHA
  - **Color CAPTCHA** -- выбор правильной цветовой комбинации
  - **Images CAPTCHA** -- визуальное распознавание изображений
  - **Digits CAPTCHA** -- числовая верификация
  - **Hold Button CAPTCHA** -- верификация удержанием кнопки
  - **Single Button CAPTCHA** -- верификация одним кликом
  - **reCAPTCHA v2** -- Google "Я не робот"
  - **reCAPTCHA v3** -- невидимая скоринговая верификация
- **Гибридная CAPTCHA** -- комбинация любой внутренней CAPTCHA с reCAPTCHA v3 для двухуровневой невидимой защиты
- **Скрытый URL входа** *(PRO)*

### 💳 Обход платёжных шлюзов (Бесплатно)
Авто-определение 25+ e-commerce платформ и 150+ платёжных провайдеров (Stripe, PayPal, WooCommerce и др.). Webhook'и и IPN-уведомления никогда не блокируются.

### 📊 Видимость и контроль (Бесплатно)
- Живой мониторинг трафика с картой атак и 54 уникальными кодами событий
- Индикатор Health Score - 42 параметра, 5 уровней безопасности
- 8 языков интерфейса - English, Deutsch, Español, Français, Polski, Русский, Українська
- Чистое удаление - ноль остаточных данных

### 🚀 PRO Тарифы

| Функция | Free | Premium | Pro | Ultimate |
|---|---|---|---|---|
| Реальная статистика посетителей | ✓ | ✓ | ✓ | ✓ |
| Режим MU-Mode | ✓ | ✓ | ✓ | ✓ |
| Защита от брутфорса | ✓ | ✓ | ✓ | ✓ |
| Обнаружение поддельных краулеров (FCrDNS) | ✓ | ✓ | ✓ | ✓ |
| Локальная блокировка ботов | ✓ | ✓ | ✓ | ✓ |
| Интеграция с Redis / Memcached | ✓ | ✓ | ✓ | ✓ |
| Режим Early Init | -- | ✓ | ✓ | ✓ |
| Облачная разведка IP | -- | ✓ | ✓ | ✓ |
| Zero-day обновления ботнетов | -- | ✓ | ✓ | ✓ |
| 5M+ сигнатур ботов | -- | ✓ | ✓ | ✓ |
| Анализ поведения | -- | ✓ | ✓ | ✓ |
| Облачных проверок / мес | -- | 25k | 100k | 250k |
| Разблокировка аддонов | -- | ✓ | ✓ | ✓ |
| Приоритетная поддержка | -- | ✓ | ✓ | ✓ |
| Экстренная поддержка (24ч) | -- | -- | -- | ✓ |
| **Цена в месяц** | **Free** | **$12** | **$50** | **$100** |
| **Цена в год** | **Free** | **$11/mo** | **$45.8/mo** | **$91.6/mo** |

При годовой оплате 1 месяц бесплатно. Лицензия на домен через Freemius.
[Сравнить тарифы →](https://botblocker.top/pricing/)

---

## Почему BotBlocker?

| | BotBlocker | Обычные плагины безопасности |
|---|---|---|
| **Точка перехвата** | До загрузки WordPress | После загрузки WordPress |
| **CPU/RAM на заблокированный запрос** | 30–100ms / 5–20MB RAM сэкономлено | Полный стек WordPress загружен |
| **Режимы CAPTCHA** | 9 (проприетарные + reCAPTCHA) | 1–2 (только reCAPTCHA) |
| **AI-устойчивая CAPTCHA** | Да -- Shapes ~в 100 раз сложнее взломать, чем reCAPTCHA (взламывается за $2-3/1 000) | Нет |
| **Ограничения бесплатной версии** | Нет - полный firewall, все CAPTCHA, полный 2FA | Урезанные функции, навязчивые экраны |
| **Приватность** | Все данные остаются на вашем сервере | Телеметрия, внешние API-вызовы |
| **Измеренные накладные расходы** | +3–15ms для верифицированных посетителей | +20–200ms |

---

## Технологический стек

- **PHP** 7.4–8.5
- **WordPress** 5.1–7.0+
- **Платформа** Linux, Windows, shared hosting
- **База данных** Ноль запросов к БД для возвращающихся посетителей - 9 предварительно сгенерированных PHP-файлов
- **Кэш** Поддержка Redis / Memcached (авто-отключение при сбое)
- **CDN / DDoS** Совместим с Cloudflare, Sucuri, StackPath, DDoS-Guard, Stormwall
- **Лицензия** GPL-2.0+

---

## Ссылки

- 🌐 [botblocker.top](https://botblocker.top/)
- 🔌 [Плагин на WordPress.org](https://wordpress.org/plugins/botblocker-security/)
- 📖 [Документация](https://botblocker.top/docs/)
- 💰 [Цены](https://botblocker.top/pricing/)
- 💬 [Сообщество](https://botblocker.top/community/)
- 📧 [Контакты](https://botblocker.top/contacts/)

---

<p align="center">
  <sub>Разработано <a href="https://globus.studio">GLOBUS.studio</a> · <a href="https://leonidov.dev">Yevhen Leonidov</a> · Andrii Lukashevych · Aleksandr Kinakh</sub>
</p>
