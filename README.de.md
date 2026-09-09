<div align="center">

<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/banner.svg" alt="Nebula AI Platform" width="100%"/>

<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-8b5cf6?style=for-the-badge">
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-22·24·26-6366f1?style=for-the-badge&logo=ubuntu&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-ready-38bdf8?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="No Code" src="https://img.shields.io/badge/No--Code-✓-10b981?style=for-the-badge">
  <img alt="Price" src="https://img.shields.io/badge/Pro-$5_lifetime-a855f7?style=for-the-badge">
</p>
<p><a href="https://t.me/NebulaAiHQ"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-@NebulaAiHQ-229ED9?style=for-the-badge&logo=telegram&logoColor=white"></a></p>
<h3>Das komplette No-Code-Telegram-Bot- & Verwaltungs-Ökosystem — ein professioneller, immer aktiver Bot mit mehrsprachigem Admin-Panel in einem Befehl. Keine Programmierung nötig.</h3>
</div>

<div align="center">

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇸🇦 العربية](README.ar.md) · [🇹🇷 Türkçe](README.tr.md) · [🇨🇳 中文](README.zh.md) · **🇩🇪 Deutsch** · [🇸🇪 Svenska](README.sv.md)

</div>

---

## 🌌 Was ist die Nebula AI Platform?

**Nebula AI Platform** ist ein komplettes, selbst gehostetes Ökosystem, mit dem **jeder — sogar Menschen ohne Programmierkenntnisse** — einen professionellen, automatisierten Telegram-Bot betreiben und ihn über ein schönes Web-Panel in **7 Sprachen** verwalten kann.

Du schreibst keine einzige Zeile Code. Du führst **einen Befehl** auf einem frischen Server aus, verbindest deinen Telegram-Bot-Token, und alles ist bereit: Bot, Datenbank, Admin-Panel, Zahlungssystem, Shop und mehr — alles automatisch in einem versiegelten Docker-Container eingerichtet.

Der Bot läuft **rund um die Uhr ohne Ausfälle**, gestützt auf eine **leistungsstarke, sicherheitsgehärtete Architektur**. Egal ob du bereits ein **Sanaei / Hiddify / 3x-ui VPN-Panel** betreibst oder neu anfängst — Nebula verbindet sich per **Automatisierung** und macht daraus einen voll ausgestatteten, monetarisierbaren Telegram-Dienst.

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/banner-hero.svg" alt="Nebula Ecosystem" width="100%"/>
</div>

---

## 👥 Für wen ist es?

- 🧑‍💻 **Nicht-Entwickler**, die einen professionellen Bot ohne Programmierer wollen
- 🌐 **VPN-/Proxy-Verkäufer** mit Sanaei-, Hiddify- oder 3x-ui-Panels
- 🛍 **Digitale Verkäufer**, die einen In-Bot-Shop mit Krypto- & Kartenzahlung wollen
- 🏢 **Agenturen & Reseller**, die Multi-Admin-Zugriff mit Bereichsrechten brauchen
- 🚀 **Jeder**, der in Minuten einen dauerhaft aktiven, monetarisierbaren Telegram-Dienst will

---

## ⚡ Installation mit einem Befehl

Führe auf einem frischen **Ubuntu 22 / 24 / 26** Server aus:

```bash
bash <(curl -Ls https://nebulapanel.cloud/install)
```

```
   ███╗   ██╗███████╗██████╗ ██╗   ██╗██╗      █████╗
   ████╗  ██║██╔════╝██╔══██╗██║   ██║██║     ██╔══██╗
   ██╔██╗ ██║█████╗  ██████╔╝██║   ██║██║     ███████║
   ██║╚██╗██║██╔══╝  ██╔══██╗██║   ██║██║     ██╔══██║
   ██║ ╚████║███████╗██████╔╝╚██████╔╝███████╗██║  ██║
   ╚═╝  ╚═══╝╚══════╝╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝
        N E B U L A   A I   P L A T F O R M
```

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/install-architecture.svg" alt="Install & Architecture" width="100%"/>
</div>

---

## 🏗️ Architektur

Nebula wird als **einzelnes versiegeltes Docker-Image** ausgeliefert, sodass dein Setup reproduzierbar bleibt und der Quellcode privat. Der Installer richtet alles automatisch ein:

- 🐳 **Docker-Container** — führt die Node.js-App mit automatischen Neustarts aus
- 🗄️ **SQLite-Datenbank** — auf einem persistenten Volume, das Updates übersteht
- 🔒 **Nginx + Let's Encrypt SSL** — optionales HTTPS für Domain oder IP per Befehl
- 🤖 **Telegram-Bot-Engine** (grammY) — immer aktiv, widerstandsfähig
- ⌨️ **`nebula`-CLI** — alles vom Terminal verwalten
- 🔑 **Ed25519-Lizenzierung** — asymmetrische, manipulationssichere Prüfung

Gebaut für **ausfallfreie Zuverlässigkeit** und **Sicherheit auf Unternehmensniveau**.

---

## ✨ Vollständige Funktionsliste

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/platform-overview.svg" alt="All Modules" width="100%"/>
</div>

### 🖥️ Admin-Panel

- ✅ Modern, responsive dashboard with live server stats (RAM / CPU / disk)
- ✅ 7-language UI (Persian · English · Arabic · Turkish · Chinese · German · Swedish) with full RTL
- ✅ Users — balances, history, profiles, avatars
- ✅ Missions & rewards — configurable gigabyte rewards with real verification
- ✅ Servers & VPN panels — Sanaei / Hiddify / 3x-ui connection & config management
- ✅ Subscriptions — manage user plans & expiry
- ✅ Follow-guard — reclaim rewards / cut subs when users leave a channel
- ✅ Submissions — screenshot anti-fraud approvals
- ✅ Broadcasts — message all users with live progress
- ✅ Emergency notifier — reach users through any bot token
- ✅ Anti-bot — blocks promo-bot button spam (even channel-posted ads)
- ✅ Agents — limited sub-admins with per-section permissions
- ✅ Referrals — invite tracking, leaderboards, bonus tiers
- ✅ Transactions & transfers — full financial ledger
- ✅ Backups — scheduled, with restore & Telegram-channel delivery
- ✅ One-click auto-update with a live progress bar

### 🤖 Telegram-Bot

- ✅ Gigabyte wallet system
- ✅ Missions / tasks with real channel-membership verification
- ✅ Referral codes & rewards
- ✅ Crypto checkout & withdrawals
- ✅ Required-channel gating
- ✅ In-bot license purchase flow
- ✅ Group management via /panel (anti-spam, anti-bot, locks, schedules)
- ✅ Always-on 24/7 with long-polling & auto-restart

### 🏪 Digitaler Shop

- ✅ Add products with photo, description, stock & categories
- ✅ In-bot storefront with category filter & search
- ✅ Shopping cart (smart single-currency)
- ✅ Multi-currency — Toman, USD, EUR with correct decimal math
- ✅ Discount coupons — percentage or fixed, with usage limits & expiry
- ✅ Payments — card-to-card (receipt upload) or online gateway
- ✅ Order management — tabs (pending / approved / rejected), receipt view, delete
- ✅ Sales reports — revenue per currency, daily chart, top products
- ✅ "Storefront-only" bot mode + customizable shop text

### 🔐 Sicherheit & Infrastruktur

- ✅ Sealed, compiled Docker image — source stays private
- ✅ Ed25519-signed licenses — cannot be forged on customer installs
- ✅ Licenses bound to a specific bot ID (anti-sharing)
- ✅ Free Let's Encrypt SSL for a domain or a bare IP
- ✅ Freemium licensing — core sections free, Pro unlocks everything ($5 lifetime)
- ✅ Automatic, controlled version releases from the master panel
- ✅ Persistent data volume — survives every update

---

## 🛠 Verwaltungsbefehle

| Command | What it does |
|---|---|
| `nebula` | Open the graphical management menu |
| `nebula start` / `stop` / `restart` | Start / stop / restart the platform |
| `nebula status` | Service status, version, panel URL (+ HTTPS) |
| `nebula logs` | Follow live logs |
| `nebula update` | Update to the newest version (data kept) |
| `nebula ssl <domain>` | Free HTTPS for a domain |
| `nebula ssl auto` | Free HTTPS on the server IP (no domain) |
| `nebula password` | Show the panel password |
| `nebula uninstall` | Remove everything |

---

## 💻 Voraussetzungen

- Server mit **Ubuntu 22.04 / 24.04 / 26.04**
- **Root**-Zugriff
- **Bot-Token** von [@BotFather](https://t.me/BotFather)
- (Optional) eine Domain für HTTPS

---

## 🆘 Support & Community

<div align="center">

Fragen, Updates und Ankündigungen — tritt unserem Telegram bei:

### [🚀 @NebulaAiHQ](https://t.me/NebulaAiHQ)

</div>

---

<details><summary>🔍 Schlüsselwörter</summary>


<sub>telegram bot, no-code telegram bot, vpn bot, hiddify bot, sanaei bot, telegram vpn panel, krypto zahlungsbot, telegram shop bot, telegram automatisierung</sub>

</details>

<div align="center">
<sub>⑂ Entwickelt vom Nebula AI Team</sub><br/>
<sub>© 2026 Nebula AI Platform.</sub>
</div>
