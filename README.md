# Chess-GUI
A chess game with a GUI board as well as chess pieces.
By typing in coordinates the chess game is played, and each move is narrated by the program. 

This is an example of how it would work:


///////// TERMINAL VIEW //////////
White's Pawn moves from E2 to E4

 A B C D E F G H
|♖|♘|♗|♕|♔|♗|♘|♖| 8
|♙|♙|♙|♙|♙|♙|♙|♙| 7
| | | | | | | | | 6
| | | | | | | | | 5
| | | | |♟| | | | 4
| | | | | | | | | 3
|♟|♟|♟|♟| |♟|♟|♟| 2
|♜|♞|♝|♛|♚|♝|♞|♜| 1

Please enter a move:



When a player enters a move, for example: black's pawn from D7 to D5, the terminal will update:


///////// TERMINAL VIEW //////////
Black's Pawn moves from D7 to D5

 A B C D E F G H
|♖|♘|♗|♕|♔|♗|♘|♖| 8
|♙|♙|♙| |♙|♙|♙|♙| 7
| | | | | | | | | 6
| | | |♙| | | | | 5
| | | | |♟| | | | 4
| | | | | | | | | 3
|♟|♟|♟|♟| |♟|♟|♟| 2
|♜|♞|♝|♛|♚|♝|♞|♜| 1

Please enter a move:


There are error checks involving all the rules for different pieces, whose turn it is to move, stalemates, checks and checkmates.

