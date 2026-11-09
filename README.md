# 🐍 Raylib C++ Snake Game

A snake related game featuring a line as a black line and the items(collectables) are shads of gray representing coal, lead, charcoal

![C++](https://img.shields.io/badge/Language-C++-blue.svg)
![Raylib](https://img.shields.io/badge/Library-Raylib-red.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)

---

## 🎮 Features

* **Smooth 2D Camera System:** Features a dynamic camera that follows the player smoothly with zoom-in and zoom-out capabilities (using arrow keys and mouse wheel).
* **Dynamic Grid Boundaries:** Play within a massive grid world where hitting the borders results in a game over and resets your progress.
* **Score & Level Tracking:** Collect items to grow longer, increase your score, and advance through levels.
* **Audio Integration:** Custom sound effects for collecting items and hitting boundaries/game over events using Raylib's audio device.
* **Clean Object-Oriented Structure:** Separated into modular classes (`Line` for the snake, `Charcoal` for collectibles, and `Camer` for camera handling).

---

## 🕹️ Controls

| Key | Action |
| :--- | :--- |
| **W / A / S / D** | Move the Snake (Up, Left, Down, Right) |
| **Arrow Keys (Up/Down/Left/Right)** | Move the Camera View manually |
| **Mouse Wheel** | Zoom In / Zoom Out |
| **ESC** | Exit Game |

---

## 📂 Project Structure

```text
├── main.cpp         # Main game loop, window initialization, and core logic
├── Engine.h         # Custom classes for Camera, Snake (Line), Collectibles (Charcoal), and Physics
└── fxsounds/        # Sound effect assets (.wav files for granite and death)
    ├── granite.wav
    └── Line_pop.wav
