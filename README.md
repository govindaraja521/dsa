# dsa

https://leetcode.com/problems/count-the-number-of-inversions/description/


1. Understand Core DSA Concepts & Patterns
Most DSA problems fall under specific patterns. Mastering these patterns will help you solve problems efficiently.

A. Arrays & Strings
Key Techniques:
Two Pointers – For sorted arrays, sliding windows, or pair problems.

Types: Opposite ends (left-right), Fast-slow (cycle detection), sliding window.

Example Problems: Two Sum, Trapping Rain Water, Minimum Window Substring.

Sliding Window – For subarray/substring problems.

Fixed size: Max sum of subarray of size k.

Variable size: Longest substring with k distinct characters.

Prefix Sum / Hashing – For subarray sum problems.

Example: Subarray sum equals k, Contiguous Array (0s and 1s).

Sorting & Searching – Binary Search, Dutch National Flag (3-way partitioning).

Example: Search in Rotated Sorted Array, Merge Intervals.

Must-Remember:
Strings: Know KMP (for pattern matching), Rabin-Karp (rolling hash), and Manacher’s (palindromes).

Anagrams: Use frequency maps or sorting.

Palindromes: Expand around center or DP.

B. Linked Lists
Key Techniques:
Fast & Slow Pointers – Detect cycles, find middle.

Example: Linked List Cycle, Palindrome Linked List.

Reverse Linked List – Iterative & recursive.

Example: Reverse Nodes in k-Group.

Dummy Node – For edge cases (deletion, merging).

Example: Merge Two Sorted Lists, Remove Nth Node from End.

Must-Remember:
Always check if (head == null || head.next == null).

Use stack for problems like "Next Greater Node".

C. Stacks & Queues
Key Techniques:
Monotonic Stack – Next Greater/Smaller Element.

Example: Daily Temperatures, Largest Rectangle in Histogram.

Queue using Stack & Vice Versa – Implement Queue using Stacks.

Priority Queue (Heap) – Kth Largest, Merge K Sorted Lists.

Must-Remember:
Stack: Parentheses validation, postfix evaluation.

Queue: BFS, Sliding Window Maximum (Deque).

D. Trees & Graphs
Key Techniques:
Tree Traversals – Inorder (LNR), Preorder (NLR), Postorder (LRN).

Example: Validate BST (Inorder gives sorted order).

BFS (Level Order) – Shortest path in unweighted graphs.

Example: Binary Tree Level Order Traversal.

DFS (Backtracking) – Path finding, permutations.

Example: Path Sum II, Subsets.

Union-Find (Disjoint Set) – Detect cycles in undirected graphs.

Example: Number of Islands (alternative to DFS/BFS).

Dijkstra’s – Shortest path in weighted graphs (no negative edges).

Topological Sort – Dependency resolution (course scheduling).

Must-Remember:
BST: Inorder is sorted, insertion/deletion rules.

Trie: For word search (prefix-based problems).

Graph Cycles: Detect using DFS (back edge) or Union-Find.

E. Dynamic Programming (DP)
Key Patterns:
Knapsack (0/1 & Unbounded) – Subset sum, coin change.

LCS (Longest Common Subsequence) – Edit distance, palindrome deletions.

Matrix DP – Unique Paths, Minimum Path Sum.

DP + Bitmasking – Traveling Salesman Problem (TSP).

MCM (Matrix Chain Multiplication) – Burst Balloons, Egg Dropping.

Must-Remember:
Always define dp[i][j] meaning clearly.

Start with recursion → memoization → tabulation.

State Transition: Write it before coding.

F. Recursion & Backtracking
Key Techniques:
Subsets/Permutations – Include/Exclude pattern.

Example: Subsets, N-Queens.

Memoization – Avoid recomputation (Fibonacci, DP).

Pruning – Early termination in backtracking.

Must-Remember:
Base Case: Always define exit condition.

Time Complexity: O(2^N) for subsets, O(N!) for permutations.

2. Problem-Solving Strategies
Clarify Inputs & Edge Cases – Ask about duplicates, negatives, empty inputs.

Brute Force First – Then optimize.

Draw Examples – Visualize before coding.

Time & Space Complexity – Always analyze (interviewers expect this).

3. MAANG-Specific Tips
Meta (Facebook): Heavy on Trees/Graphs (BFS/DFS), Recursion.

Amazon: Arrays, Strings, DP (Knapsack), System Design (OOD).

Google: Complex DP, Graph (Dijkstra’s), Math-heavy problems.

Apple: LC Medium focus, Trees, Arrays.

Netflix: System Design + LC Hard (sometimes).

4. How to Remember DSA Concepts?
Spaced Repetition – Revise problems after 1, 3, 7 days.

Flashcards – For key patterns (Anki or physical cards).

Teach Someone – Explaining reinforces memory.

Mind Maps – Connect similar problems (e.g., all BFS problems).

Daily LC/CF Practice – Consistency is key.

5. Final Checklist Before Interview
✅ Arrays: Sliding Window, Two Pointers, Prefix Sum.
✅ Strings: KMP, Rabin-Karp, Palindrome tricks.
✅ Linked Lists: Fast-slow, Reverse, Dummy node.
✅ Stacks/Queues: Monotonic stack, Heap (PQ).
✅ Trees/Graphs: BFS/DFS, Union-Find, Dijkstra’s.
✅ DP: Knapsack, LCS, Matrix DP.
✅ Recursion: Subsets, Backtracking, Memoization.

Bonus: Top 10 MAANG Interview Questions
Two Sum (Arrays)

LRU Cache (Design + Linked List)

Merge Intervals (Sorting)

Word Break (DP)

Course Schedule (Topological Sort)

Serialize & Deserialize Binary Tree (Trees)

Minimum Window Substring (Sliding Window)

Trapping Rain Water (Two Pointers)

Kth Largest Element (Heap)

Number of Islands (DFS/BFS/Union-Find)

Conclusion
Pattern Recognition is key (most problems repeat).

Practice 100-200 LC problems covering all patterns.

Mock Interviews (Pramp, Interviewing.io) to simulate real pressure.

Revise System Design (for Amazon, Meta, Google).

Follow this roadmap, and you’ll ace MAANG interviews! 🚀

Would you like a 30-day study plan tailored for MAANG? Let me know!

New chat

