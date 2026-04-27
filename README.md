# وصلة (Wasla)

> صفحة روابط أنيقة — Arabic link-in-bio PWA

A fully self-hosted, private, Arabic link-in-bio tool. No accounts, no tracking, no servers — everything lives in your browser.

## ✨ Features

- 🔗 **Unlimited links** with emoji icons, titles & descriptions
- 📊 **Built-in analytics** — views, clicks, CTR, weekly chart
- 🎨 **6 color themes** — gold, purple, blue, green, rose, amber
- 📲 **True PWA** — installable on iOS & Android, works offline
- 🔐 **4-digit PIN lock** for admin panel privacy
- 📤 **QR code** generation + share to WhatsApp, Twitter, Telegram…
- 💾 **Export/Import** JSON backup — your data, forever yours
- 🌙 **Dark, RTL-first** design optimized for Arabic
- 🚫 **Zero dependencies** — no npm, no build step, no backend

## 🚀 Deploy to GitHub Pages (2 minutes)

1. Fork or create a new repo
2. Upload `index.html`, `manifest.json`, `sw.js`, `icon.svg`
3. Go to **Settings → Pages → Source: Deploy from branch → main**
4. Your page is live at `https://yourusername.github.io/wasla/`

## 📱 Install as App

- **Android**: Open in Chrome → Menu → "Add to Home Screen"
- **iOS**: Open in Safari → Share → "Add to Home Screen"

## 🔐 Default PIN

`1234` — change it immediately in Settings → Security after first login.

## 📁 File Structure

```
wasla/
├── index.html      ← entire app (single file)
├── manifest.json   ← PWA manifest
├── sw.js           ← service worker (offline)
└── icon.svg        ← app icon
```

## 🛡️ Privacy

- **All data stored locally** in your browser's localStorage
- **No servers, no analytics, no cookies** from third parties
- **No account required** — it's yours from day one
- **Export anytime** — full JSON backup

## 📄 License

MIT — use freely, commercially, modify as needed.
