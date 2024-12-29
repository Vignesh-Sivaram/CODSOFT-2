# 3x3 TIC-TAC-TOE (XO) game

### Game representation

* This project demonstrates the working of 3 x 3 Tic Tac Toe game, where a user can either choose to play with other user or with the computer (AI) itself.
  
* Computer, which acts as AI player, uses Minmax algorithm defined in a function of program, and makes best possible decisions on placing its O versus the user's X.

* The input position where we can place X, is given by numbers 1-9.

* When chosen to play with Computer (AI), the algorithm determines the best position to place O versus the user such that it is unbeatable or ends in Draw.

### Minmax algorithm function

* The Minimax function recursively evaluates all possible moves.
  
* It assigns a score to each move based on the game's outcome (Win, Loss, Draw).

* The function maximizes the score for the AI player and minimizes it for the opponent.
