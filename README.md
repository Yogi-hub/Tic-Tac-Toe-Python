# Tic-Tac-Toe Game in Python

This project is a simple command-line Tic-Tac-Toe game implemented in Python. The game allows a human player to compete against an AI opponent.

## Features
- Classic 3x3 Tic-Tac-Toe board.
- Human player plays as 'X', and the computer plays as 'O'.
- AI opponent uses a basic strategy to block the player's winning moves and make optimal choices.
- Displays the board and game instructions clearly.
- Detects wins, losses, and ties.

## Requirements
No additional dependencies are required. The game runs using Python's built-in libraries.

## Usage
Run the script using:

```bash
python tic_tac_toe.py
```

Follow the on-screen instructions to enter your move by selecting a number corresponding to an empty board position.

## How It Works
1. The game starts with an empty 3x3 board.
2. The player chooses a position (1-9) to place 'X'.
3. The AI selects an optimal move based on available spaces.
4. The game continues until a player wins or the board is full.
5. If a player forms a line (row, column, or diagonal) with their symbol, they win.
6. If no more moves are possible and no one has won, the game ends in a tie.

## Example Board Layout
```
 1 | 2 | 3 
---|---|---
 4 | 5 | 6 
---|---|---
 7 | 8 | 9 
```

## Author
D. Yokesh

## License
This project is open-source and available under the MIT License.

