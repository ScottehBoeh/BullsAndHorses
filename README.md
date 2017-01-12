# Bulls n' Coo's
School Project/Assessment

Scenario:
A company that produces a website that develops games for casual gamers is expanding its portfolio of games based on traditional “pen and paper” games.
You are part of the project team for this development, and you have been assigned the task of troubleshooting problems reported by the testing department. Issues will be noted on fault report forms and you will have responsibility for troubleshooting and documenting your solution.
To aid you in this task, you have been given a copy of the project brief.
Project Brief:
Bulls and Cows is a traditional “pen and paper” game, played by two players. ( Each player takes turns to pick and guess numbers) 
The first player picks a four digit number ( all four digits must be different ) The second player then attempts to guess this number.
For each guess the second player makes, the first player must give feedback according to the following rules
•	If player two’s guess matches the number picked by player 1 then this constitutes four “bulls”, and this signifies the end of the turn.
•	If player two’s guess matches a number in a column of the player picked by player 1, then each match counts as a “bull”.
•	If player two’s guess contains a number that appears in the number picked by player 1, but is in the incorrect column, each one is reported as a “cow”.
The objective is to guess the opponents chosen number with the minimum number of guesses.
Examples:
Player 1 picks:	1	2	3	4
Player 2 guesses:	5	6	7	8

Feedback: There are no matches in any of the columns, so there are no bulls. There are no matches between numbers in different columns, so there are no cows. – No Bulls, no Cows.

Player 1 picks:	1	2	3	4
Player 2 guesses:	5	6	7	1

Feedback: There are no matches in any of the columns, so there are no bulls. There is one match between numbers in different columns, so there is one cow. ( column one of player one’s pick, and column 4 of player two’s pick.) No Bulls, One Cow.

Player 1 picks:	1	2	3	4
Player 2 guesses:	1	6	7	2

Feedback: There is match in columns ( column one) , so there is one bull. There is one match between numbers in different columns, so there is one cow. ( column two of player one’s pick, and column four of player two’s pick.) One Bull, One Cow.

Player 1 picks:	1	2	3	4
Player 2 guesses:	1	2	4	3

Feedback: There is match in columns ( columns one and two) , so there are two bulls. There are two matches between numbers in different columns, so there are two cows. ( columns three and four of player one’s pick, and columns three and four of player two’s pick.) Two Bulls, Two Cows.
Other information:
The program is to be developed in a number of modules, these include:
•	Computer picks number, player tries to guess number.
•	Player picks number, computer tries to guess number.
•	User interface module.
It is possible for the user to attempt to “cheat” by giving incorrect feedback. As soon as this is detected the program will accuse the player of cheating.

Further Information and sources:
https://en.wikipedia.org/wiki/Bulls_and_Cows
http://www.bullscows.com/
http://slovesnov.users.sourceforge.net/index.php?bullscows,english
https://rosettacode.org/wiki/Bulls_and_cows/Player
