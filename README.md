# 2048 Game

## Project for the _Test & Qualitat del Software_ class.

### 2048 game developed with JavaScript following a TDD implementation.

>2048 is a game where you combine numbered tiles in order to gain a higher numbered tile. In this game you start with two tiles, the lowest possible number available is two. Then you will play by combining the tiles with the same number to have a tile with the sum of the number on the two tiles.
>
>The game of 2048 does not include complicated controls. The controls you’ll be using are just upward, downward, and sideways. The rules are also simple. You just need to move the tiles, and every time you move one, another tile pops up in a random manner anywhere in the box. When two tiles with the same number on them collide with one another as you move them, they will merge into one tile with the sum of the numbers written on them initially.

Developed by:
- Pol Pages   – **1494769**
- Sergi Vila  – **1531267**

### Basic functionality tests
#### 1. Grid
- You should be able to initialize a grid with empty cells.
- You should be able to group cells by rows and columns.
- You should be able to identify a random empty cell.
#### 2. Tile
- You must be able to initialize a token with a value.
- You must be able to change the value of a token.
#### 3. Game
- You must be able to move pieces in all four directions.
- You must be able to verify if a movement is valid.