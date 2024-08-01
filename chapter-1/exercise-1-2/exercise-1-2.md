# Exercise 1-2

An exercise from the book Think Like a Programmer.

## Exercise

The sliding tile puzzle discussed in the book is of the variant where each tile have a number. Goal of the puzzle being to get all the numbers in order.

There are also variants of these puzzles where the tiles are covered with parts of a picture. Goal is here to rearrange the tiles to see the complete picture clearly.

How much does the second variant with a picture increase the difficulty and why?

## Solution

The first variant with numbers is easier to solve due to that we can deduce the position where a tile shall end up by just divide the number on the tile with the number of rows. For example for a 4 by 4 puzzle tile number 6 will go at row 1 column 2, due to that 6 divided by 4 is 1 with the remainder 2.

The second increases the difficulty due to we first need to figure out what the complete picture looks like. Especially hard if it is picture we have never seen. Say for example the flag of a country that we do not know.