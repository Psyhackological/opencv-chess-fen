# opencv-chess-fen
Detect Lichess pieces using OpenCV and template matching!

## Board

* Resolution: 720x720
* 1 square = 720/8 = 90

## Pieces

* Width: each piece is different
* Height: +- the same

How to be consistent? Well they're. PNG alpha keeps the offsets so after exporting to 90x90 pixels it's almost pixel perfect match to the board.
