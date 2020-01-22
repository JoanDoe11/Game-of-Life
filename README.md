# Game-of-Life
Parallel solution to Game of Life problem

# Conway's Game of Life
[src=wikipedia]
The Game of Life is a cellular automaton devised by the British mathematician John Horton Convay in 1970.

The game is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the Game of Life by creating an initial configuration and observing how it evolves.

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states - alive or dead (or populated and unpopulated, respectively).
Every cell interacts with its eight neighbours, which are the cells that are horizontally, verticaly or diagonally adjacent.

At each step in time, the following transitions occur:
1.  Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2.  Any live cell with two or three live neighbours lives on to the next generation.
3.  Any live cell with more than three live neighbours becomes a live cell, as if by overpopulation.
4.  Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed; births and deaths occur simultaneously. Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations.

From most random initial patterns of living cells on the grid, observers will find the population constantly changing as the generations tick by. The patterns that emerge from the simple rules may be considered a form of mathematical beauty.


# Python multiprocessing

[src=geeksforgeeks]
Applications in a multiprocessing system are broken to smaller routines that run independently. The operating system allocates these threads to the processors improving performance of the system.
Python's multiprocessing module includes an API for diving work between multiple processes.

# Google Colaboratory

[src=colab.research.google]
Colaboratory is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud.
A notebook is a list of cells. Cells contain either explanatory text or executable code and its output.
