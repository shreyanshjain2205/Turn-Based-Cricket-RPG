# Turn-Based-Cricket-RPG
The game partly works on a Random Number
Generator.
The user starts the game by entering cricket()
in Python Shell. The user then is asked to
input how many overs they wish to play the
game of (variable: x).
Player 1 is then asked to input their name.
Variable x is sent to inning() function, in which
the main frame of the game lies.
The list of pre-made teams is printed (from
key values of dictionary teams), and the user
is asked to input their team name. If the
entered team name is not from the printed
list, then a custom team is created, and the
user is asked to input player names using a
for loop.
Then the batting inning begins, using a for
loop for each over and a nested while loop for
each ball. A random integer between 0 and
2000 is generated.
The user is then asked to input (8/9/0), 8 for
attack shot, 9 for defense shot and 0 for loft
shot. Using nested if-elif-else clauses, the
command (8/9/0) chosen, the random
number (a) generated, and some modifier for
player number (adaption of the fact that
lower down the batting list, the players are
not as good batsman as the first few
batsmen), outcome of the ball is decided.
Using if-elif-else clauses, if the batman is out,
then the batsman is dismissed and the next
batsman on the team list is brought to play. If
the outcome is runs, then the runs scored are
added. If 1 or 3 runs are scored, like in real
cricket, the two batmen on the field are
swapped.
When all overs are completed, or 10 batsmen
have been dismissed, the play part for player
1 is over, the final score and scores of all 11
batsmen are displayed.
The final score is returned to cricket().
Player 2 is asked to input their name and this
time, the final score of player 1 is also sent to
inning().
The play for player 2 is the same as player 1,
except this time, if player 2 crosses the final
score of player 1 during the match, the match
is over, and player 2 wins. If player 2 fails to
do so, player 1 wins the game.
The name of the winner is then displayed.

VALIDATION AND CHECKS
I have made many validations and checks to the
project:
When asking for a team name, if the name the user
enters is not in the given list of teams, the user creates
a custom team with that name and is the program
proceeds to ask names of the 11 players from the user.
When asking the user for the command, if the
command is not from (8/9/0), the program repeatedly
asks the user for a command until the command is
from (8/9/0)
