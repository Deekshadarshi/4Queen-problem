4 Queens Problem

The 4 Queens Problem is a classic computer science and mathematics puzzle. The objective is to place four queens on a 4x4 chessboard such that no two queens threaten each other. This means:

No two queens can be in the same row.

No two queens can be in the same column.

No two queens can be on the same diagonal.

This README explains the implementation of the 4 Queens Problem and how to use the code provided in this repository.

Table of Contents

Problem Description

Algorithm Used

Setup Instructions

Usage

Examples

Contributing

License

Problem Description

The 4 Queens Problem involves solving a smaller version of the famous N Queens Problem, which is a generalization for an N x N chessboard with N queens. The challenge lies in arranging the queens such that none of them threaten each other. The solution to this problem is often used as an introduction to backtracking algorithms.

Algorithm Used

The primary algorithm used to solve this problem is Backtracking. Here's a brief explanation of the process:

Place a queen in the first column of the first row.

Move to the next column and try placing a queen in a safe position in that row.

If a safe position is found, move to the next row. If not, backtrack to the previous row and move the queen to the next possible position.

Repeat until all queens are placed or all possibilities are exhausted.

Happy coding!
