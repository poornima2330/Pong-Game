# Pong in Ebitengine

This is a simple implementation of the classic Pong game using the Ebiten game library in Go. The game features a paddle and a ball, with basic collision detection and scoring.

## Features

- Paddle controlled with the arrow keys.
- Ball movement with collision detection for walls and paddle.
- Score tracking with a high score feature.
- Simple graphics using the Ebitengine library.

## Requirements

- Go 1.18 or higher
- Ebiten v2

## Game Controls

- **Up Arrow**: Move the paddle up.
- **Down Arrow**: Move the paddle down.

## Code Overview

- `main.go`: The main entry point for the game. It initializes the game and runs the game loop.
- `Object`: A struct representing a generic game object with position and size.
- `Paddle`: A struct extending `Object` that represents the player's paddle.
- `Ball`: A struct extending `Object` that represents the ball, including its velocity.
- `Game`: The main game struct that manages the game state, including the paddle, ball, score, and collision detection.
- `MoveOnKeyPress`: Handles paddle movement based on key presses.
- `Move`: Updates the ball's position based on its velocity.
- `Reset`: Resets the ball's position and score.
- `CollideWithWall`: Handles collision detection between the ball and the screen boundaries.
- `CollideWithPaddle`: Handles collision detection between the ball and the paddle.

## Overview 
![image](https://github.com/user-attachments/assets/3f7453f7-b973-4fb5-acf4-80de17683ad5)
![image](https://github.com/user-attachments/assets/21e1177c-a0fb-4109-bbaf-4c05bbba991a)
![image](https://github.com/user-attachments/assets/4ddbaf11-b027-4986-a3cb-7e1cc254621b)


## Acknowledgments

- The Ebiten game library: [https://ebiten.org/](https://ebiten.org/)
