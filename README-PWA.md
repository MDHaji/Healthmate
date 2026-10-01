# Healthmate – Installable Mobile App (PWA)

## How to install on your phone

### Option A – Best (Recommended)
1. Upload the entire folder (`index.html`, `manifest.json`, `sw.js`, `logo.jpg`) to any free hosting:
   - Netlify Drop (drag & drop)
   - GitHub Pages
   - Vercel
   - Firebase Hosting
2. Open the link on your Android phone (Chrome).
3. Tap the menu (⋮) → **“Add to Home screen”** or **“Install app”**.
4. The app will appear on your home screen like a native app (full screen, no browser bar).

### Option B – Local testing
- Serve the folder with any local server (e.g. `npx serve .` or VS Code Live Server).
- Open on phone via the same Wi-Fi network.

## Features added
- ✅ Installable on Android (and iOS via “Add to Home Screen”)
- ✅ Works offline (core screens cached)
- ✅ Custom app icon (your logo)
- ✅ Theme color matching the hospital brand
- ✅ Standalone mode (no browser UI when installed)
- ✅ Professional status bar color

## Files
- `index.html` – Main app
- `manifest.json` – App identity & icons
- `sw.js` – Offline support
- `logo.jpg` – App icon
