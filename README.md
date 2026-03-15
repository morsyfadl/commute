# Commute Checklist PWA

An offline-capable Progressive Web App for your Alexandria ↔ Cairo commute.

## 🚀 Deploy to GitHub Pages (5 min)

1. **Create a GitHub repo** (e.g. `commute-checklist`) — make it **public**
2. **Upload these files** by dragging them into the repo on GitHub.com:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder (with both PNGs)
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch** → `main` → `/ (root)` → Save
5. Your app will be live at: `https://YOUR_USERNAME.github.io/commute-checklist`

> GitHub Pages takes ~1–2 minutes to deploy on first push.

## 📱 Install as App (PWA)

**iPhone/iPad (Safari):**
- Open the URL in Safari → tap the Share icon → "Add to Home Screen"

**Android (Chrome):**
- Open the URL → tap the 3-dot menu → "Add to Home Screen" or "Install App"

**Desktop (Chrome/Edge):**
- Click the install icon (⊕) in the address bar

Once installed, the app works **fully offline**.

## Features

| Feature | How it works |
|---|---|
| ✅ Check items off | Tap any item |
| ✏️ Edit list | Tap **Edit List** to rename/add/delete items & categories |
| 🔄 Sync across devices | Tap **Sync Code** → Export code on one device, Import on another |
| 🗑 Reset for next trip | Tap **Clear All** at the bottom |
| 📴 Works offline | Service worker caches everything after first load |
| 💾 Saves progress | Uses localStorage — survives page close/refresh on same browser |

## Cross-Device Sync Notes

The sync is **manual** (copy-paste a code), which means no backend is needed.
For *automatic* live sync across devices, you'd need Firebase Firestore (free tier).
See: https://firebase.google.com/docs/firestore/quickstart
