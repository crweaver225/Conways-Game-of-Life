## Conways Game of Life

### Built in Rust 

#### Description
The rules for Conway's Game of Life are:
- Birth: A dead cell becomes alive if it has exactly three live neighbors
- Death by isolation: A live cell dies if it has one or fewer live neighbors
- Death by overcrowding: A live cell dies if it has four or more live neighbors
- Survival: A live cell survives if it has two or three live neighbors 

The game is played on a grid of square cells, where each cell is either alive or dead. The cells interact with their eight neighbors, which are the cells that are adjacent to them horizontally, vertically, or diagonally. 

To play, you start by clicking on dead (empty) cells to make them alive (black). When the grid is to your liking, click the space bar to start or pause the game. Clicking the up arrow on your keyboard will speed up the game. Clicking the down arrow on your keyboad will slow down the game. 

https://github.com/user-attachments/assets/9b7dd07b-0801-4e38-9a3e-0c7605144f0e

#### Dependencies
- ggez
