# Rules

1. The game will feature a series of levels

2. Each level will feature a grid of the same size
  i. Some tiles will have "pipes" in them
  ii. Two arbitrary tiles of the grid will be labeled "start" and "end" respectively

3. Each pipe will ocupy 1 grid tile
  i. Each pipe can have up to 4 neighbouring pipes (up/down/left/right) with whom a connection *can* be stablished
  ii. Different types of pipes will have different "open" sides, so that not all 4 sides can stablish a connection 
  iii. Pipes can be rotated 360 degrees so that its open sides can change directions
  iv. When a pipe is directly connected with the "start" tile or another active tile, it is considered "active"

3. In order to complete the level, the "start" and "end" tiles must be connected with pipes
  i. In order to progress to the next level, the previous level must have been completed successfully
  ii. Levels can be failed if the solution is not reached within a "time limit"
  iii. Each level will have a different layout and time limit
