# 🟥 Square Game

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=for-the-badge)
![Browser Game](https://img.shields.io/badge/Platform-Browser-blueviolet?style=for-the-badge)

**A fast-paced, browser-based square game built entirely with vanilla HTML, CSS & JavaScript — no libraries, no frameworks.**

[🐛 Report Bug](https://github.com/harshit8204/square-game/issues) &nbsp;·&nbsp; [✨ Suggest Feature](https://github.com/harshit8204/square-game/issues)

</div>

---

## 📌 Table of Contents

- [About](#-about)
- [How to Play](#-how-to-play)
- [Tech Stack](#️-tech-stack)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Game Logic](#-game-logic)
- [Roadmap](#-roadmap)
- [Author](#-author)

---

## 🎮 About

**Square Game** is a lightweight, zero-dependency browser game built entirely with **vanilla JavaScript, HTML5, and CSS3**.

> ✏️ **Harshit's note:** *(Update this line with one sentence about what the player does — e.g., "Click the appearing squares before they disappear to score points!" or "Guide your square through obstacles to survive as long as possible!")*

Built to sharpen core JavaScript skills — this project demonstrates:

- 🎮 **Game loop design** — frame-by-frame rendering with `requestAnimationFrame` or `setInterval`
- 🧠 **State management** — tracking score, lives, speed, and game state in vanilla JS
- 🎯 **Event-driven programming** — keyboard/mouse/touch input handling
- 🎨 **Dynamic DOM manipulation** — real-time UI updates without any framework
- 📱 **Responsive design** — playable across screen sizes using CSS

> A clean showcase of browser game fundamentals — built from scratch, no engine required.

---

## 🕹️ How to Play

| Action | Control |
|--------|---------|
| ▶️ Start Game | Click the **Start** button |
| 🖱️ Interact | Click / tap on squares |
| ⌨️ Move (if applicable) | Arrow keys or `W A S D` |
| 🔄 Restart | Press **R** or click **Restart** |

> ✏️ *Update the controls above to match your actual game mechanics.*

---

## 🛠️ Tech Stack

| Technology | Role | Share |
|------------|------|-------|
| 🌐 **HTML5** | Game canvas & UI structure | 23% |
| 🎨 **CSS3** | Styling, animations, layout | 18.5% |
| ⚡ **JavaScript (ES6+)** | Game logic, rendering, input | 58.5% |

> **Zero npm packages. Zero build tools. Zero dependencies.**
> Clone it, open it, play it. That's it.

---

## ✨ Features

- 🟥 **Square-based gameplay** — clean, minimalistic visuals
- ⏱️ **Score / Timer system** — tracks your performance in real time
- 🚀 **Progressive difficulty** — game speeds up as you improve
- 🎯 **Collision / click detection** — precise interaction logic
- 🔄 **Restart without refresh** — full game state reset in-browser
- 📱 **Responsive layout** — works on desktop, tablet & mobile
- ⚡ **Instant load** — no server, no build step, just open and play
- 🎨 **Smooth animations** — CSS transitions and JS-driven motion

---

## 📁 Project Structure

```
square-game/
│
├── index.html      # Game shell — canvas/grid, UI elements (score, timer, buttons)
├── style.css       # All visual styling — squares, animations, responsive layout
├── script.js       # Core game engine — loop, state, input, scoring, collision
└── README.md       # Project documentation
```

> **Just 3 files** — the entire game is self-contained. This is a deliberate choice to
> demonstrate mastery of web fundamentals before introducing tooling or frameworks.

---

## 🚀 Getting Started

No install. No `npm install`. No build step. Just run it.

### Option 1 — Clone & Open

```bash
# 1. Clone the repository
git clone https://github.com/harshit8204/square-game.git

# 2. Navigate into the folder
cd square-game

# 3. Open in your browser
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

### Option 2 — Live Server (Recommended for Dev)

Using **VS Code**? Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer):

1. Right-click `index.html`
2. Click **"Open with Live Server"**
3. Auto-reloads on save ✅

### Option 3 — Play Online

> 🔗 Deploy on GitHub Pages for free — see [Deployment](#-deployment) below.

---

## ⚙️ Game Logic

```
Browser loads index.html
         │
         ▼
script.js initializes game state
  { score: 0, lives: 3, speed: 1, running: false }
         │
         ▼
Player clicks START
         │
         ▼
Game loop begins (requestAnimationFrame / setInterval)
         │
    ┌────┴────────────────────────────┐
    │  Every frame:                   │
    │  → Spawn / move squares         │
    │  → Check collisions / clicks    │
    │  → Update score & speed         │
    │  → Re-render UI                 │
    └────────────────────────────────┘
         │
         ▼
Game Over → show final score → offer restart
```

---

## 🌍 Deployment

Deploy for free in under 2 minutes using **GitHub Pages**:

1. Go to your repo → **Settings** → **Pages**
2. Under *Source*, select **`main` branch** → **Save**
3. Your game is live at:
   ```
   https://harshit8204.github.io/square-game/
   ```
4. Paste this URL in the **🕹️ Play Now** link at the top of this README!

---

## 🗺️ Roadmap

- [x] Core square game mechanics
- [x] Score tracking
- [x] Progressive difficulty
- [x] Responsive layout
- [ ] 🔜 High score saved with `localStorage`
- [ ] 🔜 Sound effects & background music
- [ ] 🔜 Multiple difficulty levels (Easy / Medium / Hard)
- [ ] 🔜 Mobile touch controls
- [ ] 🔜 Leaderboard / shareable score

---

## 🤝 Contributing

All contributions welcome!

1. Fork the repo
2. Create a branch: `git checkout -b feature/add-highscore`
3. Commit: `git commit -m "feat: add localStorage high score"`
4. Push: `git push origin feature/add-highscore`
5. Open a Pull Request 🚀

---

## 👤 Author

**Harshit**

[![GitHub](https://img.shields.io/badge/GitHub-harshit8204-181717?style=flat-square&logo=github)](https://github.com/harshit8204)

---

## 📄 License

This project is open source under the **MIT License**.

---

<div align="center">

*Simple concept. Pure JavaScript. Endless fun.* 🟥

⭐ **If you enjoyed the game, please star the repo!**

</div>
