# TIC TAC TOE GAME
 A tic tac toe game for two players
First off, make sure you understand the project scope. What needs to happen?



We need to print a board.

Take in player input.

Place their input on the board.

Check if the game is won,tied, lost, or ongoing.

Repeat c and d until the game has been won or tied.

Ask if players want to play again.

Ok so we got a general idea of what we need to do. Let's break it down by steps.
USEFUL PROJECT HINTS:



Started by deciding how to will store the player's marker positions (Xs and Os).I choose a list, where each index corresponds with a number on a keypad, which in turn corresponds with a position on the 3 by 3 board.

Created a list called board which will keep track of the player markers.

The list should already be the same length as your intended board.

Created a function that will print a board. Not just the list, but an actual representation of a board! This can be done with multiple print statements within the function. Thought about how to take elements from the list and print them out into the board. (can also be cleared output in jupyter notebook with clear_output() . I needed to import this, so at the top of a cell i copied and pasted: from IPython.display import clear_output

Wrote a function which takes an input marker string 'X' or "O' and a given number and stores it to a list at that appendix.


Wrote a function that takes in the board and a player marker and checks it theres a win or a tie.

The checking for a win should be a series of a bunch checks, for example: (board[7] == board[8] == board[9] == marker)would check the first top row if they all match a player's marker.

Checked for a tie (this means nobody won and the board list is full!)

Finaly begun writing functions that begin game play.

Wrote a function which starts combining and calling the different functions i made within it.

For example, a function which asks for a player's move, then updates the board,then checks for a win, then prints out the board.

Kept the game continually going using a while loop.

Something like, while the board isn't full and nobody's won...

Alright now i had enough now to begin piecing things together!

