# Sudoku Solver

This project is a Sudoku solver implemented in C. It uses a backtracking algorithm to solve a given Sudoku puzzle.

## Prerequisites

To compile and run this project, you need to have the following tools installed on your system:
- `gcc`: The GNU Compiler Collection.
- `make`: A build automation tool.

## Installation

To compile the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Compile the project using the Makefile:
    ```sh
    make
    ```

## Usage

To run the Sudoku solver, execute the following command:
```sh
make run
```
Makefile: Contains the instructions to compile, run, and clean the project.

src/sudoku.c: The main file that initializes the puzzle and runs the solver.

src/puzzle.c: Contains functions to create and print the Sudoku puzzle.

src/box.c: Contains functions related to the boxes in the Sudoku puzzle.

src/square.c: Contains functions related to the squares in the Sudoku puzzle.

include/sudoku.h: Header file containing the definitions and declarations used across the project.
