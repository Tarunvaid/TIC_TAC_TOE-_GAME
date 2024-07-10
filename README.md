# Tic Tac Toe Game

Welcome to the Tic Tac Toe game project! This project was developed as part of an internship task at Intern Pe. It is a classic Tic Tac Toe game built using Python and Tkinter, providing a fun and interactive GUI experience. 

## Features

- **Interactive GUI**: A clean and user-friendly interface developed with Tkinter.
- **Square-shaped Buttons**: Ensuring a visually appealing and intuitive layout.
- **Game Logic**: Efficiently handles player turns, win/draw detection, and game flow.
- **End Game Popup**: Displays a popup for wins and draws with a retry option.
- **Menu Options**: Allows restarting the game or exiting through a menu.

## Requirements

- Python 3.x
- Tkinter (usually included with Python installations)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/tic-tac-toe.git
    cd tic-tac-toe
    ```

2. **Run the game**:
    ```bash
    python tictactoe.py
    ```

## Usage

### Starting the Game
Run the `tictactoe.py` script to start the game. A window will pop up with the Tic Tac Toe board.

### Playing the Game
- Click on any cell in the grid to make your move.
- The game will alternate turns between Player X (blue) and Player O (green).
- The game will automatically detect a win or a draw.
- A popup will appear announcing the result and providing an option to play again.

### Menu Options
- **Play Again**: Restarts the game without closing the window.
- **Exit**: Closes the game window.

## Code Overview

### `tictactoe.py`
This file contains the main code for the game.

#### Classes

- **`Player`**: A named tuple to represent each player with a label and a color.
- **`Move`**: A named tuple to represent a move with row, column, and label attributes.
- **`TicTacToeGame`**: Manages the game logic including setting up the board, validating moves, checking for winners, and resetting the game.
- **`TicTacToeBoard`**: Handles the GUI using Tkinter, including creating the menu, display, grid, and handling user interactions.

#### Key Methods

- **`_setup_board`**: Initializes the game board.
- **`_get_winning_combos`**: Computes all possible winning combinations.
- **`is_valid_move`**: Checks if a move is valid.
- **`process_move`**: Processes a move and checks for a win.
- **`has_winner`**: Returns whether there is a winner.
- **`is_tied`**: Returns whether the game is a draw.
- **`toggle_player`**: Switches to the next player.
- **`reset_game`**: Resets the game state.

- **`_create_menu`**: Creates the game menu with options to play again or exit.
- **`_create_board_display`**: Creates the display for showing messages.
- **`_create_board_grid`**: Creates the grid of buttons for the game board.
- **`play`**: Handles a player's move.
- **`_update_button`**: Updates the button text and color based on the player's move.
- **`_update_display`**: Updates the display message.
- **`_highlight_cells`**: Highlights the winning combination.
- **`_show_popup`**: Shows a popup message for win/draw with a retry option.
- **`reset_board`**: Resets the game board.


