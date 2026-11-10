# 🚀 DSA & LeetCode Practice Repository

## 📌 About
This repository contains my **Data Structures & Algorithms (DSA)** and **SQL** practice solutions from LeetCode, written primarily in **Java**, along with **SQL** and **Shell** solutions. I consistently solve problems to strengthen my problem-solving skills and prepare for technical interviews.

---

## 💻 Platform
- **LeetCode** ([Profile](https://leetcode.com/u/Ayush_Abhinav05/))

---

## 📊 Progress Tracker
- ✅ **Total Solution Files:** 227 (`224` unique problems + `3` duplicate/alternate solutions)
- 📅 **Active Practice Span:** April 14, 2026 – November 10, 2026 (`229` commits)
- 🛠️ **Languages Used:**
  - **Java:** 204 solutions
  - **SQL:** 22 solutions
  - **Shell:** 1 solution

> **Note:** The repository also includes `Graph/Intro.text` (a brief note file), and three problems appear in two locations (`Leetcode_189.java` & `LeetCode Submissions/Leetcode_189.java`, `Find the Winner of the Circular Game` & `Queues/Find the Winner of the Circular Game`, and `find the index of first occurance in string` & `Strings/Find the Index of the First Occurrence in a String`).

---

## 💡 DSA Skills Overview
Across **224 unique problems** (`227` solution files in Java, SQL, and Shell), this repository demonstrates progression from foundational problem solving to advanced competitive and interview-grade techniques:
- **Core Fluency:** Strong command of arrays, strings, hashing, two pointers, sliding windows, prefix sums, and in-place linked list pointer manipulation.
- **Trees & Graphs:** Extensive practice across binary trees, BSTs, multi-source BFS, grid DFS, topological sorting (Kahn's algorithm), bipartite checking, cycle detection, Prim's MST, Bellman-Ford, and state-space Dijkstra.
- **Advanced & Contest-Level Techniques:** Implemented complex structures and optimizations from scratch, including **Segment Trees with Lazy Propagation**, **Dual-`TreeMap` Sliding Window Median + DP**, **Doubly Linked List + HashMap (`LRUCache`)**, **Trie (Prefix Tree)**, **Difference Arrays + Binary Search on Answer**, and **Offline Query Sorting**.
- **Database & Scripting:** Solid relational querying skills in **SQL** (`22` solutions covering `JOIN`s, `GROUP BY`/`HAVING`, and subqueries) alongside **Shell** (`sed`).

---

## 🧱 Data Structures Solved

| Data Structure | Usage & Highlights | Example Solutions |
|---|---|---|
| **Arrays & 2D Grids** | Prefix sums, difference arrays, in-place partitioning, matrix traversal | [Minimum Initial Strength to Defeat All Monsters](./Arrays/Minimum%20Initial%20Strength%20to%20Defeat%20All%20Monsters), [Number of Closed Islands](./Arrays/Number%20of%20Closed%20Islands) |
| **HashMap & HashSet** | Frequency counting, lookup optimization, subarray sum hashing, graph/LRU mapping | [Leetcode_560](./Leetcode_560), [Group Anagrams](./Strings/Group%20Anagrams), [Contains Duplicate II](./Arrays/Contains%20Duplicate%20II) |
| **Linked List (Singly & Doubly)** | Custom node classes, dummy heads, fast/slow pointers, O(1) LRU eviction | [LRU Cache](./Linked%20List/LRU%20Cache), [Design Linked List](./Linked%20List/Design%20Linked%20List), [Reverse-Nodes-In-K_Groups](./Linked%20List/Reverse-Nodes-In-K_Groups) |
| **Stack & Monotonic Stack** | Parentheses matching, expression decoding, lexicographical subsequence | [Decode String](./Stack/Decode%20String), [Longest_Valid_Paranthesis](./Stack/Longest_Valid_Paranthesis), [Smallest Subsequence of Distinct Characters](./Strings/Smallest%20Subsequence%20of%20Distinct%20Characters) |
| **Queue** | BFS level-order traversal, multi-source propagation, simulation | [Rotting Oranges](./Graph/Rotting%20Oranges), [Time Needed to Buy Tickets](./Queues/Time%20Needed%20to%20Buy%20Tickets) |
| **Binary Tree & BST** | Recursive & iterative traversals, LCA, BST validation/construction | [Lowest Common Ancestor of a Binary Tree](./Binary%20Tree/Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree), [Unique Binary Search Trees II](./Binary%20Tree/Unique%20Binary%20Search%20Trees%20II) |
| **Heap / PriorityQueue** | Dual-heap task scheduling, Prim's MST, state-space Dijkstra | [Process Tasks Using Servers](./Arrays/Process%20Tasks%20Using%20Servers), [Min Cost to Connect All Points](./Graph/Min%20Cost%20to%20Connect%20All%20Points) |
| **Balanced BST (`TreeMap`)** | Dual-`TreeMap` sliding window median maintenance | [Minimum Operations to Make Elements Within K Subarrays Equal](./Arrays/Minimum%20Operations%20to%20Make%20Elements%20Within%20K%20Subarrays%20Equal) |
| **Trie (Prefix Tree)** | Custom `TrieNode` insertion, word search, prefix matching | [Implement Trie (Prefix Tree)](./Implement%20Trie%20%28Prefix%20Tree%29), [Longest-Common-Prefix](./Tries/Longest-Common-Prefix) |
| **Segment Tree (Lazy Propagation)** | Range updates & squared distinct element queries modulo 10⁹+7 | [Subarrays Distinct Element Sum of Squares II](./Arrays/Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20II) |

---

## 🧩 Algorithmic Patterns Solved

| Pattern | Example Solutions |
|---|---|
| **Two Pointers & Sliding Window** | [Longest Substring Without Repeating Characters](./Strings/Longest%20Substring%20Without%20Repeating%20Characters), [Minimum Size Subarray Sum](./Arrays/Minimum%20Size%20Subarray%20Sum), [Count Zero Request Servers](./Arrays/Count%20Zero%20Request%20Servers) |
| **Binary Search & Search on Answer** | [Find Minimum in Rotated Sorted Array II](./Arrays/Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II), [Find the Duplicate Number](./Binary%20Search/Find%20the%20Duplicate%20Number), [Heaters](./Binary%20Search/Heaters), [Minimum Initial Strength to Defeat All Monsters](./Arrays/Minimum%20Initial%20Strength%20to%20Defeat%20All%20Monsters) |
| **Prefix Sum & Difference Array** | [Range Sum Query - Immutable](./Arrays/Range%20Sum%20Query%20-%20Immutable), [Leetcode_560](./Leetcode_560), [Left and Right Sum Differences](./Arrays/Left%20and%20Right%20Sum%20Differences) |
| **Fast & Slow Pointers** | [Middle of the Linked List](./Linked%20List/Middle%20of%20the%20Linked%20List), [Delete the Middle Node of a Linked List](./Linked%20List/Delete%20the%20Middle%20Node%20of%20a%20Linked%20List), [Remove Nth Node From End of List](./Linked%20List/Remove%20Nth%20Node%20From%20End%20of%20List) |
| **Breadth-First Search (BFS / Multi-Source)** | [Binary Tree Zigzag Level Order Traversal](./Binary%20Tree/Binary%20Tree%20Zigzag%20Level%20Order%20Traversal), [Rotting Oranges](./Graph/Rotting%20Oranges), [Is Graph Bipartite?](./Graph/Is%20Graph%20Bipartite%3F) |
| **Depth-First Search (DFS / Grid)** | [Surrounded Regions](./Graph/Surrounded%20Regions), [Number of Provinces](./Graph/Number%20of%20Provinces), [All Paths From Source to Target](./Graph/All%20Paths%20From%20Source%20to%20Target) |
| **Topological Sort & Graph Peeling** | [Course Schedule](./Graph/Course%20Schedule), [Course Schedule II](./Graph/Course%20Schedule%20II), [Minimum Height Trees](./Graph/Minimum%20Height%20Trees) |
| **Shortest Path & MST** | [Shortest Path With At Most K Consecutive Identical Characters](./Graph/Shortest%20Path%20With%20At%20Most%20K%20Consecutive%20Identical%20Characters) (Dijkstra), [Network Delay Time](./Graph/Network%20Delay%20Time) (Bellman-Ford), [Cheapest Flights Within K Stops](./Graph/Cheapest%20Flights%20Within%20K%20Stops), [Min Cost to Connect All Points](./Graph/Min%20Cost%20to%20Connect%20All%20Points) (Prim's) |
| **Backtracking** | [N-Queens](./Arrays/N-Queens), [Permutation](./Arrays/Permutation), [Combination Sum](./Combination%20Sum), [Palindrome Partitioning](./Strings/Palindrome%20Partitioning), [Generate Parentheses](./Generate%20Parentheses) |
| **Dynamic Programming** | [Best Time to Buy and Sell Stock III](./Arrays/Best%20Time%20to%20Buy%20and%20Sell%20Stock%20III), [Minimum Path Sum](./Arrays/Minimum%20Path%20Sum), [Triangle](./Triangle), [Climbing Stairs](./Climbing%20Stairs) |
| **Greedy & Sorting / Divide & Conquer** | [Gas Station](./Gas%20Station), [H-Index](./Arrays/H-Index), [Sort List](./Linked%20List/Sort%20List) (Merge Sort), [Sort_Array(Quick Sort)](./Sort_Array%28Quick%20Sort%29) |
| **Bit Manipulation & Math** | [Find the Difference](./Strings/Find%20the%20Difference) (XOR), [Maximum K to Sort a Permutation](./Arrays/Maximum%20K%20to%20Sort%20a%20Permutation) (Bitwise AND), [Number of Digit One](./Number%20of%20Digit%20One), [Factorial Trailing Zeroes](./Factorial%20Trailing%20Zeroes) |
| **SQL Querying** | [Students and Examinations](./SQL/Students%20and%20Examinations), [Department Highest Salary](./SQL/Department%20Highest%20Salary), [Confirmation Rate](./SQL/Confirmation%20Rate) |

---

## 🧠 Categories Solved

| Category | Solutions | Notes |
|---|---:|---|
| **Arrays** | 73 | Sorting, Two Pointers, Sliding Window, Prefix Sum, Backtracking, DP |
| **Binary Search** | 8 | Search Space Reduction, Lower/Upper Bound |
| **Binary Search Tree** | 3 | BST Properties & Traversals |
| **Binary Tree** | 14 | DFS, BFS / Level Order, Recursion |
| **Graph** | 14 | BFS, DFS, Topological Sort, Dijkstra, Bellman-Ford, Prim's MST, Bipartite Coloring (plus `Intro.text`) |
| **Linked List** | 19 | Fast/Slow Pointers, Reversal, LRU Cache, Merge/Sort |
| **Queues** | 2 | Queue Simulation |
| **SQL** | 21 | Joins, Aggregations, Subqueries, Filtering |
| **Stack** | 5 | Monotonic Stack, Parentheses, Expression Decoding |
| **Strings** | 31 | Sliding Window, Hashing, Backtracking, Greedy |
| **Tries** | 1 | Prefix Matching |
| **LeetCode Contest - 26-04-2026** | 2 | Contest submissions (April 26, 2026) |
| **LeetCode Submissions** | 1 | Additional submission (`Leetcode_189.java`) |
| **Root (Uncategorized)** | 33 | Standalone Java, SQL (`Classes With at Least 5 Students`), and Shell (`Tenth Line`) solutions |
| **Total** | **227** | |

---

## 📂 Problem Index
Click any section below to browse all solutions with direct links to the source files.

<details>
<summary><strong>Arrays</strong> (73 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Best Time to Buy and Sell Stock II](./Arrays/Best%20Time%20to%20Buy%20and%20Sell%20Stock%20II) | Java | 2026-07-09 |
| 2 | [Best Time to Buy and Sell Stock III](./Arrays/Best%20Time%20to%20Buy%20and%20Sell%20Stock%20III) | Java | 2026-07-10 |
| 3 | [Build an Array With Stack Operations](./Arrays/Build%20an%20Array%20With%20Stack%20Operations) | Java | 2026-05-15 |
| 4 | [Can Place Flowers](./Arrays/Can%20Place%20Flowers) | Java | 2026-08-13 |
| 5 | [Check if Array Is Sorted and Rotated](./Arrays/Check%20if%20Array%20Is%20Sorted%20and%20Rotated) | Java | 2026-05-28 |
| 6 | [Construct Uniform Parity Array I](./Arrays/Construct%20Uniform%20Parity%20Array%20I) | Java | 2026-09-02 |
| 7 | [Construct Uniform Parity Array II](./Arrays/Construct%20Uniform%20Parity%20Array%20II) | Java | 2026-09-03 |
| 8 | [Contains Duplicate II](./Arrays/Contains%20Duplicate%20II) | Java | 2026-08-10 |
| 9 | [Count Islands With Total Value Divisible by K](./Arrays/Count%20Islands%20With%20Total%20Value%20Divisible%20by%20K) | Java | 2026-10-26 |
| 10 | [Count Zero Request Servers](./Arrays/Count%20Zero%20Request%20Servers) | Java | 2026-11-06 |
| 11 | [Create Grid With Exactly One Path](./Arrays/Create%20Grid%20With%20Exactly%20One%20Path) | Java | 2026-10-27 |
| 12 | [Distribute Elements Into Two Arrays I](./Arrays/Distribute%20Elements%20Into%20Two%20Arrays%20I) | Java | 2026-08-20 |
| 13 | [Earliest Finish Time for Land and Water Rides I](./Arrays/Earliest%20Finish%20Time%20for%20Land%20and%20Water%20Rides%20I) | Java | 2026-06-02 |
| 14 | [Find All Numbers Disappeared in an Array](./Arrays/Find%20All%20Numbers%20Disappeared%20in%20an%20Array) | Java | 2026-05-13 |
| 15 | [Find Greatest Common Divisor of Array](./Arrays/Find%20Greatest%20Common%20Divisor%20of%20Array) | Java | 2026-07-18 |
| 16 | [Find Minimum in Rotated Sorted Array](./Arrays/Find%20Minimum%20in%20Rotated%20Sorted%20Array) | Java | 2026-05-15 |
| 17 | [Find Minimum in Rotated Sorted Array II](./Arrays/Find%20Minimum%20in%20Rotated%20Sorted%20Array%20II) | Java | 2026-05-16 |
| 18 | [Find Missing Elements](./Arrays/Find%20Missing%20Elements) | Java | 2026-08-04 |
| 19 | [Finding 3-Digit Even Numbers](./Arrays/Finding%203-Digit%20Even%20Numbers) | Java | 2026-09-27 |
| 20 | [First Letter to Appear Twice](./Arrays/First%20Letter%20to%20Appear%20Twice) | Java | 2026-09-26 |
| 21 | [H-Index](./Arrays/H-Index) | Java | 2026-07-03 |
| 22 | [How Many Numbers Are Smaller Than the Current Number](./Arrays/How%20Many%20Numbers%20Are%20Smaller%20Than%20the%20Current%20Number) | Java | 2026-05-14 |
| 23 | [Intersection of Two Arrays](./Arrays/Intersection%20of%20Two%20Arrays) | Java | 2026-07-12 |
| 24 | [Intersection of Two Arrays II](./Arrays/Intersection%20of%20Two%20Arrays%20II) | Java | 2026-07-17 |
| 25 | [Island Perimeter](./Arrays/Island%20Perimeter) | Java | 2026-08-12 |
| 26 | [Left and Right Sum Differences](./Arrays/Left%20and%20Right%20Sum%20Differences) | Java | 2026-06-06 |
| 27 | [Maximum Alternating Sum of Squares](./Arrays/Maximum%20Alternating%20Sum%20of%20Squares) | Java | 2026-10-13 |
| 28 | [Maximum Element After Decreasing and Rearranging](./Arrays/Maximum%20Element%20After%20Decreasing%20and%20Rearranging) | Java | 2026-06-28 |
| 29 | [Maximum Ice Cream Bars](./Arrays/Maximum%20Ice%20Cream%20Bars) | Java | 2026-06-21 |
| 30 | [Maximum K to Sort a Permutation](./Arrays/Maximum%20K%20to%20Sort%20a%20Permutation) | Java | 2026-10-24 |
| 31 | [Maximum Product of Three Numbers](./Arrays/Maximum%20Product%20of%20Three%20Numbers) | Java | 2026-07-26 |
| 32 | [Maximum Product of Two Elements in an Array](./Arrays/Maximum%20Product%20of%20Two%20Elements%20in%20an%20Array) | Java | 2026-07-27 |
| 33 | [Maximum Total Subarray Value I](./Arrays/Maximum%20Total%20Subarray%20Value%20I) | Java | 2026-04-25 |
| 34 | [Minimum Common Value](./Arrays/Minimum%20Common%20Value) | Java | 2026-05-19 |
| 35 | [Minimum Element After Replacement With Digit Sum](./Arrays/Minimum%20Element%20After%20Replacement%20With%20Digit%20Sum) | Java | 2026-05-29 |
| 36 | [Minimum Initial Strength to Defeat All Monsters](./Arrays/Minimum%20Initial%20Strength%20to%20Defeat%20All%20Monsters) | Java | 2026-08-01 |
| 37 | [Minimum Moves to Equal Array Elements](./Arrays/Minimum%20Moves%20to%20Equal%20Array%20Elements) | Java | 2026-11-01 |
| 38 | [Minimum Moves to Equal Array Elements II](./Arrays/Minimum%20Moves%20to%20Equal%20Array%20Elements%20II) | Java | 2026-11-02 |
| 39 | [Minimum Moves to Equal Array Elements III](./Arrays/Minimum%20Moves%20to%20Equal%20Array%20Elements%20III) | Java | 2026-11-03 |
| 40 | [Minimum Operations to Make Elements Within K Subarrays Equal](./Arrays/Minimum%20Operations%20to%20Make%20Elements%20Within%20K%20Subarrays%20Equal) | Java | 2026-11-04 |
| 41 | [Minimum Operations to Sort a Permutation](./Arrays/Minimum%20Operations%20to%20Sort%20a%20Permutation) | Java | 2026-10-22 |
| 42 | [Minimum Path Sum](./Arrays/Minimum%20Path%20Sum) | Java | 2026-06-20 |
| 43 | [Minimum Size Subarray Sum](./Arrays/Minimum%20Size%20Subarray%20Sum) | Java | 2026-10-29 |
| 44 | [Minimum Swaps to Move Zeros to End](./Arrays/Minimum%20Swaps%20to%20Move%20Zeros%20to%20End) | Java | 2026-05-23 |
| 45 | [Minimum Swaps to Sort by Digit Sum](./Arrays/Minimum%20Swaps%20to%20Sort%20by%20Digit%20Sum) | Java | 2026-10-17 |
| 46 | [Most Frequent Even Element](./Arrays/Most%20Frequent%20Even%20Element) | Java | 2026-09-05 |
| 47 | [Move Zeroes](./Arrays/Move%20Zeroes) | Java | 2026-08-19 |
| 48 | [N-Queens](./Arrays/N-Queens) | Java | 2026-10-07 |
| 49 | [Number of Closed Islands](./Arrays/Number%20of%20Closed%20Islands) | Java | 2026-10-25 |
| 50 | [Partition Array According to Given Pivot](./Arrays/Partition%20Array%20According%20to%20Given%20Pivot) | Java | 2026-06-08 |
| 51 | [Pascal's Triangle](./Arrays/Pascal%27s%20Triangle) | Java | 2026-06-14 |
| 52 | [Permutation](./Arrays/Permutation) | Java | 2026-05-13 |
| 53 | [Process Tasks Using Servers](./Arrays/Process%20Tasks%20Using%20Servers) | Java | 2026-11-07 |
| 54 | [Range Sum Query - Immutable](./Arrays/Range%20Sum%20Query%20-%20Immutable) | Java | 2026-08-28 |
| 55 | [Rank Transform of an Array](./Arrays/Rank%20Transform%20of%20an%20Array) | Java | 2026-07-13 |
| 56 | [Rectangle Overlap](./Arrays/Rectangle%20Overlap) | Java | 2026-09-14 |
| 57 | [Relative Ranks](./Arrays/Relative%20Ranks) | Java | 2026-09-07 |
| 58 | [Remove Duplicates from Sorted Array II](./Arrays/Remove%20Duplicates%20from%20Sorted%20Array%20II) | Java | 2026-06-23 |
| 59 | [Removing Minimum and Maximum From Array](./Arrays/Removing%20Minimum%20and%20Maximum%20From%20Array) | Java | 2026-08-30 |
| 60 | [Set Mismatch](./Arrays/Set%20Mismatch) | Java | 2026-05-12 |
| 61 | [Shift 2D Grid](./Arrays/Shift%202D%20Grid) | Java | 2026-07-20 |
| 62 | [Smallest Index With Digit Sum Equal to Index](./Arrays/Smallest%20Index%20With%20Digit%20Sum%20Equal%20to%20Index) | Java | 2026-09-24 |
| 63 | [Smallest Missing Integer Greater Than Sequential Prefix Sum](./Arrays/Smallest%20Missing%20Integer%20Greater%20Than%20Sequential%20Prefix%20Sum) | Java | 2026-08-11 |
| 64 | [Smallest Missing Multiple of K](./Arrays/Smallest%20Missing%20Multiple%20of%20K) | Java | 2026-08-25 |
| 65 | [Smallest Stable Index I](./Arrays/Smallest%20Stable%20Index%20I) | Java | 2026-09-04 |
| 66 | [Sort Colors](./Arrays/Sort%20Colors) | Java | 2026-07-17 |
| 67 | [Subarrays Distinct Element Sum of Squares I](./Arrays/Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20I) | Java | 2026-10-15 |
| 68 | [Subarrays Distinct Element Sum of Squares II](./Arrays/Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20II) | Java | 2026-10-16 |
| 69 | [Sum of Squares of Special Elements](./Arrays/Sum%20of%20Squares%20of%20Special%20Elements) | Java | 2026-10-11 |
| 70 | [Summary Ranges](./Arrays/Summary%20Ranges) | Java | 2026-06-07 |
| 71 | [Third Maximum Number](./Arrays/Third%20Maximum%20Number) | Java | 2026-07-11 |
| 72 | [Unique 3-Digit Even Numbers](./Arrays/Unique%203-Digit%20Even%20Numbers) | Java | 2026-09-11 |
| 73 | [Wiggle Sort II](./Arrays/Wiggle%20Sort%20II) | Java | 2026-11-08 |

</details>

<details>
<summary><strong>Binary Search</strong> (8 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [4sum](./Binary%20Search/4sum) | Java | 2026-05-10 |
| 2 | [Find Peak Element](./Binary%20Search/Find%20Peak%20Element) | Java | 2026-07-21 |
| 3 | [Find the Duplicate Number](./Binary%20Search/Find%20the%20Duplicate%20Number) | Java | 2026-07-22 |
| 4 | [Guess Number Higher or Lower](./Binary%20Search/Guess%20Number%20Higher%20or%20Lower) | Java | 2026-09-23 |
| 5 | [Heaters](./Binary%20Search/Heaters) | Java | 2026-09-25 |
| 6 | [Peak Index in a Mountain Array](./Binary%20Search/Peak%20Index%20in%20a%20Mountain%20Array) | Java | 2026-06-10 |
| 7 | [Two Sum II - Input Array Is Sorted](./Binary%20Search/Two%20Sum%20II%20-%20Input%20Array%20Is%20Sorted) | Java | 2026-07-02 |
| 8 | [Valid Perfect Square](./Binary%20Search/Valid%20Perfect%20Square) | Java | 2026-09-12 |

</details>

<details>
<summary><strong>Binary Search Tree</strong> (3 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Construct Binary Search Tree from Preorder Traversal](./Binary%20Search%20Tree/Construct%20Binary%20Search%20Tree%20from%20Preorder%20Traversal) | Java | 2026-07-08 |
| 2 | [Find Mode in Binary Search Tree](./Binary%20Search%20Tree/Find%20Mode%20in%20Binary%20Search%20Tree) | Java | 2026-04-24 |
| 3 | [Minimum Absolute Difference in BST](./Binary%20Search%20Tree/Minimum%20Absolute%20Difference%20in%20BST) | Java | 2026-06-27 |

</details>

<details>
<summary><strong>Binary Tree</strong> (14 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Average of Levels in Binary Tree](./Binary%20Tree/Average%20of%20Levels%20in%20Binary%20Tree) | Java | 2026-05-07 |
| 2 | [Binary Tree Paths](./Binary%20Tree/Binary%20Tree%20Paths) | Java | 2026-05-31 |
| 3 | [Binary Tree Right Side View](./Binary%20Tree/Binary%20Tree%20Right%20Side%20View) | Java | 2026-07-28 |
| 4 | [Binary Tree Zigzag Level Order Traversal](./Binary%20Tree/Binary%20Tree%20Zigzag%20Level%20Order%20Traversal) | Java | 2026-06-25 |
| 5 | [Find Bottom Left Tree Value](./Binary%20Tree/Find%20Bottom%20Left%20Tree%20Value) | Java | 2026-10-09 |
| 6 | [Find Largest Value in Each Tree Row](./Binary%20Tree/Find%20Largest%20Value%20in%20Each%20Tree%20Row) | Java | 2026-06-26 |
| 7 | [Increasing Order Search Tree](./Binary%20Tree/Increasing%20Order%20Search%20Tree) | Java | 2026-10-01 |
| 8 | [Kth Smallest Element in a BST](./Binary%20Tree/Kth%20Smallest%20Element%20in%20a%20BST) | Java | 2026-09-13 |
| 9 | [Lowest Common Ancestor of a Binary Tree](./Binary%20Tree/Lowest%20Common%20Ancestor%20of%20a%20Binary%20Tree) | Java | 2026-09-17 |
| 10 | [Minimum Distance Between BST Nodes](./Binary%20Tree/Minimum%20Distance%20Between%20BST%20Nodes) | Java | 2026-06-13 |
| 11 | [Sum of Left Leaves](./Binary%20Tree/Sum%20of%20Left%20Leaves) | Java | 2026-06-01 |
| 12 | [Sum Root to Leaf Numbers](./Binary%20Tree/Sum%20Root%20to%20Leaf%20Numbers) | Java | 2026-09-22 |
| 13 | [Two Sum IV - Input is a BST](./Binary%20Tree/Two%20Sum%20IV%20-%20Input%20is%20a%20BST) | Java | 2026-10-10 |
| 14 | [Unique Binary Search Trees II](./Binary%20Tree/Unique%20Binary%20Search%20Trees%20II) | Java | 2026-10-18 |

</details>

<details>
<summary><strong>Graph</strong> (14 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [All Paths From Source to Target](./Graph/All%20Paths%20From%20Source%20to%20Target) | Java | 2026-08-26 |
| 2 | [Cheapest Flights Within K Stops](./Graph/Cheapest%20Flights%20Within%20K%20Stops) | Java | 2026-08-21 |
| 3 | [Course Schedule](./Graph/Course%20Schedule) | Java | 2026-05-11 |
| 4 | [Course Schedule II](./Graph/Course%20Schedule%20II) | Java | 2026-08-05 |
| 5 | [Find Eventual Safe States](./Graph/Find%20Eventual%20Safe%20States) | Java | 2026-10-20 |
| 6 | [Is Graph Bipartite?](./Graph/Is%20Graph%20Bipartite%3F) | Java | 2026-08-03 |
| 7 | [Jump Game III](./Graph/Jump%20Game%20III) | Java | 2026-05-17 |
| 8 | [Min Cost to Connect All Points](./Graph/Min%20Cost%20to%20Connect%20All%20Points) | Java | 2026-08-24 |
| 9 | [Minimum Height Trees](./Graph/Minimum%20Height%20Trees) | Java | 2026-08-15 |
| 10 | [Network Delay Time](./Graph/Network%20Delay%20Time) | Java | 2026-08-22 |
| 11 | [Number of Provinces](./Graph/Number%20of%20Provinces) | Java | 2026-10-21 |
| 12 | [Rotting Oranges](./Graph/Rotting%20Oranges) | Java | 2026-10-14 |
| 13 | [Shortest Path With At Most K Consecutive Identical Characters](./Graph/Shortest%20Path%20With%20At%20Most%20K%20Consecutive%20Identical%20Characters) | Java | 2026-10-30 |
| 14 | [Surrounded Regions](./Graph/Surrounded%20Regions) | Java | 2026-10-31 |

</details>

<details>
<summary><strong>Linked List</strong> (19 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Add-Two-Numbers](./Linked%20List/Add-Two-Numbers) | Java | 2026-04-18 |
| 2 | [Delete Node in a Linked List](./Linked%20List/Delete%20Node%20in%20a%20Linked%20List) | Java | 2026-06-04 |
| 3 | [Delete the Middle Node of a Linked List](./Linked%20List/Delete%20the%20Middle%20Node%20of%20a%20Linked%20List) | Java | 2026-06-15 |
| 4 | [Design Linked List](./Linked%20List/Design%20Linked%20List) | Java | 2026-08-08 |
| 5 | [Find the Minimum and Maximum Number of Nodes Between Critical Points](./Linked%20List/Find%20the%20Minimum%20and%20Maximum%20Number%20of%20Nodes%20Between%20Critical%20Points) | Java | 2026-08-31 |
| 6 | [Flatten Binary Tree to Linked List](./Linked%20List/Flatten%20Binary%20Tree%20to%20Linked%20List) | Java | 2026-05-05 |
| 7 | [Insertion Sort List](./Linked%20List/Insertion%20Sort%20List) | Java | 2026-09-01 |
| 8 | [Linked List Components](./Linked%20List/Linked%20List%20Components) | Java | 2026-07-01 |
| 9 | [Linked List Random Node](./Linked%20List/Linked%20List%20Random%20Node) | Java | 2026-07-24 |
| 10 | [LRU Cache](./Linked%20List/LRU%20Cache) | Java | 2026-05-09 |
| 11 | [Merge-Two-Sorted-List](./Linked%20List/Merge-Two-Sorted-List) | Java | 2026-04-18 |
| 12 | [Middle of the Linked List](./Linked%20List/Middle%20of%20the%20Linked%20List) | Java | 2026-05-08 |
| 13 | [Odd Even Linked List](./Linked%20List/Odd%20Even%20Linked%20List) | Java | 2026-06-30 |
| 14 | [Populating Next Right Pointers in Each Node](./Linked%20List/Populating%20Next%20Right%20Pointers%20in%20Each%20Node) | Java | 2026-05-22 |
| 15 | [Remove Nth Node From End of List](./Linked%20List/Remove%20Nth%20Node%20From%20End%20of%20List) | Java | 2026-07-26 |
| 16 | [Reverse Linked List](./Linked%20List/Reverse%20Linked%20List) | Java | 2026-05-08 |
| 17 | [Reverse-Nodes-In-K_Groups](./Linked%20List/Reverse-Nodes-In-K_Groups) | Java | 2026-04-18 |
| 18 | [Sort List](./Linked%20List/Sort%20List) | Java | 2026-04-18 |
| 19 | [Swap Nodes in Pairs](./Linked%20List/Swap%20Nodes%20in%20Pairs) | Java | 2026-07-26 |

</details>

<details>
<summary><strong>Queues</strong> (2 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Find the Winner of the Circular Game](./Queues/Find%20the%20Winner%20of%20the%20Circular%20Game) | Java | 2026-06-19 |
| 2 | [Time Needed to Buy Tickets](./Queues/Time%20Needed%20to%20Buy%20Tickets) | Java | 2026-06-12 |

</details>

<details>
<summary><strong>SQL</strong> (21 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Average Selling Price](./SQL/Average%20Selling%20Price) | SQL | 2026-05-05 |
| 2 | [Biggest Single Number](./SQL/Biggest%20Single%20Number) | SQL | 2026-05-25 |
| 3 | [Combine Two Tables](./SQL/Combine%20Two%20Tables) | SQL | 2026-06-04 |
| 4 | [Confirmation Rate](./SQL/Confirmation%20Rate) | SQL | 2026-04-23 |
| 5 | [Customers Who Never Order](./SQL/Customers%20Who%20Never%20Order) | SQL | 2026-05-04 |
| 6 | [Department Highest Salary](./SQL/Department%20Highest%20Salary) | SQL | 2026-06-11 |
| 7 | [Duplicate Emails](./SQL/Duplicate%20Emails) | SQL | 2026-05-03 |
| 8 | [Employee Bonus](./SQL/Employee%20Bonus) | SQL | 2026-04-24 |
| 9 | [Employees Earning More Than Their Managers](./SQL/Employees%20Earning%20More%20Than%20Their%20Managers) | SQL | 2026-05-02 |
| 10 | [Find_Customer_Referee](./SQL/Find_Customer_Referee) | SQL | 2026-04-20 |
| 11 | [Invalid_Tweets](./SQL/Invalid_Tweets) | SQL | 2026-04-20 |
| 12 | [Managers with at Least 5 Direct Reports](./SQL/Managers%20with%20at%20Least%205%20Direct%20Reports) | SQL | 2026-05-20 |
| 13 | [Not Boring Movies](./SQL/Not%20Boring%20Movies) | SQL | 2026-04-29 |
| 14 | [Number of Unique Subjects Taught by Each Teacher](./SQL/Number%20of%20Unique%20Subjects%20Taught%20by%20Each%20Teacher) | SQL | 2026-05-06 |
| 15 | [Product Sales Analysis I](./SQL/Product%20Sales%20Analysis%20I) | SQL | 2026-04-22 |
| 16 | [Project Employees I](./SQL/Project%20Employees%20I) | SQL | 2026-04-30 |
| 17 | [Queries Quality and Percentage](./SQL/Queries%20Quality%20and%20Percentage) | SQL | 2026-05-21 |
| 18 | [Recyclable_And_LowFat_Products](./SQL/Recyclable_And_LowFat_Products) | SQL | 2026-04-20 |
| 19 | [Replace Employee ID With The Unique Identifier](./SQL/Replace%20Employee%20ID%20With%20The%20Unique%20Identifier) | SQL | 2026-04-22 |
| 20 | [Rising Temperature](./SQL/Rising%20Temperature) | SQL | 2026-04-27 |
| 21 | [Students and Examinations](./SQL/Students%20and%20Examinations) | SQL | 2026-04-28 |

</details>

<details>
<summary><strong>Stack</strong> (5 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Decode String](./Stack/Decode%20String) | Java | 2026-06-19 |
| 2 | [Implement-queue-using-stacks](./Stack/Implement-queue-using-stacks) | Java | 2026-04-19 |
| 3 | [Longest_Valid_Paranthesis](./Stack/Longest_Valid_Paranthesis) | Java | 2026-04-19 |
| 4 | [Remove All Adjacent Duplicates In String](./Stack/Remove%20All%20Adjacent%20Duplicates%20In%20String) | Java | 2026-06-05 |
| 5 | [Score of Parentheses](./Stack/Score%20of%20Parentheses) | Java | 2026-10-06 |

</details>

<details>
<summary><strong>Strings</strong> (31 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Concatenate Non-Zero Digits and Multiply by Sum I](./Strings/Concatenate%20Non-Zero%20Digits%20and%20Multiply%20by%20Sum%20I) | Java | 2026-07-07 |
| 2 | [Count Commas in Range](./Strings/Count%20Commas%20in%20Range) | Java | 2026-09-08 |
| 3 | [Count Commas in Range II](./Strings/Count%20Commas%20in%20Range%20II) | Java | 2026-09-09 |
| 4 | [Count Substrings Starting and Ending with Given Character](./Strings/Count%20Substrings%20Starting%20and%20Ending%20with%20Given%20Character) | Java | 2026-08-14 |
| 5 | [Excel Sheet Column Number](./Strings/Excel%20Sheet%20Column%20Number) | Java | 2026-07-14 |
| 6 | [Excel Sheet Column Title](./Strings/Excel%20Sheet%20Column%20Title) | Java | 2026-05-26 |
| 7 | [Find the Difference](./Strings/Find%20the%20Difference) | Java | 2026-07-29 |
| 8 | [Find the Index of the First Occurrence in a String](./Strings/Find%20the%20Index%20of%20the%20First%20Occurrence%20in%20a%20String) | Java | 2026-04-21 |
| 9 | [Group Anagrams](./Strings/Group%20Anagrams) | Java | 2026-08-27 |
| 10 | [Integer to Roman](./Strings/Integer%20to%20Roman) | Java | 2026-08-18 |
| 11 | [Isomorphic Strings](./Strings/Isomorphic%20Strings) | Java | 2026-08-09 |
| 12 | [Letter Combinations of a Phone Number](./Strings/Letter%20Combinations%20of%20a%20Phone%20Number) | Java | 2026-09-06 |
| 13 | [Longest Substring Without Repeating Characters](./Strings/Longest%20Substring%20Without%20Repeating%20Characters) | Java | 2026-10-28 |
| 14 | [Maximum Nesting Depth of the Parentheses](./Strings/Maximum%20Nesting%20Depth%20of%20the%20Parentheses) | Java | 2026-09-28 |
| 15 | [Maximum Nesting Depth of Two Valid Parentheses Strings](./Strings/Maximum%20Nesting%20Depth%20of%20Two%20Valid%20Parentheses%20Strings) | Java | 2026-09-30 |
| 16 | [Maximum Number of Balloons](./Strings/Maximum%20Number%20of%20Balloons) | Java | 2026-06-22 |
| 17 | [Minimum Number of Pushes to Type Word I](./Strings/Minimum%20Number%20of%20Pushes%20to%20Type%20Word%20I) | Java | 2026-07-30 |
| 18 | [Minimum Number of Pushes to Type Word II](./Strings/Minimum%20Number%20of%20Pushes%20to%20Type%20Word%20II) | Java | 2026-07-31 |
| 19 | [Multiply Strings](./Strings/Multiply%20Strings) | Java | 2026-07-06 |
| 20 | [Number of Strings That Appear as Substrings in Word](./Strings/Number%20of%20Strings%20That%20Appear%20as%20Substrings%20in%20Word) | Java | 2026-06-29 |
| 21 | [Palindrome Partitioning](./Strings/Palindrome%20Partitioning) | Java | 2026-11-10 |
| 22 | [Process String with Special Operations I](./Strings/Process%20String%20with%20Special%20Operations%20I) | Java | 2026-06-16 |
| 23 | [Process String with Special Operations II](./Strings/Process%20String%20with%20Special%20Operations%20II) | Java | 2026-06-17 |
| 24 | [Remove Outermost Parentheses](./Strings/Remove%20Outermost%20Parentheses) | Java | 2026-10-08 |
| 25 | [Reverse Degree of a String](./Strings/Reverse%20Degree%20of%20a%20String) | Java | 2026-09-20 |
| 26 | [Rotate String](./Strings/Rotate%20String) | Java | 2026-05-18 |
| 27 | [Shortest Distance to a Character](./Strings/Shortest%20Distance%20to%20a%20Character) | Java | 2026-08-02 |
| 28 | [Smallest Subsequence of Distinct Characters](./Strings/Smallest%20Subsequence%20of%20Distinct%20Characters) | Java | 2026-07-19 |
| 29 | [Sum Game](./Strings/Sum%20Game) | Java | 2026-08-23 |
| 30 | [Valid Palindrome](./Strings/Valid%20Palindrome) | Java | 2026-05-24 |
| 31 | [Valid Parenthesis String](./Strings/Valid%20Parenthesis%20String) | Java | 2026-10-04 |

</details>

<details>
<summary><strong>Tries</strong> (1 solution)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Longest-Common-Prefix](./Tries/Longest-Common-Prefix) | Java | 2026-04-23 |

</details>

<details>
<summary><strong>LeetCode Contest - 26-04-2026</strong> (2 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Minimum Operations to Make Array Non Decreasing](./LeetCode%20Contest%20-%2026-04-2026/Minimum%20Operations%20to%20Make%20Array%20Non%20Decreasing) | Java | 2026-04-26 |
| 2 | [valid_elements_in_an_array](./LeetCode%20Contest%20-%2026-04-2026/valid_elements_in_an_array) | Java | 2026-04-26 |

</details>

<details>
<summary><strong>LeetCode Submissions</strong> (1 solution)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Leetcode_189.java](./LeetCode%20Submissions/Leetcode_189.java) | Java | 2026-04-14 |

</details>

<details>
<summary><strong>Root (Uncategorized)</strong> (33 solutions)</summary>

| # | Problem / File | Language | Last Updated |
|---:|---|---|---|
| 1 | [Add Binary](./Add%20Binary) | Java | 2026-09-16 |
| 2 | [Binary Tree Tilt](./Binary%20Tree%20Tilt) | Java | 2026-09-19 |
| 3 | [Check Divisibility by Digit Sum and Product](./Check%20Divisibility%20by%20Digit%20Sum%20and%20Product) | Java | 2026-08-22 |
| 4 | [Circle and Rectangle Overlapping](./Circle%20and%20Rectangle%20Overlapping) | Java | 2026-09-21 |
| 5 | [Classes With at Least 5 Students](./Classes%20With%20at%20Least%205%20Students) | SQL | 2026-05-01 |
| 6 | [Climbing Stairs](./Climbing%20Stairs) | Java | 2026-05-30 |
| 7 | [Combination Sum](./Combination%20Sum) | Java | 2026-11-06 |
| 8 | [Count of Matches in Tournament](./Count%20of%20Matches%20in%20Tournament) | Java | 2026-09-29 |
| 9 | [Count the Number of Special Characters I](./Count%20the%20Number%20of%20Special%20Characters%20I) | Java | 2026-05-27 |
| 10 | [Factorial Trailing Zeroes](./Factorial%20Trailing%20Zeroes) | Java | 2026-09-10 |
| 11 | [Fibonacci Number](./Fibonacci%20Number) | Java | 2026-08-16 |
| 12 | [find the index of first occurance in string](./find%20the%20index%20of%20first%20occurance%20in%20string) | Java | 2026-04-21 |
| 13 | [Find the Winner of the Circular Game](./Find%20the%20Winner%20of%20the%20Circular%20Game) | Java | 2026-06-18 |
| 14 | [Gas Station](./Gas%20Station) | Java | 2026-10-12 |
| 15 | [GCD of Odd and Even Sums](./GCD%20of%20Odd%20and%20Even%20Sums) | Java | 2026-07-15 |
| 16 | [Generate Parentheses](./Generate%20Parentheses) | Java | 2026-10-02 |
| 17 | [Happy Number](./Happy%20Number) | Java | 2026-06-24 |
| 18 | [Implement Trie (Prefix Tree)](./Implement%20Trie%20%28Prefix%20Tree%29) | Java | 2026-07-23 |
| 19 | [Leetcode_189.java](./Leetcode_189.java) | Java | 2026-04-16 |
| 20 | [Leetcode_29](./Leetcode_29) | Java | 2026-04-17 |
| 21 | [Leetcode_560](./Leetcode_560) | Java | 2026-04-16 |
| 22 | [Leetcode_96](./Leetcode_96) | Java | 2026-04-16 |
| 23 | [Maximum Product of Two Digits](./Maximum%20Product%20of%20Two%20Digits) | Java | 2026-07-25 |
| 24 | [Number of Digit One](./Number%20of%20Digit%20One) | Java | 2026-10-03 |
| 25 | [Populating Next Right Pointers in Each Node II](./Populating%20Next%20Right%20Pointers%20in%20Each%20Node%20II) | Java | 2026-07-16 |
| 26 | [Power of Three](./Power%20of%20Three) | Java | 2026-06-09 |
| 27 | [Reveal Cards In Increasing Order](./Reveal%20Cards%20In%20Increasing%20Order) | Java | 2026-06-03 |
| 28 | [Smallest Divisible Digit Product I](./Smallest%20Divisible%20Digit%20Product%20I) | Java | 2026-08-06 |
| 29 | [Sort_Array(Quick Sort)](./Sort_Array%28Quick%20Sort%29) | Java | 2026-04-20 |
| 30 | [Tenth Line](./Tenth%20Line) | Shell | 2026-09-15 |
| 31 | [Triangle](./Triangle) | Java | 2026-07-05 |
| 32 | [Ugly Number](./Ugly%20Number) | Java | 2026-09-18 |
| 33 | [Unique Middle Element](./Unique%20Middle%20Element) | Java | 2026-07-04 |

</details>

---

## 🎯 Goals
- [x] Solve 200+ problems on LeetCode *(Achieved: 224 unique problems solved)*
- [ ] Master core DSA & SQL concepts
- [ ] Crack product-based companies

---

## 💡 Why This Repository?
This repository reflects my consistency, problem-solving ability, and dedication toward improving my coding and algorithmic thinking skills.

---

## 🔗 Connect with Me
- **LeetCode:** https://leetcode.com/u/Ayush_Abhinav05/
- **GitHub:** https://github.com/Ayush5424

---

> “Consistency beats intensity. Solve daily and keep improving.”
