# Vela — Trading Journal

A professional PWA trading journal. Works offline, installs on phone like a real app.

## Files
- `index.html` — main app
- `manifest.json` — PWA config (name, icon, colors)
- `sw.js` — service worker (offline support)
- `icon.svg` — app icon

## How to install on phone

### Option A — Free hosting with Netlify (easiest, 2 min)
1. Go to https://app.netlify.com/drop
2. Drag the entire `vela` folder onto the page
3. You get a live URL like `vela-abc123.netlify.app`
4. Open that URL on your phone
5. Tap **Share → Add to Home Screen** (iOS) or the install prompt (Android)
6. Vela appears on your home screen like a native app ✓

### Option B — GitHub Pages (free, permanent)
1. Create a GitHub account at github.com
2. New repo → upload all 4 files
3. Settings → Pages → deploy from main branch
4. You get `yourusername.github.io/vela`

### Option C — Local only (no internet needed)
- Open `index.html` in Chrome on your computer
- It won't install as PWA locally, but works fully in browser

## Notes
- All trade data is saved in the browser (localStorage)
- Data stays on the device — no server, no account needed
- Each device has its own separate journal

## Branding
Feel free to change the name, colors, or icon for your own use.
Main color variable in CSS: `--green: #00e676`
Font: Syne (headers) + DM Mono (numbers)
