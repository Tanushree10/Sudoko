Sudoku

A Python module to solve the standard 9 by 9 Sudoku puzzle.
This Python module can solve even 'hard' sudoku problems almost instantly. It takes
longer to input the board, then it does to solve the problem.

__How to use__

import sudoko

t=sudoko.create_board()
sudoko.print_board(t)
sudoko.solve(t)

To solve a different problem, pass in the board you want to solve through create_board() 
function.  The board should be a list of 9 elements of length 9. Each entry 
represents a square on the board. Use 0 for blanks.

for example input should be given in this manner:

enter the 1 row seperated by comma:0,9,0,0,6,3,8,0,5
enter the 2 row seperated by comma:0,0,0,2,0,9,1,6,0
enter the 3 row seperated by comma:0,0,0,0,0,8,0,0,3
enter the 4 row seperated by comma:0,0,0,0,9,0,0,5,1
enter the 5 row seperated by comma:0,0,1,0,2,0,3,0,0
enter the 6 row seperated by comma:6,8,0,0,5,0,0,0,0
enter the 7 row seperated by comma:7,0,0,1,0,0,0,0,0
enter the 8 row seperated by comma:0,1,8,6,0,7,0,0,0
enter the 9 row seperated by comma:5,0,4,9,3,0,0,1,0
