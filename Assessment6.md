### **Assessment 6: Advanced Backtracking Challenges**
*Goal*: Solve real-world, challenging problems involving recursion and backtracking.

1. **Generate All Valid Parentheses**  
   Given `n` pairs of parentheses, generate all valid combinations.  
   *Input*: `n = 3`  
   *Output*: `["((()))", "(()())", "(())()", "()(())", "()()()"]`

2. **Subset Sum Problem**  
   Find all subsets of an array whose sum equals a target value.  
   *Input*:  
   ```
   arr = [2, 3, 5, 7], target = 10
   ```  
   *Output*:  
   ```
   [[3, 7], [2, 3, 5]]
   ```

3. **Kth Permutation Sequence**  
   Find the `k`th permutation of the first `n` natural numbers.  
   *Input*: `n = 3, k = 3`  
   *Output*: `"213"`

4. **Word Break Problem**  
   Given a string and a dictionary of words, check if the string can be segmented into valid words.  
   *Input*:  
   ```
   str = "leetcode", dictionary = ["leet", "code"]
   ```  
   *Output*: `true`

5. **N-Knights Problem**  
   Place `k` knights on an `n x n` chessboard such that no two knights attack each other. Print all valid arrangements.  
   *Input*: `n = 4, k = 4`  
   *Output*: All valid knight placements.

6. **Lexicographical Order Permutations**  
   Generate all permutations of a string in lexicographical order.  
   *Input*: `"abc"`  
   *Output*: `["abc", "acb", "bac", "bca", "cab", "cba"]`

7. **Solve a Crossword Puzzle**  
   Given a crossword grid and a set of words, fill in the words into the grid using backtracking.  
   *Input*:  
   ```
   grid = [['+', '-', '+', '+', '+'], 
           ['+', '-', '+', '+', '+'], 
           ['+', '-', '-', '-', '+'], 
           ['+', '-', '+', '-', '+']]
   words = ["CAT", "DOG"]
   ```  
   *Output*: Solved crossword grid.

8. **Hamiltonian Path**  
   Find a Hamiltonian path in a given graph using backtracking (visiting each vertex exactly once).  
   *Input*:  
   ```
   Graph: Adjacency Matrix
   [[0, 1, 0, 1], 
    [1, 0, 1, 0], 
    [0, 1, 0, 1], 
    [1, 0, 1, 0]]
   ```  
   *Output*: One valid Hamiltonian path.
