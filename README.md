https://revo0808.github.io/Translator/

[README.md](https://github.com/user-attachments/files/26249577/README.md)
# 🗺️ Euro Fling — Travel Translator

A conversational travel translator for **English, French, and German** — built for the Euro Spring Fling crew. Translates the way a native speaker actually talks, not like a textbook.

---

## What it does

- **Translates in all directions** — EN ↔ FR, EN ↔ DE, FR ↔ DE
- **Online**: uses MyMemory (free, no account needed) for live translations
- **Offline**: built-in phrasebook with 300+ conversational phrases that work with no internet
- **Phrasebook categories**: Greetings, Restaurant, Getting Around, Hotel, Shopping, Emergency, Airport, Directions, Small Talk, Ski & Alps, Numbers, Time & Days
- **Voice input** — tap the mic and speak your phrase
- **Favorites** — star any phrase or save any custom translation
- **Dark mode** — automatic based on your phone settings
- **iPhone home screen app** — installs like a native app, no App Store needed

---

## How to install on iPhone

1. Open **Safari** on your iPhone (must be Safari, not Chrome)
2. Go to: `https://yourusername.github.io/euro-fling`
3. Tap the **Share button** (the box with an arrow at the bottom of Safari)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **"Add"** in the top right
6. The app will appear on your home screen like a regular app

> **Before you fly:** open the app once on Wi-Fi so it caches itself. After that, the phrasebook and the whole app work with no internet connection.

---

## How to use it

### Translate tab
- Select your **from** and **to** languages at the top
- Type your phrase — it auto-translates after a short pause, or tap **Translate →**
- Tap 🎙 to use your voice instead of typing
- Tap 📋 to copy the translation
- Tap **☆ Save** to add it to your Favorites

### Phrasebook tab
- Browse by category using the pills at the top
- Tap any phrase card to expand it and see all three languages
- Tap ☆ to save a phrase to your Favorites

### Favorites tab
- All your saved phrases in one place
- Tap 📋 to copy, 🗑 to remove

### Offline mode
When you have no internet connection, a small **✈ Offline** banner appears at the top. The phrasebook works fully offline. For free-text translations, it finds the closest matching phrase from the phrasebook and shows you the match confidence.

---

## Language notes

- **French**: Parisian French conventions — uses *tu* for casual/peer situations, *vous* for service and strangers
- **German**: Austrian/Swiss vocabulary preferred — *Grüß Gott*, *Servus*, *Schnaps*, *Glühwein*, common Alpine expressions
- **Ski & Alps category**: Specific to Chamonix and Zermatt — covers rentals, lift passes, après-ski, mountain rescue, snow conditions, and more

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — all UI, logic, and phrasebook data |
| `sw.js` | Service worker — enables offline caching after first load |
| `manifest.json` | PWA manifest — controls home screen name, icon, and display |

---

## Tech notes

- No frameworks, no build step — plain HTML, CSS, and JavaScript
- Translation powered by [MyMemory](https://mymemory.translated.net/) (free, 1000 words/day)
- Fonts: Playfair Display + Nunito via Google Fonts
- All phrasebook data is embedded directly in `index.html` — no external data files needed
- Favorites are stored in your browser's `localStorage`
