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
<h3>完整的零代码 Telegram 机器人与管理生态系统——一条命令即可部署专业的、全天候运行的机器人和多语言管理面板。无需编程。</h3>
</div>

<div align="center">

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇸🇦 العربية](README.ar.md) · [🇹🇷 Türkçe](README.tr.md) · **🇨🇳 中文** · [🇩🇪 Deutsch](README.de.md) · [🇸🇪 Svenska](README.sv.md)

</div>

---

## 🌌 什么是 Nebula AI Platform？

**Nebula AI Platform** 是一个完整的自托管生态系统，让**任何人——即使没有任何编程知识**——都能运行专业的自动化 Telegram 机器人，并通过提供**7 种语言**的精美网页面板进行管理。

你不用写一行代码。在全新服务器上运行**一条命令**，连接你的 Telegram 机器人令牌，一切就绪：机器人、数据库、管理面板、支付系统、商店等等——全部在密封的 Docker 容器中自动配置。

机器人**全天候无中断运行**，由专为可靠性设计的**强大、安全加固的架构**支撑。无论你已经运营 **Sanaei / Hiddify / 3x-ui VPN 面板**，还是从零开始，Nebula 都能通过**自动化**连接并将其转变为功能齐全、可盈利的 Telegram 服务。

<div align="center">
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/banner-hero.svg" alt="Nebula Ecosystem" width="100%"/>
</div>

---

## 👥 适合谁？

- 🧑‍💻 想要专业机器人又不想雇程序员的**非开发者**
- 🌐 运营 Sanaei、Hiddify 或 3x-ui 面板的 **VPN/代理销售商**
- 🛍 想要带加密货币和银行卡支付的机器人内商店的**数字卖家**
- 🏢 需要按板块权限的多管理员访问的**代理商与分销商**
- 🚀 想在几分钟内拥有全天候盈利 Telegram 服务的**任何人**

---

## ⚡ 一条命令安装

在全新的 **Ubuntu 22 / 24 / 26** 服务器上运行：

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

## 🏗️ 架构

Nebula 以**单个密封的 Docker 镜像**发布，让你的配置可复现，源码保持私有。安装程序自动配置一切：

- 🐳 **Docker 容器**——运行 Node.js 应用并自动重启
- 🗄️ **SQLite 数据库**——存储在更新后仍保留的持久卷上
- 🔒 **Nginx + Let's Encrypt SSL**——为域名或 IP 一键 HTTPS
- 🤖 **Telegram 机器人引擎**（grammY）——全天候、有韧性
- ⌨️ **`nebula` 命令行**——从终端管理一切
- 🔑 **Ed25519 授权**——非对称、防篡改验证

专为**零停机可靠性**和**企业级安全**打造。

---

## ✨ 完整功能列表

<div align="center">
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/platform-overview.svg" alt="All Modules" width="100%"/>
</div>

### 🖥️ 管理面板

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

### 🤖 Telegram 机器人

- ✅ Gigabyte wallet system
- ✅ Missions / tasks with real channel-membership verification
- ✅ Referral codes & rewards
- ✅ Crypto checkout & withdrawals
- ✅ Required-channel gating
- ✅ In-bot license purchase flow
- ✅ Group management via /panel (anti-spam, anti-bot, locks, schedules)
- ✅ Always-on 24/7 with long-polling & auto-restart

### 🏪 数字商店

- ✅ Add products with photo, description, stock & categories
- ✅ In-bot storefront with category filter & search
- ✅ Shopping cart (smart single-currency)
- ✅ Multi-currency — Toman, USD, EUR with correct decimal math
- ✅ Discount coupons — percentage or fixed, with usage limits & expiry
- ✅ Payments — card-to-card (receipt upload) or online gateway
- ✅ Order management — tabs (pending / approved / rejected), receipt view, delete
- ✅ Sales reports — revenue per currency, daily chart, top products
- ✅ "Storefront-only" bot mode + customizable shop text

### 🔐 安全与基础设施

- ✅ Sealed, compiled Docker image — source stays private
- ✅ Ed25519-signed licenses — cannot be forged on customer installs
- ✅ Licenses bound to a specific bot ID (anti-sharing)
- ✅ Free Let's Encrypt SSL for a domain or a bare IP
- ✅ Freemium licensing — core sections free, Pro unlocks everything ($5 lifetime)
- ✅ Automatic, controlled version releases from the master panel
- ✅ Persistent data volume — survives every update

---

## 🛠 管理命令

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

## 💻 系统要求

- 运行 **Ubuntu 22.04 / 24.04 / 26.04** 的服务器
- **Root** 权限
- 来自 [@BotFather](https://t.me/BotFather) 的**机器人令牌**
- （可选）用于 HTTPS 的域名

---

## 🆘 支持与社区

<div align="center">

问题、更新和公告——加入我们的 Telegram：

### [🚀 @NebulaAiHQ](https://t.me/NebulaAiHQ)

</div>

---

<details><summary>🔍 关键词</summary>


<sub>telegram 机器人, 无代码机器人, vpn 机器人, hiddify 机器人, sanaei 机器人, telegram vpn 面板, 加密支付机器人, telegram 商店机器人, telegram 自动化</sub>

</details>

<div align="center">
<sub>⑂ 由 Nebula AI 团队开发</sub><br/>
<sub>© 2026 Nebula AI Platform.</sub>
</div>
