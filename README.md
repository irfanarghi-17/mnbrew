# ☕ Manual Brew Guide

A mobile-first web app for manual coffee brewing — step-by-step guides with built-in timers for 7 brew methods.

## Features

- **7 brew methods**: Hario V60, Chemex, French Press, AeroPress, Moka Pot, Cold Brew, Siphon
- **16 coffee varieties**: Rich Indonesian origins (Aceh Gayo, Bali Kintamani, Sulawesi Toraja, Argopuro, Flores Bajawa, Papua Wamena, and more) plus African and American origins
- **Smart ratio calculation**: Coffee-to-water ratio and brew temperature adjust automatically per roast level
- **Grind size guide**: 7 grind levels with method-specific auto-recommendation
- **Built-in brew timer**: Phase-aware timer shows current step as you brew
- **PWA ready**: Installable on iOS and Android as a home screen app
- **Mobile-first**: Designed for one-handed use in the kitchen

## Deploy

### Netlify (recommended)
1. Push this folder to a GitHub repository
2. Go to [netlify.com](https://netlify.com) → **Add new site** → **Import from Git**
3. Select your repo — build settings are auto-detected via `netlify.toml`
4. Click **Deploy site**

### GitHub Pages
1. Push to GitHub
2. Go to repo **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your site will be live at `https://yourusername.github.io/repo-name`

## Project structure

```
brewguide/
├── index.html      # Main app (single file, no build step needed)
├── manifest.json   # PWA manifest
├── icon-192.png    # App icon (192×192)
├── icon-512.png    # App icon (512×512)
├── netlify.toml    # Netlify deploy config
└── README.md
```

## Tech

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies.
