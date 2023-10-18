# nycu-ai-final-project
Final Project for Artificial Intelligence course at National Yang Ming Chiao Tung University, Taiwan

The project consists of a two players game, played on a 3x3 matrix initialized with random integers from 50 to 100, 
every turn the player can subtract 1, 2 or 3 to a choosen row or column.

Rules:
-You can't subtract from a row or column containg a 0
-the game ends when one of the two player hits a row, column or diagonal full of zeros or when there is a situation
 in which you cannot legally choose a move.


every move has a cost, at the end of the game the player who creates a row, column or diagonal full of zeros gets
a bonus, if you enter a situation where you cannot choose a legal move you get a malus, the winner is the player 
that 'spent' less during the whole game.

You have to implement both game and algorithm to use to win the game, bonus if you implement a best-first search
algorithm.
