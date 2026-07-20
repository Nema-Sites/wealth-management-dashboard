# 💼 Meridian — Wealth Management Platform Demo

![HTML](https://img.shields.io/badge/HTML5-Multi--page-E34F26?logo=html5&logoColor=white&style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black&style=flat-square)
![Fintech](https://img.shields.io/badge/Domain-Fintech-0A66C2?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-success?style=flat-square)

**Meridian** is a wealth management platform demo that replaces the spreadsheets and email chains advisory firms rely on with a single system: guided client onboarding with KYC, live portfolio dashboards, and a firm-wide advisor console with compliance oversight.

🔗 **Live demo:** [wealthmanagementdemo.nemasites.com](https://wealthmanagementdemo.nemasites.com)

<!-- Add a screenshot or GIF here -->
<!-- ![Meridian Demo](./screenshots/preview.png) -->

---

## ✨ Highlights

- 📝 **Client onboarding & KYC** — a guided five-step intake wizard capturing personal details, risk profile, investment goals, documents, and final review
- 📈 **Live client dashboard** — holdings, allocation, and performance in a clean client-facing view
- 🧑‍💼 **Advisor console** — firm-wide oversight of assets under management, every client account's status, and compliance alerts from one screen
- 🔒 **Compliance-first design** — onboardings and transactions are logged, flaggable, and auditable
- 🔁 **Two-sided flow** — the demo's signature moment: complete an onboarding as a client, then open the advisor console and watch that client appear for review
- 📱 **Fully responsive** — mobile, tablet, and desktop

## 🧠 Why I Built This

Fintech is my core interest as a developer, and this demo targets a specific pain point I've seen in the wealth management space: firms running client intake, portfolio reporting, and compliance across four disconnected tools. Meridian shows what those workflows look like unified in one platform — and serves as a live, clickable proposal when pitching wealth managers and advisory firms.

## 🗺️ Demo Walkthrough

The demo is designed to be experienced from both sides:

1. **Start onboarding** → complete the five-step KYC wizard as a new client
2. **Open the client dashboard** → see holdings, allocation, and performance
3. **Switch to the advisor console** → your newly onboarded client appears with their status and any compliance flags, alongside firm-wide AUM and account metrics

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Multi-page HTML5 + vanilla JavaScript |
| State | Client-side (browser storage) — onboarded clients persist across pages |
| Styling | Custom CSS, responsive layout |
| Deployment | Self-hosted with Coolify + nginx on a Nemasites VPS |

## 📁 Project Structure

```
wealth-management-demo/
├── index.html        # Landing page — platform overview
├── onboarding.html   # Five-step KYC onboarding wizard
├── dashboard.html    # Client portfolio dashboard
├── admin.html        # Advisor console — firm-wide oversight
└── assets/           # CSS, JS, images
```

## 👤 Author

**Lufuno Nemathaga (Nema)** — Software Developer & Founder of [Nemasites](https://nemasites.com), a web and software development agency based in Pretoria, South Africa, with a focus on fintech.

- 🌐 Portfolio: [lufunonemathaga.nemasites.com](https://lufunonemathaga.nemasites.com)
- 🏢 Agency: [nemasites.com](https://nemasites.com)

---

> ⚠️ This is a demonstration project. All figures (AUM, client counts, portfolio data) are simulated, and no real financial data is processed or stored server-side.
