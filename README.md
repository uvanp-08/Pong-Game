# Classic Pong Game

Welcome to Classic Pong, a Python implementation of the timeless arcade game. This version of Pong is split across four files to demonstrate a simple modular approach to game development.

## How to Play
- Use the arrow keys or 'W' and 'S' keys to control the paddle on the left.
- Challenge a friend by having them control the paddle on the right with the 'Up' and 'Down' arrow keys.
- Hit the ball with your paddle to keep it in play and try to outmaneuver your opponent to score points.

## Files Overview

### `main.py`
The `main.py` file serves as the entry point for the game. It contains the main game loop where the game initializes, updates, and renders the game objects. It handles user input and collision detection between the ball and the paddles.

### `ball.py`
The `ball.py` file defines the `Ball` class, responsible for creating and updating the game's ball object. It contains methods to move the ball, check for collisions with the walls, and handle bouncing off the paddles.

### `paddle.py`
The `paddle.py` file contains the `Paddle` class, which represents the paddles controlled by the players. It includes methods to move the paddles up and down, as well as collision detection to prevent paddles from moving outside the game area.

### `scoreboard.py`
The `scoreboard.py` file defines the `Scoreboard` class, which manages the scoring system for the game. It keeps track of each player's score and provides methods to update and display the scores on the screen.

## Getting Started
1. Clone this repository to your local machine.
2. Ensure you have Python installed on your system.
3. Open a terminal or command prompt and navigate to the directory containing the game files.
4. Run the `main.py` file using Python: `python main.py`.
5. Enjoy playing Classic Pong!

## Features
- Classic two-player gameplay.
- Intuitive controls that anyone can pick up and play.
- Simple yet engaging graphics and sound effects.

## Dependencies
This project requires Python to run. No additional external dependencies are needed.

## Credits
This project was inspired by the original Pong game created by Atari in 1972. Developed by Yuvashree (myself) as a fun project to recreate the classic arcade experience.

## Feedback
If you have any feedback, suggestions, or bug reports, feel free to open an issue on GitHub or reach out to uvanp05@gmail.com .

Enjoy playing Classic Pong!
