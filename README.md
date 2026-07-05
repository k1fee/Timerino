# ⏱ Focus

> A clean Pomodoro timer that remembers your progress.

A minimal, beautiful focus timer built with zero dependencies. Tracks sessions, focused minutes, and your daily streak — all saved locally in your browser.

---

## ✨ Features

- **3 modes** — Focus, Short break, Long break
- **Circular progress ring** — fills as the session runs
- **Auto-switching** — switches to break mode when a session ends, and back again
- **Session dots** — visual progress through your cycle before a long break
- **Chime sound** — a soft three-note chord when the timer ends
- **Stats tracking** — total sessions, focused minutes, and daily streak (persisted in localStorage)
- **Fully configurable** — set your own durations and sessions-per-cycle in Settings
- **Keyboard shortcuts** — Space (play/pause), R (reset), S (skip)
- **Zero dependencies** — one HTML file, no npm, no build step

---

## 🚀 Getting started

```bash
git clone https://github.com/YOUR_USERNAME/focus.git
cd focus
open index.html
```

No server needed — just open the file directly.

---

## ⌨️ Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `R` | Reset current session |
| `S` | Skip to next mode |

---

## ⚙️ Settings

Click the ⚙ icon to configure:

- Focus duration (default: 25 min)
- Short break (default: 5 min)
- Long break (default: 15 min)
- Sessions before long break (default: 4)

Settings are saved to localStorage and persist across visits.

---

## 📁 Project structure

```
focus/
├── index.html    # Everything in one file
└── README.md
```

---

## 🌐 Deploying

Static file — deploy anywhere:

- **GitHub Pages** — enable in Settings → Pages
- **Netlify** — drag and drop the folder
- No backend needed

---

## 📄 License

Copyright (c) 2026 Mariam Tsagareishvili. All rights reserved.
