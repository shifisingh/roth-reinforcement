## Authors
Alexander Jordan and Shefali Singh, with assistance from Prof. Rory Smead of Northeastern University. 

## Rationale
This project served as a way to implement the insights from the Roth-Erev model of reinforcement learning into an actual model. It was inspired by coursework 
in Ethics and Evolutionary Game Theory, PHIL2001. 

# Notes 
Exceptions to the entering of inputs remain largely unchecked so it is important that numbers are entered in the correct format. 

The error rate and discount rate should be entered as decimals, any level of precision is acceptable.

For the games played, in order to avoid having to wait too long it is best to enter number less than or equal to 100. 

There also must be weights which are associated with each strategy, weights must be entered. Weights are entered in the left most column and topmost row, which can be distinguished by the fact that they are slightly separated from the 4x4 matrix. 

The payoffs must be entered by entering Player 1’s payoff, then a comma, then Player 2 into the 4x4 matrix.  Enter the payoffs using the upper left corners if not a 4x4 matrix, i.e a 2x3 game would use rows 1 and 2 and the leftmost 3 columns. 

The number of rows and columns must be entered as integer values which correspond to the matrix which was inputted.

When there is at least data in the matrix for payoffs and weights, and for the number of rows and columns, then the submit button can be pressed. A heat map based on the probabilities/weights and a slider will load, and the slider can be moved with the mouse to produce heat maps at different iterations of the game. 

If the user wished to input a new game, then the application should be closed and reopened to enter the new parameters. 
