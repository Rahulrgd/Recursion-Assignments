### Assessment Creation: Part 2 (Assessment 3 and Assessment 4)

Now, we’ll build on the foundation of recursion with **backtracking** problems in **Assessment 3** and introduce **basic dynamic programming (1D)** in **Assessment 4**.

---

### **Assessment 3: Backtracking Basics**
*Goal*: Teach students how to use recursion with backtracking to solve problems involving constraints.

1. **N-Queens Problem (Size = 4)**  
   Place `n` queens on an `n x n` chessboard such that no two queens attack each other. Print all valid board configurations.  
   *Input*: `n = 4`  
   *Output*: All valid arrangements of 4 queens on the board.

2. **Rat in a Maze**  
   Given a maze (2D grid), find a path from the top-left to the bottom-right corner. The rat can only move right or down.  
   *Input*:  
   ```
   maze = [[1, 0, 0], 
           [1, 1, 0], 
           [0, 1, 1]]
   ```  
   *Output*:  
   ```
   [ [1, 0, 0], 
     [1, 1, 0], 
     [0, 1, 1] ]
   ```

3. **Permutations of a String**  
   Generate all permutations of a given string.  
   *Input*: `"abc"`  
   *Output*: `["abc", "acb", "bac", "bca", "cab", "cba"]`

4. **Word Search**  
   Given a 2D grid of letters and a word, check if the word exists in the grid by moving horizontally, vertically, or diagonally.  
   *Input*:  
   ```
   board = [['A','B','C','E'], 
            ['S','F','C','S'], 
            ['A','D','E','E']]
   word = "ABCCED"
   ```  
   *Output*: `true`

5. **Combination Sum**  
   Find all unique combinations of numbers from an array that sum up to a target. Each number can be used unlimited times.  
   *Input*:  
   ```
   arr = [2, 3, 6, 7], target = 7
   ```  
   *Output*:  
   ```
   [[7], [2, 2, 3]]
   ```

6. **Sudoku Solver**  
   Write a recursive function to solve a 9x9 Sudoku puzzle. Fill in the grid while adhering to Sudoku rules.  
   *Input*:  
   ```
   [[5,3,0,0,7,0,0,0,0], 
    [6,0,0,1,9,5,0,0,0], 
    [0,9,8,0,0,0,0,6,0], 
    ...
   ```
   *Output*: Solved Sudoku grid.
