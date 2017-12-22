# p5js-Chess

Chess game by GreedyCoding using the p5js library


## Current Features
 - Rendering the Gameboard.
 - Creating all the Chesspieces using inheritance.
 - Following logic is working for the Game:
    - Pawns Rooks and Knights can fully move across the board


## Current Bugs
  - Highlights dont seem to work at all with most pieces.
  - Knights moves are not right when they are placed in a corner.

### Changelog 0.0.3
  Additions:
  - Added interactive Centering for the Chessboard and the buttons
  - Added Page Background
  - Added Button to restart the game.
  - Added function restartGame().
  - Added Touch Support.

  Removed:
  - Removed some useless comments.
  - Removed some calculations in the Cell functions with an addation of a new Variable.
  - Removed part of function setStartPos() that had no use.

### Changelog 0.0.2
  Additions:
  - Added movement of the Rooks and Knights.
  - Changed inheritance so the white pieces are getting their movement from their black counterparts.



### Changelog 0.0.1
  Additions:
  - Added function unsetHighlights();
  - Changed the function highlights() to loop through moves[] instead of the nested Array;
  - Fixed function move() from PawnB Object and added function unsetHighlights() to move();
  - Added loop for pawns to function setStartPos();

  Fixed Bugs:
  - Cell where the first pawn moved to gets highlighted;
  - After Moving the first Pawn all Pawns are only able to move 1 spot.
