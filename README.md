# Aureum — Premium Vietcombank Digibank Clone & Luxury Mobile Banking UI

<p align="center">
  <img src="screenshots/09_feature_graphic.png" alt="Aureum - Premium Vietcombank Digibank Clone UI" width="100%" />
</p>

<p align="center">
  A high-fidelity luxury mobile banking UI case study and clone of <strong>Vietcombank Digibank (VCB)</strong> built with Flutter.<br/>
  Featuring 107 screens, full glassmorphism dark theme, and complete Vietnamese-first UX flows.
</p>

<p align="center">
  <a href="#-try-the-app-beta">Try the App Beta</a> ·
  <a href="#-screenshots">Screenshots</a> ·
  <a href="#-feature-overview">Features</a> ·
  <a href="#-disclaimer">Disclaimer</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Screens-107-8B5E3C" alt="107 screens" />
  <img src="https://img.shields.io/badge/Vietcombank-Study-00A859?logo=googleplay&logoColor=white" alt="Vietcombank Study" />
  <img src="https://img.shields.io/badge/Data-Mock_Demo-D4AF37" alt="Mock demo" />
  <img src="https://img.shields.io/badge/Platform-Android_%7C_iOS-green" alt="Android iOS" />
</p>

---

## 🏛️ About & Inspiration

**Aureum** is a production-grade **UI/UX portfolio case study** of a premium mobile banking application. It started as a comprehensive design study and functional clone of **Vietcombank Digibank** (Vietnam's leading digital banking app) and was reimagined as an independent luxury brand — **Aureum** (Latin for _golden_).

This project serves as an educational resource and interactive showcase for mobile developers and designers. It demonstrates how to scale a Flutter codebase to **107 screens** using clean architecture, robust state management, and custom glassmorphism design tokens.

<table>
  <tr>
    <td><b>Concept</b></td>
    <td>Vietcombank Digibank Clone / UI Study</td>
  </tr>
  <tr>
    <td><b>Screens</b></td>
    <td>107 across 24 feature systems</td>
  </tr>
  <tr>
    <td><b>Design Style</b></td>
    <td>Dark glassmorphism, bronze & gold luxury palette</td>
  </tr>
  <tr>
    <td><b>Languages</b></td>
    <td>Vietnamese (default) + English (complete localization)</td>
  </tr>
  <tr>
    <td><b>Architecture</b></td>
    <td>Clean Architecture, BLoC, go_router, get_it</td>
  </tr>
</table>

---

## 📲 Try the App (Beta)

Experience the luxury UI firsthand by installing the beta app on your device. Since this is a pure UI/UX mockup, it is **100% safe** — it requests no sensitive permissions, handles no real funds, and requires no registration.

> [!IMPORTANT]
> **Android Beta Installation Steps:**
>
> 1. **Join the Testers Group:** Join our Google Group [aureum-digibank-testers](https://groups.google.com/g/aureum-digibank-testers) to authorize your Google Play Account for the testing track.
> 2. **Opt-in & Download:** Click the [Google Play Testing Link](https://play.google.com/apps/testing/com.dinhsoft.aureum) to accept the testing invite and download the app directly from the Google Play Store.

### Download

| Platform    | Link / Instructions                                                   | Status            |
| ----------- | --------------------------------------------------------------------- | ----------------- |
| **Android** | Follow the [Steps Above](#-try-the-app-beta) to get it on Google Play | **Active (Live)** |
| **iOS**     | [TestFlight](https://testflight.apple.com/join/YOUR_CODE)             | Coming soon       |

### 🚀 Quick Start (After Install)

1. **Install** the app from Google Play (testing track) or TestFlight.
2. **Open** Aureum — you will land on the login screen.
3. **Sign in** with any non-empty password (demo mock auth).
   - Example: `demo123`
   - Or tap the **biometric** button to simulate fingerprint / Face ID login.
4. **Explore** via the 5-tab bottom navigation:
   - **Trang chủ** (Home) · **Lịch sử** (History) · **Quét QR** (QR) · **Tài chính** (Finance) · **Thêm** (More)
5. **Try key flows** — transfers, bill pay, cards, savings, invest, eKYC, settings, and more (all mock).
6. **Switch language** — Settings → Language → English / Vietnamese.
7. **Share feedback** — [Open an issue](https://github.com/DucQA/vietcombank_digibank/issues/new) with screenshots and steps.

### 🔍 What to Explore & Test

We encourage you to explore the depth of this case study:

- 📱 **Smooth Navigation:** Test the complex back-stack behavior and deep navigation flows across 107 screens.
- 🎨 **Premium Aesthetics:** Inspect the custom dark glassmorphism theme, gold/bronze design tokens, readability, and touch targets.
- 💸 **Interactive Mock Flows:** Try making a mock transfer, paying bills, opening savings accounts, or applying for mock loans.
- 🇻🇳 **Dual Language Localization:** Switch between Vietnamese (default) and English seamlessly in Settings.
- 🛡️ **Interactive eKYC:** Experience the custom mock eKYC flow including simulated OCR card scanning, FacePay, and document verification.

### 🔒 Privacy & Safety Guarantee

- **Zero Permissions:** The app does not request access to your contacts, camera (except for mock eKYC preview), location, or files.
- **No Real Assets:** No real money or accounts are connected. All balances and transactions are generated locally.

---

## 📸 Screenshots

<p align="center">
  <img src="screenshots/02_transfers.png" width="200" />
  <img src="screenshots/03_qr_payments.png" width="200" />
  <img src="screenshots/04_finance.png" width="200" />
  <img src="screenshots/05_cards.png" width="200" />
</p>

<p align="center">
  <img src="screenshots/06_savings.png" width="200" />
  <img src="screenshots/07_investments.png" width="200" />
  <img src="screenshots/08_security.png" width="200" />
</p>

<details>
<summary><strong>Raw device screenshots (Pixel 6 Pro)</strong></summary>

| Screen   | Preview                                                 |
| -------- | ------------------------------------------------------- |
| Login    | <img src="marketing/raw/01_login.png" width="200" />    |
| Home     | <img src="marketing/raw/02_home.png" width="200" />     |
| History  | <img src="marketing/raw/03_history.png" width="200" />  |
| QR       | <img src="marketing/raw/04_qr.png" width="200" />       |
| Finance  | <img src="marketing/raw/05_finance.png" width="200" />  |
| Transfer | <img src="marketing/raw/07_transfer.png" width="200" /> |
| Cards    | <img src="marketing/raw/08_cards.png" width="200" />    |
| Bills    | <img src="marketing/raw/09_bills.png" width="200" />    |
| Savings  | <img src="marketing/raw/10_savings.png" width="200" />  |
| Invest   | <img src="marketing/raw/11_invest.png" width="200" />   |
| eKYC     | <img src="marketing/raw/12_ekyc.png" width="200" />     |

</details>

---

## ✨ Feature Overview

All features below are **UI mockups with simulated data** — fully navigable, not connected to real services.

### Core navigation

| Tab         | Description                                                              |
| ----------- | ------------------------------------------------------------------------ |
| **Home**    | Account overview, balance card, quick actions, services grid, promotions |
| **History** | Transaction history with filters                                         |
| **QR**      | My QR, scan-to-pay, QR history                                           |
| **Finance** | Personal finance / spending insights (charts)                            |
| **More**    | Extended services, settings entry points                                 |

### Authentication & onboarding

- Login with password (mock)
- Biometric login (fingerprint / Face ID UI)
- eKYC flow — OCR, liveness, NFC, FacePay screens
- VNeID digital ID linking (mock)
- Session & device management

### Money & accounts

- **Transfers** — input, confirm, OTP, success, beneficiaries, templates, scheduled & batch transfers, limits
- **Accounts** — multi-account view, aliases, statements, limits, closure flow
- **Savings** — open account, top-up, withdraw, projection, payout options, settlement
- **Loans** — overview, detail, payment, schedule, documents
- **PFM** — budget planner, expense tracker, financial goals

### Cards

- Card carousel & details
- Card services hub
- Lock / unlock, PIN change, limits
- Statements, transactions, installments
- Virtual card, activation, replacement, repayment

### Payments & top-up

- **QR payments** — scan, pay, result, My QR, ATM cardless, lucky money QR
- **Bill payment** — electricity, water, internet, TV, tuition, traffic, hospital, insurance + autopay
- **Mobile top-up** — prepaid recharge flow
- **eWallets** — Momo, ZaloPay linking (mock)

### Investments & insurance

- Investment portfolio & products
- Stock top-up, certificates
- Insurance products & policy management

### QR & lifestyle utilities

- Flights, taxi, hotel, movies booking (UI)
- SJC gold booking, toll top-up (ePass / VETC)
- Forex, charity, shopping, lounge access
- Lucky money (Lì xì) themes & forms

### Support & engagement

- Live chat, FAQ, branch / ATM map
- Branch booking & rates info
- Promotions, vouchers, loyalty points, rewards catalog
- Notifications center
- Document center & e-statements

### Settings & security

- Profile, security, notifications
- Biometric settings, 2FA, transaction PIN
- Trusted devices, session history
- Language (VI / EN), accessibility, auto-lock
- About, terms & privacy

---

## 📊 Project scale

| Metric           | Value                   |
| ---------------- | ----------------------- |
| Screens          | **107 / 107**           |
| Feature systems  | **24**                  |
| State management | flutter_bloc            |
| Routing          | go_router + auth guards |
| DI               | get_it                  |
| Networking       | Dio (mock fallback)     |

<details>
<summary><strong>All 24 feature systems</strong></summary>

1. Core Structure · 2. eKYC · 3. Investment · 4. Settings & Profile · 5. Notifications
2. Transaction History · 7. Insurance · 8. More Services · 9. Utilities · 10. Promotions
3. Customer Support · 12. Account Management · 13. Financial Tools · 14. Rewards & Loyalty
4. Documents · 16. Advanced Settings · 17. QR Payment · 18. Transfer · 19. Cards
5. Bill Payment · 21. Savings · 22. Loans · 23. Authentication · 24. Home & Navigation

</details>

---

## 🎨 Design

| Element         | Detail                                                         |
| --------------- | -------------------------------------------------------------- |
| **Brand**       | Aureum — premium private banking                               |
| **Palette**     | Bronze `#8B5E3C`, Gold `#D4AF37`, Dark `#0A0A0A`               |
| **Typography**  | Playfair Display + Inter                                       |
| **Style**       | Glassmorphism, dark luxury theme                               |
| **Inspiration** | Premium digital banking UX (Vietcombank Digibank design study) |

---

## ⚠️ Disclaimer

> **Aureum is a UI/UX demonstration project.** It is not affiliated with Vietcombank or any financial institution. It does not provide real banking services, store real credentials, or process real transactions. Do not enter real personal or financial data. For educational and design portfolio purposes only.
