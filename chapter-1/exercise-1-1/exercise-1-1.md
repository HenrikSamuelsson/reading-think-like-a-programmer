# Exercise 1-1

Exercise from the book Think Like a Programmer.

## Exercise

Try a medium-difficulty Sudoku puzzle.

- Experiment with different strategies
- Take notes of the results
- Write a general plan for solving a Sudoku

## Solution

Tried and solved a medium-difficulty Sudoku was given at [Sudoku.com](https://sudoku.com/medium/).

### Experimenting

Initial strategy used was to start with the sub-square that had the most numbers in it already. Choose a number not present in this sub-square and check if could be fitted in only one place, and if so place the number. After having tested all number is the first sub-square move on to another sub-square with many numbers in it and repeat the process.

After a while it became harder to find numbers to be fitted with the initial strategy then started working with rows and columns. For example choosing a missing number in a row as a whole and placing it if would only fit in one place.

### Notes

Did solve the Sudoku but not in a systematic way. Basically just choose a random missing number in a region and checked if it was only one place in the region where the number would fit.

### General Plan

A general plan for solving a Sudoku.

- While not solved try to fill in a number, start over here at top each time a number have been filled in:
  - For each of the 9 sub-squares:
    - If there is a sub-square with 8 different numbers already filled in:
      - Then fill in the missing number.
  - For each of the 9 columns:
    - If there is a column with 8 different numbers already filled in:
      - Then fill in the missing number.
  - For each of the 9 rows:
    - If there is a row with 8 different numbers already filled in
      - Then fill in the missing number.
  - For each position on the Sudoku board:
    - If position is empty:
      - For each number in range 1 to 9:
        - If the number can be placed in the empty position:
          - If the number be can not be fitted in any other position in the same sub-square:
            - Then fill in the missing number.

This plan will likely not solve all Sudoku's because it relies on the Sudoku being kind of simple to solve.
