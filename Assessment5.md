### **Assessment 5: Intermediate Dynamic Programming (1D and 2D)**
*Goal*: Develop problem-solving skills using dynamic programming in both 1D and 2D arrays.

1. **Coin Change (Minimum Coins)**  
   Given an array of coin denominations and a total amount, find the minimum number of coins needed to make up the amount.  
   *Input*: `coins = [1, 2, 5], amount = 11`  
   *Output*: `3` (5+5+1)

2. **Longest Common Subsequence (LCS)**  
   Find the length of the longest subsequence common to two strings.  
   *Input*: `"abcde", "ace"`  
   *Output*: `3` (`"ace"`)

3. **Knapsack Problem (0/1 Knapsack)**  
   You are given weights and values of items, and a maximum capacity for the knapsack. Find the maximum value you can achieve.  
   *Input*:  
   ```
   weights = [1, 2, 3], values = [10, 15, 40], capacity = 5
   ```  
   *Output*: `55`

4. **Matrix Chain Multiplication**  
   Find the minimum number of scalar multiplications needed to multiply a chain of matrices.  
   *Input*: `arr = [40, 20, 30, 10, 30]`  
   *Output*: `26000`

5. **Edit Distance**  
   Find the minimum number of operations (insert, delete, replace) required to convert one string into another.  
   *Input*: `"horse", "ros"`  
   *Output*: `3`

6. **Maximum Subarray Sum (Kadane's Algorithm)**  
   Find the contiguous subarray with the maximum sum.  
   *Input*: `arr = [-2, 1, -3, 4, -1, 2, 1, -5, 4]`  
   *Output*: `6` (`[4, -1, 2, 1]`)

7. **Unique Paths in a Grid**  
   Find the number of unique paths to reach the bottom-right corner of an `m x n` grid starting from the top-left corner.  
   *Input*: `m = 3, n = 2`  
   *Output*: `3`

8. **Maximal Square**  
   Find the largest square containing only 1s in a binary matrix and return its area.  
   *Input*:  
   ```
   matrix = [[1, 0, 1, 0, 0], 
             [1, 0, 1, 1, 1], 
             [1, 1, 1, 1, 1], 
             [1, 0, 0, 1, 0]]
   ```  
   *Output*: `4` (2x2 square)
