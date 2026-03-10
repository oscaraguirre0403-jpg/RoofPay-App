# RoofPay – Roofing Sub Price List

A fully offline-capable Progressive Web App (PWA) for roofing subcontractor job pricing.

## Features
- 18 roofing line items organized by category
- Extra items, discount, liability %, and payment tracking
- Auto-save to localStorage
- Job history (up to 8 saved jobs)
- Print/export
- Installable on iPhone, Android, and Desktop (no App Store needed)

---

## 🚀 Deploy in 5 Minutes

### Option A — Netlify (Recommended, Free)
1. Go to [netlify.com](https://netlify.com) → Sign up free
2. Click **"Add new site" → "Import from Git"**
3. Connect your GitHub repo containing this folder
4. Build settings are auto-detected from `netlify.toml`
5. Click **Deploy** — you'll get a live URL like `https://roofpay.netlify.app`

### Option B — Vercel (Also Free)
1. Go to [vercel.com](https://vercel.com) → Sign up free
2. Click **"New Project" → Import your repo**
3. Vercel detects Vite automatically
4. Click **Deploy**

### Option C — Run Locally
```bash
npm install
npm run dev
# Opens at http://localhost:5173
```

### Option D — Build & Host Anywhere
```bash
npm install
npm run build
# Upload the /dist folder to any static host
```

---

## 📱 Installing on iPhone
1. Open the deployed URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Done — it works like a native app, offline included!

## 📱 Installing on Android
1. Open the URL in **Chrome**
2. Tap the **"Install"** banner that appears, or tap menu → "Add to Home Screen"

---

## Project Structure
```
roofpay/
├── src/
│   ├── main.jsx          # Entry point
│   ├── App.jsx           # Main application
│   └── InstallPrompt.jsx # PWA install banner
├── public/
│   ├── manifest.json     # Web app manifest
│   ├── icons/            # App icons
│   └── apple-touch-icon.png
├── index.html
├── vite.config.js        # Vite + PWA plugin config
├── netlify.toml          # Netlify deploy config
└── vercel.json           # Vercel deploy config
```

---

Built with React + Vite + vite-plugin-pwa
