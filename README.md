# Snake Game

This is a simple implementation of the classic Snake game using Python and the Pygame library.

## Prerequisites

- Python 3.x
- Pygame library

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Idhant-Mehta/snake-game.git
   cd snake-game
ou can install Pygame using pip:

sh
Copy code
pip install pygame
How to Play
Run the game:

sh
Copy code
python snake_game.py
Controls:

Use the arrow keys to move the snake:
Left arrow key to move left
Right arrow key to move right
Up arrow key to move up
Down arrow key to move down
Objective:

The objective of the game is to eat the green food squares.
Each time the snake eats food, it grows in length, and the score increases.
Avoid hitting the walls or the snake's own body.
Code Explanation
The main code is contained in the snake_game.py file. Here's a brief overview of the main components:

Colors and Display Settings: Defines colors and sets the display dimensions and caption.
Clock: Initializes the clock object to control the speed of the snake.
Font Styles: Sets font styles for displaying text.
Functions:
our_snake: Draws the snake on the display.
your_score: Displays the score on the screen.
message: Displays a message on the screen.
Game Loop: Main loop where the game logic is executed:
Checks for game over and game close conditions.
Handles keyboard inputs for controlling the snake.
Updates the position of the snake and checks for collisions.
Updates the display and controls the frame rate.
