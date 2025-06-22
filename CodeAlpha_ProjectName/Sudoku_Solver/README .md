## Domain: C++ Programming — CodeAlpha Internship

Internship Domain: C++ Programming
Internship Platform: CodeAlpha
Intern Name: Rishaw Prabhakar
Task Name: sudoku solver
Task Number: Task 3
Duration: April 30 – June 30, 2025

## Task: Sudoku Solver

This project is part of the C++ Programming Internship at CodeAlpha. The objective is to create a fully functional Sudoku Solver that reads a 9x9 Sudoku puzzle, processes it using a backtracking algorithm, and displays the solved puzzle.

## Features

- Represent the Sudoku grid as a 2D array
- Validate moves based on Sudoku rules:
  - Each row must contain digits 1–9 with no repetition
  - Each column must contain digits 1–9 with no repetition
  - Each 3×3 subgrid must contain digits 1–9 with no repetition
- Use of recursive backtracking to solve the puzzle
- Easy-to-read console output format
- Optional: Add a graphical interface (future scope)

## How It Works

1. The user provides a partially filled 9x9 Sudoku puzzle.
2. The algorithm attempts to fill empty cells by testing all values from 1–9.
3. If a value satisfies all Sudoku rules, it is placed in the cell.
4. The solver proceeds recursively; if no valid value is found, it backtracks.
5. The process continues until the board is solved or deemed unsolvable.

## Technologies Used

- C++ Programming Language
- Object-Oriented Programming
- Recursive Backtracking Algorithm

## How to Run

1. Clone or download this repository.
2. Open the `sudoku_solver.cpp` file in your preferred C++ environment.
3. Compile the program using a C++ compiler (e.g., g++).
4. Run the executable and follow the prompts to input your Sudoku puzzle.

## Sample Input Format

Use 0 for empty cells:

```
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

