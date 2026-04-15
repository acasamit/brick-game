# 🧱 Brick Shooter (Raylib C)

A simple grid-based brick shooting game built using **C** and **raylib**.  
Control your player, shoot falling bricks, and try to survive as long as possible while increasing your score.

> Created by **@noryx101**

---

## 🎮 Gameplay

- Bricks spawn from the top at random positions
- They move downward in grid steps
- You control a player at the bottom of the screen
- Shoot bullets to destroy incoming bricks
- Game ends if bricks reach the bottom
- Restart anytime using the "Play Again" button

---

## 🕹️ Controls

| Key            | Action        |
|----------------|--------------|
| `A` / `←`      | Move left     |
| `D` / `→`      | Move right    |
| `SPACE`        | Shoot bullet  |
| Mouse Click    | Restart game  |

---

## ✨ Features

- Grid-based movement system
- Random brick spawning
- Bullet collision detection
- Score tracking
- Simple UI (score + restart button)
- Lightweight and easy to understand code

---

## 🧠 How It Works

### Core Systems

- **Bricks**
  - Stored in a fixed-size array (`MAX_BRICKS`)
  - Spawn every second
  - Move downward in steps

- **Bullets**
  - Dynamically allocated using `MemAlloc`
  - Stored as pointers (`Brick*`)
  - Destroyed on collision or when off-screen

- **Player**
  - Moves horizontally on a grid
  - Rendered as a plus-shaped block

- **Collision**
  - Uses `CheckCollisionRecs()` from raylib

---

## ⚙️ Requirements

- raylib installed
- C/C++ compiler (GCC / MinGW / Clang)

---

## 🚀 Build & Run

### ✅ Easiest Way (Recommended)

If you're using an editor like **VS Code** with a configured Makefile:

- Just press **`F5`**
- The project will automatically:
  - Build using the provided Makefile
  - Run the game

---
<img width="1440" height="861" alt="brick_game" src="https://github.com/user-attachments/assets/4c21903c-acae-4c56-a8de-0eadaaf53ac6" />
