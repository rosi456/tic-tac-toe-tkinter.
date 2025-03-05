# tic-tac-toe-tkinter.
This repository contains a simple Tic Tac Toe game implemented using Python and the Tkinter library. The game features a graphical user interface where two players can take turns to play as "X" and "O". The game checks for win conditions and handles draws, providing feedback to the players through message boxes. The board resets automatically after a win or draw, allowing for continuous play.
Features
Two-player mode (X and O)
Graphical user interface using Tkinter
Automatic win and draw detection
Game board resets after each game
Code Overview
Main Components
Global Variables:

player: Tracks the current player ("X" or "O").
board: Represents the 3x3 game board as a list.
buttons: Holds the button widgets for the game board.
Functions:

check_winner(): Checks for a win or draw condition.
button_click(index): Handles button clicks, updates the board, and checks for a winner or draw.
reset_game(): Resets the game board and player to the initial state.
UI Setup:

Initializes the main window with a 3x3 grid of buttons.
