# Tic_Tac_Toe_Game

# Tic Tac Toe Game

This project implements a Tic Tac Toe game in Python without a graphical user interface (GUI). The game is played on the command line, where players enter their moves as text inputs. The project focuses on implementing the game logic using Python's built-in data structures and control flow statements.

## Game Rules

- The game is played on a 3x3 grid.
- Two players participate, one playing as "X" and the other as "O".
- Players take turns placing their symbol on an empty square of the grid.
- The objective is to get three of your symbols in a row, either horizontally, vertically, or diagonally.
- The game ends when one player achieves three in a row or the grid is full without a winner, resulting in a tie.

## Project Structure

The project consists of the following components:

- `main.py`: The main Python script that runs the Tic Tac Toe game.
- `README.md`: This readme file, providing an overview of the project and instructions for running the game.

## Getting Started

To play the Tic Tac Toe game, follow these steps:

1. Ensure you have Python 3 installed on your machine.

1. Download or clone the project repository to your local machine.

1. Open a terminal or command prompt and navigate to the project directory.

1. Run the following command to start the game:

   ````
   python main.py
   ```

   ````

1. The game will begin, and you will see the empty game board displayed. Players will take turns entering their moves.

1. When prompted, enter the row and column numbers (0-2) for your move. The row and column indices start from 0.

1. The game will continue until one player wins or the game ends in a tie. The final game board and the result will be displayed.

1. After the game ends, you can choose to play again by running the script again.

## Project Components

### `main.py`

The `main.py` script contains the implementation of the Tic Tac Toe game. It includes the following functions:

- `print_board(board)`: Prints the current game board to the console.

- `player_move(board, player)`: Handles a player's move by prompting them to enter the row and column numbers for their move. Updates the game board with the player's symbol if the move is valid.

- `check_win(board, player)`: Checks if the current player has won the game by examining the rows, columns, and diagonals of the board.

- `check_tie(board)`: Checks if the game has ended in a tie by verifying if all squares on the board are filled.

- The main game loop: Alternates between the two players, displaying the game board, handling player moves, and checking for a win or tie. The loop continues until the game has been won or tied.

## Conclusion

The Tic Tac Toe game project provides an interactive and enjoyable gaming experience on the command line. It demonstrates the use of basic Python concepts, such as lists, loops, conditionals, and functions, to implement a simple game logic. Feel free to explore and modify the code to enhance the game or add additional features.

Enjoy playing Tic Tac Toe!
