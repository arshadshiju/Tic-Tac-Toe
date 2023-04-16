# Tic-Tac-Toe
This code shows the implementation of a two-player Tic-Tac-Toe game in Python. It starts by initializing an empty dictionary, `theBoard`, that represents the game board. Then a function called `printBoard` is defined to print the current state of the board.

The `game` function is the main function containing all the game functionality. It starts by initializing variables for the current turn and the number of moves played so far. A loop runs ten times, asking the current player to make a move and checking if the move is valid (i.e., the chosen space is empty). If the move is valid, the space is filled with the current player's symbol (either 'X' or 'O'), and the `count` variable is incremented.

After every move, the function checks if either player has won by checking for three in a row either horizontally, vertically, or diagonally. If a player has won, the game is over, and the winner is declared. If no one wins and all spaces are filled, the game is declared a tie.

Finally, the player is asked if they want to restart the game. If yes, the `theBoard` dictionary is reset, and the `game` function is called again.
