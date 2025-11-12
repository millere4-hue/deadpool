# deadpool
tic_tac_toe/
│
├── main.py          # Runs the game
├── functions.py     # Contains game logic functions
└── README.md        # Project documentation
:rocket: How to Run
Clone or download this repository.
Open a terminal in the project folder.
Run the game using:
:jigsaw: Game Rules
The board is a 3×3 grid.
Player X always goes first.
Players take turns entering a row and column number (0–2) to place their mark.
The first player to align three marks in a row, column, or diagonal wins.
If all spaces are filled without a winner, the game ends in a draw.
:brain: Code Overview
functions.py
Contains helper functions for:
Displaying the board (print_board)
Checking for a winner (check_winner)
Making valid moves (make_move)
Checking if the board is full (is_full)
main.py
Handles:
Game setup
Turn-taking between players
User input and game loop
:toolbox: Requirements
Python 3.7 or higher
(No external libraries required)
:checkered_flag: Example Gameplay
 |   |
-----
 |   |
-----
 |   |
Player X's turn.
Enter row (0-2): 0
Enter column (0-2): 0
X |   |
-----
 |   |
-----
 |   |
:bulb: Future Improvements
Add a simple AI opponent
Add input validation and replay option
Create a graphical (GUI) version using tkinter