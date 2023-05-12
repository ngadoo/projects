# Chess Game using SFML

This is a simple chess game implemented using the SFML library. The game allows two players to play against each other or a player can play against an AI. The AI uses the Minimax algorithm with alpha-beta pruning to determine its moves.

## Requirements

- C++ compiler
- SFML library

## Installation

1. Clone the repository.
2. Install the SFML library.
3. Compile the source code using a C++ compiler.

## Usage

Run the compiled executable file to start the game. The game allows the following options:

- Play against another human player.
- Play against the AI.
- Quit the game.

The game can be played using the mouse to select and move pieces. If a player selects a piece, the game will highlight all the possible moves for that piece. If a move is not valid, the game will display an error message.

## Code Structure

The code is structured using object-oriented programming principles. The `GameManager` class manages the game state and provides methods to handle player moves and the AI. The `QuanCo` struct represents a chess piece and contains its sprite and position on the board. The `Vector2f` class represents a 2D vector used to store positions on the board.

The game uses a 2D array to represent the board state. The pieces are represented by integers with the following values:

- -1: black rook
- -2: black knight
- -3: black bishop
- -4: black queen
- -5: black king
- -6: black pawn
- 0: empty square
- 1: white rook
- 2: white knight
- 3: white bishop
- 4: white queen
- 5: white king
- 6: white pawn

## AI

The AI uses the Minimax algorithm with alpha-beta pruning to determine its moves. The `Alpha_Beta` method recursively searches through the possible moves and returns the best move based on the estimated value of the board state. The `CostMove` method assigns a score to the board state based on the number and type of pieces on the board.

## Future Improvements

- Implement a graphical user interface to allow players to start a new game and select game options.
- Add more options for the AI difficulty.
- Implement a timer for each player's turn.
- Improve the AI algorithm to make it more efficient and effective.
- Add more features such as highlighting check and checkmate.
