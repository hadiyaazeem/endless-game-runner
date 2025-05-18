# Endless-Runner-Game
A console-based endless runner game in C++ with player movement, obstacles, coins, and a chasing enemy.
---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Controls](#controls)
- [Gameplay Mechanics](#gameplay-mechanics)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Files](#files)
- [High Scores](#high-scores)
- [Author](#author)
- [License](#license)
- [ScreenShots](#ScreenShots)

---

## Overview

This game runs in the Windows console and simulates an endless runner where the player must avoid obstacles (X), collect coins ($), and survive enemy (E) attacks. The game uses simple ASCII graphics, colored text, and real-time keyboard input to create an interactive experience.

---

## Features

- *Player Movement:* Move left, right, jump, and slide.
- *Obstacles & Coins:* Randomly spawn as the map scrolls.
- *Enemy:* Activates after a certain distance and chases the player.
- *Lives System:* Player starts with 3 lives, lose lives on collisions.
- *Score & Distance Tracking:* Collect coins and track distance traveled.
- *High Scores:* Saves player names and scores to file.
- *Instructions & Menu:* Interactive menu with instructions and high score display.

---

## Controls

| Key           | Action         |
|---------------|----------------|
| Left Arrow    | Move Left      |
| Right Arrow   | Move Right     |
| Up Arrow      | Jump           |
| Down Arrow    | Slide          |
| Enter         | Select in menu |

---

## Gameplay Mechanics

- The player character is represented by an ASCII figure.
- The map scrolls downward to simulate forward movement.
- Obstacles (X) and coins ($) randomly spawn on the top row.
- The player can jump to avoid obstacles or slide under them.
- After traveling a certain distance (2000m), an enemy (E) appears and chases the player.
- Collisions with obstacles or the enemy reduce lives.
- Collecting coins increases score.
- The game ends when the player loses all lives.

---

## Installation

1. Make sure you are on a Windows machine (requires Windows console for color and cursor control).
2. Have a C++ compiler installed (e.g., MinGW, Visual Studio).
3. Copy the source code into a .cpp file (e.g., EndlessRunner.cpp).
4. Compile the code using your compiler:
   ```sh
   g++ EndlessRunner.cpp -o EndlessRunner.exe
---

## Screenshots

You can view the game screenshots here: [View Screenshots](https://docs.google.com/document/d/e/2PACX-1vTxTqeH3RsKZkVMOb341TIOhIMF-n7QaAurlfvxyLQDnPVAHXRUpi9ZScaemVZG7D-ltFe435jwsLw0/pub)
