# CS301 — Design & Analysis of Algorithms — PLAN

**Semester:** 3 · **Credits:** 4 · **Level:** Intermediate
**Theory:** 45 hrs · **Lab:** 30 hrs · **Language:** C or Python

## Syllabus

### Unit 1 — Algorithm Analysis Foundations (9 lectures)
1. What an algorithm is — correctness and efficiency
2. RAM model of computation
3. Best, worst, and average case analysis
4. Asymptotic notation — O, Omega, Theta
5. Common growth functions — log n, n, n log n, n^2, 2^n
6. Analysing loops, nested loops, and recursive calls
7. Recurrence relations — substitution method
8. The Master Theorem
9. Amortised analysis — aggregate and accounting methods

### Unit 2 — Divide and Conquer (9 lectures)
1. The divide-and-conquer paradigm
2. Merge sort — algorithm and analysis
3. Quicksort — algorithm, analysis, randomisation
4. Binary search — iterative and recursive
5. Finding the maximum subarray
6. Matrix multiplication — Strassen's algorithm
7. Closest pair of points
8. Karatsuba integer multiplication
9. Divide and conquer vs dynamic programming trade-offs

### Unit 3 — Greedy Algorithms (9 lectures)
1. The greedy strategy — local choice, global optimum
2. Interval scheduling and activity selection
3. Fractional knapsack
4. Huffman coding
5. Minimum spanning trees — Prim and Kruskal revisited
6. Shortest paths — Dijkstra's algorithm
7. When greedy fails — counterexamples
8. Matroids and greedy optimality (intuition)
9. Disjoint set union and Kruskal's algorithm

### Unit 4 — Dynamic Programming (9 lectures)
1. Overlapping subproblems and optimal substructure
2. Memoisation vs tabulation
3. 0/1 knapsack
4. Longest common subsequence
5. Edit distance
6. Matrix chain multiplication
7. Shortest paths — Bellman-Ford and Floyd-Warshall
8. Longest increasing subsequence — O(n^2) and O(n log n)
9. DP on trees and intervals

### Unit 5 — Graph Algorithms and Complexity (9 lectures)
1. Graph traversal review — BFS and DFS
2. Topological sorting and cycle detection
3. Strongly connected components — Kosaraju and Tarjan
4. Maximum flow — Ford-Fulkerson and Edmonds-Karp
5. Bipartite matching — Hopcroft-Karp (overview)
6. Complexity classes — P, NP, NP-complete
7. Reductions — polynomial-time reduction examples
8. Classic NP-complete problems — SAT, 3-SAT, TSP, Vertex Cover
9. Approximation algorithms — vertex cover, TSP

## Practical Labs (18)

1. Implement insertion sort, merge sort, quicksort; measure and compare
2. Empirically verify O(n log n) vs O(n^2) growth
3. Solve recurrences with the Master Theorem
4. Implement binary search — iterative and recursive — with tests
5. Maximum subarray — brute force, divide and conquer, Kadane
6. Strassen's matrix multiplication
7. Activity selection greedy
8. Fractional knapsack
9. Huffman coding — encode and decode a file
10. Dijkstra's algorithm with a priority queue
11. Prim's and Kruskal's MST on the same graph
12. 0/1 knapsack with DP and memoisation
13. Longest common subsequence — DP table visualiser
14. Edit distance with reconstruction
15. Floyd-Warshall all-pairs shortest paths
16. Topological sort and cycle detection
17. Maximum flow on a small network
18. Approximation algorithm for vertex cover

## Assignments

1. Asymptotic analysis of 10 given functions
2. Recurrence solving — Master Theorem exercise set
3. Divide and conquer — implement and analyse three algorithms
4. Greedy algorithms — correctness proof for one, counterexample for another
5. Dynamic programming — solve five classic DP problems
6. NP-completeness — reduction exercise and writeup
