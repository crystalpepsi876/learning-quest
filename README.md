# Learning Quest PWA - Setup Guide

## What's in this folder
- `index.html` — The complete app (all code is self-contained)
- `manifest.json` — PWA configuration (app name, icons, display settings)
- `sw.js` — Service worker for offline caching
- `icon-192.png` — App icon (192×192)
- `icon-512.png` — App icon (512×512)

## How to install on your devices

### Option A: Free hosting with GitHub Pages (recommended)
1. Go to https://github.com and create a free account (or log in)
2. Click **New Repository** → name it `learning-quest` → make it **Public**
3. Upload all 5 files from this folder into the repository
4. Go to **Settings** → **Pages** → set source to **main** branch → Save
5. Your app will be live at `https://yourusername.github.io/learning-quest/`

### Option B: Free hosting with Netlify
1. Go to https://app.netlify.com/drop
2. Drag and drop the entire `learning-quest-pwa` folder
3. Your app gets a free URL instantly

---

## Installing on iPad / iPhone
1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the app icon appears on your home screen
5. Open it — it runs full-screen like a native app!

## Installing on Android
1. Open the URL in **Chrome**
2. You should see an **"Install app"** banner at the bottom — tap it
3. If no banner appears, tap the **⋮ menu** → **"Install app"** or **"Add to Home Screen"**
4. The app icon appears in your app drawer
5. Open it — it runs full-screen like a native app!

## Works Offline!
Once you've opened the app at least once, it caches everything locally. Your kids can use it even without internet (except the spelling text-to-speech which needs a connection on some devices).
