# Tic-Tac-Toe Game

## Overview

This is a **Tic-Tac-Toe game** developed as my first project in my **first year** of Computer Science Engineering at Chitkara University. It’s a simple two-player game that lets players take turns to play as 'X' or 'O'. The game checks for a winner after every turn and displays the current state of the game board.

## Features

- **Two-player gameplay**: Players take turns to play as 'X' or 'O'.
- **Dynamic Board Display**: The game board is displayed after every move, showing the updated status.
- **Winner Detection**: The game checks for winning combinations after every move and announces the winner.
- **Simple Input/Output**: Players input their chosen position on the board by entering a number corresponding to the cell (0-8).

## Game Flow

1. Players are alternately prompted to enter a position (from 0 to 8) to place their mark ('X' or 'O') on the board.
2. The game board is displayed after each move.
3. The program checks for a winning combination after each move.
4. The game ends when either 'X' or 'O' wins, or the board is full.

## How to Play

- The game board is represented by a 3x3 grid, numbered from 0 to 8 as shown below:

  ```
  0 | 1 | 2
  --|---|---
  3 | 4 | 5
  --|---|---
  6 | 7 | 8
  ```

- Players enter the number corresponding to the cell where they want to place their mark.
- The game alternates between players with 'X' going first.
- The game will announce when a player wins or if the game ends in a draw.

## Sample Output

```
welcome to the game!! Anmol
TURN - X
enter a value: 4
0 |1 |2
--|---|---
3 |X |5
--|---|---
6 |7 |8
TURN - O
Please enter a value: 0
X |1 |2
--|---|---
O |X |5
--|---|---
6 |7 |8
...
X WON THE GAME
Match over
```

## Technologies Used

- Python

## Future Improvements

- Add a feature for handling invalid inputs.
- Implement a GUI for a more user-friendly experience.
- Enhance the game to handle multiple rounds and show score tracking.

---
