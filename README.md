# 🍔 Bhook Busters — Fast-Paced Campus Canteen & Food Delivery Web App (Pakistan)

**Bhook Busters** is a modern, responsive food ordering and canteen management web application tailored for Pakistani university campuses, colleges, and hostels. It provides real-time digital token generation, live kitchen preparation countdowns, Pakistani Rupee (PKR / Rs.) pricing with JazzCash/EasyPaisa integration, and a **Passcode-Protected Kitchen Staff / KDS Entrance**.

---

## 🔒 Staff Entrance Passcode Security

To prevent unauthorized students from accessing the Kitchen Display and Admin Controls, the Staff Portal is secured with a passcode gatekeeper:

* **Official Staff Access Code:** `BB-CHEF-786`
* **Alternate Numeric PIN:** `7860` or `CHEF2026`

---

## 🇵🇰 Key Features & Pakistani Campus Integration

### 1. 🎓 Student / Customer Portal
* **Pakistani Rupee (Rs.) Pricing:** Complete authentic menu with realistic Pakistani canteen pricing (Zinger Burgers, Dum Biryani, Malai Boti Paratha Rolls, Samosa Chaat, Karak Doodh Patti Chai, Loaded Fries).
* **Payment Gateways:**
  * 📱 **JazzCash / EasyPaisa / Raast:** Simulated instant QR scan and 1-click demo payment.
  * 💳 **PayPak / Visa / Mastercard** Card payments.
  * 💵 **Cash at Canteen Counter / COD.**
* **Hostel & Campus Delivery:** Pre-configured with Pakistani campus hostel blocks (Jinnah Hostel, Iqbal Hostel, Fatima & Ayesha Girls Hostels, Library Hall) with automated Rs. 50 delivery fee.
* **Campus Promo Codes:** `CAMPUS20` (20% OFF) and `DEAL100` (Flat Rs. 100 OFF).

### 2. 🎫 Digital Token & Live Order Tracking System
* **Digital Token Number:** Generates formatted tokens (e.g. `BB-104`, `BB-105`).
* **4-Stage Visual Progress Timeline:**
  $$\text{Order Received} \longrightarrow \text{Cooking in Kitchen 🍳} \longrightarrow \text{Ready for Pickup 🔔} \longrightarrow \text{Completed 🏁}$$
* **Live Dynamic Countdown Clock:** Estimated prep countdown in minutes and seconds.
* **Synthesized Audio Bell:** Automatic buzzer chime when kitchen marks order as Ready.
* **Printable Thermal Slip:** Clean layout formatted for token printing.

### 3. 👨‍🍳 Passcode-Protected Kitchen Staff KDS & Admin Dashboard
* **Secure Gatekeeper:** Prompts for staff access code (`BB-CHEF-786` or `7860`).
* **Live 3-Column Kanban Board:** *Received Queue*, *In Preparation 🍳*, and *Ready for Counter 🔔*.
* **Menu Stock Controller:** Live toggle between *In Stock* and *Sold Out Today* for any dish.
* **Real-time Metrics:** Pending count, active cooking, ready tokens, and daily PKR revenue.

### 4. ⚡ Multi-Window Real-Time Sync
* Dual-screen testing supported via `BroadcastChannel` and `localStorage`.
* Open Student view in Window 1 and Staff KDS in Window 2 — orders placed in Window 1 appear instantly in Window 2 with sound alerts!

---

## 📂 File Structure

```
c:/Users/Admin/Downloads/Bhook_Busters_App/
│── index.html       # Complete Single-Page Web Application
│── logo.png         # Bhook Busters Chef Mascot Logo
└── README.md        # Documentation & Architecture
```

---

## 💻 How to Run

Double-click [`index.html`](file:///c:/Users/Admin/Downloads/Bhook_Busters_App/index.html) to run in Chrome, Edge, or any browser without installing servers or dependencies.
