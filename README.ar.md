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
<h3>منظومة متكاملة لبوت تيليجرام والإدارة بدون برمجة — انشر بوتًا احترافيًا يعمل دائمًا مع لوحة إدارة متعددة اللغات بأمر واحد. لا حاجة للبرمجة.</h3>
</div>

<div align="center">

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · **🇸🇦 العربية** · [🇹🇷 Türkçe](README.tr.md) · [🇨🇳 中文](README.zh.md) · [🇩🇪 Deutsch](README.de.md) · [🇸🇪 Svenska](README.sv.md)

</div>

---

## 🌌 ما هي Nebula AI Platform؟

**Nebula AI Platform** منظومة متكاملة ومُستضافة ذاتيًا تتيح **لأي شخص — حتى بدون أي معرفة بالبرمجة** — تشغيل بوت تيليجرام احترافي ومؤتمت وإدارته من لوحة ويب جميلة متوفرة بـ**7 لغات**.

لا تكتب سطرًا واحدًا من الكود. تُنفّذ **أمرًا واحدًا** على خادم جديد، تربط توكن بوت تيليجرام، وكل شيء جاهز: البوت وقاعدة البيانات ولوحة الإدارة ونظام الدفع والمتجر والمزيد — كلها تُهيَّأ تلقائيًا داخل حاوية Docker مغلقة.

يعمل البوت **24/7 دون انقطاع**، مدعومًا بـ**بنية قوية ومُحصّنة أمنيًا**. سواء كنت تدير بالفعل لوحة **VPN من Sanaei / Hiddify / 3x-ui** أو تبدأ من الصفر، تتصل Nebula بها عبر **الأتمتة** وتحوّلها إلى خدمة تيليجرام كاملة ومُدرّة للدخل.

<div align="center">
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/banner-hero.svg" alt="Nebula Ecosystem" width="100%"/>
</div>

---

## 👥 لمن هي؟

- 🧑‍💻 **غير المبرمجين** الذين يريدون بوت تيليجرام احترافيًا دون توظيف مبرمج
- 🌐 **بائعو VPN / بروكسي** الذين يشغّلون لوحات Sanaei أو Hiddify أو 3x-ui
- 🛍 **البائعون الرقميون** الذين يريدون متجرًا داخل البوت بدفع بالعملات الرقمية والبطاقات
- 🏢 **الوكالات والموزعون** الذين يحتاجون وصولًا متعدد المدراء بصلاحيات لكل قسم
- 🚀 **أي شخص** يريد خدمة تيليجرام دائمة العمل ومُدرّة للدخل خلال دقائق

---

## ⚡ التثبيت بأمر واحد

على خادم **Ubuntu 22 / 24 / 26** جديد، شغّل:

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

## 🏗️ البنية

تُنشر Nebula كـ**صورة Docker مغلقة واحدة** لتكون إعداداتك قابلة للتكرار ويبقى الكود المصدري خاصًا. يُهيّئ المُثبّت كل شيء تلقائيًا:

- 🐳 **حاوية Docker** — تشغّل تطبيق Node.js مع إعادة تشغيل تلقائي
- 🗄️ **قاعدة بيانات SQLite** — على وحدة تخزين دائمة تبقى بعد التحديثات
- 🔒 **Nginx + شهادة Let's Encrypt SSL** — HTTPS اختياري بأمر واحد
- 🤖 **محرك بوت تيليجرام** (grammY) — دائم العمل وصامد
- ⌨️ **أداة `nebula`** — إدارة كل شيء من الطرفية
- 🔑 **ترخيص Ed25519** — تحقق غير متماثل مقاوم للتلاعب

بُنيت لـ**موثوقية دون انقطاع** و**أمان بمستوى المؤسسات**.

---

## ✨ قائمة الميزات الكاملة

<div align="center">
<img src="https://raw.githubusercontent.com/NebulaAiHQ/nebula-ai-platform/main/platform-overview.svg" alt="All Modules" width="100%"/>
</div>

### 🖥️ لوحة الإدارة

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

### 🤖 بوت تيليجرام

- ✅ Gigabyte wallet system
- ✅ Missions / tasks with real channel-membership verification
- ✅ Referral codes & rewards
- ✅ Crypto checkout & withdrawals
- ✅ Required-channel gating
- ✅ In-bot license purchase flow
- ✅ Group management via /panel (anti-spam, anti-bot, locks, schedules)
- ✅ Always-on 24/7 with long-polling & auto-restart

### 🏪 المتجر الرقمي

- ✅ Add products with photo, description, stock & categories
- ✅ In-bot storefront with category filter & search
- ✅ Shopping cart (smart single-currency)
- ✅ Multi-currency — Toman, USD, EUR with correct decimal math
- ✅ Discount coupons — percentage or fixed, with usage limits & expiry
- ✅ Payments — card-to-card (receipt upload) or online gateway
- ✅ Order management — tabs (pending / approved / rejected), receipt view, delete
- ✅ Sales reports — revenue per currency, daily chart, top products
- ✅ "Storefront-only" bot mode + customizable shop text

### 🔐 الأمان والبنية

- ✅ Sealed, compiled Docker image — source stays private
- ✅ Ed25519-signed licenses — cannot be forged on customer installs
- ✅ Licenses bound to a specific bot ID (anti-sharing)
- ✅ Free Let's Encrypt SSL for a domain or a bare IP
- ✅ Freemium licensing — core sections free, Pro unlocks everything ($5 lifetime)
- ✅ Automatic, controlled version releases from the master panel
- ✅ Persistent data volume — survives every update

---

## 🛠 أوامر الإدارة

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

## 💻 المتطلبات

- خادم بـ**Ubuntu 22.04 / 24.04 / 26.04**
- صلاحية **root**
- **توكن بوت** من [@BotFather](https://t.me/BotFather)
- (اختياري) نطاق لـHTTPS

---

## 🆘 الدعم والمجتمع

<div align="center">

الأسئلة والتحديثات والإعلانات — انضم إلى تيليجرام:

### [🚀 @NebulaAiHQ](https://t.me/NebulaAiHQ)

</div>

---

<details><summary>🔍 كلمات مفتاحية</summary>


<sub>بوت تيليجرام, بوت بدون برمجة, بوت VPN, بوت Hiddify, بوت Sanaei, لوحة VPN تيليجرام, بوت دفع كريبتو, بوت متجر تيليجرام, أتمتة تيليجرام</sub>

</details>

<div align="center">
<sub>⑂ من تطوير فريق Nebula AI</sub><br/>
<sub>© 2026 Nebula AI Platform.</sub>
</div>
