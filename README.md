# 🐍 Snake Game (Rust)

## 📖 Project Overview

This project is a classic **Snake Game** developed in **Rust**, demonstrating the use of Rust for game development. The objective of the game is to control the snake, collect food to increase its length, and survive as long as possible without colliding with the walls or the snake's own body.

The project showcases fundamental game development concepts such as game loops, collision detection, input handling, rendering, and score management while leveraging Rust's performance and memory safety.

---

## 📂 Project Structure

```text
snake-game/
├── src/                 # Source code
│   ├── main.rs          # Entry point of the application
│   ├── game.rs          # Core game logic
│   ├── snake.rs         # Snake movement and behavior
│   ├── food.rs          # Food generation
│   └── ...              # Additional modules
├── assets/              # Images, fonts, or game resources (if any)
├── Cargo.toml           # Project dependencies and metadata
├── Cargo.lock           # Dependency lock file
├── README.md            # Project documentation
└── target/              # Compiled build files (generated automatically)
```

> **Note:** The exact files may vary depending on the project implementation.

---

## ✨ Features

* Classic Snake gameplay
* Smooth snake movement
* Random food spawning
* Real-time score tracking
* Collision detection with walls and snake body
* Increasing difficulty as the snake grows
* Fast and efficient implementation using Rust

---

## 🛠 Requirements

Before running the project, ensure the following are installed:

* Rust (latest stable version)
* Cargo (comes with Rust)

To verify installation:

```bash
rustc --version
cargo --version
```

Install Rust from:

https://www.rust-lang.org/tools/install

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/snake-game.git
```

### 2. Navigate to the project directory

```bash
cd snake-game
```

### 3. Build the project

```bash
cargo build
```

### 4. Run the game

```bash
cargo run
```

---

## 🎮 Controls

| Key | Action                   |
| --- | ------------------------ |
| ↑   | Move Up                  |
| ↓   | Move Down                |
| ←   | Move Left                |
| →   | Move Right               |
| Esc | Exit Game (if supported) |

---

## 🎥 Demo

## 🎮 Demo

Gameplay Video: [Watch the gameplay](demo/gameplay.mp4)
---

## 🚀 Future Enhancements

Some planned improvements include:

* High score saving
* Pause and resume functionality
* Multiple difficulty levels
* Sound effects and background music
* Improved graphics and animations
* Power-ups and special food
* Main menu and game settings
* Mobile or web support

---

## ⚠ Known Issues / Limitations

* No persistent high-score storage.
* Game ends immediately upon collision.
* Difficulty progression is limited.
* Window resizing may not be supported.
* Limited visual effects and animations.

---

## 📚 Technologies Used

* **Rust**
* **Cargo**
* Rust game development libraries (as specified in `Cargo.toml`)

---
## 📄 License

This project is intended for educational and learning purposes. 
