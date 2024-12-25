### **Assessment 4: Basic Dynamic Programming (1D Array)**
*Goal*: Introduce the concept of memoization and tabulation for solving recursive problems efficiently.

1. **Fibonacci Numbers (Top-Down DP)**  
   Modify the recursive Fibonacci function to use **memoization** for optimization.  
   *Input*: `n = 10`  
   *Output*: `55`

2. **Climbing Stairs**  
   You are climbing a staircase with `n` steps. You can climb 1 or 2 steps at a time. How many distinct ways can you reach the top?  
   *Input*: `n = 4`  
   *Output*: `5`

3. **Min Cost to Climb Stairs**  
   Given an array `cost[]`, where `cost[i]` is the cost of the `i`th step, find the minimum cost to reach the top.  
   *Input*: `cost = [10, 15, 20]`  
   *Output*: `15`

4. **House Robber Problem**  
   Given an array representing the amount of money at each house, find the maximum money you can rob without robbing adjacent houses.  
   *Input*: `arr = [1, 2, 3, 1]`  
   *Output*: `4`

5. **Can Sum (Target Sum)**  
   Write a function to check if it is possible to generate the target sum using numbers from an array. Each number can be used multiple times.  
   *Input*:  
   ```
   arr = [2, 3], target = 7
   ```  
   *Output*: `true`

6. **Longest Increasing Subsequence**  
   Given an array, find the length of the longest increasing subsequence (LIS).  
   *Input*: `arr = [10, 9, 2, 5, 3, 7, 101, 18]`  
   *Output*: `4`

7. **Partition Equal Subset Sum**  
   Determine if a given array can be partitioned into two subsets with equal sums.  
   *Input*: `arr = [1, 5, 11, 5]`  
   *Output*: `true`

8. **Decode Ways**  
   A message containing letters from A-Z is encoded using numbers: `A=1, B=2, ..., Z=26`. Count the number of ways to decode a given string.  
   *Input*: `"226"`  
   *Output*: `3`  
   *Explanation*: `"2|2|6"`, `"22|6"`, `"2|26"`
