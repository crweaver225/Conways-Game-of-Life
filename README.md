## Conways Game of Life

### Built in Rust 

https://github.com/user-attachments/assets/9b7dd07b-0801-4e38-9a3e-0c7605144f0e

#### Description
The rules for Conway's Game of Life are:
Birth: A dead cell becomes alive if it has exactly three live neighbors
Death by isolation: A live cell dies if it has one or fewer live neighbors
Death by overcrowding: A live cell dies if it has four or more live neighbors
Survival: A live cell survives if it has two or three live neighbors 
 Conway's Game of Life – MathCommunities.org

The game is played on a grid of square cells, where each cell is either alive or dead. The cells interact with their eight neighbors, which are the cells that are adjacent to them horizontally, vertically, or diagonally. 
To play, you start by making some dead cells alive. The alive cells then make other cells alive or dead based on the rules.

#### Dependencies
- ggez
