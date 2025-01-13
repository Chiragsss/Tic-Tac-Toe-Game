# Tic-Tac-Toe-Game
This is a simple graphical implementation of the classic Tic-Tac-Toe game using Python and the Tkinter library. The game allows two players to take turns marking spaces in a 3x3 grid until one player wins or the game ends in a tie.

Features

Graphical Interface: Uses Tkinter to provide an interactive game board.

Two-Player Mode: Allows two players to play the game alternately.

Score Tracking: Tracks and displays the score for Player 1 (X), Player 2 (O), and ties.

Restart Option: Automatically resets the board for a new game after a match concludes.

Game Over Display: Declares the winner or announces a tie at the end of the game.

Prerequisites

Python 3.x

NumPy library

How to Run

Ensure you have Python 3 installed on your system.

Install the NumPy library if you don’t already have it:

pip install numpy

Copy the provided code into a Python file, e.g., tic_tac_toe.py.

Run the file using the command:

python tic_tac_toe.py

The game window will open, and you can start playing.

Game Rules

The game board consists of a 3x3 grid.

Player 1 (X) and Player 2 (O) take turns clicking on an empty grid cell to mark it with their symbol.

The first player to align three of their symbols horizontally, vertically, or diagonally wins the game.

If all cells are filled without a winner, the game ends in a tie.

Controls

Left Mouse Click: Place your mark (X or O) on the desired cell.

Click Anywhere After Game Over: Start a new game.

Code Breakdown

Main Components

Game Initialization:

Creates the game window and initializes variables for board state, scores, and player turns.

Board Drawing:

Uses the Canvas widget to draw the game board and symbols (X and O).

Game Logic:

Checks for winners, ties, and occupied cells.

Converts grid positions to pixel positions and vice versa.

Event Handling:

Captures mouse clicks to mark cells and restart the game.

Game Over Display:

Shows the winner or announces a tie, along with the updated scores.

Customization

Board Size: Adjust the size_of_board variable to change the dimensions of the board.

Symbol Colors: Modify symbol_X_color and symbol_O_color for different X and O colors.

Line Thickness: Change symbol_thickness for different symbol thickness.

Acknowledgments

This implementation uses the Tkinter library for GUI creation and NumPy for board state management. It’s a great starting point for learning about event-driven programming and game development in Python.

