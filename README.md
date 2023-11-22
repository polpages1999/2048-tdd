# 2048 Game
## Project for the _Test & Qualitat del Software_ class.
### 2048 game developed with JavaScript following a TDD implementation.

>2048 is a game where you combine numbered tiles in order to gain a higher numbered tile. In this game you start with two tiles, the lowest possible number available is two. Then you will play by combining the tiles with the same number to have a tile with the sum of the number on the two tiles.
>
>The game of 2048 does not include complicated controls. The controls you’ll be using are just upward, downward, and sideways. The rules are also simple. You just need to move the tiles, and every time you move one, another tile pops up in a random manner anywhere in the box. When two tiles with the same number on them collide with one another as you move them, they will merge into one tile with the sum of the numbers written on them initially.

Developed by:
- Pol Pages   – **1494769**
- Sergi Vila  – **1531267**

<hr />

# Tests implemented
### Equivalent partitions tests
#### Board
1. You should be able to initialize a board with empty cells.
2. When the game starts, typically two tiles are added to the board in random positions. These tiles can either be a 2 or a 4.
3. After a player moves left, the tiles should shift in the direction of the move, combining equal tiles.
4. After a player moves right, the tiles should shift in the direction of the move, combining equal tiles.
5. After a player moves up, the tiles should shift in the direction of the move, combining equal tiles.
6. After a player moves down, the tiles should shift in the direction of the move, combining equal tiles.
7. A test to check if the combining of tiles works correctly. For example, when two '2' tiles combine, they should become one '4' tile.
8. A test to determine if the game correctly identifies when no moves are left, meaning the game is over.
