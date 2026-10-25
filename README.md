# 🎮 Mobile Web Game: Player Auth & Play

A mobile-first web game featuring user registration, persistent login, and cross-session player state tracking.

---

## 🚀 Features

- **Mobile-Optimized Auth UI**: Responsive layout preventing iOS auto-zoom (`font-size: 16px`, standard 48px touch targets).
- **Persistent Sessions**: Automatic sign-in persistence via `IndexedDB` / `localStorage` to survive mobile background tab eviction.
- **Account Management**: Email/password authentication, validation, and error feedback.
- **Seamless Transition**: Dynamic overlay that dismisses itself upon authentication to reveal the game canvas.

---

## 🛠️ Tech Stack

- **Front-End**: HTML5, CSS3, JavaScript (ES6+ Modules)
- **Game Rendering**: HTML5 Canvas / Phaser 3 / Three.js
- **Authentication**: Firebase Authentication (or Supabase Auth)
- **Hosting**: Vercel / Netlify / Firebase Hosting

---

## 📂 Project Structure

```text
├── index.html         # Main entry point: auth modal + game canvas
├── styles/
│   └── auth.css       # Mobile touch-friendly UI styles
├── scripts/
│   ├── firebase.js    # Firebase initialization & auth methods
│   ├── auth.js        # Form handling, listeners & UI state
│   └── game.js        # Core game initialization logic
└── README.md
