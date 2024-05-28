## Tic-Tac-Toe Game

This Python code implements a simple Tic-Tac-Toe game where a player can play against the computer or another player. The game involves placing X's and O's on a 3x3 grid, aiming to get three in a row horizontally, vertically, or diagonally to win.

### How to Play

1. Run the code and follow the prompts to choose between single-player (against the computer) or multiplayer.
2. If playing against the computer, you will be assigned X and the computer will be O.
3. Enter the position where you want to place your X (1-9) when prompted.
4. The computer will make its move, and the game continues until there is a winner or a draw.
5. The game will display the current state of the board after each move and announce the winner at the end.

### Functions

- **ConstBoard(board)**: Displays the current state of the board.
- **User1Turn(board)**: Handles the user's turn in single-player mode.
- **minmax(board, player)**: Implements the minimax algorithm for the computer's move.
- **CompTurn(board)**: Handles the computer's turn in single-player mode.
- **analyzeboard(board)**: Analyzes the board to check for a winning condition.
- **main()**: Main function to run the game, handle player choices, and game flow.

### Features

- Single-player mode against a computer opponent.
- Multiplayer mode for two players.
- Intelligent computer moves using the minimax algorithm.
- Clear board display and win/draw announcements.

### How to Run

1. Copy the code into a Python file, for example, `tic_tac_toe.py`.
2. Run the Python script in your terminal or command prompt.
3. Follow the on-screen instructions to play the game.

### Enjoy the Game!

Have fun playing this classic Tic-Tac-Toe game either against the computer or with a friend. Test your strategic skills and aim to outsmart your opponent to claim victory!
