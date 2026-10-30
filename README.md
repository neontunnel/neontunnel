# Neon Tunnel

**Один клиент вместо зоопарка.** Всё, что вы держали в разных приложениях, в одном, с общими правилами маршрутизации. Для Windows, Android, Linux (бета) и macOS (бета).

Сайт: **[neontunnel.pro](https://neontunnel.pro/ru/)** · [English](#english)

## Скачать

Последняя версия: **[Releases → Latest](https://github.com/neontunnel/neontunnel/releases/latest)**. Здесь те же сборки, что на сайте, файл в файл: у каждого файла в описании версии указан SHA-256, сверьте его перед установкой. Это зеркало на случай, если сайт не открывается.

| Система | Файл |
|---|---|
| Windows, x64 | `neon_tunnel_setup_<версия>.exe` |
| Android, arm64 | `neon_tunnel_<версия>.apk` |
| Linux x64, бета (Debian, Ubuntu) | `neon-tunnel_<версия>_amd64.deb` |
| macOS, бета (Intel и Apple Silicon) | `NeonTunnel-<версия>-macos.dmg` |

## Что умеет

- **Все ваши серверы в одном списке.** VLESS с REALITY и XHTTP, Hysteria2, TUIC, AmneziaWG 1.0–3.1 со всеми параметрами, WireGuard, Trojan, Shadowsocks, VMess. Одни правила для любого сервера.
- **Вставьте как есть.** Ссылка на подписку, отдельная ссылка, файл `.conf`, ключ `vpn://` или QR-код: клиент сам поймёт, что это. Подписки в виде списка ссылок, Xray JSON и sing-box JSON, с остатком трафика и сроком.
- **Работает с тем, что у вас уже стоит.** 3x-ui, Remnawave (лимит устройств только с вашего согласия), официальный сервер Hysteria2, AmneziaWG; ключи из приложения Amnezia импортируются как есть.
- **Российские сервисы напрямую, остальное через ваш сервер.** Готовые наборы правил в одно касание, свои правила по доменам, geosite/geoip и IP-сетям, блокировка рекламы. На Android можно выбрать приложения для VPN.
- **Аварийное отключение (Kill Switch).** Если туннель оборвался, трафик не уйдёт мимо него. Windows и Linux; на Android работает системный «Постоянный VPN».
- **Раздача в домашнюю сеть.** PlayStation, Switch и телевизор ходят через тот же туннель и по тем же правилам.

## Исходный код и безопасность

Исходный код закрыт. Сборки для Windows подписаны, у каждой сборки опубликован SHA-256. Как приложение и сайт обращаются с данными: [neontunnel.pro/ru/privacy/](https://neontunnel.pro/ru/privacy/).

Ошибки и пожелания: форма на [сайте](https://neontunnel.pro/ru/#feedback) или [Issues](https://github.com/neontunnel/neontunnel/issues).

---

## English

**One client instead of a zoo.** Everything you kept in separate apps, in one, with shared routing rules. For Windows, Android, Linux (beta) and macOS (beta).

Website: **[neontunnel.pro](https://neontunnel.pro/)**

**Download:** [Releases → Latest](https://github.com/neontunnel/neontunnel/releases/latest). These are the website's builds, byte for byte; each release lists the SHA-256 of every file. This is a mirror for when the website cannot be reached.

- **All your servers in one list:** VLESS with REALITY and XHTTP, Hysteria2, TUIC, AmneziaWG 1.0–3.1, WireGuard, Trojan, Shadowsocks, VMess; one set of rules for any server.
- **Paste it as it is:** a subscription link, a single link, a `.conf` file, a `vpn://` key or a QR code.
- **Works with what you already run:** 3x-ui, Remnawave, the official Hysteria2 server, AmneziaWG.
- **Routing:** ready-made rule sets, your own rules by domain, geosite/geoip and IP ranges, ad blocking; per-app VPN on Android.
- **Kill switch** on Windows and Linux; **sharing to your home network** for consoles and TVs.

The source code is closed. Bugs and ideas: the form on the [website](https://neontunnel.pro/#feedback) or [Issues](https://github.com/neontunnel/neontunnel/issues).
