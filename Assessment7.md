### **Assessment 7: Advanced Dynamic Programming Problems**
*Goal*: Solve advanced dynamic programming problems involving real-world applications and multi-dimensional data.

1. **Longest Palindromic Subsequence**  
   Find the length of the longest subsequence of a string that is also a palindrome.  
   *Input*: `"bbbab"`  
   *Output*: `4` (`"bbbb"`)

2. **Word Search in a Grid**  
   Given a 2D board and a word, check if the word exists in the grid. The word can be constructed from adjacent letters (horizontally or vertically) but cannot reuse the same cell.  
   *Input*:  
   ```
   board = [["A","B","C","E"], 
            ["S","F","C","S"], 
            ["A","D","E","E"]]
   word = "ABCCED"
   ```  
   *Output*: `true`

3. **Burst Balloons**  
   Given `n` balloons, each with a number, maximize coins obtained by bursting balloons sequentially.  
   *Input*: `nums = [3, 1, 5, 8]`  
   *Output*: `167`

4. **Wildcard Matching**  
   Implement wildcard pattern matching with `'*'` (matches zero or more characters) and `'?'` (matches one character).  
   *Input*:  
   ```
   s = "aa", p = "*"
   ```  
   *Output*: `true`

5. **Rod Cutting Problem**  
   Given a rod of length `n` and an array of prices for different lengths, find the maximum value that can be obtained.  
   *Input*:  
   ```
   n = 8, prices = [1, 5, 8, 9, 10, 17, 17, 20]
   ```  
   *Output*: `22`

6. **Count Palindromic Subsequences**  
   Count the number of distinct palindromic subsequences in a string.  
   *Input*: `"bccb"`  
   *Output*: `6`

7. **Painting the Fence**  
   Given `n` fence posts and `k` colors, find the number of ways to paint the fence such that no more than two adjacent posts have the same color.  
   *Input*: `n = 3, k = 2`  
   *Output*: `6`

8. **Shortest Common Supersequence**  
   Find the shortest string that has both given strings as subsequences.  
   *Input*: `"abac", "cab"`  
   *Output*: `"cabac"`
