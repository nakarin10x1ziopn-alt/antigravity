# 🏓 Pong AI Game

A retro-style **Pong game** with an AI opponent, built with pure HTML/CSS/JavaScript — no dependencies, no frameworks.

🎮 **[Play Online](https://YOUR_USERNAME.github.io/pong-ai-game/)** ← (replace with your URL after deploy)

---

## ✨ Features

- 🤖 **AI Opponent** with 4 difficulty levels
- 🔮 **Ball Prediction** — Hard & Impossible AI predicts bounce trajectories
- 📡 **AI Status Display** — See what the AI is thinking (IDLE / TRACKING / PREDICTING)
- 💥 **Particle Effects** — Sparks on paddle hits and scoring
- 🎵 **Sound Effects** — Web Audio API generated beeps
- ⏱️ **Countdown Timer** — 3-2-1 countdown before each round
- 🖱️ **Mouse & Touch Support** — Works on desktop and mobile
- ⚡ **Speed Escalation** — Ball speeds up with each rally

---

## 🎮 How to Play

| Control | Player |
|---------|--------|
| `W` / `S` | Move paddle up / down |
| `↑` / `↓` | (unused — AI controls right paddle) |
| Mouse | Move mouse to control paddle |
| Touch | Touch and drag on mobile |

**First to 7 points wins!**

---

## 🧠 AI Difficulty

| Level | Speed | Look-ahead | Miss Chance |
|-------|-------|------------|-------------|
| 🟢 Easy | Slow | None | 25% |
| 🟡 Medium | Moderate | 1 step | 10% |
| 🔴 Hard | Fast | 3 steps | 3% |
| 💀 Impossible | Maximum | 10 steps | 0% |

---

## 🚀 Run Locally

Just open `index.html` in any modern browser — no server needed!

```bash
git clone https://github.com/YOUR_USERNAME/pong-ai-game.git
cd pong-ai-game
# Open index.html in your browser
```

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — Game rendering
- **Web Audio API** — Sound effects (no external files)
- **Vanilla JavaScript** — Game logic & AI
- **CSS3** — UI, animations, glow effects

---

## 📄 License

MIT — Feel free to fork, modify, and share!
