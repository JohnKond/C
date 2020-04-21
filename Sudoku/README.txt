Compile files using makefile ,with command:
>make sudoku


Executions: 

>./sudoku
Reads a new puzzle from input and solves it (if correct).

>./sudoku -c
Reads a new puzzle from input and checks if is correct or not.

>./sudoku -g nelts
Generates a new puzzle with nelts/81 numbers on the grid.
e.g ./sudoku - g 50 , generates a new puzzle with 50 numbers on the grid.

>./sudoku -g nelts -u
Generates a new puzzle with nelts/81 numbers on the grid. This puzzle has unique solution(no backtracking need).