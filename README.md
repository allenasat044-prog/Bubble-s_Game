# 🦕 Bubble's Adventure

> A browser-based pixel art side-scrolling shooter inspired by the classic **Contra** arcade series — built entirely in vanilla HTML5 Canvas with **zero dependencies**.

![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange?style=flat-square&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=flat-square&logo=javascript)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-blue?style=flat-square)

---

## 🎮 About the Game

Step into the boots of **Bubble** — a lone warrior dropped into a dense prehistoric jungle crawling with monsters. Fight through endless waves of enemies, grab power-ups scattered across the terrain, and survive long enough to face the fearsome **Dino Boss** lurking at the end of each level.

Every level gets harder. Can you beat your hi-score?

---

## 🚀 Play Instantly

No install. No build step. No dependencies.

```bash
# Clone the repo
git clone https://github.com/your-username/Bubbles_Adventure.git

# Open in your browser
open contra-pixel-game.html
```

Or just **drag `contra-pixel-game.html` into any modern browser** and play.

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `← →` | Move left / right |
| `Space` | Jump |
| `Z` or `X` | Shoot |
| `↑ + Z` | Shoot upward |
| `↓ + Z` | Shoot downward *(in air)* |
| `↓` | Duck |
| `Enter` | Start / Continue |

---

## ✨ Features

### 🧍 Player
- Run, duck, jump, and aim in multiple directions
- Invincibility frames on hit
- Visual feedback: boost trail, shield bubble, spread shot glow

### 👾 5 Enemy Monster Types

| Monster | Behavior |
|---------|----------|
| 🟢 **Goblin** | Fast melee chaser with oversized ears |
| 🟡 **Lizard** | Medium speed, back spines, dragging tail |
| 🟣 **Spider** | Erratic jumper, drops from web threads |
| 🟦 **Toad** | Ranged — fires aimed shots, flicks tongue |
| 🟩 **Dino** | Charges and shoots projectiles |
| 🟠 **Dino Boss** | Giant pixel dino — spray attack, leaps, full HP bar |

### 🎁 Power-Ups

Spawned on the ground and on floating platforms throughout each level.

| Icon | Name | Effect |
|------|------|--------|
| 🛡 | **Shield** | Absorbs the next 3 hits — glowing blue bubble |
| ⚡ | **Boost** | Double movement speed + rapid fire + golden trail |
| ★ | **Spread Shot** | Fires 3 bullets in a fan pattern |
| ❤ | **Extra Life** | +1 life (maximum 5) |

### 🎨 Visual Polish
- Parallax jungle background with 3 depth layers + firefly particles
- Hand-crafted pixel art sprites drawn entirely with `fillRect`
- CRT scanline + vignette post-processing overlay
- Full particle system: muzzle flash, blood splatter, explosions
- Animated shield bubble with hit-pip indicators
- Bobbing pickups with colored glow effects
- Boss HP bar with gradient fill (screen-space)
- Enemy health bars on multi-HP monsters

### 📈 Progression
- Levels scale in enemy count, speed, and boss difficulty
- Bonus score awarded on level clear
- Persistent hi-score across runs
- 3 starting lives with respawn

---

## 🛠️ Tech Stack

| Tech | Usage |
|------|-------|
| **HTML5 Canvas 2D** | All rendering — background, sprites, particles, UI |
| **Vanilla JavaScript** | Game loop, physics, AI, collision, state |
| **CSS3** | HUD styling, overlay screens, pickup notifications |
| **Google Fonts** | *Press Start 2P* — retro pixel font |

No frameworks. No canvas libraries. No bundlers. Just one `.html` file.

---

## 🗂️ Project Structure

```
Bubbles_Adventure/
├── contra-pixel-game.html   # Entire game — HTML + CSS + JS in one file
└── README.md
```

---

## 🎯 Roadmap / Ideas

- [ ] Mobile touch controls
- [ ] Sound effects & chiptune BGM
- [ ] More enemy types (flying, armored)
- [ ] Weapon drop system (laser, grenade)
- [ ] Local leaderboard (localStorage)
- [ ] Stage select screen

---

## 📸 Inspired By

> **Contra** (Konami, 1987) — the legendary run-and-gun arcade classic that defined a genre.

---

## 📄 License

This project is licensed under the **MIT License** — free to use, fork, modify, and build upon.

---

<p align="center">Made with ❤️ and pixel art — <b>Bubble's Adventure</b></p>
