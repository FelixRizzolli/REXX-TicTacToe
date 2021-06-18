# REXX-TicTacToe
TicTacToe is a paper-and-pencil Game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a diagonal, horizontal, or vertical row is the winner. It is a solved game with a forced draw assuming best play from both players.

## Gameplay
### Theory
In order to win the game, a player must place three of their marks in a horizontal, vertical, or diagonal row.
More on [Wikipedia](https://en.wikipedia.org/wiki/Tic-tac-toe)

### REXX UI for TicTacToe
The playing field looks like this:
```
   EMPTY         X-WON         O-WON         DRAW
   !   !       X ! O !       X !   ! O     X ! O ! X
-----------   -----------   -----------   -----------
   !   !       O ! X !       X ! O ! X     X ! O ! X
-----------   -----------   -----------   -----------
   !   !       O ! X ! X     O ! X ! O     O ! X ! O
```
The player in turn must enter the coordinates on which he wants to place his mark as follows:
```
XSY
```
`X` = X coordinate = 1, 2 or 3

`S` = separator = one character

`Y` = Y coordinate = 1, 2 or 3

## Roadmap
### v1.0
 - [X] README file with game description
 - [ ] Game with basic features
   - [ ] The playing field is displayed in the console
   - [ ] The player whose turn it is is asked to set his character
   - [ ] The game displays whether a player has won and which player has won or if it is a draw.

#### v1.1
 - [ ] After a game the player is asked if he wants to play another game.

#### v1.2
 - [ ] Players can choose their character
 - [ ] Players can choose which player starts.

#### v1.3
 - [ ] The players play blind. If a player has placed a character on the board, an X is displayed. Where which player has placed his character has to be remembered by each player. This increases the difficulty and possibly the fun of the game.

### v2.0
 - [ ] Player vs. bot

### v3.0-zos
 - [ ] GUI for zOS

### v3.0-windows
 - [ ] GUI for Windows

### v3.0-linux
 - [ ] GUI for Linux

### v3.0-macos
 - [ ] GUI for macOS