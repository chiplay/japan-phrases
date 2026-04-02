# Japan Phrases 日本語

Essential Japanese phrases for travel — with pronunciation, audio playback, and custom phrase lists. Works offline as an installable PWA.

## What's included

| File | Purpose |
|------|---------|
| `index.html` | The complete app in one file |
| `manifest.json` | Makes it an installable PWA |
| `sw.js` | Service worker for offline support |
| `icon-192.png` | App icon (192x192) |
| `icon-512.png` | App icon (512x512) |

## Features

- **5 categories**: Greetings, Restaurant, Transportation, Shopping, Hotel
- **Audio playback**: Tap 🔊 to hear Japanese pronunciation
- **Copy to clipboard**: One-tap copy of Japanese text
- **Custom phrases**: Add your own phrases to "My Phrases"
- **Drag to reorder**: Hold and drag cards to rearrange
- **Works offline**: Service worker caches everything on first load
- **Installable**: Add to home screen on iPhone or Android

## Deploy to Netlify

1. Push this repo to GitHub
2. Go to [netlify.com](https://netlify.com) and sign in
3. Click **"Add new site"** → **"Import an existing project"**
4. Connect your GitHub repo
5. Deploy settings: leave defaults (no build command needed)
6. Click **Deploy** — you'll get a URL like `https://japan-phrases-abc123.netlify.app`

## Install on your phone

### iPhone (Safari)
1. Open the Netlify URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Name it "Japan Phrases" → tap **Add**

### Android (Chrome)
1. Open the URL in **Chrome**
2. Tap the **three-dot menu** → **"Add to Home screen"**
3. Tap **Add**

## Offline support

The app works fully offline once loaded. The service worker caches all files on first visit — no internet needed after that. Perfect for Japan!
