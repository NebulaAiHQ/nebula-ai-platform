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
<h3>Kod gerektirmeyen eksiksiz Telegram bot & yönetim ekosistemi — çok dilli yönetim paneliyle profesyonel, her zaman açık bir botu tek komutla kur. Kodlama gerekmez.</h3>
</div>

<div align="center">

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇸🇦 العربية](README.ar.md) · **🇹🇷 Türkçe** · [🇨🇳 中文](README.zh.md) · [🇩🇪 Deutsch](README.de.md) · [🇸🇪 Svenska](README.sv.md)

</div>

---

## 🌌 Nebula AI Platform nedir?

**Nebula AI Platform**, **herkesin — sıfır programlama bilgisi olanların bile** — profesyonel, otomatik bir Telegram botu çalıştırmasını ve onu **7 dilde** güzel bir web panelinden yönetmesini sağlayan eksiksiz, kendi kendine barındırılan bir ekosistemdir.

Tek satır kod yazmazsınız. Yeni bir sunucuda **tek komut** çalıştırır, Telegram bot tokeninizi bağlarsınız ve her şey hazırdır: bot, veritabanı, yönetim paneli, ödeme sistemi, mağaza ve daha fazlası — tümü mühürlü bir Docker konteynerinde otomatik kurulur.

Bot, güvenilirlik için tasarlanmış **güçlü, güvenlik açısından sağlamlaştırılmış bir mimariyle 7/24 kesintisiz** çalışır. İster **Sanaei / Hiddify / 3x-ui VPN paneli** işletiyor olun ister sıfırdan başlayın, Nebula **otomasyon** ile bağlanır ve tam donanımlı, gelir getiren bir Telegram hizmetine dönüştürür.

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/banner-hero.svg" alt="Nebula Ecosystem" width="100%"/>
</div>

---

## 👥 Kimler için?

- 🧑‍💻 Programcı tutmadan profesyonel bot isteyen **geliştirici olmayanlar**
- 🌐 Sanaei, Hiddify veya 3x-ui panelleri işleten **VPN / proxy satıcıları**
- 🛍 Bot içi mağaza ve kripto/kart ödemesi isteyen **dijital satıcılar**
- 🏢 Bölüm bazlı izinlerle çok yöneticili erişim gereken **ajanslar ve bayiler**
- 🚀 Dakikalar içinde her zaman açık, gelir getiren bir Telegram hizmeti isteyen **herkes**

---

## ⚡ Tek Komutla Kurulum

Yeni bir **Ubuntu 22 / 24 / 26** sunucusunda çalıştırın:

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

## 🏗️ Mimari

Nebula, **tek mühürlü Docker imajı** olarak sunulur; kurulumunuz tekrarlanabilir ve kaynak kodunuz gizli kalır. Kurulum her şeyi otomatik hazırlar:

- 🐳 **Docker konteyneri** — Node.js uygulamasını otomatik yeniden başlatmayla çalıştırır
- 🗄️ **SQLite veritabanı** — güncellemelerden sağ çıkan kalıcı bir birimde
- 🔒 **Nginx + Let's Encrypt SSL** — alan adı veya IP için tek komutla HTTPS
- 🤖 **Telegram Bot motoru** (grammY) — her zaman açık, dayanıklı
- ⌨️ **`nebula` CLI** — her şeyi terminalden yönetin
- 🔑 **Ed25519 lisanslama** — asimetrik, kurcalanmaya dayanıklı

**Kesintisiz güvenilirlik** ve **kurumsal düzeyde güvenlik** için tasarlandı.

---

## ✨ Tüm Özellikler

<div align="center">
<img src="https://raw.githubusercontent.com/lifemeligve-design/nebula-panel-installer/main/platform-overview.svg" alt="All Modules" width="100%"/>
</div>

### 🖥️ Yönetim Paneli

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

### 🤖 Telegram Botu

- ✅ Gigabyte wallet system
- ✅ Missions / tasks with real channel-membership verification
- ✅ Referral codes & rewards
- ✅ Crypto checkout & withdrawals
- ✅ Required-channel gating
- ✅ In-bot license purchase flow
- ✅ Group management via /panel (anti-spam, anti-bot, locks, schedules)
- ✅ Always-on 24/7 with long-polling & auto-restart

### 🏪 Dijital Mağaza

- ✅ Add products with photo, description, stock & categories
- ✅ In-bot storefront with category filter & search
- ✅ Shopping cart (smart single-currency)
- ✅ Multi-currency — Toman, USD, EUR with correct decimal math
- ✅ Discount coupons — percentage or fixed, with usage limits & expiry
- ✅ Payments — card-to-card (receipt upload) or online gateway
- ✅ Order management — tabs (pending / approved / rejected), receipt view, delete
- ✅ Sales reports — revenue per currency, daily chart, top products
- ✅ "Storefront-only" bot mode + customizable shop text

### 🔐 Güvenlik & Altyapı

- ✅ Sealed, compiled Docker image — source stays private
- ✅ Ed25519-signed licenses — cannot be forged on customer installs
- ✅ Licenses bound to a specific bot ID (anti-sharing)
- ✅ Free Let's Encrypt SSL for a domain or a bare IP
- ✅ Freemium licensing — core sections free, Pro unlocks everything ($5 lifetime)
- ✅ Automatic, controlled version releases from the master panel
- ✅ Persistent data volume — survives every update

---

## 🛠 Yönetim Komutları

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

## 💻 Gereksinimler

- **Ubuntu 22.04 / 24.04 / 26.04** sunucusu
- **Root** erişimi
- [@BotFather](https://t.me/BotFather)'dan **bot tokeni**
- (İsteğe bağlı) HTTPS için alan adı

---

## 🆘 Destek & Topluluk

<div align="center">

Sorular, güncellemeler ve duyurular — Telegram'a katılın:

### [🚀 @NebulaAiHQ](https://t.me/NebulaAiHQ)

</div>

---

<details><summary>🔍 Anahtar kelimeler</summary>


<sub>telegram bot, kodsuz telegram bot, vpn bot, hiddify bot, sanaei bot, telegram vpn panel, kripto ödeme bot, telegram mağaza bot, telegram otomasyon</sub>

</details>

<div align="center">
<sub>⑂ Nebula AI Ekibi tarafından geliştirildi</sub><br/>
<sub>© 2026 Nebula AI Platform.</sub>
</div>
