# SudokuSolver
<<< Sudoku solver >>>

<< Main technique used >> Recursion and backtracking techinques

<< Brief overview of functions included >>

void printGrid() : prints the solved matrix .

void UsedInRow() : checks for the occurence of given element in same row . returns false on occurence and true on non-occurence .

void UsedInCol() : checks for the occurence of given element in same column . returns false on occurence and true on non-occurence .

void UsedInBox() : checks for the occurence of given element in it's respective box of 9 elements . returns false on occurence and ture on non-occurence.

void SolveSudoku() : solves the matrix based on backtracking and recursive techniques . used functions rowcheck , colcheck , boxcheck to find correct spaces to fill digits .

<< Entering Matrix >>

To enter matix : in the main() section change the grid[N][N] value .

<< Compilation & Execution >>

platform : windows

compiling command > cd "d:\Sudoku Solver\" ; if ($?) { g++ sudoku.cpp -o sudoku } ; if ($?) { .\sudoku }

submitted by : Aditya Bahuguna (Section H IIIrd Sem)
