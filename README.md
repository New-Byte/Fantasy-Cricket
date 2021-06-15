# Fantasy-Cricket
Fantasy Cricket game using python
Fantasy Cricket Game GUI using Python(PyQt5) and sqlite3 is an online game where we can create a virtual cricket Team of Real Cricket Players.

Programming Language Used: Python

Database: MySql

Fantasy Cricket Game is a game where we can create a virtual cricket team of real cricket players. Each player has their own Points. There will be a limited no. of points to select 11 players, if we don't have enough points we can't select a player if his points are more and the team is evaluated using points of each player based on their performance internally. To win a tournament, we must try and get the maximum points and the No. 1 rank amongst other participants.

The team is evaluated using these rules for each Player:

Batting: 1 point for 2 runs scored, Additional 5 Points for half Century, Additional 10 points for a century, 2 points for strike rate (runs/balls faced) of 80 - 100, Additional 4 points for strike rate>100, 1 point for hitting a boundary (four) and 2 points for over boundary(six).

Bowling: 10 points for each wicket, Additional 5 points for 3 wickets/innings, additional 10 points for 5 or more wickets in innings, 4 points for econiomy rate (runs given per over) between 3.5 and 4.5, 7 points for economy rate between 2 nd 3.5, 10 points for economy rate less than 2.

Fielding: 10 points each for catch/stumping/run out.

You can check the DataBase created for this Game named Fantasycricket.db.

To execute this program, we need to install PyQt5 which is a Python GUI Library.
And that's, we are all set to run this program.

If we want to make changes in the "evaluate teams" which is present in the evaluation module, we can change manually by just editing the code, but the edited code will not reflect back to the main GUI. To execute the edited "evaluate teams" code, we need to install the evaluation module.
