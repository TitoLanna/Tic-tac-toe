
# Tic Tac Toe AI with Pygame

## Overview

This project is a simple implementation of Tic Tac Toe using Python and the Pygame library. The game features a graphical interface and allows players to play against each other. Additionally, there's a restart button to reset the game when it's over.

## Features

- Graphical Tic Tac Toe game using Pygame.
- Player vs. Player gameplay.
- Restart button to reset the game.
- Easy-to-understand code structure.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/TitoLanna/tic-tac-toe-pygame.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd tic-tac-toe-pygame
    ```

3. **Install the required dependencies:**

    You need Python and Pygame installed. If you don't have Pygame, you can install it using pip:

    ```bash
    pip install pygame
    ```

## Usage

1. **Run the game:**

    ```bash
    python tic_tac_toe.py
    ```

2. **Gameplay:**

    - Click on the grid to place your mark (Circle or Cross).
    - The game switches between two players.
    - If a player wins, or the board is full, a "Restart" button will appear.
    - You can also press the 'R' key to restart the game.
## Archieture

![tictactoe drawio](https://github.com/user-attachments/assets/c0290184-dbd1-421c-b972-df198ffac36c)

## Code Explanation

- **Initialization:**
  The game initializes the Pygame library, sets up the screen, and defines the colors, sizes, and initial state of the board.

- **Drawing Functions:**
  `draw_lines()`: Draws the grid lines of the board.
  `draw_restart_button()`: Draws a restart button at the bottom of the screen.
  `draw_figures()`: Draws the current state of the board (Circles and Crosses).

- **Game Logic:**
  - `mark_square()`: Marks a square on the board with the current player's mark.
  - `available_square()`: Checks if a square is available for marking.
  - `is_board_full()`: Checks if the board is full.
  - `check_win()`: Checks if the current player has won the game.
  - `restart_game()`: Resets the game to its initial state.

- **Event Handling:**
  The main game loop handles user input, including mouse clicks and key presses. It updates the game state accordingly and redraws the screen.

  ## Output
  <img width="535" alt="Screen Shot 2024-09-17 at 2 54 24 PM" src="https://github.com/user-attachments/assets/e4c7b5de-56e6-4866-b9b5-22521fa419bb">


## Acknowledgments

- Pygame library for creating the graphical interface.


