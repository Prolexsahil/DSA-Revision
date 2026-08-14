# DSA-Revision
DSA revision for placements

# Big-Tech DSA Placement Preparation Roadmap

## Goal

Prepare for big-tech placement interviews over the remaining ~2 months with a focus on:

> **Pattern recognition → optimal approach → implementation speed → edge cases → interview communication.**

The objective is not to simply finish a DSA sheet. The goal is to recognize the correct pattern quickly, derive the optimal solution, implement it cleanly, and explain it like an interview candidate.

---

# 1. Problem-Solving Procedure

For every problem, use this process.

## Round 1 — Recognition

Before coding, answer:

1. What pattern is this?
2. What is the brute-force approach?
3. Why is brute force too slow?
4. What invariant/property allows optimization?
5. What is the target time and space complexity?

## Round 2 — Implementation

Code the optimal approach without looking at the solution.

## Round 3 — Interview Explanation

Be able to explain:

> "The key observation is ___, therefore we maintain ___, which lets us reduce ___ from O(...) to O(...)."

## Round 4 — Re-solve

Re-solve important problems after:

- 1 day
- 7 days
- 21 days

The objective is to convert recognition into interview-level recall.

---

# 2. Complete DSA Pattern Roadmap

## 2.1 Arrays + Hashing

**12 problems**

1. Two Sum
2. Contains Duplicate
3. Valid Anagram
4. Group Anagrams
5. Product of Array Except Self
6. Longest Consecutive Sequence
7. Majority Element
8. Subarray Sum Equals K
9. Longest Subarray with Sum K
10. Sort Colors
11. Maximum Subarray
12. Maximum Product Subarray

### Must Know

- HashMap / HashSet
- Frequency counting
- Prefix sum + hashmap
- Kadane's algorithm
- In-place array manipulation

---

## 2.2 Two Pointers

**12 problems**

1. Valid Palindrome
2. Two Sum II
3. 3Sum
4. 4Sum
5. Container With Most Water
6. Trapping Rain Water
7. Remove Duplicates from Sorted Array
8. Remove Duplicates from Sorted Array II
9. Move Zeroes
10. Squares of a Sorted Array
11. Backspace String Compare
12. Boats to Save People

### Must Recognize

- Left/right pointers
- Slow/fast pointers
- Sorted array + two pointers
- Opposite-direction pointers
- Same-direction pointers

---

## 2.3 Sliding Window

**12 problems**

1. Best Time to Buy and Sell Stock
2. Longest Substring Without Repeating Characters
3. Longest Repeating Character Replacement
4. Permutation in String
5. Find All Anagrams in a String
6. Minimum Window Substring
7. Maximum Average Subarray I
8. Max Consecutive Ones III
9. Fruit Into Baskets
10. Minimum Size Subarray Sum
11. Subarray Product Less Than K
12. Sliding Window Maximum

### Must Know

- Fixed window
- Variable window
- Frequency map
- Shrinking condition
- Monotonic deque

---

## 2.4 Prefix Sum / Difference Array

**12 problems**

1. Range Sum Query
2. Subarray Sum Equals K
3. Continuous Subarray Sum
4. Find Pivot Index
5. Product of Array Except Self
6. Corporate Flight Bookings
7. Car Pooling
8. Range Addition
9. Subarray Sums Divisible by K
10. Contiguous Array
11. Maximum Size Subarray Sum Equals k
12. Path Sum III

### Critical Concepts

- `prefix[i] - prefix[j]`
- Prefix remainder
- Prefix + hashmap
- 2D prefix sum
- Difference array

---

## 2.5 Binary Search

**12 problems**

1. Binary Search
2. Search Insert Position
3. First Bad Version
4. Find First and Last Position
5. Search in Rotated Sorted Array
6. Search in Rotated Sorted Array II
7. Find Minimum in Rotated Sorted Array
8. Find Peak Element
9. Koko Eating Bananas
10. Capacity To Ship Packages Within D Days
11. Split Array Largest Sum
12. Median of Two Sorted Arrays

### Must Master

#### Type A — Normal Binary Search

```text
Search in sorted data.
```

#### Type B — Lower Bound / Upper Bound

```text
Find first/last valid position.
```

#### Type C — Rotated Array

```text
Use sorted half to eliminate search space.
```

#### Type D — Binary Search on Answer

```text
Search over the possible answer rather than the array.
```

#### Type E — Advanced Binary Search

```text
Partition-based / 2D binary search.
```

---

## 2.6 Linked List

**12 problems**

1. Reverse Linked List
2. Merge Two Sorted Lists
3. Linked List Cycle
4. Linked List Cycle II
5. Middle of the Linked List
6. Remove Nth Node From End
7. Reorder List
8. Add Two Numbers
9. Copy List with Random Pointer
10. Merge K Sorted Lists
11. Reverse Nodes in K-Group
12. LRU Cache

### Must Know

- Fast/slow pointers
- Dummy node
- Pointer reversal
- Merge
- Cycle detection
- In-place manipulation
- HashMap + linked list

---

## 2.7 Stack / Queue

**12 problems**

1. Valid Parentheses
2. Min Stack
3. Evaluate Reverse Polish Notation
4. Daily Temperatures
5. Next Greater Element I
6. Next Greater Element II
7. Largest Rectangle in Histogram
8. Car Fleet
9. Decode String
10. Simplify Path
11. Asteroid Collision
12. Basic Calculator

### Core Pattern

If you see:

> "next greater/smaller"

Immediately think:

**Monotonic Stack**

---

## 2.8 Monotonic Stack / Deque

**12 problems**

1. Daily Temperatures
2. Next Greater Element I
3. Next Greater Element II
4. Online Stock Span
5. Largest Rectangle in Histogram
6. Maximal Rectangle
7. Remove K Digits
8. Sum of Subarray Minimums
9. Sum of Subarray Ranges
10. Sliding Window Maximum
11. Trapping Rain Water
12. Constrained Subsequence Sum

### Must Understand

- Increasing stack
- Decreasing stack
- Previous greater
- Next greater
- Previous smaller
- Next smaller
- Contribution technique
- Monotonic deque

---

## 2.9 Intervals

**12 problems**

1. Merge Intervals
2. Insert Interval
3. Non-overlapping Intervals
4. Meeting Rooms
5. Meeting Rooms II
6. Minimum Number of Arrows to Burst Balloons
7. Car Pooling
8. Employee Free Time
9. My Calendar I
10. My Calendar II
11. Interval List Intersections
12. Minimum Interval to Include Each Query

### Pattern Recognition

Sort by:

- Start
- End

Then reason about overlap.

---

# 3. Trees

## 3.1 Binary Trees — DFS

This is a high-priority area.

**12 problems**

1. Maximum Depth of Binary Tree
2. Same Tree
3. Invert Binary Tree
4. Diameter of Binary Tree
5. Balanced Binary Tree
6. Binary Tree Maximum Path Sum
7. Lowest Common Ancestor
8. Path Sum
9. Path Sum II
10. Path Sum III
11. Serialize and Deserialize Binary Tree
12. Construct Binary Tree from Preorder and Inorder

### Must Master

- Preorder
- Inorder
- Postorder
- Recursive DFS
- Return-value DFS
- Global-answer DFS
- Tree DP

---

## 3.2 Binary Trees — BFS / Views

**12 problems**

1. Binary Tree Level Order Traversal
2. Zigzag Level Order Traversal
3. Right Side View
4. Average of Levels
5. Minimum Depth
6. Maximum Width
7. Populating Next Right Pointers
8. Vertical Order Traversal
9. Binary Tree Vertical Order Traversal
10. Bottom Left Value
11. Cousins in Binary Tree
12. Find Largest Value in Each Tree Row

### Must Know

- Queue
- Level-size technique
- BFS
- DFS equivalent
- Tree views

---

## 3.3 BST

**12 problems**

1. Search in a BST
2. Validate BST
3. Insert into BST
4. Delete Node in BST
5. Kth Smallest Element in a BST
6. Lowest Common Ancestor of BST
7. Convert Sorted Array to BST
8. Convert BST to Greater Tree
9. Two Sum IV
10. Recover Binary Search Tree
11. Binary Search Tree Iterator
12. Balance a Binary Search Tree

### Critical Observation

> **Inorder traversal of a BST produces sorted order.**

---

# 4. Heap / Priority Queue

**12 problems**

1. Kth Largest Element
2. K Closest Points to Origin
3. Top K Frequent Elements
4. Find Median from Data Stream
5. Merge K Sorted Lists
6. Kth Smallest Element in a Sorted Matrix
7. Task Scheduler
8. Reorganize String
9. Meeting Rooms II
10. Last Stone Weight
11. Smallest Range Covering Elements from K Lists
12. IPO

### Must Know

- Min heap
- Max heap
- Top K
- Two heaps
- Heap + greedy
- Heap + sorting
- Heap + sliding window

---

# 5. Greedy

**12 problems**

1. Best Time to Buy and Sell Stock II
2. Jump Game
3. Jump Game II
4. Gas Station
5. Partition Labels
6. Assign Cookies
7. Non-overlapping Intervals
8. Merge Triplets to Form Target Triplet
9. Hand of Straights
10. Task Scheduler
11. Candy
12. Minimum Number of Arrows

### Most Important Skill

Do not simply memorize greedy solutions.

Learn to prove:

> **Why is the locally optimal decision safe?**

---

# 6. Backtracking

**12 problems**

1. Subsets
2. Subsets II
3. Permutations
4. Permutations II
5. Combination Sum
6. Combination Sum II
7. Letter Combinations of a Phone Number
8. Generate Parentheses
9. Palindrome Partitioning
10. Word Search
11. N-Queens
12. Sudoku Solver

### Template

```cpp
void solve(state) {
    if (base_condition) {
        ans.push_back(...);
        return;
    }

    for (...) {
        choose();
        solve(...);
        undo();
    }
}
```

---

# 7. Graphs

## 7.1 Graph — BFS / DFS

**12 problems**

1. Number of Islands
2. Clone Graph
3. Max Area of Island
4. Flood Fill
5. Rotting Oranges
6. Pacific Atlantic Water Flow
7. Surrounded Regions
8. Number of Provinces
9. Word Ladder
10. Open the Lock
11. Shortest Path in Binary Matrix
12. Walls and Gates

### Must Know

- Graph representation
- Grid → graph
- DFS
- BFS
- Visited array/set
- Multi-source BFS
- Shortest unweighted path
- Connected components

---

## 7.2 Topological Sort

**12 problems**

1. Course Schedule
2. Course Schedule II
3. Alien Dictionary
4. Minimum Height Trees
5. Find Eventual Safe States
6. Parallel Courses
7. Parallel Courses III
8. Sequence Reconstruction
9. Minimum Semesters
10. Sort Items by Groups Respecting Dependencies
11. Build a Matrix With Conditions
12. Strange Printer II

### Know Both

- Kahn's BFS
- DFS cycle detection

---

## 7.3 Union Find / DSU

**12 problems**

1. Number of Provinces
2. Redundant Connection
3. Redundant Connection II
4. Accounts Merge
5. Graph Valid Tree
6. Most Stones Removed with Same Row or Column
7. Number of Connected Components
8. Satisfiability of Equality Equations
9. Kruskal's Minimum Spanning Tree
10. Min Cost to Connect All Points
11. Number of Islands II
12. Checking Existence of Edge Length Limited Paths

### Must Implement from Memory

```cpp
find()
union()
```

With:

- Path compression
- Union by rank
- Union by size

---

## 7.4 Shortest Path Algorithms

**12 problems**

1. Network Delay Time
2. Cheapest Flights Within K Stops
3. Path With Minimum Effort
4. Swim in Rising Water
5. The Maze II
6. Minimum Cost to Make at Least One Valid Path
7. Shortest Path in Binary Matrix
8. Number of Ways to Arrive at Destination
9. Path With Maximum Probability
10. Find the City With the Smallest Number of Neighbors
11. Bellman-Ford style negative-edge problem
12. Floyd-Warshall all-pairs problem

### Algorithms to Know

| Algorithm | Use |
|---|---|
| BFS | Unweighted graph |
| 0-1 BFS | Edge weights 0/1 |
| Dijkstra | Non-negative weights |
| Bellman-Ford | Negative edges |
| Floyd-Warshall | All-pairs shortest paths |
| DAG shortest path | DAG |

---

# 8. Dynamic Programming

## 8.1 DP — 1D

**12 problems**

1. Climbing Stairs
2. Min Cost Climbing Stairs
3. House Robber
4. House Robber II
5. Maximum Subarray
6. Decode Ways
7. Coin Change
8. Coin Change II
9. Perfect Squares
10. Word Break
11. Partition Equal Subset Sum
12. Combination Sum IV

### Understand

- State
- Transition
- Base case
- Iteration order
- Space optimization

Do not memorize DP tables.

---

## 8.2 DP — 2D / Grid

**12 problems**

1. Unique Paths
2. Unique Paths II
3. Minimum Path Sum
4. Triangle
5. Dungeon Game
6. Longest Increasing Path in a Matrix
7. Maximal Square
8. Interleaving String
9. Edit Distance
10. Distinct Subsequences
11. Minimum Falling Path Sum
12. Cherry Pickup

---

## 8.3 DP — Subsequences / Strings

**12 problems**

1. Longest Common Subsequence
2. Longest Palindromic Subsequence
3. Longest Palindromic Substring
4. Edit Distance
5. Distinct Subsequences
6. Interleaving String
7. Word Break
8. Regex Matching
9. Wildcard Matching
10. Shortest Common Supersequence
11. Delete Operation for Two Strings
12. Minimum ASCII Delete Sum

### Critical Patterns

- LCS
- LIS
- Palindrome DP
- String matching DP
- Edit distance
- Subsequence DP

---

## 8.4 DP — Knapsack / Partition

**12 problems**

1. 0/1 Knapsack
2. Partition Equal Subset Sum
3. Target Sum
4. Coin Change
5. Coin Change II
6. Combination Sum IV
7. Ones and Zeroes
8. Last Stone Weight II
9. Rod Cutting
10. Unbounded Knapsack
11. Minimum Subset Sum Difference
12. Count of Subsets With Given Sum

### Must Know the Difference

- 0/1 Knapsack
- Unbounded Knapsack
- Subset Sum
- Partition DP
- Counting DP

---

# 9. Tries + String Algorithms

**12 problems**

1. Implement Trie
2. Design Add and Search Words
3. Word Search II
4. Replace Words
5. Search Suggestions System
6. Longest Word in Dictionary
7. Maximum XOR of Two Numbers
8. Word Squares
9. Implement strStr / substring search
10. KMP pattern matching
11. Rabin-Karp
12. Z-algorithm

### Must Understand

- Trie
- Prefix search
- Word dictionary
- XOR Trie
- KMP
- Rabin-Karp
- Z algorithm

---

# 10. Sorting Algorithms

Know implementation and complexity for:

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Heap Sort
- Counting Sort
- Radix Sort
- Bucket Sort

### Especially Important

- Merge Sort
- Quick Sort
- Heap Sort
- Counting Sort

---

# 11. Complete Graph Algorithm Checklist

## Traversal

- DFS
- BFS

## Components

- Connected Components
- Strongly Connected Components

## DAG

- Topological Sort
- Kahn's Algorithm
- DFS Topological Sort

## Shortest Path

- BFS
- 0-1 BFS
- Dijkstra
- Bellman-Ford
- Floyd-Warshall
- DAG shortest path

## MST

- Kruskal
- Prim

## Advanced

- DSU
- SCC / Kosaraju
- Tarjan
- Bridges
- Articulation Points

### Priority Note

Tarjan / Bridges / Articulation Points are lower frequency than Dijkstra, DSU, and Topological Sort, but they should not be completely skipped.

---

# 12. Advanced Data Structures

## Must Know

- Hash table
- Stack
- Queue
- Deque
- Linked List
- Heap
- BST
- Trie
- Union Find
- Segment Tree
- Fenwick Tree / BIT

## Advanced / Lower Priority

- AVL Tree
- Red-Black Tree concept
- B-Tree concept
- Sparse Table
- Ordered Set / Ordered Map
- LRU Cache
- LFU Cache

### Priority

For interviews, **Segment Tree + Fenwick Tree** are more useful than spending large amounts of time implementing AVL or Red-Black trees.

---

# 13. Bit Manipulation

**At least 10 problems**

1. Single Number
2. Single Number II
3. Single Number III
4. Number of 1 Bits
5. Counting Bits
6. Reverse Bits
7. Missing Number
8. Power of Two
9. Sum of Two Integers
10. Maximum XOR of Two Numbers

### Must Know

```cpp
x & 1
x << k
x >> k
x ^ y
x & -x
x &= (x - 1)
```

### Concepts

- XOR properties
- Bit masks
- Subsets using bits
- Brian Kernighan's algorithm

---

# 14. Math / Number Theory

At least basic interview competence.

### Know

- GCD / Euclid
- LCM
- Prime checking
- Sieve of Eratosthenes
- Modular arithmetic
- Fast exponentiation
- Modular exponentiation
- Combinations
- Permutations
- Overflow handling
- Matrix exponentiation concept

---

# 15. Advanced Array Techniques

Do not forget these because they often appear disguised inside harder questions.

- Difference arrays
- Sweep line
- Coordinate compression
- Prefix XOR
- 2D prefix sum
- Kadane
- Circular Kadane
- Dutch National Flag
- Meet in the middle
- Offline queries

---

# 16. Tiered Priority

## Tier 1 — Absolutely Master

1. Arrays + Hashing
2. Two Pointers
3. Sliding Window
4. Prefix Sum
5. Binary Search
6. Stack
7. Monotonic Stack
8. Linked List
9. Trees DFS
10. Trees BFS
11. BST
12. Heap
13. Intervals
14. Greedy
15. Backtracking
16. Graph BFS/DFS
17. Topological Sort
18. DSU
19. Dijkstra
20. DP 1D
21. DP 2D
22. Knapsack
23. LCS/LIS/String DP
24. Trie

These are the areas where the target is **10–12 problems per pattern**.

---

## Tier 2 — Strong

- 0-1 BFS
- Bellman-Ford
- Floyd-Warshall
- Kruskal
- Prim
- SCC
- Bridges
- Articulation Points
- Segment Tree
- Fenwick Tree
- KMP
- Rabin-Karp
- Z Algorithm
- Bit manipulation
- Sweep line
- Coordinate compression
- Meet in the middle

---

# 17. Eight-Week Strategy

If approximately 8 weeks are available:

## Week 1 — Array Foundation

### Day 1
- Arrays
- Hashing
- 10–12 problems

### Day 2
- Two Pointers
- 10–12 problems

### Day 3
- Sliding Window
- 10–12 problems

### Day 4
- Prefix Sum
- Difference Array
- 10–12 problems

### Day 5
- Binary Search I
- 10–12 problems

### Day 6
- Binary Search II
- Binary Search on Answer

### Day 7
- Revision
- 5 mixed problems
- 1 timed contest

---

# 18. Week 2 — Core Data Structures

### Day 8
Linked List

### Day 9
Linked List Advanced

### Day 10
Stack / Queue

### Day 11
Monotonic Stack

### Day 12
Heap

### Day 13
Intervals + Greedy

### Day 14
Full Revision + Mock

---

# 19. Week 3 — Trees

### Day 15
Tree Traversal

### Day 16
Tree DFS

### Day 17
Tree Path Problems

### Day 18
Tree BFS

### Day 19
BST

### Day 20
Tree Hard Problems

### Day 21
Tree Revision + Mock

---

# 20. Week 4 — Graphs

### Day 22
Graph Representation + DFS

### Day 23
BFS + Grid

### Day 24
Topological Sort

### Day 25
DSU

### Day 26
Dijkstra

### Day 27
MST + Bellman-Ford + 0-1 BFS

### Day 28
Graph Revision + Mock

---

# 21. Week 5 — Dynamic Programming

This should be one of the most important weeks.

### Day 29
DP Fundamentals + 1D

### Day 30
Knapsack

### Day 31
Subset / Partition

### Day 32
Grid DP

### Day 33
LCS / LIS

### Day 34
String DP

### Day 35
DP Revision + Mock

---

# 22. Week 6 — Advanced Patterns

### Day 36
Backtracking

### Day 37
Trie

### Day 38
Bit Manipulation

### Day 39
String Algorithms

### Day 40
Segment Tree

### Day 41
Fenwick + Advanced Data Structures

### Day 42
Advanced Mixed Problems

---

# 23. Week 7 — Interview Pattern Mixing

Stop organizing problems only by topic.

Instead of:

> "Today is Sliding Window."

Switch to:

> "Here is a random problem. Identify the pattern."

### Every Day

**Block 1**
- 5 random Medium problems

**Block 2**
- 2 Hard problems

**Block 3**
- 1 timed problem

**Block 4**
- Review mistakes

Mix:

- Arrays
- Binary Search
- Trees
- Graphs
- DP
- Greedy
- Heap
- Stack
- Backtracking

---

# 24. Week 8 — Placement Simulation

This week should NOT focus on learning large amounts of new DSA.

### Every Day

**Morning**
- 1 Easy warm-up

**Main Session**
- 2 Medium
- 1 Hard

**Evening**
- 45–60 minute mock interview

**Night**
- Error log revision

---

# 25. Difficulty Distribution

For each major pattern, use approximately:

### Standard Pattern

- 2 Easy
- 7 Medium
- 3 Hard

### Difficult Pattern such as DP / Graphs

- 1 Easy
- 8 Medium
- 3 Hard

The objective is not:

> 12 Easy + 12 Easy + 12 Easy

The objective is interview competence.

---

# 26. Target Numbers

| Category | Target |
|---|---:|
| Major patterns | 24 |
| Problems per pattern | 12 |
| Core DSA problems | **288** |
| Advanced algorithm problems | ~40–50 |
| Mock interviews | 15–20 |
| Timed sets | 15+ |
| Re-solved problems | 100+ |

### Important

Do NOT interpret 288 as 288 completely new LeetCode questions.

A better target is:

> **~200–250 unique questions + ~100 strategic re-solves.**

This is much more valuable than blindly completing 400+ questions.

---

# 27. DSA Revision Notebook

Maintain one small document.

For every important problem, record only:

```text
Problem:
Pattern:
Key observation:
Brute:
Optimal:
Time:
Space:
Mistake:
```

### Example

```text
Problem: Subarray Sum Equals K

Pattern:
Prefix Sum + HashMap

Observation:
sum[i] - sum[j] = k
=> sum[j] = sum[i] - k

Optimal:
Maintain frequency of prefix sums.

Time: O(n)
Space: O(n)

Mistake:
Forgot to initialize mp[0] = 1
```

This notebook becomes the primary material for the final 1–2 days of revision.

---

# 28. C++ Interview Readiness

DSA preparation should be accompanied by C++ readiness.

### STL

- vector
- unordered_map
- map
- set
- unordered_set
- priority_queue
- deque
- stack
- queue
- custom comparator
- lambda functions

### C++ Fundamentals

- References
- Pointers
- const
- Memory
- Recursion
- Stack vs heap
- Pass by value vs reference
- Object lifetime
- Basic OOP

---

# 29. Core CS Preparation

Big-tech placement preparation should not be DSA-only.

Also revise:

- OOP
- DBMS
- Operating Systems
- Computer Networks
- SQL
- System Design basics
- C++ fundamentals

After coding rounds, these can become major differentiators.

---

# 30. Final Interview Standard

The most important metric is NOT:

> "How many LeetCode questions have I solved?"

The actual metric is:

> **Can I identify the pattern within 2–3 minutes and produce the optimal solution within 15–25 minutes without help?**

For a strong big-tech interview candidate, the target should be:

1. Recognize the pattern quickly.
2. State the brute-force approach.
3. Derive the optimization.
4. Explain the invariant.
5. Code cleanly.
6. Analyze time and space complexity.
7. Test edge cases.
8. Communicate while solving.
9. Handle follow-up variations.
10. Solve unseen problems, not only previously memorized ones.

---

# 31. Recommended Priority Order

## P0 — Absolutely Master

```text
Arrays
→ Hashing
→ Two Pointers
→ Sliding Window
→ Binary Search
→ Stack
→ Linked List
→ Trees
→ Heap
→ Graphs
→ DP
```

## P1 — Strong

```text
Intervals
→ Greedy
→ Backtracking
→ Trie
→ DSU
→ Topological Sort
→ Dijkstra
→ Bit Manipulation
```

## P2 — Advanced

```text
MST
→ Bellman-Ford
→ 0-1 BFS
→ SCC
→ Bridges
→ Articulation Points
→ Segment Tree
→ Fenwick Tree
→ KMP
→ Z Algorithm
→ Rabin-Karp
→ Advanced DP
```

---

# 32. Final Preparation Philosophy

The preparation should progress through three stages.

## Stage 1 — Learn

Understand each pattern and its canonical implementation.

## Stage 2 — Practice

Solve 10–12 carefully selected problems per major pattern.

## Stage 3 — Randomize

Mix all patterns and solve unseen problems under time pressure.

The third stage is essential because being able to solve a familiar problem is not the same as being able to recognize the correct approach in an interview.

---

# Final Goal

By the end of the preparation period, aim to reach this state:

> **I don't need to remember a specific problem. I can look at a new problem, identify the underlying pattern, derive the optimal approach, implement it in C++, and explain the solution clearly under interview pressure.**
