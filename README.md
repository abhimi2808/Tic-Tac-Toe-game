This Tic-Tac-Toe game was created using Java. The logic is simple, yet comprehensive enough to cover all game scenarios, including a win, a draw, and valid/invalid moves. Here's a breakdown of the core components:

Game Board Initialization: The game board is a 3x3 grid of characters, initialized with '-' to indicate empty spots. The players are represented by 'X' and 'O'.

Game Flow:

Players take turns choosing their move by inputting the row and column where they want to place their symbol ('X' or 'O').
The board is printed after each move to show the current game state.
Game Logic:

Win Condition: The program checks rows, columns, and diagonals to determine if a player has won.
Draw Condition: It checks if the board is full and there's no winner, in which case the game is declared a draw.
Switching Turns: After every valid move, the current player is switched from 'X' to 'O' or vice versa.

User Interaction: After each game, players are asked whether they want to play again.
