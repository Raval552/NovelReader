# 📖 Novel Reader

A personal PWA for reading PDF novels and books — fully offline, no server needed.

## Features
- 📂 Open PDF files directly from your device
- 📚 Library with reading progress saved locally
- 🔤 Auto-detect Arabic/English with correct RTL rendering
- 🌐 Bidirectional translation (AR ↔ EN)
- 🌙 Dark theme optimized for reading
- 📱 Installable as a PWA (Add to Home Screen)

## Deploy on GitHub Pages (3 steps)

1. **Fork or upload** this repo to your GitHub account
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch** → `main` → `/ (root)` → Save

Your app will be live at:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

## Usage
- Open the link in Chrome on your phone
- Tap the browser menu → **Add to Home Screen** to install as an app
- Open any PDF from your device — it gets saved locally for future sessions

## Notes
- All data stays **100% on your device** — no server, no accounts
- Works offline after first load (Service Worker caches assets)
- Library persists between sessions via IndexedDB (won't persist in Incognito mode)
