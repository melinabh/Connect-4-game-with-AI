# Connect-4-game-with-AI

a fully working intelligent Connect 4 command line game using Java. The game must allow the user to select the mode of the game. The two modes are:
 2 player (2 human players)
 1 player (Human vs AI)

Connect Four is a two-player connection board game in which players choose a color (Red or Yellow) and then take turns dropping colored discs from the top into a seven-column, six-row vertically suspended grid. The objective is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs.

This logic for the AI must be implemented using the strategy outlined below.
Intelligent AI:
This must be implemented using the Minimax algorithm. The computer must examine the game state at each point and deduce the optimal (best) play that can be made.

The Game operates as follows:
1) The user should be asked if it is a 2 player OR 1 player game (versus AI) 2) If the user selects 1 player (versus minimax AI)
a. TheHumanplayershouldbeaskedtheirname
b. The player must be prompted to choose their symbol (‘R’ or ‘Y’) (R for red, Y for
yellow)
c. The player should be able to choose if the computer will go first or the player will go
 first
d. The present board state will be displayed and:
1. If the computer is to play, it will now show the board updated with the computer’s symbol.
2. If it is the player’s turn, the player will be prompted for a column location to play.
e. The board will then be checked for a winning state or draw and if it is not in a winning state or draw(tie), go to step d otherwise display the winner or declare a draw (tie).
3) If the user selects 2 player (2 Human players)
f. Each human player must be prompted to choose their name and symbol (‘R’ or ‘Y’) (R
for red, Y for yellow)
g. An empty board will then be displayed.
h. The player next to move will be prompted for a column location to play.
i. The present board state will be displayed showing their updated play.
j. The board will then be checked for a winning state or draw and if it is not in a
winning state or draw, go to step h otherwise display the winner or declare a draw.
At the end of a game, the result should be displayed.

