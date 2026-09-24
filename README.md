# Suzy — Your Virtual Companion

Mobile-friendly AI companion that runs as a Progressive Web App.
Hosted on GitHub Pages. Uses OpenRouter free models + browser voice + local memory.

## Features (v0.1)
- Chat with Suzy (OpenRouter free / uncensored-capable models)
- Persistent memory stored in your browser (IndexedDB / localStorage)
- Voice input & output using the browser’s built-in speech APIs (works on most phones)
- Mobile-first responsive UI
- Lightweight avatar placeholder (upgradeable later)
- No server required — pure static site

## Important security note
Your OpenRouter API key is stored **only in your browser** (localStorage).
It never leaves your device and is never uploaded to GitHub.
Do **not** commit any real key.

## How to use
1. Enable GitHub Pages on this repo (Settings → Pages → Source: Deploy from branch `main` / root)
2. Open the live site
3. Tap the gear icon → paste your OpenRouter API key → Save
4. Start talking or typing with Suzy

## Local development
Just open `index.html` or serve the folder with any static server:

```bash
npx serve .
```

---
Suzy is being built step by step. More features (better memory, 3D avatar, smoother voice) coming next.
