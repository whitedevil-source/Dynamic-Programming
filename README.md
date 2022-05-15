# Dynamic-Programming

Properties of DP:
* Optimal Substructure: If we can write a recurrence relation, then a problem
  is said to have optimal substructure
* Overlapping Subproblem: If our subproblems repeat, then a problem is said
  to have overlapping subproblem

Ways to handle Overlapping Subproblem:
* Memoization (Top-Down): A lookup table is maintained and checked
  before computation of any state. Recursion is involved.
* Tabulation (Bottom-Up): Solution is built from base. It is an
  iterative process.

Key Points:
* Minimization and maximization problems are generally solved with dp where we
  want exhaustive solutions. (Sometimes with binary search on answer)
* "Find the number of ways" is also a very popular type of DP problems.
* Wherever we can form recurrence relation or given in question can be solved
  using DP. (Sometimes with matrix exponentiation).
 
