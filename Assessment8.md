### **Assessment 8: Challenging Problems (Combination of Recursion, Backtracking, and DP)**  
*Goal*: Tackle interview-level problems combining multiple concepts.

1. **Sudoku Solver**  
   Solve a partially filled `9x9` Sudoku board using backtracking.  
   *Input*:  
   ```
   board = [["5","3",".",".","7",".",".",".","."], 
            ["6",".",".","1","9","5",".",".","."], 
            [".","9","8",".",".",".",".","6","."], 
            ["8",".",".",".","6",".",".",".","3"], 
            ["4",".",".","8",".","3",".",".","1"], 
            ["7",".",".",".","2",".",".",".","6"], 
            [".","6",".",".",".",".","2","8","."], 
            [".",".",".","4","1","9",".",".","5"], 
            [".",".",".",".","8",".",".","7","9"]]
   ```  
   *Output*: Solved board.

2. **Partition Equal Subset Sum**  
   Determine if an array can be partitioned into two subsets with equal sums.  
   *Input*: `nums = [1, 5, 11, 5]`  
   *Output*: `true`

3. **N-Queens Problem**  
   Place `N` queens on an `N x N` chessboard so that no two queens attack each other. Print all valid solutions.  
   *Input*: `n = 4`  
   *Output*:  
   ```
   [
     [".Q..", 
      "...Q", 
      "Q...", 
      "..Q."], 
     ["..Q.", 
      "Q...", 
      "...Q", 
      ".Q.."]
   ]
   ```

4. **Traveling Salesman Problem (TSP)**  
   Find the minimum cost of visiting all cities exactly once, starting and ending at the same city. Use dynamic programming and bit masking.  
   *Input*:  
   ```
   distances = [[0, 10, 15, 20], 
                [10, 0, 35, 25], 
                [15, 35, 0, 30], 
                [20, 25, 30, 0]]
   ```  
   *Output*: `80`

5. **K-Partition Problem**  
   Partition an array into `k` subsets such that the sum of each subset is equal.  
   *Input*: `nums = [4, 3, 2, 3, 5, 2, 1], k = 4`  
   *Output*: `true`

6. **Largest Rectangle in Histogram**  
   Given a histogram, find the largest rectangle area.  
   *Input*: `heights = [2, 1, 5, 6, 2, 3]`  
   *Output*: `10`

7. **Dungeon Game**  
   Find the minimum initial health a knight needs to rescue the princess at the bottom-right corner of a dungeon grid.  
   *Input*:  
   ```
   dungeon = [[-2, -3, 3], 
              [-5, -10, 1], 
              [10, 30, -5]]
   ```  
   *Output*: `7`

8. **Regex Matching**  
   Implement regular expression matching for a string and a pattern, supporting `'.'` and `'*'`.  
   *Input*:  
   ```
   s = "mississippi", p = "mis*is*p*."
   ```  
   *Output*: `false`