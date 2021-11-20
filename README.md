# Sudoku-Solver
A Sudoku puzzle generator written in C++ using recursion and backtracking algorithm and further implemented as a web app using HTML and Javascript.

# Screenshot
Every time you press Get Another Puzzle, you get a new one to solve!

![image](https://user-images.githubusercontent.com/76108859/142727592-db7e7466-9f89-4d51-be04-e90753b6eee9.png)

Voila! You solved it !

![image](https://user-images.githubusercontent.com/76108859/142727632-d5f7a520-8ad2-473c-9215-f27c456e73bc.png)


# How It Works - Methodology 
How It Works
This particular algorithm employs the use of backtracking, one of the more common methods to solve Sudoku puzzles. I've written a simple algorithm to give an idea of how the program works.

1.Start. <br />
2.We start with the first empty cell. <br />
3.We generate a list of possible valid values that can be filled in that cell. <br />
4.We iterate over this list and start with the first value. This value is placed in the required cell. <br />
5.We move on to the next cell. We again generate a list of possibilities. However, if no list can be generated, then this means that there is something wrong with the value of the previous cell. We then move back to the previous cell and place the next value on the generated list in the cell now. We repeat this step until the current cell has a valid value placed inside it. <br />
6.We stop when we reach the 81st cell (the last cell in a Sudoku puzzle) and have placed a valid value. <br />
7.The puzzle has now been solved. <br />
8.Stop.

# LiveLink
https://harshitagupta1999.github.io/Sudoku-Solver/


