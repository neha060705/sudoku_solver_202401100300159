# sudoku_solver_202401100300159
Sudoku Solver - README

Project Overview

This project is a Python-based Sudoku solver that takes an incomplete Sudoku puzzle as input and solves it using a backtracking algorithm. The program ensures that all Sudoku rules are followed while filling the missing numbers in the grid.

Features

Accepts user input for an incomplete Sudoku board.

Implements the backtracking algorithm to solve the puzzle.

Displays the original and solved Sudoku board.

Handles standard 9x9 Sudoku puzzles.

Installation

Ensure you have Python installed on your system (Python 3.x recommended).

Install Jupyter Notebook or Google Colab for easy execution.

Clone or download this repository.

Usage

Run the Python script in Jupyter Notebook or Google Colab.

Enter the Sudoku puzzle row by row using 0 for empty spaces.

The program will solve the Sudoku puzzle and display the result.

Code Explanation

is_valid(board, row, col, num): Checks whether a number can be placed in a given position.

find_empty_cell(board): Identifies the next empty cell to be filled.

solve_sudoku(board): Recursively fills the board using backtracking.

display_board(board): Prints the Sudoku board in a user-friendly format.

get_user_sudoku(): Allows users to input a Sudoku puzzle.

Example

Input (Unsolved Sudoku)

5 3 0 | 0 7 0 | 0 0 0
6 0 0 | 1 9 5 | 0 0 0
0 9 8 | 0 0 0 | 0 6 0
---------------------
8 0 0 | 0 6 0 | 0 0 3
4 0 0 | 8 0 3 | 0 0 1
7 0 0 | 0 2 0 | 0 0 6
---------------------
0 6 0 | 0 0 0 | 2 8 0
0 0 0 | 4 1 9 | 0 0 5
0 0 0 | 0 8 0 | 0 7 9

Output (Solved Sudoku)

5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
---------------------
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
---------------------
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9

Future Enhancements

Implement a graphical user interface (GUI).

Optimize the backtracking algorithm for faster solving.

Generate random Sudoku puzzles for users to solve interactively.

License

This project is open-source and free to use for educational and personal purposes.


-Neha yadav
