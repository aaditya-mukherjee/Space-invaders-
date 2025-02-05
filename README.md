# Top-Down Shooter Game (Space Invaders-like)

## Game Description
This is a simple top-down shooter game inspired by classic space invaders. The player controls a spaceship that moves horizontally at the bottom of the screen. The objective is to shoot incoming enemies while avoiding enemy bullets.

The game features:
- Player movement (left and right)
- Shooting bullets upwards
- Enemy spawning and movement
- Collision detection between bullets and enemies
- Score tracking
- Game Over when player is hit by an enemy

## Technologies
- **C++**: Main programming language used.
- **SFML (Simple and Fast Multimedia Library)**: A multimedia library used for graphics rendering, input handling, and window management.

## Prerequisites
- A C++ compiler (e.g., GCC, Clang, or MinGW).
- SFML 2.x or later library installed and linked to your project.
- A font file (e.g., Arial.ttf) for displaying the score.

## Installation Guide

### 1. Install SFML
#### On Windows:
- Download SFML from [SFML Downloads](https://www.sfml-dev.org/download.php).
- Follow the [SFML setup guide](https://www.sfml-dev.org/tutorials/2.5/start/) for your IDE/compiler.

#### On Linux:
- Use the package manager to install SFML.
  ```bash
  sudo apt-get install libsfml-dev

git clone https://github.com/your-username/top-down-shooter.git
cd top-down-shooter
Run game by:./shooter
## Features
- **Player Movement**: The spaceship moves left and right along the bottom of the screen.
- **Shooting Mechanism**: Shoot bullets upwards to destroy enemies.
- **Enemy AI**: Enemies spawn at the top, move downwards, and get destroyed when hit by bullets.
- **Collision Detection**: Enemies and bullets collide, and the game ends if the player collides with an enemy.
- **Score Tracking**: The score increases when enemies are destroyed and is displayed in the top left corner.
- **Game Over**: The game ends when the player collides with an enemy.


