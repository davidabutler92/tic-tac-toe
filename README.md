# tic-tac-toe
## Goal 

#### The goal of this project is to use everything learned from the previous weeks and include constructors and protoypes along with refactured DRY code.
#### By _**{David Butler}**_

## Description
#### Create a Tic Tac Toe game for two players. 

* A player should know whether it's an X or an O and be able to report that (e.g. player.mark() could return "X" or "O").
* A space should know its coordinates and be able to be marked by a player (e.g., space.mark(player_X)).
* A space should be able to report who it's marked by (e.g. space.markedby() could return "X" or "O", or it could return a player object - _player1 or player2).
* A board should create 9 spaces with the proper coordinates, and tell if there are three in a row marked by the same player. A board should be able to return a space by its coordinates (e.g., board.find(1, 2)).
* A game should create 2 players and a board, be able to move to the next turn, know which player's turn it is, and be able to tell if the game is over or not.


## Example 

* var testPlayer = new Player("X");
testPlayer.mark(); // returns "X"
* var board = new Board();
var testSpace = board.find(1, 2); // board.find(1,2) returns a Space object
* testSpace.xCoordinate(); // returns 1
testSpace.yCoordinate(); // returns 2
* testSpace.mark(testPlayer);
testSpace.markedBy(); // returns testPlayer or "X"
* board.gameOver(); // returns a boolean

### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
| ** 1. The program returns a range of numbers from 0 to the users inputted number | 3 | 0,1,2,3
| ** 2. The program will replace numbers containing 1 with "beep | 5 | 0,beep,2,3,4,5 |
| ** 3. The program will replace the numbers containing 2 with "boop" | 5 | 1,boop,3,4,5 |
| ** 4. The program will replace the numbers container 3 with "wont you be my neighbor?" | 3 | 1,2,wont you be my neighbor?" | 
| ** 5. The program has exceptions, 3 takes priority over 2 and 1 | 13 | wont you be my neighbor? |
  
## Setup/Installation Requirements
* Make a new directory to clone the repo in.
* Clone repository @ [Click here](https://github.com/davidabutler92/tic-tac-toe.git.git)
* Open directory (code .) in terminal.
* To see in gh-pages [Click Here]()  
* 

## Known Bugs 
#### There are no known bugs at the time.

## Support and Contact Details
* davidabutler92@yahoo.com

## Technologies Used 
#### HTML
#### CSS
#### Git 
#### Bootstrap
#### Javascript
#### jQuery 
#### Markdown
#### node.js 

#### Copyright (c) 2020 **_{David Butler}_**
#### The software is licensed under the MIT license [Click here](LICENSE.md)
