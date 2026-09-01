# 🏷️ Case Study: Full-Stack Coupon & Merchant Loyalty Platform

**Role:** Full-Stack System Architect & Developer  
**Tech Stack:** C#, Cross-Platform Mobile, Desktop (PC) Software, Web Infrastructure, MySQL/SQL Server  
**Status:** In Production / Live System

> ⚠️ *Note: The source code for this enterprise system is private. This repository serves as a case study to showcase the full-stack architecture, business logic, and cross-platform ecosystem.*

---

### 🎥 Visual Overview

<p align="center">
  <img src="https://raw.githubusercontent.com/ZackAnSimpleDeveloper/cupom_validate/main/images/Aplicativo.jpg" alt="Mobile App Interface" width="240"/>
  <img src="https://raw.githubusercontent.com/ZackAnSimpleDeveloper/cupom_validate/main/images/appCupomGenerated.jpeg" alt="Coupon Generated" width="240"/>
  <img src="https://raw.githubusercontent.com/ZackAnSimpleDeveloper/cupom_validate/main/images/controlpcSystem.jpeg" alt="Desktop PC Management Software" width="300"/>
</p>

---

### 🚨 The Business Problem
Small and medium-sized merchants struggle with customer retention and effective sales promotion tracking. Traditional paper coupons or flat discounts either erode profit margins or fail to engage customers dynamically.

### 💡 The Solution
I architected and built a complete end-to-end loyalty ecosystem consisting of three core pillars:

1. **Consumer Mobile App (Android/Play Store):** Allows users to register, discover local merchant offers, and receive dynamic discount coupons after purchases.
2. **Merchant PC Desktop Software:** A dedicated Windows application for store managers to handle cash flow, validate incoming customer coupons, and manage sales controls in real time.
3. **Web Infrastructure & Smart Algorithm:** A centralized backend that connects the mobile apps and desktop clients, featuring a **weighted random probability engine** for coupon distribution.

### 🎲 The Gamified Coupon Engine
To keep customer engagement high while protecting merchant margins, I engineered a custom dynamic reward algorithm:
- Coupons range from **1% to 100% discount**.
- The algorithm uses a weighted probability curve where random rewards heavily cluster between **5% and 15%**, providing frequent low-cost wins for consumers while keeping high-value discounts rare and exciting.
- Configurable rules allow merchants to define specific campaign characteristics and reward triggers.

---

### 📈 Key Business Results
- **Full Operational Integration:** Real-time synchronization between what the customer sees on their phone and what the merchant processes on their PC terminal.
- **Gamified Retention:** The dynamic probability system increases repeat purchases through gamified discount mechanics.
- **Merchant Protection:** Automated coupon validation prevents double-spending and fraud at the register.

---

### 🏗️ Full-Stack System Architecture
- **Mobile Client:** Native/Cross-platform mobile app published on the Google Play Store for consumer interaction.
- **Desktop Client:** C# PC application for fast, offline-resilient merchant register management.
- **Backend & Database:** Web API layer handling authentication, probabilistic reward generation, and transaction history sync.
