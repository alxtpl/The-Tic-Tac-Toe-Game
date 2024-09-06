# Tic-Tac-Toe Game

## Overview
This is a simple implementation of the classic Tic-Tac-Toe game using React. The game allows two players to take turns and checks for a winner after each move.

## Features
- **Player Turns:** Players alternate between 'X' and 'O'.
- **Winning Detection:** The game checks for a winner based on predefined winning combinations.
- **Game Status:** Displays the current player's turn and the winner.
## Roadmap of Future Improvements

1. **Highlight Winning Combination**
   To improve the user experience, I plan to implement a feature that highlights the winning combination of squares. This will involve updating the `checkForWinner` function to return the winning indices and applying a special CSS class to these squares to visually distinguish them.

2. **Reset Game Functionality**
   Adding a reset button would allow players to start a new game more easily. This feature can be implemented by creating a `resetGame` function in the `Board` component to clear the game state and then adding a button in the `Game` component to trigger this reset function.
