<div align="center">

# 🕌 Al-Quran Bangla AI (আল-কুরআন বাংলা)

**An AI-powered Quran platform built for the Bangla-speaking community.**

Read, listen, search, and understand the Quran with Gemini-powered Tafsir, semantic search, and a live voice assistant.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Version](https://img.shields.io/badge/version-1.2.0-emerald)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-Installable-5A0FC8?logo=pwa&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?logo=googlegemini&logoColor=white)

[**Live Demo**](https://YOUR-LIVE-LINK) · [**Report a Bug**](https://github.com/shahinprpl-sketch/alQural/issues) · [**Request a Feature**](https://github.com/shahinprpl-sketch/alQural/issues)

</div>

---

## 📸 Screenshots

| Home | Tafsir | Voice Assistant |
|:---:|:---:|:---:|
| ![Home](screenshots/home.png) | ![Tafsir](screenshots/tafsir.png) | ![Voice](screenshots/voice.png) |

## 📖 About

Most Quran apps offer text and audio. **Al-Quran Bangla AI** goes further by helping Bangla speakers *understand* what they read. It combines the complete Quran with AI features so users can ask questions, explore topics, and get contextual explanations in their own language.

## 🌟 Features

| Feature | Description |
|---|---|
| 📖 **Complete Quran** | All 114 Surahs with Arabic script and Bangla/English translations |
| 🧠 **AI Tafsir** | Contextual verse explanations generated with Google Gemini |
| 🔍 **Semantic Search** | Search by topic or meaning (e.g. "Patience", "Inheritance"), not just keywords |
| 🎙️ **Live Voice Assistant** | Ask spiritual or historical questions and get real-time audio answers |
| 🎧 **Master Reciters** | Stream recitations from 12 renowned Qaris, including Alafasy and Minshawi |
| 🕋 **Daily Utilities** | Location-based prayer times and a Ramadan countdown |
| 🎨 **Reading Experience** | Dark mode, smooth animations, and adjustable typography |
| 📱 **Installable PWA** | Works like a native app on Android and iOS |

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Vite
- **AI:** Google Gemini API (Tafsir, semantic search, voice assistant)
- **App type:** Progressive Web App (service worker + web manifest)
- **Deployment:** Vercel / Netlify

## 🚀 Getting Started

### Prerequisites

- Node.js 18 or later
- A [Google Gemini API key](https://aistudio.google.com/apikey)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/shahinprpl-sketch/alQural.git
cd alQural

# 2. Install dependencies
npm install

# 3. Add your environment variables
cp .env.example .env
# then open .env and set API_KEY=your_gemini_api_key

# 4. Start the development server
npm run dev
```

### Build for production

```bash
npm run build
npm run preview
```

## 📱 Install as a Mobile App (PWA)

- **Android:** open in Chrome → menu → **Add to Home Screen**
- **iOS:** open in Safari → **Share** → **Add to Home Screen**

## 📂 Project Structure

```
alQural/
├── components/      # UI components
├── services/        # API and AI service logic
├── App.tsx          # Root component
├── constants.ts     # App constants
├── translations.ts  # Bangla / English strings
├── types.ts         # Shared TypeScript types
├── sw.js            # Service worker (offline support)
└── manifest.json    # PWA manifest
```

## 🔐 Security Note

Never commit your API key. Keep it in `.env` (already ignored by `.gitignore`). For production, route Gemini requests through a serverless function so the key is never exposed in the browser.

## 🗺️ Roadmap

- [ ] Serverless proxy for secure API calls
- [ ] Bookmarks and reading history
- [ ] More translations and languages
- [ ] Offline Surah downloads
- [ ] Verse sharing as images

## 🤝 Contributing

Contributions are welcome.

1. Fork the project
2. Create your feature branch: `git checkout -b feat/your-feature`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push to the branch: `git push origin feat/your-feature`
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for details.

## 👨‍💻 Author

**Md Shahin** · AI Apps Developer · Founder of Pixel Retouch Pro

[![GitHub](https://img.shields.io/badge/GitHub-shahinprpl--sketch-181717?logo=github)](https://github.com/shahinprpl-sketch)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN)

---

<div align="center">

If you find this project useful, please give it a ⭐

*Built with ❤️ for the Bangla-speaking Muslim community.*

</div>
