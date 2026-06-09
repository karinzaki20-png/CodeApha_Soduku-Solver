# CodeApha_Soduku-Solver
# CodeAlpha Sudoku Solver

## Overview

This project is a Sudoku Solver developed in C++ as part of the CodeAlpha C++ Programming Internship.

The program uses the **Backtracking Algorithm** to solve a standard 9×9 Sudoku puzzle. It automatically fills empty cells while ensuring that all Sudoku rules are satisfied.

---

## Features

* Solves any valid 9×9 Sudoku puzzle.
* Uses Backtracking for efficient problem solving.
* Checks row, column, and 3×3 subgrid constraints.
* Displays the solved Sudoku grid.
* Simple and easy-to-understand implementation.

---

## Technologies Used

* C++
* Object-Oriented Programming Concepts
* Recursion
* Backtracking Algorithm

---

## How the Algorithm Works

1. Find an empty cell in the Sudoku grid.
2. Try numbers from 1 to 9.
3. Check whether the number is valid according to Sudoku rules.
4. If valid, place the number and recursively solve the remaining puzzle.
5. If no valid number exists, backtrack and try another number.
6. Continue until the puzzle is solved.

---

## Project Structure

```text
CodeAlpha_SudokuSolver/
│
├── SudokuSolver.cpp
├── README.md
└── screenshots/
    ├── input.png
    └── output.png
```

---

## How to Compile and Run

### Using g++

```bash
g++ SudokuSolver.cpp -o sudoku
./sudoku
```

### Using Visual Studio

1. Open the project in Visual Studio.
2. Build the solution.
3. Run the program.

---

## Sample Input

```text
3 0 6 5 0 8 4 0 0
5 2 0 0 0 0 0 0 0
0 8 7 0 0 0 0 3 1
0 0 3 0 1 0 0 8 0
9 0 0 8 6 3 0 0 5
0 5 0 0 9 0 6 0 0
1 3 0 0 0 0 2 5 0
0 0 0 0 0 0 0 7 4
0 0 5 2 0 6 3 0 0
```

---

## Sample Output

```text
3 1 6 5 7 8 4 9 2
5 2 9 1 3 4 7 6 8
4 8 7 6 2 9 5 3 1
2 6 3 4 1 5 9 8 7
9 7 4 8 6 3 1 2 5
8 5 1 7 9 2 6 4 3
1 3 8 9 4 7 2 5 6
6 9 2 3 5 1 8 7 4
7 4 5 2 8 6 3 1 9
```

---

## Learning Outcomes

Through this project, I gained experience in:

* Recursive programming
* Backtracking algorithms
* Problem-solving techniques
* C++ programming fundamentals
* Debugging and testing algorithms

---

## Author

Karin Zaki

CodeAlpha C++ Programming Internship
