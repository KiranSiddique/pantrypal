# 🥦 PantryPal — Smart Food Expiry Tracker

> **Stop wasting food. Start saving money.**  
> An AI-powered pantry management app that tracks your food items, sends expiry alerts, and suggests recipes using ingredients that are about to expire.

---

## 🖼️ Preview

| Dashboard | Inventory | AI Recipes |
|-----------|-----------|------------|
| Live stats, alerts & savings tracker | Filter by status, add/delete items | AI-generated recipes from expiring items |

---

## ✨ Features

- **🔐 User Authentication** — Sign up / Sign in system with persistent sessions (localStorage)
- **📦 Smart Inventory** — Add food items with name, brand, category, quantity & expiry date
- **📷 OCR Simulation** — Camera-based expiry date scanning (simulated)
- **🔔 Expiry Alerts** — Color-coded alerts: Expired 🔴 / Expiring Soon 🟡 / Safe 🟢
- **💬 WhatsApp Alerts** — Notify family members before items expire
- **🤖 AI Recipe Suggestions** — Recipes generated based on YOUR expiring items using Claude API (Anthropic) — chosen because it is one of the most capable and up-to-date AI models available today
- **💰 Savings Tracker** — Track how much money you save by using items before expiry
- **📱 Mobile-First Design** — Responsive UI with bottom navigation bar

---

## 🚀 Getting Started

### Prerequisites

No installation needed. This is a **single-file HTML app** — just open it in any browser.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/pantrypal.git

# Navigate into the project
cd pantrypal

# Open in browser
open pantrypal-v2.html
# OR just double-click the file
```

### Demo Account

Click **"Try Demo"** on the login screen — no signup required. Pre-loaded with sample pantry items.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML / CSS / JavaScript** | Frontend — single file, zero dependencies |
| **localStorage** | User accounts, pantry data & session persistence |
| **Claude API (Anthropic)** | AI recipe generation — used for being the most advanced AI available |
| **Google ML Kit (planned)** | OCR for expiry date scanning |
| **Firebase (planned)** | Cloud sync & push notifications |
| **WhatsApp Business API (planned)** | Family alert messages |

---

## 📁 Project Structure

```
pantrypal/
│
├── pantrypal-v2.html      # Main app (single file — fully self-contained)
├── README.md              # This file
└── assets/                # (optional) Screenshots, icons
```

---

## 💡 How It Works

```
1. Sign Up / Login
        ↓
2. Add pantry items (name, brand, expiry date, category)
        ↓
3. App automatically tracks status:
   - ✅ Safe      → more than 3 days left
   - ⚠️ Expiring  → 1–3 days left
   - 🚨 Expired   → past expiry date
        ↓
4. Get alerts on the Alerts tab + WhatsApp notifications
        ↓
5. Click "Generate Recipes" → AI suggests recipes
   using your expiring ingredients
        ↓
6. Use items before they expire → Track money saved!
```

---

## 💰 Revenue Model

| Stream | Description | Earning |
|--------|-------------|---------|
| **B2C Freemium** | Free app, premium family accounts | Rs. 299/month |
| **B2B Grocery** | "Order Now" links to Carrefour, Al-Fatah | 5–8% per order |
| **Sponsored Recipes** | Shan, National, Nestle sponsored suggestions | Rs. 50K–200K/month |

---

## 🗺️ Roadmap

- [x] User authentication (localStorage)
- [x] Full pantry CRUD (add, view, delete, filter)
- [x] Expiry status tracking (expired / soon / safe)
- [x] Alerts page with WhatsApp button
- [x] AI recipe generation
- [x] Savings tracker
- [ ] Real Firebase backend + cloud sync
- [ ] Push notifications (browser + mobile)
- [ ] Real OCR via Google ML Kit
- [ ] React Native mobile app (iOS + Android)
- [ ] Family account sharing
- [ ] Barcode scanner for product lookup
- [ ] Grocery store integration (Carrefour, Daraz)

---

## 🌍 Impact

> According to the UN, **1/3 of all food produced globally is wasted.**  
> In Pakistan, the average household loses **thousands of rupees** annually due to expired pantry items.  
> PantryPal directly addresses this — one expiry date at a time.

---

## 👩‍💻 Author

**Kiran Siddique**  
Built for **Idea-Thon 2025** · Food Tech Category · Rawalpindi, Pakistan 🇵🇰

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<p align="center">Made with ❤️ by Kiran Siddique to reduce food waste in Pakistan</p>
