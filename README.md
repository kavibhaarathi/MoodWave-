[README_moodwave.md](https://github.com/user-attachments/files/27271172/README_moodwave.md)
# MoodWave 🎵 — AI Mood-Based Playlist Generator

> Tell it how you feel. Gemini AI curates the perfect playlist for your mood.

![MoodWave Banner](https://img.shields.io/badge/Powered%20by-Gemini%20AI-blueviolet?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2F%20CSS%20%2F%20JS-orange?style=for-the-badge)
![No Backend](https://img.shields.io/badge/Backend-None%20Required-lightgrey?style=for-the-badge)

---

## 📖 About

**MoodWave** is a fully client-side AI-powered playlist generator. Select your mood, set your genre and era preferences, and Gemini AI instantly curates a personalized playlist with real songs — complete with direct Spotify and YouTube search links. No backend, no database, no sign-up required.

---

## ✨ Features

- **8 Mood Modes**
  - ☀️ Happy — Uplifting & joyful
  - 🌧️ Sad — Emotional & healing
  - ⚡ Energetic — Pump it up
  - 🌊 Chill — Relax & unwind
  - 🌹 Romantic — Love & longing
  - 🎯 Focused — Deep work mode
  - 🔥 Angry — Let it out
  - 🌙 Melancholic — Late night thoughts

- **Smart Filters**
  - 13 Genre options (Pop, Hip-Hop, Rock, Indie, R&B, Lo-Fi, K-Pop & more)
  - 6 Era filters (2020s → 70s & Earlier)
  - Playlist size: 8 / 12 / 16 / 20 songs

- **Custom Vibe Input** — Describe any situation in your own words
  > *"driving at night in the rain"*, *"studying in a cozy coffee shop"*, *"heartbreak at 2am"*

- **Per-Track Actions**
  - ▶ Direct Spotify search link
  - ▶ Direct YouTube search link

- **Playlist Actions**
  - ⧉ Copy full playlist to clipboard
  - ↓ Download as `.txt` file
  - ↺ Regenerate a fresh playlist

- **Design**
  - Dark cosmic UI with animated gradient orbs
  - Animated sound wave loading indicator
  - Mood-specific color accents
  - Fully responsive for mobile

---

## 🚀 Live Demo

> 🔗 `https://kavibhaarathi.github.io/moodwave`

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | App structure |
| CSS3 | Animations, layout, theming |
| Vanilla JavaScript | Logic, API calls, rendering |
| Google Gemini 1.5 Flash | AI playlist generation |
| Google Fonts | Syne, Instrument Sans, Instrument Serif |

---

## 📦 Project Structure

```
moodwave/
│
├── index.html      ← Full single-file app
└── README.md       ← Documentation
```

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/kavibhaarathi/moodwave.git
cd moodwave
```

### 2. Get a Free Gemini API Key

1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **"Create API Key"**
4. Copy your key — it starts with `AIza...`

> ✅ Gemini API has a generous **free tier** — no credit card needed.

### 3. Open the App

```bash
# Option 1 — just open in browser
open index.html

# Option 2 — local server with Python
python -m http.server 8000
# Visit: http://localhost:8000

# Option 3 — VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

### 4. Enter Your API Key

A modal will appear on first load asking for your Gemini API key. Paste it in — it lives only in session memory.

---

## 🌐 Deploy to GitHub Pages (Free Hosting)

```bash
# Step 1 — Initialize and push to GitHub
git init
git add .
git commit -m "Initial commit — MoodWave"
git branch -M main
git remote add origin https://github.com/kavibhaarathi/moodwave.git
git push -u origin main
```

```
# Step 2 — Enable GitHub Pages
1. Open your repo on GitHub
2. Click Settings → Pages
3. Source: Deploy from a branch
4. Branch: main → / (root) → Save
```

```
# Step 3 — Your site is live at:
https://kavibhaarathi.github.io/moodwave
```

---

## 🎮 How to Use

| Step | Action |
|---|---|
| 1 | Enter your Gemini API key on first load |
| 2 | Click a mood card (Happy, Sad, Energetic, etc.) |
| 3 | Choose a genre, era, and song count |
| 4 | Optionally type a custom vibe description |
| 5 | Hit **Generate ✦** |
| 6 | Browse your AI-curated playlist |
| 7 | Click Spotify or YouTube to listen instantly |
| 8 | Copy or download your playlist |

---

## 🔐 API Key Security

- Your API key is **never stored** in the source code
- It is held in **session memory only** — cleared when the tab closes
- All requests go **directly to Google's API** — no third-party server involved
- Each user provides their own key
- **Never commit your API key to a public repo**

---

## 📸 Screenshots

> Add your own screenshots after deployment.

```
screenshots/
├── home.png
├── mood-selected.png
├── playlist-generated.png
└── mobile-view.png
```

---

## 🤝 Contributing

Pull requests are welcome!

```bash
# Fork the repository
# Create a feature branch
git checkout -b feature/your-feature

# Commit your changes
git commit -m "Add: your feature description"

# Push and open a Pull Request
git push origin feature/your-feature
```

---

## 💡 Future Ideas

- [ ] Spotify OAuth — add playlist directly to your Spotify account
- [ ] Save playlist history with localStorage
- [ ] Share playlist via unique URL
- [ ] Album art generation using Gemini Vision
- [ ] BPM / energy level slider
- [ ] Multi-language support
- [ ] Light theme toggle
- [ ] Mood journal — log moods over time

---

## 📄 License

This project is licensed under the **MIT License** — free to use, fork, and build upon.

---

## 🙏 Acknowledgements

- [Google Gemini API](https://ai.google.dev/) — AI playlist curation
- [Google AI Studio](https://aistudio.google.com/) — Free API key management
- [Google Fonts](https://fonts.google.com/) — Syne, Instrument Sans, Instrument Serif
- [Spotify](https://spotify.com) & [YouTube](https://youtube.com) — Music playback links

---

<p align="center">Built with 🎵 and Gemini AI · <a href="https://aistudio.google.com/app/apikey">Get your free API key</a></p>
