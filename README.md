# tic-tac-toe-in-python
# Tic Tac Toe (Terminal Version)

A simple command-line Tic Tac Toe game in Python, where two players (X and O) take turns choosing their moves until someone wins or the game ends.

## Description

This Python program allows two users to play the classic **Tic Tac Toe** game in the terminal. The board is displayed after every move, and the program checks for a winner after each turn.

## Features

* Command-line interface
* Two-player support (X and O)
* Board updates after every move
* Win checking after every move
* Easy-to-understand code structure

## Game Logic

* The game board is represented as two lists: `xState` and `zState` for player X and O respectively.
* A position from 0 to 8 is chosen by the player to mark their move.
* The game checks for 8 possible winning combinations after every move.
* If a player wins, the game announces the winner and exits.

## How to Run

1. Make sure you have Python installed.
2. Clone the repository or copy the code into a `.py` file (e.g., `tic_tac_toe.py`)
3. Run the script:

```bash
python tic_tac_toe.py
```

## 🎮 Sample Gameplay

```
Welcome to Tic Tac Toe
0 | 1 | 2 
--|---|---
3 | 4 | 5 
--|---|---
6 | 7 | 8 
X's Chance
Please enter a value: 0
O's Chance
Please enter a value: 4
...
X Won the match
Match over
```

## Code Structure

* `sum(a, b, c)`: Utility function to add three values.
* `printBoard(xState, zState)`: Displays the current board with X and O.
* `checkWin(xState, zState)`: Checks if any player has won.
* `main()`: Game loop that controls turns and game flow.

## Requirements

* Python 3.x

## Contributing

Feel free to fork this repository and improve the game with features like:

* Draw detection
* Single-player mode (AI)
* GUI version

## License

This project is open-source and free to use.

