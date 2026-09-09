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
<h3>The complete no-code Telegram bot & management ecosystem — deploy a professional, always-on bot with a multilingual admin panel in one command. No coding required.</h3>
</div>

<div align="center">

**🇬🇧 English** · [🇮🇷 فارسی](README.fa.md) · [🇸🇦 العربية](README.ar.md) · [🇹🇷 Türkçe](README.tr.md) · [🇨🇳 中文](README.zh.md) · [🇩🇪 Deutsch](README.de.md) · [🇸🇪 Svenska](README.sv.md)

</div>

---

## 🌌 What is Nebula AI Platform?

**Nebula AI Platform** is a complete, self-hosted ecosystem that lets **anyone — even people with zero programming knowledge** — run a professional, automated Telegram bot and manage it from a beautiful web panel available in **7 languages**.

You don't write a single line of code. You run **one command** on a fresh server, connect your Telegram bot token, and everything is ready: the bot, the database, the admin panel, the payment system, the shop, and more — all provisioned automatically inside a sealed Docker container.

The bot runs **24/7 without downtime**, backed by a **powerful, security-hardened architecture** designed for reliability. Whether you already operate a **Sanaei / Hiddify / 3x-ui VPN panel** or you're starting fresh, Nebula connects to it through **automation** and turns it into a fully-featured, monetizable Telegram service — with subscriptions, crypto payments, a digital shop, referrals, missions, anti-fraud tooling, and much more.

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/banner-hero.svg" alt="Nebula Ecosystem" width="100%"/>
</div>

---

## 👥 Who is it for?

- 🧑‍💻 **Non-developers** who want a professional Telegram bot without hiring a programmer
- 🌐 **VPN / proxy sellers** running Sanaei, Hiddify, or 3x-ui panels who want to automate sales & support
- 🛍 **Digital sellers** who want an in-bot shop with crypto & card payments
- 🏢 **Agencies & resellers** who need multi-admin access with per-section permissions
- 🚀 **Anyone** who wants an always-on, monetizable Telegram service in minutes

---

## ⚡ One-Command Install

On a fresh **Ubuntu 22 / 24 / 26** server, run:

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

## 🏗️ Architecture

Nebula ships as a **single sealed Docker image** so your setup is reproducible and your source stays private. The installer provisions everything automatically:

- 🐳 **Docker container** — runs the Node.js app (admin panel + bot) with automatic restarts
- 🗄️ **SQLite database** — users, tasks, licenses, orders, settings; stored on a **persistent volume** that survives updates
- 🔒 **Nginx + Let's Encrypt SSL** — optional one-command HTTPS for a domain or a bare IP
- 🤖 **Telegram Bot engine** (grammY) — long-polling, always-on, resilient
- ⌨️ **`nebula` CLI** — manage everything from the terminal (start, stop, update, logs, ssl, password)
- 🔑 **Ed25519 licensing** — asymmetric, tamper-proof license verification

The architecture is built for **zero-downtime reliability** and **enterprise-grade security** — no exposed source, signed licenses, sealed images, and automatic backups.

---

## ✨ Full Feature List

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/platform-overview.svg" alt="All Modules" width="100%"/>
</div>

### 🖥️ Admin Panel

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

### 🤖 Telegram Bot

- ✅ Gigabyte wallet system
- ✅ Missions / tasks with real channel-membership verification
- ✅ Referral codes & rewards
- ✅ Crypto checkout & withdrawals
- ✅ Required-channel gating
- ✅ In-bot license purchase flow
- ✅ Group management via /panel (anti-spam, anti-bot, locks, schedules)
- ✅ Always-on 24/7 with long-polling & auto-restart

### 🏪 Digital Shop

- ✅ Add products with photo, description, stock & categories
- ✅ In-bot storefront with category filter & search
- ✅ Shopping cart (smart single-currency)
- ✅ Multi-currency — Toman, USD, EUR with correct decimal math
- ✅ Discount coupons — percentage or fixed, with usage limits & expiry
- ✅ Payments — card-to-card (receipt upload) or online gateway
- ✅ Order management — tabs (pending / approved / rejected), receipt view, delete
- ✅ Sales reports — revenue per currency, daily chart, top products
- ✅ "Storefront-only" bot mode + customizable shop text

### 🔐 Security & Infrastructure

- ✅ Sealed, compiled Docker image — source stays private
- ✅ Ed25519-signed licenses — cannot be forged on customer installs
- ✅ Licenses bound to a specific bot ID (anti-sharing)
- ✅ Free Let's Encrypt SSL for a domain or a bare IP
- ✅ Freemium licensing — core sections free, Pro unlocks everything ($5 lifetime)
- ✅ Automatic, controlled version releases from the master panel
- ✅ Persistent data volume — survives every update

---

## 🛠 Management Commands

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

## 💻 Requirements

- A server running **Ubuntu 22.04 / 24.04 / 26.04**
- **Root** access (the installer handles the rest)
- A **Telegram bot token** from [@BotFather](https://t.me/BotFather) — added later from the panel
- (Optional) a domain for HTTPS — or use a bare IP

---

## 🆘 Support & Community

<div align="center">

Questions, updates, and announcements — join our Telegram:

### [🚀 @NebulaAiHQ](https://t.me/NebulaAiHQ)

</div>

---

<details><summary>🔍 Keywords</summary>


<sub>telegram bot, no-code telegram bot, vpn bot, hiddify bot, sanaei bot, 3x-ui bot, telegram vpn panel, crypto payment bot, telegram shop bot, self-hosted telegram bot, docker telegram bot, multilingual admin panel, telegram automation, sell vpn telegram, subscription bot</sub>

</details>

<div align="center">
<sub>⑂ Engineered by the Nebula AI Team</sub><br/>
<sub>© 2026 Nebula AI Platform.</sub>
</div>
