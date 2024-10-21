# Tic-Tac-Toe Game

This is a simple implementation of the Tic-Tac-Toe game in C++. The game is played in a 3x3 grid, where two players (Player 'X' and Player 'O') take turns marking the empty spots on the board. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins the game. If the board is full and no player has won, the game ends in a tie.

## How to Play

1. Player X starts first.
2. The game prompts each player to enter the row and column number where they want to place their mark.
3. The game checks if the move is valid:
   - If valid, the mark is placed on the board.
   - If invalid (e.g., if the cell is already occupied), the game asks for a new input.
4. The game alternates turns between Player X and Player O.
5. The game ends when:
   - A player gets three marks in a row (horizontally, vertically, or diagonally).
   - The board is full, resulting in a tie.

## Game Flow

1. The game starts with an empty board, represented by `#` for empty cells.
2. Players enter their moves by specifying the row and column.
3. The game updates the board after each move and checks if there's a winner or if the game has tied.
4. The winner is announced, or the game declares a tie if no winner exists after 9 moves.



