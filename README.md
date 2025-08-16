> Minesweeper Game in Java

This is a simple implementation of the classic Minesweeper game using Java.  
The game runs in the console and allows players to uncover cells, avoid hidden mines, and win by revealing all safe spaces.

> Features
- Text-based interface (console)
- Random mine placement
- Recursive reveal of empty cells
- Win/loss detection
- Customizable board size and difficulty (optional)

> How It Works
- The board is represented using a 2D array.
- Mines are placed randomly at the start of the game.
- The player selects cells by entering coordinates.
- If a mine is uncovered, the game ends.
- If the player reveals all non-mine cells, they win.

> How to Run
1. Clone the repository or download the source code.
2. Compile the game:
   ```bash
   javac Minesweeper.java
