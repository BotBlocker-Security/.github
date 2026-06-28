<p align="center">
  <img src="https://ps.w.org/botblocker-security/assets/banner-1544x500.png?rev=3405280" alt="BotBlocker Security">
</p>

<p align="center">
  <a href="./README.md">English</a> ·
  <a href="./README_de.md">Deutsch</a> ·
  <a href="./README_es.md">Español</a> ·
  <a href="./README_fr.md">Français</a> ·
  <b>Polski</b> ·
  <a href="./README_pt.md">Português</a> ·
  <a href="./README_ru.md">Русский</a> ·
  <a href="./README_uk.md">Українська</a> ·
  <a href="./README_ar.md">العربية</a> ·
  <a href="./README_zh.md">中文</a> ·
  <a href="./README_ja.md">日本語</a>
</p>

<h1 align="center">BotBlocker Security</h1>

<p align="center">
  <strong>WordPress Firewall i Ochrona przed Botami</strong><br>
  Zatrzymuje boty, brute force, spam i fałszywe crawlery - zanim dotrą do WordPress.
</p>

<p align="center">
  <a href="https://botblocker.top">Strona</a> ·
  <a href="https://wordpress.org/plugins/botblocker-security/">WordPress.org</a> ·
  <a href="https://botblocker.top/docs/">Dokumentacja</a> ·
  <a href="https://botblocker.top/pricing/">Cennik</a> ·
  <a href="https://botblocker.top/community/">Społeczność</a>
</p>

---

## Czym jest BotBlocker?

**BotBlocker Security blokuje 99% zautomatyzowanych ataków, zanim WordPress w ogóle się załaduje.** Zero obciążenia, zero spowolnień, zero miesięcznych opłat za podstawową ochronę. Konfiguracja w 60 sekund.

Trzy warstwy przechwytywania zatrzymują złośliwy ruch na poziomie `wp-config.php` (przed WordPress), w fazie MU-plugin i w głównej tarczy - oszczędzając 30–100ms i 5–20MB RAM na każde zablokowane żądanie. Konkurencja reaguje po uruchomieniu WordPress; BotBlocker zatrzymuje zagrożenia u drzwi.

**3 000+ aktywnych instalacji · 8 języków · Zgodność z RODO / CCPA · Współpracuje z Cloudflare, WP Rocket, LiteSpeed, WooCommerce, Elementor, multisite, IPv6**

---

## Kluczowe Funkcje

### 🛡️ Główny Firewall (Darmowy)
- **Trójwarstwowy firewall** z aktualizacjami reguł WAF w czasie rzeczywistym
- **2 899 sygnatur User-Agent** - największa czarna lista wśród wtyczek WordPress
- **Ochrona przed brute force** z progresywnymi blokadami i eskalacją banów
- **Anti-spam** dla komentarzy, rejestracji i formularzy kontaktowych
- **Wykrywanie fałszywych crawlerów** przez FCrDNS - 95% skuteczności, niemożliwe do podrobienia
- **Zarządzanie crawlerami LLM / AI** - zezwalaj lub blokuj GPTBot, ClaudeBot, PerplexityBot, Bytespider
- **Blokowanie według kraju, ASN, zakresu IP, User-Agent, Referer**
- **Obsługa Cloudflare** - rozpoznawanie prawdziwego IP i ochrona przed obejściem origin
- **Pełne wsparcie IPv6** - osobne tabele i logika dla IPv4 i IPv6
- **Automatyczne wykrywanie DDoS** - rozpoznawanie JS-challenge dla DDoS-Guard, Stormwall, Qrator. Jedyna wtyczka WordPress działająca za agresywną ochroną DDoS bez ręcznego whitelistingu

### 🔒 Bezpieczeństwo Logowania i 2FA (Darmowe)
- **Uwierzytelnianie Dwuskładnikowe** - standard TOTP (Google Authenticator, Authy, Bitwarden)
- **9 trybów CAPTCHA**:
  - **Silent Auto-Verify** -- prawdziwi użytkownicy przechodzą automatycznie bez klikania, boty widzą "Dostęp zabroniony"
  - **Shapes CAPTCHA** -- Canvas 60fps z ruchomymi figurami geometrycznymi, ~100x trudniejsze do złamania przez AI niż reCAPTCHA
  - **Color CAPTCHA** -- wybierz właściwą kombinację kolorów
  - **Images CAPTCHA** -- wyzwanie rozpoznawania wizualnego
  - **Digits CAPTCHA** -- weryfikacja numeryczna
  - **Hold Button CAPTCHA** -- weryfikacja przez przytrzymanie przycisku
  - **Single Button CAPTCHA** -- weryfikacja jednym kliknięciem
  - **reCAPTCHA v2** -- Google "Nie jestem robotem"
  - **reCAPTCHA v3** -- niewidoczna weryfikacja oparta na scoringu
- **Hybrydowe CAPTCHA** -- połączenie dowolnego wewnętrznego CAPTCHA z reCAPTCHA v3 dla dwuwarstwowej niewidocznej obrony
- **Ukryty URL logowania** *(PRO)*

### 💳 Obejście Bramek Płatności (Darmowe)
Automatyczne wykrywanie 25+ platform e-commerce i 150+ dostawców płatności (Stripe, PayPal, WooCommerce itp.). Webhooki i powiadomienia IPN nigdy nie są blokowane.

### 📊 Widoczność i Kontrola (Darmowe)
- Monitor ruchu na żywo z mapą ataków i 54 unikalnymi kodami zdarzeń
- Wskaźnik Health Score - 42 parametry, 5 poziomów bezpieczeństwa
- 8 języków interfejsu - English, Deutsch, Español, Français, Polski, Русский, Українська
- Czysta dezinstalacja - zero pozostałych danych

### 🚀 Plany PRO

| Funkcja | Free | Premium | Pro | Ultimate |
|---|---|---|---|---|
| Statystyki odwiedzających w czasie rzeczywistym | ✓ | ✓ | ✓ | ✓ |
| Tryb MU-Mode | ✓ | ✓ | ✓ | ✓ |
| Ochrona przed brute force | ✓ | ✓ | ✓ | ✓ |
| Wykrywanie fałszywych crawlerów (FCrDNS) | ✓ | ✓ | ✓ | ✓ |
| Lokalne blokowanie botów | ✓ | ✓ | ✓ | ✓ |
| Integracja z Redis / Memcached | ✓ | ✓ | ✓ | ✓ |
| Tryb Early Init | -- | ✓ | ✓ | ✓ |
| Wywiad IP w chmurze | -- | ✓ | ✓ | ✓ |
| Aktualizacje botnetów zero-day | -- | ✓ | ✓ | ✓ |
| 5M+ sygnatur botów | -- | ✓ | ✓ | ✓ |
| Silnik analizy behawioralnej | -- | ✓ | ✓ | ✓ |
| Sprawdzeń cloud / mies. | -- | 25k | 100k | 250k |
| Odblokowanie Addonów | -- | ✓ | ✓ | ✓ |
| Priorytetowe wsparcie | -- | ✓ | ✓ | ✓ |
| Wsparcie alarmowe (24h) | -- | -- | -- | ✓ |
| **Cena miesięczna** | **Free** | **$12** | **$50** | **$100** |
| **Cena roczna** | **Free** | **$11/mo** | **$45.8/mo** | **$91.6/mo** |

Rozliczenie roczne obejmuje 1 miesiąc za darmo. Licencja na domenę przez Freemius.
[Porównaj plany →](https://botblocker.top/pricing/)

---

## Dlaczego BotBlocker?

| | BotBlocker | Typowe wtyczki bezpieczeństwa |
|---|---|---|
| **Punkt przechwytywania** | Przed załadowaniem WordPress | Po uruchomieniu WordPress |
| **CPU/RAM na zablokowane żądanie** | 30–100ms / 5–20MB RAM zaoszczędzone | Pełny stos WordPress załadowany |
| **Tryby CAPTCHA** | 9 (własne + reCAPTCHA) | 1–2 (tylko reCAPTCHA) |
| **CAPTCHA odporne na AI** | Tak -- Shapes ~100x trudniejsze do złamania niż reCAPTCHA (łamliwe za $2-3/1 000) | Nie |
| **Ograniczenia darmowej wersji** | Brak - pełny firewall, wszystkie CAPTCHA, pełny 2FA | Okrojone funkcje, natrętne ekrany |
| **Prywatność** | Wszystkie dane pozostają na Twoim serwerze | Telemetria, zewnętrzne wywołania API |
| **Zmierzone obciążenie** | +3–15ms dla zweryfikowanych odwiedzających | +20–200ms |

---

## Stos Technologiczny

- **PHP** 7.4–8.5
- **WordPress** 5.1–7.0+
- **Platforma** Linux, Windows, hosting współdzielony
- **Baza danych** Zero zapytań DB dla powracających odwiedzających - 9 wstępnie wygenerowanych plików PHP runtime
- **Cache** Obsługa Redis / Memcached (automatyczne wyłączenie przy awarii)
- **CDN / DDoS** Kompatybilny z Cloudflare, Sucuri, StackPath, DDoS-Guard, Stormwall
- **Licencja** GPL-2.0+

---

## Linki

- 🌐 [botblocker.top](https://botblocker.top/)
- 🔌 [Wtyczka na WordPress.org](https://wordpress.org/plugins/botblocker-security/)
- 📖 [Dokumentacja](https://botblocker.top/docs/)
- 💰 [Cennik](https://botblocker.top/pricing/)
- 💬 [Społeczność](https://botblocker.top/community/)
- 📧 [Kontakt](https://botblocker.top/contacts/)

---

<p align="center">
  <sub>Stworzone przez <a href="https://globus.studio">GLOBUS.studio</a> · <a href="https://leonidov.dev">Yevhen Leonidov</a> · Andrii Lukashevych · Aleksandr Kinakh</sub>
</p>
