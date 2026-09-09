<div align="center">

<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/banner.svg" alt="Nebula AI Platform" width="100%"/>

<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-8b5cf6?style=for-the-badge">
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-22·24·26-6366f1?style=for-the-badge&logo=ubuntu&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-ready-38bdf8?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="No Code" src="https://img.shields.io/badge/No--Code-✓-10b981?style=for-the-badge">
  <img alt="Price" src="https://img.shields.io/badge/Pro-$5_lifetime-a855f7?style=for-the-badge">
</p>
<p><a href="https://t.me/NebulaAiHQ"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-@NebulaAiHQ-229ED9?style=for-the-badge&logo=telegram&logoColor=white"></a></p>
<h3>Det kompletta no-code Telegram-bot- & hanteringsekosystemet — distribuera en professionell, alltid aktiv bot med flerspråkig adminpanel med ett kommando. Ingen kodning krävs.</h3>
</div>

<div align="center">

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇸🇦 العربية](README.ar.md) · [🇹🇷 Türkçe](README.tr.md) · [🇨🇳 中文](README.zh.md) · [🇩🇪 Deutsch](README.de.md) · **🇸🇪 Svenska**

</div>

---

## 🌌 Vad är Nebula AI Platform?

**Nebula AI Platform** är ett komplett, självhostat ekosystem som låter **vem som helst — även personer utan programmeringskunskap** — driva en professionell, automatiserad Telegram-bot och hantera den från en vacker webbpanel på **7 språk**.

Du skriver inte en enda rad kod. Du kör **ett kommando** på en ny server, ansluter din Telegram-bot-token, och allt är klart: boten, databasen, adminpanelen, betalsystemet, butiken och mer — allt konfigureras automatiskt i en förseglad Docker-container.

Boten körs **dygnet runt utan avbrott**, med en **kraftfull, säkerhetshärdad arkitektur**. Oavsett om du redan driver en **Sanaei / Hiddify / 3x-ui VPN-panel** eller börjar från noll, ansluter Nebula via **automation** och förvandlar den till en fullfjädrad, intäktsgenererande Telegram-tjänst.

<div align="center">
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/banner-hero.svg" alt="Nebula Ecosystem" width="100%"/>
</div>

---

## 👥 Vem är det för?

- 🧑‍💻 **Icke-utvecklare** som vill ha en professionell bot utan att anlita en programmerare
- 🌐 **VPN-/proxy-säljare** som driver Sanaei-, Hiddify- eller 3x-ui-paneler
- 🛍 **Digitala säljare** som vill ha en bot-butik med krypto- & kortbetalning
- 🏢 **Byråer & återförsäljare** som behöver fleradminåtkomst med behörigheter
- 🚀 **Alla** som vill ha en alltid aktiv, intäktsgenererande Telegram-tjänst på minuter

---

## ⚡ Installation med ett kommando

På en ny **Ubuntu 22 / 24 / 26**-server, kör:

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
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/install-architecture.svg" alt="Install & Architecture" width="100%"/>
</div>

---

## 🏗️ Arkitektur

Nebula levereras som en **enda förseglad Docker-avbild** så din uppsättning är reproducerbar och källkoden förblir privat. Installeraren konfigurerar allt automatiskt:

- 🐳 **Docker-container** — kör Node.js-appen med automatiska omstarter
- 🗄️ **SQLite-databas** — på en beständig volym som överlever uppdateringar
- 🔒 **Nginx + Let's Encrypt SSL** — valfri HTTPS för domän eller IP
- 🤖 **Telegram-bot-motor** (grammY) — alltid aktiv, motståndskraftig
- ⌨️ **`nebula` CLI** — hantera allt från terminalen
- 🔑 **Ed25519-licensiering** — asymmetrisk, manipuleringssäker

Byggd för **driftsäkerhet utan avbrott** och **säkerhet i företagsklass**.

---

## ✨ Fullständig funktionslista

<div align="center">
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/platform-overview.svg" alt="All Modules" width="100%"/>
</div>

### 🖥️ Adminpanel

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

### 🤖 Telegram-bot

- ✅ Gigabyte wallet system
- ✅ Missions / tasks with real channel-membership verification
- ✅ Referral codes & rewards
- ✅ Crypto checkout & withdrawals
- ✅ Required-channel gating
- ✅ In-bot license purchase flow
- ✅ Group management via /panel (anti-spam, anti-bot, locks, schedules)
- ✅ Always-on 24/7 with long-polling & auto-restart

### 🏪 Digital butik

- ✅ Add products with photo, description, stock & categories
- ✅ In-bot storefront with category filter & search
- ✅ Shopping cart (smart single-currency)
- ✅ Multi-currency — Toman, USD, EUR with correct decimal math
- ✅ Discount coupons — percentage or fixed, with usage limits & expiry
- ✅ Payments — card-to-card (receipt upload) or online gateway
- ✅ Order management — tabs (pending / approved / rejected), receipt view, delete
- ✅ Sales reports — revenue per currency, daily chart, top products
- ✅ "Storefront-only" bot mode + customizable shop text

### 🔐 Säkerhet & Infrastruktur

- ✅ Sealed, compiled Docker image — source stays private
- ✅ Ed25519-signed licenses — cannot be forged on customer installs
- ✅ Licenses bound to a specific bot ID (anti-sharing)
- ✅ Free Let's Encrypt SSL for a domain or a bare IP
- ✅ Freemium licensing — core sections free, Pro unlocks everything ($5 lifetime)
- ✅ Automatic, controlled version releases from the master panel
- ✅ Persistent data volume — survives every update

---

## 🛠 Hanteringskommandon

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

## 💻 Krav

- Server med **Ubuntu 22.04 / 24.04 / 26.04**
- **Root**-åtkomst
- **Bot-token** från [@BotFather](https://t.me/BotFather)
- (Valfritt) en domän för HTTPS

---

## 🆘 Support & Gemenskap

<div align="center">

Frågor, uppdateringar och meddelanden — gå med i vår Telegram:

### [🚀 @NebulaAiHQ](https://t.me/NebulaAiHQ)

</div>

---

<details><summary>🔍 Nyckelord</summary>


<sub>telegram bot, no-code telegram bot, vpn bot, hiddify bot, sanaei bot, telegram vpn panel, krypto betalningsbot, telegram butik bot, telegram automation</sub>

</details>

<div align="center">
<sub>⑂ Utvecklad av Nebula AI-teamet</sub><br/>
<sub>© 2026 Nebula AI Platform.</sub>
</div>
