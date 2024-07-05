# NxN Game Board Color Arrangement

## Introduction
This project implements a backtracking algorithm to arrange colors on an NxN game board such that each column contains all unique colors. The game board can be circularly shifted right for each row to achieve the desired arrangement. This approach uses recursive backtracking to explore all possible configurations.

## Problem Description
- The game board is an NxN grid where N colors are arranged in each row.
- The colors in each row can be circularly shifted to the right.
- The goal is to arrange the board such that each column contains each color exactly once using backtracking.

## Requirements
1. The game board size `N` must be in the range 3 <= N <= 8.
2. The initial state of the game board is provided as input.
3. Each color in the input is mapped to a unique integer for easier processing.



## Usage
### Compilation
To compile the program, use a C compiler such as `gcc`:
```bash
gcc -o game game.c
