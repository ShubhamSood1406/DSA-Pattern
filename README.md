# Pattern wise Ques


## Source:
-	[LeetCode was HARD until I Learned these 15 Patterns](https://www.youtube.com/watch?v=DjYZk8nrXVY)
-	[20 Coding Patterns to Master a DSA (Data Structures and Algorithms) Interview](https://www.linkedin.com/pulse/20-coding-patterns-master-dsa-data-structures-algorithms-ankit-malik/)
-	[22 Key DSA Patterns with Must-Solve Problems!](https://gist.github.com/PrinceSinghhub/c74372270cf45df2087816a75c87bb06)
-	[Misc] [If I only had a short time to study for my coding interview, these are the 15 questions I would solve](https://www.linkedin.com/posts/navdeep-singh-3aaa14161_if-i-only-had-a-short-time-to-study-for-my-activity-7312473774598012928-ZhXz?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAACMGebYBKY8HnG-p3doo8gpo-3Dc_TXuHFI)
- [Misc] [BitFlip’s Leetcode Pattern Recognition Cheat Sheet](https://github.com/bitflipdev/guides/blob/main/Leetcode%20Pattern%20Recognition%20Guide.pdf)

## Practice
- [Striver's A2Z DSA Course](http://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2)

## 1. Core Array
- [26: Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description)
- [189: Rotate Array](https://leetcode.com/problems/rotate-array/description)
- [121: Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/description)
- [1: Two Sum](https://leetcode.com/problems/two-sum/description) (Hash Table)
- [169: Majority Element (>n/2 times)](https://leetcode.com/problems/majority-element/description) (Moore's Voting Algorithm)
- [229: Majority Element II (>n/3 times)](https://leetcode.com/problems/majority-element-ii/description) (Moore's Voting Algorithm)
- [53: Maximum Subarray](https://leetcode.com/problems/maximum-subarray/description) (Kadane's Algorithm)
- [152: Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/description) (Kadane's Algorithm)
- [645: Set Mismatch](https://leetcode.com/problems/set-mismatch/description) (Find Repeating and Missing number)
- [41: First Missing Positive](https://leetcode.com/problems/first-missing-positive/description)
  
## 2. String
- [151: Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/description/) (Two Pointers)
- [14: Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/description/)
- [205: Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/description/) (Hash Table)
- [796: Rotate String](https://leetcode.com/problems/rotate-string/description/)
- [242: Valid Anagram](https://leetcode.com/problems/valid-anagram/description/) (Hash Table)
- [451: Sort Characters By Frequency](https://leetcode.com/problems/sort-characters-by-frequency/description/) (Hash Table, Sorting)
- [13: Roman to Integer](https://leetcode.com/problems/roman-to-integer/description/) (Hash Table)

## 3.	Two Pointers
This technique is commonly applied on sorted arrays or linked lists to find pairs or reverse elements. It is an ideal strategy when managing elements with pair relationships.
-	[167: Two Sum II - Input Array is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/description/)
- [75: Sort Colors](https://leetcode.com/problems/sort-colors/description/) (Dutch National Flag)
- [31: Next Permutation](https://leetcode.com/problems/next-permutation/description/)
-	[15: 3 Sum](https://leetcode.com/problems/3sum/description/)
-	[42: Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/description/)
-	[11: Container With Most Water](https://leetcode.com/problems/container-with-most-water/description/)
-	948: Bag of Tokens

## 4.	Prefix Sum (Hash Table involved)
Prefix Sums/Products are techniques that store cumulative sums or products up to each index, allowing for quick subarray range queries.
-	[Longest subarray with sum K](https://takeuforward.org/arrays/longest-subarray-with-sum-k-postives-and-negatives/) (array having Positive and Negative elements)
-	[560: Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/description/)
-	[525: Contiguous Array](https://leetcode.com/problems/contiguous-array/description/)
-	238: Product of Array Except Self
-	303: Range Sum Query - Immutable
-	1991: Find the Middle Index in Array
-	2270: Number of Ways to Split Array
-	304: Range Sum Query 2D

## 5.	Matrix Traversal
Problems involving 2D arrays (matrices) are often solved using row-column traversal or manipulation based on matrix properties.
-	[48: Rotate Image](https://leetcode.com/problems/rotate-image/description/)
-	[54: Spiral Matrix](https://leetcode.com/problems/spiral-matrix/description/)
-	[73: Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/description/)
-	733: Flood Fill
-	200: Number of Islands
-	130: Surrounded Regions
-	289: Game of Life

## 6.	Merge Intervals / Overlapping Intervals
Use this pattern to deal with overlapping intervals, helping to create a more organized and efficient structure. Intervals are often manipulated through sorting and merging based on their start and end times.
-	[56: Merge Intervals](https://leetcode.com/problems/merge-intervals/description/) (Basic Merge)
-	[57: Insert Interval](https://leetcode.com/problems/insert-interval/description/) (Interval Insertion)
-	435: Non-overlapping Intervals [(In Greedy Section)](https://github.com/ShubhamSood1406/DSA-Pattern/blob/master/README.md#15-greedy)
- 452: Minimum Number of Arrows to Burst Balloons [(In Greedy Section)](https://github.com/ShubhamSood1406/DSA-Pattern/blob/master/README.md#15-greedy)
-	731: My Calendar II

## 7.	Modified Binary Search
An adaptation of the binary search for situations where a standard binary search doesn't apply. A modified version of binary search that applies to rotated arrays, unsorted arrays, or specialized conditions.
- [Floor and Ceil in Sorted Array](https://takeuforward.org/arrays/floor-and-ceil-in-sorted-array/)
-	[33: Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)
-	[81: Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/description/)  (Contains Duplicate)
-	[153: Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/description/)
-	[540: Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/description/)
-	[162: Find Peak Element](https://leetcode.com/problems/find-peak-element/description/)
-	[875: Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/description/)
-	[1011: Capacity to Ship Packages Within 'd' Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/description/)
-	[4: Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/description/)
-	[240: Search a 2D Matrix II](https://leetcode.com/problems/search-a-2d-matrix-ii/description/)
-	1870: Minimum Speed to Arrive on Time
-	1095: Find in Mountain Array

## 8.	Fast and Slow Pointers (Tortoise-Hare Method / Floyd's Cycle Detection Algorithm)
Used in linked list or array problems, this pattern is ideal for detecting cycles or finding a midpoint.
- [876: Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/description/)
-	[141: Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/description/)
-	[142: Linked List Cycle II (Find starting point of cycle](https://leetcode.com/problems/linked-list-cycle-ii/description/)
- [243: Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/description/) (Recursion)
-	[19: Remove nth Node from the End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/description/)
-	202: Happy Number
-	287: Find the Duplicate Number

## 9.	Linked List in-place reversal
Reversing a linked list in place without using extra space is key for problems that require in-place list manipulations. 
- [206: Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/description/)
-	[92: Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/description/) (Reverse from position left to right)
-	[25: Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/description/)
-	24: Swap Nodes in Pairs

## 10.	Backtracking / Recursion
Backtracking helps in problems where you need to explore all potential solutions, such as solving puzzles, generating combinations, or finding paths.
-	[22: Generate Parenthesis](https://leetcode.com/problems/generate-parentheses/description/)
-	[78: Subsets](https://leetcode.com/problems/subsets/description/)
-	[39: Combination Sum](https://leetcode.com/problems/combination-sum/description/) (Same element may be chosen unlimited times)
- [40: Combination Sum II](https://leetcode.com/problems/combination-sum-ii/description/) (Each element only be used once in the combination)
- [90: Subsets II](https://leetcode.com/problems/subsets-ii/description/) (Contains Duplicate)
-	[131: Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/description/)
-	[79: Word Search](https://leetcode.com/problems/word-search/description/) (DFS)
-	[51: N-Queens](https://leetcode.com/problems/n-queens/description/) (DFS)
- [37: Sudoku Solver](https://leetcode.com/problems/sudoku-solver/description/)
- [46: Permutations](https://leetcode.com/problems/permutations/description/)
-	[47: Permutations II](https://leetcode.com/problems/permutations-ii/description/) (Contains Duplicate)

## 11.	Bit Manipulation
Description: Bit manipulation is a powerful technique that can solve problems like finding single numbers or efficiently pairing elements.
- [268: Missing Number](https://leetcode.com/problems/missing-number/description/)
- [231: Power of Two](https://leetcode.com/problems/power-of-two/description/) (Kernighan's Algorithm)
- [191: Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/description/) (Kernighan's Algorithm)
-	[2220: Minimum Bit Flips to Convert Number](https://leetcode.com/problems/minimum-bit-flips-to-convert-number/description/)
-	[136: Single Number](https://leetcode.com/problems/single-number/description/) (Every element appears twice except for one)
-	[137: Single Number II](https://leetcode.com/problems/single-number-ii/description/) (Every element appears three times except for one)
-	[260: Single Number III](https://leetcode.com/problems/single-number-iii/description/) (Exactly two elements appear only once and all the other elements appear exactly twice)
-	[1310: XOR Queries of a Subarray](https://leetcode.com/problems/xor-queries-of-a-subarray/description/)
-	2433: Find the Original Array of Prefix XOR

## 12. Stack
- [20: Valid Parentheses](https://leetcode.com/problems/valid-parentheses/description/) (Balanced Parantheses)
- [155: Min Stack](https://leetcode.com/problems/min-stack/description/)
- [735: Asteroid Collision](https://leetcode.com/problems/asteroid-collision/description/)
-	[402: Remove K Digits](https://leetcode.com/problems/remove-k-digits/description/)
-	[277: Find the Celebrity](https://leetcode.com/problems/find-the-celebrity/description/)
### Monotonic Stack
A monotonic stack helps solve range queries by maintaining a stack of elements in increasing or decreasing order.
-	[496: Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/description/)
-	[503 Next Greater Element II](https://leetcode.com/problems/next-greater-element-ii/description/) (Next Greater Element in Circular Array)
-	[739: Daily Temperatures](https://leetcode.com/problems/daily-temperatures/description/)
-	[901: Online Stock Span](https://leetcode.com/problems/online-stock-span/description/)
-	[84: Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/description/)
-	[239: Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/description/) (De-Queue)
-	1019: Next Greater Node in Linked List
-	962: Maximum Width Ramp

## 13.	Sliding Window
This pattern is used to track a subset of data within a larger dataset. It's particularly useful in array or string problems when you need to maintain a 'window' of elements satisfying a certain condition.
### Fixed Size
-	[424: Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/description/) (Hash Table)
-	[567: Permutation in String](https://leetcode.com/problems/permutation-in-string/description/) / [438: Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/description/) (Hash table)
-	643: Maximum Average Subarray I
-	Maximum Sum Subarray of Size K
-	1343: Number of Sub-arrays of Size K and Average Greater or Equal to Threshold
-	187: Repeated DNA Sequences
-	2653: Sliding Subarray Beauty
### Variable Size
-	[3: Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/description/) (Hash Table)
-	[1004: Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/description/)
-	[904: Fruit Into Baskets](https://leetcode.com/problems/fruit-into-baskets/description/) (Hash Table)
-	[340: Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/description/) / [Longest Substring with K Unique Characters](https://www.geeksforgeeks.org/dsa/find-the-longest-substring-with-k-unique-characters-in-a-given-string/) (Hash Table)
-	[209: Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/description/)
-	[713: Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/description/)
-	[76: Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/description/) (Hash Table)
### Variable Size (Counting Subarrays Problems)
-	[930: Binary Subarrays With Sum](https://leetcode.com/problems/binary-subarrays-with-sum/description/)
-	[1248: Count Number of Nice Subarrays](https://leetcode.com/problems/count-number-of-nice-subarrays/description/)
-	[992: Subarrays with K Different Integers](https://leetcode.com/problems/subarrays-with-k-different-integers/description/) (Hash Table)

## 14. Heap (Priority Queue)
### Top ‘K’ Elements OR min/max Heap
This pattern is beneficial for problems that require identifying the top or bottom 'k' elements in a set. 
This pattern uses heaps or quickselect to efficiently find the top 'K' largest/smallest elements from a dataset.
-	[215: Kth Largest element in an array](https://leetcode.com/problems/kth-largest-element-in-an-array/description/)
-	[Sort K sorted array](https://www.geeksforgeeks.org/dsa/nearly-sorted-algorithm/)
-	[347: Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/description/) (Hash Table)
-	[621: Task Scheduler](https://leetcode.com/problems/task-scheduler/description/) (Hash Table)
-	264: Ugly Number II
-	973: K Closest Points to Origin

### K-way Merge
The K-way merge technique uses a heap to efficiently merge multiple sorted lists or arrays.
-	[23: Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/description/) (Linked List)
-	373: Find K Pairs with Smallest Sums
-	378: Kth Smallest Element in a Sorted Matrix
-	632: Smallest Range Covering Elements from K Lists

### Two Heaps
Description: This pattern uses two heaps (max heap and min heap) to solve problems involving tracking medians and efficiently managing dynamic data.
-	[295: Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/description/)
-	480: Sliding Window Median
-	502: IPO

## 15. Greedy
Description: Greedy algorithms make local optimal choices at each step, which lead to a global optimal solution for problems like scheduling and resource allocation.
- [55: Jump Game](https://leetcode.com/problems/jump-game/description/)
-	[45: Jump Game II](https://leetcode.com/problems/jump-game-ii/description/)
- [Fractional Knapsack](https://www.geeksforgeeks.org/dsa/fractional-knapsack-problem/)
-	[Job Sequencing Problem](https://www.geeksforgeeks.org/dsa/job-sequencing-problem/)
-	[N Meetings in one Room](https://www.geeksforgeeks.org/dsa/find-maximum-meetings-in-one-room/) / [452: Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/description/)
- [435: Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/description/)
- [Minimum Platforms Required](https://www.geeksforgeeks.org/dsa/minimum-number-platforms-required-railwaybus-station/)
- [135: Candy](https://leetcode.com/problems/candy/description/)
-	[134: Gas Station](https://leetcode.com/problems/gas-station/description/)
-	[678: Valid Parenthesis String](https://leetcode.com/problems/valid-parenthesis-string/description/)
-	948: Bag of Tokens
-	881: Boats to Save People
-	376: Wiggle Subsequence
-	1094: Car Pooling

## 16.	Trees
### Depth First Search (Uses Recursion)
This pattern allows you to traverse a tree or graph using depth as the main factor.
- [144: Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/description/)
- [94: Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/description/)
- [145: Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/description/)
-	[100: Same Tree](https://leetcode.com/problems/same-tree/description/)
-	[545: Boundary of Binary Tree](https://leetcode.com/problems/boundary-of-binary-tree/description/)
-	[101: Symmetric Tree](https://leetcode.com/problems/symmetric-tree/description/)
-	[226: Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/description/)
-	[257: Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/description/)
-	[Path from Root to a given node in Binary Tree](https://www.geeksforgeeks.org/dsa/print-path-root-given-node-binary-tree/)
-	[863: All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/description/)
-	[297: Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/description/)
-	[114: Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/description/)
-	133: Clone Graph
-	113: Path Sum II
-	210: Course Schedule II
-	107: Binary Tree Level Order Traversal II
-	129: Sum Root to Leaf Numbers
-	988: Smallest String Starting from Leaf
-	1080: Insufficient Nodes in Root to Leaf
-	1457: Pseudo-Palindromic Paths in a Binary Tree
#### Height Related Problems
-	[104: Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/description/) (DFS)
- [111: Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/description/) (DFS)
-	[110: Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/description/) (DFS)
-	[543: Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/description/) (DFS)
-	[124: Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/description/) (DFS)
-	[222: Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/description/) [In O(log N * log N)] (DFS)
#### Ancestor Problem
-	[236: Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/description/) (DFS)
-	1026: Maximum Difference Between Node and Ancestor
-	1123: LCA of Deepest Leaves
-	1483: Kth Ancestor of a Tree Node
### Breadth First Search (Level Order Traversal)
Perfect for traversing a tree level-by-level, providing a comprehensive overview of all nodes.
-	[102: Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/description/)
-	[103: Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/description/)
-	[987: Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/description/)
-	[Top View of Binary Tree](https://www.geeksforgeeks.org/dsa/print-nodes-top-view-binary-tree/) / [Bottom View of Binary Tree](https://www.geeksforgeeks.org/dsa/bottom-view-binary-tree/)
- [199: Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/description/) / [Left View of Binary Tree](https://www.geeksforgeeks.org/dsa/print-left-view-binary-tree/)
-	[662: Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/description/)
-	1609: Even Odd Tree
-	2415: Reverse Odd Levels of Binary Tree
-	1302: Deepest Leaves Sum
-	623: Add One Row to Tree
### Tree Construction
-	[105: Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/description/)
-	[106: Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/description/)
-	654: Maximum Binary Tree
### Binary Search Tree
- [700: Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree/description/)
-	701: Insert into a BST
- 230: Kth Smallest Element in a BST
- 1008: Construct BST from Preorder
-	98: Validate BST
-	938: Range Sum of BST
-	530: Minimum Absolute Difference in BST
-	235: LCA of BST

## 19.	Dynamic Programming
### Take / Not Take (DP)
Description: Solve optimization problems like selecting items with the max/min value under certain constraints.
-	70 Climbing Stairs
-	House Robber II
-	Target Sum
-	416 Partition Equal Subset Sum
-	Ones and Zeroes
-	Last Stone Weight II
### Infinite Supply (DP)
Description: Similar to the 0/1 knapsack, but items can be chosen multiple times.
-	322 Coin Change
-	Coin Change II
-	Perfect Squares
-	Minimum Cost For Tickets
### Longest Increasing Subsequence
Description: It involves finding the longest subsequence of a given sequence where the elements are in ascending order.
-	300 Longest Increasing Subsequence
-	Largest Divisible Subset
-	Maximum Length of Pair Chain
-	Number of LIS
-	Longest String Chain
### DP on Grids
Description: Dynamic Programming on matrices involves solving problems that can be broken down into smaller overlapping subproblems within a matrix.
-	Unique Paths II
-	Minimum Path Sum
-	Triangle
-	Minimum Falling Path Sum
-	Maximal Square
-	Cherry Pickup
-	Dungeon Game
### DP on Strings
Description: It involves two strings, focusing on what happens when the last characters of the two substrings are the same.
-	1143 Longest Common Subsequence
-	Longest Palindromic Subsequence
-	Palindromic Substrings
-	Longest Palindromic Substrings
-	Edit Distance
-	Minimum ASCII Delete Sum for Two Strings
-	Distinct Subsequences
-	Shortest Common Supersequence
-	Wildcard Matching
### DP on Stocks
Description: It focuses on maximizing profit from buying and selling stocks over time while considering constraints.
-	Buy and Sell Stocks II
-	Buy and Sell Stocks III
-	Buy and Sell Stocks IV
-	Buy and Sell Stocks with Cooldown
-	Buy and Sell Stocks with Transaction Fee
### Partition DP (MCM - Matrix Chain Multiplication)
Description: It involves a sequence that needs to be divided into partitions in an optimal way.
-	Partition Array for Maximum Sum
-	312 Burst Balloons
-	Minimum Cost to Cut a Stick
-	Palindrome Partitioning II

## 20.	Graphs
### Topological Sort
Description: Topological sorting is useful for tasks that require dependency resolution (InDegree) in directed acyclic graphs (DAGs).
-	Course Schedule
-	Course Schedule II
-	Strange Printer II
-	Sequence Reconstruction
-	Alien Dictionary
### Union Find (Disjoint Set)
Description: Union-Find (or Disjoint Set) is used to solve problems involving connectivity or grouping, often in graphs.
-	Number of Operations to Make Network Connected
-	Redundant Connection
-	Accounts Merge
-	Satisfiability of Equality Equations
### Graph Algorithms
Description: Advanced graph algorithms are used to solve complex problems involving shortest paths, minimum spanning trees, and graph cycles.
-	Kruskal's Algorithm: Minimum Cost to Connect All Points
-	Dijkstra's Algorithm: Cheapest Flights Within K Stops
-	Floyd-Warshall: Find the City with Smallest Number of Neighbours at a Threshold Distance
-	Bellman Ford: Network Delay Time

## 9.	Breadth First Search (BFS)
Description: BFS explores nodes level by level using a queue. It is particularly useful for shortest path problems.
-	Shortest Path in Binary Matrix
-	994 Rotting Oranges
-	127 Word Ladder
-	As Far From Land as Possible

## 10.	Depth First Search (DFS)
Description: DFS explores as far as possible along a branch before backtracking. It's useful for graph traversal, pathfinding, and connected components.
-	Number of Closed Islands
-	Coloring a Border
-	DFS from Boundary: Number of Enclaves
-	Shortest Time: Time Needed to Inform All Employees
-	Cyclic Find: Find Eventual Safe States

## 22.	Design Data Structure
Description: It involves building custom data structures to efficiently handle specific operations, like managing data access, updates, and memory usage.
-	[146: LRU Cache](https://leetcode.com/problems/lru-cache/description/) (Hash Table + Doubly-Linked List)
-	LFU Cache
-	Design Twitter
-	Design Browser History
-	Design Circular Deque
-	Snapshot Array
