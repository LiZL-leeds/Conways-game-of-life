# Conways-game-of-life


Conway's set of rules are summarised as:
1. Any live cell with 0 or 1 live neighbours becomes dead because of underpopulation
2. Any live cell with 2 or 3 live neighbours stays alive because its neighbourhood is just right
3. Any live cell with more than 3 live neighbours becomes dead because of overpopulation
4. Any dead cell with exactly 3 live neighbours becomes alive by reproduction


In this game, the death of the cell is defined as 0 and the living cells are defined as 1.

This game provides the users with two kinds of models including the user-defined model and the file model.
For both models, the user should set the number of cells for the width and height of the whole map.
Besides, the number of steps should also be set by users at the beginning.

Then the game will start with the initial state and change the state of each cell according to the rules of the Coneay's Game of Life until the number of loops is equal to the number of steps.

The final state will be written into an text file.

