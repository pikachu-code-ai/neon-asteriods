# neon-asteriods# 🚀 NEON ASTEROIDS — Cyberpunk Vector Arcade

A high-speed, single-file cyberpunk vector space combat game built with HTML5 Canvas, Tailwind CSS, and procedural Web Audio synthesis. Pilot your delta-wing starfighter across a toroidal neon grid, shatter splitting asteroids, fend off Cyber UFO ambushes, and chain combo multipliers for the high score!

---

## ✨ Features

* **Dual-Layer Vector Neon Graphics:** Crisp multi-pass vector strokes, pre-rendered radial glow sprites, twinkling starfields, screen shake, and pooled particle explosions engineered for a locked 60 FPS.
* **Toroidal Wrap-Around Physics:** Seamlessly fly, shoot, and drift across all four edges of the screen with real-time boundary mirroring.
* **Escalating Waves & Cyber UFOs:** Clear waves of 3-tier splitting asteroids (Large, Medium, Small). Starting on **Wave 2**, hostile Cyber UFOs warp into the sector, firing aimed plasma bolts and guaranteeing power-up drops when destroyed.
* **Combo Multiplier System:** Chain consecutive kills within the combo decay window to build up to a **12x score multiplier**.
* **Hyperspace Warp:** Emergency teleportation system with a 4-second cooldown that relocates your ship to safe coordinates with brief invulnerability.
* **Procedural Web Audio Synth:** Retro synthesized laser beams, railgun blasts, explosions, UFO warbles, and power-up chimes—zero external audio files required.
* **Cross-Platform Controls:** Full keyboard support on desktop plus translucent multi-touch controls on mobile and tablet devices.

---

## ⚡ 6 Tactical Power-Up Capsules

Destroyed asteroids and Cyber UFOs drop rotating hexagonal capsules that magnetically pull toward your ship when nearby:

| Icon | Power-Up | Duration | Effect |
| :--- | :--- | :--- | :--- |
| **`3X`** | **Triple Scatter** | `10s` | Fires a 3-way spread of high-velocity plasma bolts. |
| **`R`** | **Plasma Railgun** | `8s` | Fires high-energy piercing beams that slice through multiple targets. |
| **`S`** | **Aegis Shield** | `12s` / 1 Hit | Surrounds your fighter in a hexagonal barrier that absorbs one impact and blasts nearby asteroids. |
| **`C`** | **Chrono Field** | `8s` | Slows all asteroids and enemy plasma bolts by **50%**. |
| **`E`** | **Nova EMP** | `Instant` | Unleashes a massive radial shockwave that vaporizes enemy bolts and shatters nearby rocks. |
| **`+1`** | **Extra Hull Life** | `Instant` | Restores **+1 Hull Life** (up to 5 max, or awards **+500 bonus points** at full hull). |

---

## 🎮 Controls

### Desktop Keyboard
| Action | Keys |
| :--- | :--- |
| **Thrust Forward** | `W` or `Up Arrow` |
| **Rotate Left / Right** | `A` / `D` or `Left` / `Right Arrow` |
| **Auto-Fire Weapons** | `Space` (Hold) |
| **Hyperspace Warp** | `Shift`, `S`, or `Down Arrow` |
| **Pause / Resume** | `P` or `Esc` |
| **Mute / Unmute Audio** | `M` |

### Mobile & Touch Devices
* **Bottom-Left Pad:** Hold **`↺`** or **`↻`** to rotate and **`▲ THRUST`** to accelerate.
* **Bottom-Right Pad:** Hold **`◎ FIRE`** for continuous plasma fire and tap **`✦ WARP`** for an emergency hyperspace jump.

---


---

## 🛠️ Tech Stack

* **HTML5 Canvas (2D Context):** High-FPS vector rendering, DPR scaling, toroidal edge rendering, and pooled particle systems.
* **Vanilla JavaScript (ES6+):** Real-time physics, collision detection, wave spawner, and `localStorage` high-score persistence.
* **Web Audio API:** Procedural oscillators and filtered noise bursts for retro arcade sound effects.
* **Tailwind CSS (CDN) & Orbitron Typography:** Responsive HUD cards, active power-up countdown bars, and cyberpunk overlays.
