<div align="center">

# 🌿 কৃষিবন্ধু · Krishibondhu

### Fair markets. Direct connections. Better opportunities.

An interactive, mobile-friendly agricultural marketplace prototype connecting
Bangladeshi farmers directly with households, shops, and restaurants.

<br>

**[Open the demo](https://someoneforu.github.io/My-first-Website/)** · **[Explore the features](#-what-you-can-try)**

<br>

![HTML5](https://img.shields.io/badge/HTML5-single--file-orange?style=flat-square&logo=html5&logoColor=white)
![Responsive](https://img.shields.io/badge/design-responsive-2e704d?style=flat-square)
![Demo data](https://img.shields.io/badge/data-simulated-f2a65a?style=flat-square)
![License](https://img.shields.io/badge/status-prototype-607d68?style=flat-square)

</div>

---

## ✨ The idea

Farmers deserve more control over how they sell their crops. Krishibondhu
demonstrates a welcoming digital marketplace where farmers can explore
illustrative market prices, compare buyer offers, and sell directly—while
customers discover fresh products from local farms.

> **This is a demo, not a live commerce service.** Profiles, listings, orders,
> and market prices are fictional sample data. No payment, delivery, Firebase,
> GPS, or live market-price integrations are connected.

## 🧭 What you can try

| Demo area | Explore |
| --- | --- |
| **Marketplace** | Search and filter 24 sample crop listings, browse farmer profiles, save favorites, and add products to a demo cart. |
| **Market prices** | Compare sample prices across five markets and explore a seven-day illustrative price chart. |
| **Farmer portal** | Manage a sample farm’s listings, compare buyer offers by estimated net earnings, and review incoming orders. |
| **Orders & delivery** | Place simulated orders, move orders through their workflow, reserve stock on acceptance, and explore fictional delivery partners. |
| **Earnings calculator** | Compare estimated wholesale and direct-sale gross revenue, expenses, and net earnings. |
| **Admin & settings** | Review fictional farmer profiles, add sample price records, switch demo roles, change theme/language, or reset local data. |

### A quick look at the experience

- Forest-green branding, warm cream surfaces, rounded cards, and crop-inspired details
- Responsive layout with a collapsible mobile navigation
- English/Bangla navigation toggle and light/dark themes
- Browser-local demo persistence with a **Reset demo data** option
- Sample profiles spanning districts across Bangladesh
- Clear labeling wherever market values or transactions are simulated

## 🚀 Run it locally

No build step, package installation, or API key is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/SomeoneForU/My-first-Website.git
   cd My-first-Website
   ```

2. Open `index.html` in a browser, or start a small local server:

   ```bash
   python3 -m http.server 8000
   ```

3. Visit [http://localhost:8000](http://localhost:8000).

All application markup, styles, and demo logic live in [`index.html`](./index.html).
Demo changes are stored in your browser’s `localStorage`; use **Reset demo data**
to restore the original sample dataset.

## 🧪 Demo data at a glance

- 10 fictional farmer profiles
- 24 crop listings across grains, vegetables, fruits, pulses, and spices
- 40 simulated market-price records, including seven-day histories
- 8 fictional customer profiles and 15 sample orders
- 5 fictional delivery partners, plus sample reviews and notifications

All sample prices use BDT for illustration only. They are **not live market
prices, quotes, or forecasts**.

## 🛠 Built with

- HTML5
- CSS3 (responsive layouts, design tokens, dark mode)
- Vanilla JavaScript
- Browser `localStorage` for the isolated demo state

The prototype intentionally uses no external runtime dependencies. Production
authentication, Firestore persistence, trusted price data, payments, delivery,
weather, and messaging would require separately configured providers and
security controls.

## 🔒 Prototype limitations

This project is for exploring interface and workflow ideas. It does not provide
authentication, server-side authorization, protected admin access, payment
processing, real orders, real-time tracking, or verified market data. Do not
enter real personal, account, or payment information.

## 📄 License

No license has been specified yet. Contact the repository owner before
redistributing or reusing this project.
