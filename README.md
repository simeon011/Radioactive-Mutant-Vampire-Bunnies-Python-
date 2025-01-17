Rules of the Game:

1.Input:
  A grid is given where each cell contains one of the characters "P", "B", or ".".
  A sequence of commands ("U", "D", "L", "R") is provided, dictating the player's movements:
    -"U": Move up.
    -"D": Move down.
    -"L": Move left.
    -"R": Move right.
2.Player Movement:
  The player moves according to the commands.
  If the player moves outside the grid boundaries, they win the game.
3.Bunny Spread:
  After each player movement, the bunnies spread to all adjacent cells (up, down, left, and right).
  Any cell that a bunny spreads to becomes a bunny ("B").
  The spread of bunnies happens simultaneously across all initial bunny positions.
4.Winning or Losing Conditions:
  Winning:
    *The player escapes the grid (moves outside its boundaries).
  Losing:
    *The player moves into a cell occupied by a bunny ("B").
    *The player remains in their position, but a bunny spreads into that cell during the bunny-spreading phase.
Example:
  5 5
.....
.....
.P...
.B...
.....
ULDDR
