# Coding Interview Questions and Answers (LeetCode Solutions)

> Prepare for software engineer coding interviews with our curated collection of real-world problems, detailed solutions, and time/space complexity analysis.

<!-- Keywords: coding interview, leetcode solutions, data structures, algorithms, software engineer interview -->

[⬅ Back to All Categories](README.md)

---

## [Reverse a Singly Linked List](https://interviewgpt.deepchill.app/blogs/coding/reverse-a-singly-linked-list-4W8jqJQkfjWGKAAws93baf)
> 📅 *4/11/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given the head of a singly linked list, implement a function to reverse the list in-place and return the new head pointer. Discuss the trade-offs between an iterative approach and a recursive approach, specifically focusing on time and space complexity constraints.

</details>

---

## [Climbing Stairs Path Counting](https://interviewgpt.deepchill.app/blogs/coding/climbing-stairs-path-counting-99nyieknrnVHigw8p3zUdn)
> 📅 *4/10/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

You are climbing a staircase that takes n steps to reach the top. Each time you can either take 1 or 2 steps. Implement an optimal function in C++ to determine the total number of distinct ways you can reach the top, considering constraints where n can be up to 45 and efficiency in both time and space is required.

</details>

---

## [Sum of Sortable Partition Sizes](https://interviewgpt.deepchill.app/blogs/coding/sum-of-sortable-partition-sizes-5VdkPUcZ2H1wDmW7REBjLe)
> 📅 *4/9/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer array `nums` of length `n`, a positive integer `k` is defined as 'sortable' if `k` is a divisor of `n` and the array can be sorted into non-decreasing order by partitioning it into consecutive subarrays of length `k` and independently rotating each subarray any number of times. Write a function to return the sum of all such sortable integers `k`. Your solution should handle large inputs efficiently and account for duplicate elements.

</details>

---

## [Minimum Increments for Circular Peaks](https://interviewgpt.deepchill.app/blogs/coding/minimum-increments-for-circular-peaks-eN94TjBLnsk7oTH9kz6pzq)
> 📅 *4/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a circular integer array `nums` of length $n$, an index $i$ is defined as a peak if `nums[i]` is strictly greater than both its circular neighbors. You can increase any element `nums[i]` by 1 at the cost of 1 operation. Design an efficient algorithm to find the minimum total operations required to ensure the array contains at least $k$ peaks. If it is impossible to achieve $k$ peaks, return -1.

</details>

---

## [Consistent Parity Cycle Detection](https://interviewgpt.deepchill.app/blogs/coding/consistent-parity-cycle-detection-7kz3oS6LT8ZDxoqNxugF8Q)
> 📅 *4/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an undirected graph with $n$ nodes and a sequence of weighted edges where weights are either 0 or 1, process the edges one by one in the given order. An edge is added to the graph if and only if its inclusion does not create any cycle with an odd sum of weights. Determine the total number of edges successfully added to the graph.

</details>

---

## [Unique String Permutations with Duplicates](https://interviewgpt.deepchill.app/blogs/coding/unique-string-permutations-with-duplicates-6yH6AHD1UW6HPosFxLWApT)
> 📅 *4/7/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a string that may contain duplicate characters (e.g., 'google'), implement an efficient algorithm to generate all unique permutations of the string. The solution should avoid generating duplicate results and optimize for both time and space complexity, explaining how duplicates are handled during the recursion process.

</details>

---

## [Maintaining Even Cycle Weight Constraints](https://interviewgpt.deepchill.app/blogs/coding/maintaining-even-cycle-weight-constraints-emayRGBsSQ7FDUaBwrPiBW)
> 📅 *4/3/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an undirected graph with $n$ nodes and a series of edges with binary weights (0 or 1), implement an algorithm to process edges one by one. An edge $(u, v)$ with weight $w$ should only be added if all resulting cycles in the graph have an even total weight sum. Return the total count of successfully added edges. Optimize for large $n$ and $E$ using a Disjoint Set Union (DSU) variant.

</details>

---

## [Max Chunks To Make Sorted](https://interviewgpt.deepchill.app/blogs/coding/max-chunks-to-make-sorted-eaHdKyuRUf8yPM2UTDweXv)
> 📅 *3/30/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer array `arr` that may contain duplicate elements, determine the maximum number of contiguous chunks the array can be partitioned into such that if each chunk is sorted individually and then concatenated, the entire resulting array is sorted in non-decreasing order. Provide an optimal solution in terms of time and space complexity.

</details>

---

## [Minimum Candy Distribution](https://interviewgpt.deepchill.app/blogs/coding/minimum-candy-distribution-oHZEyTJa1K6tUDTVwGe1me)
> 📅 *3/30/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array of integers representing ratings of $n$ children in a line, determine the minimum number of candies required to satisfy two conditions: 1) Each child must receive at least one candy. 2) A child with a higher rating than an adjacent neighbor must receive more candies than that neighbor. Implement an efficient solution and discuss its time and space complexity.

</details>

---

## [FEFO Credit Management System](https://interviewgpt.deepchill.app/blogs/coding/fefo-credit-management-system-bZZ54ghMjyu45W8DatAVx8)
> 📅 *3/27/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a resource management system (like GPU credits) that allows users to add credit packs with varying expiration dates. Implement a mechanism to consume credits such that the credits expiring soonest are used first (FEFO). The system must support adding credits, consuming a specific amount at a given timestamp, and querying the current valid balance.

</details>

---

## [Profitable Schemes Optimization](https://interviewgpt.deepchill.app/blogs/coding/profitable-schemes-optimization-p1znJsG8j8yFP4AnNv9EHh)
> 📅 *3/22/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a set of $k$ tasks, where each task $i$ requires $group[i]$ workers and yields $profit[i]$ profit, determine the number of distinct subsets of tasks that can be performed such that the total number of workers required does not exceed $n$ and the total profit generated is at least $minProfit$. Note that each worker can only be assigned to one task. Return the total number of valid subsets modulo $10^9 + 7$.

</details>

---

## [Special Positions in Binary Matrix](https://interviewgpt.deepchill.app/blogs/coding/special-positions-in-binary-matrix-xpEe9gdAiUo4pQDt58BtAY)
> 📅 *3/20/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an m x n binary matrix, a cell (i, j) is defined as 'special' if mat[i][j] is 1 and all other elements in the i-th row and j-th column are 0. Write an efficient algorithm to calculate the total number of special positions in the matrix. Analyze the time and space complexity of your approach.

</details>

---

## [Longest Consecutive Sequence](https://interviewgpt.deepchill.app/blogs/coding/longest-consecutive-sequence-c5HxTc3Vw2zaawENxUQ6D1)
> 📅 *3/20/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an unsorted array of integers, design an algorithm to find the length of the longest sequence of consecutive elements (e.g., [1, 2, 3, 4]). The solution must achieve O(n) time complexity, where n is the number of elements in the array.

</details>

---

## [Stable Sorting with Divide and Conquer](https://interviewgpt.deepchill.app/blogs/coding/stable-sorting-with-divide-and-conquer-fkji2tNYTZqyNUh5JQ5yiq)
> 📅 *3/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Implement a stable sorting algorithm that guarantees O(n log n) time complexity. Discuss the trade-offs regarding space complexity and how the algorithm handles the 'merge' step to maintain stability.

</details>

---

## [Merge Sort Implementation](https://interviewgpt.deepchill.app/blogs/coding/merge-sort-implementation-9Gs5DPDxwqeCK5nPeXatfX)
> 📅 *3/13/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Implement a stable, recursive Merge Sort algorithm to sort an array of integers. Discuss its time and space complexity, and explain how the merge step ensures the sorting stability.

</details>

---

## [Design an LRU Cache](https://interviewgpt.deepchill.app/blogs/coding/design-an-lru-cache-6frqiPv99NQKFv33aY4CZ1)
> 📅 *3/12/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design and implement a data structure for a Least Recently Used (LRU) Cache. It should support 'get' and 'put' operations in O(1) time complexity. When the cache reaches its capacity, it should invalidate the least recently used item before inserting a new item.

</details>

---

## [Hotel Room Availability Problem](https://interviewgpt.deepchill.app/blogs/coding/hotel-room-availability-problem-jG1EPS5AUUVgJYXG8Uk1Uo)
> 📅 *3/12/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a set of guest arrival and departure dates for a hotel and a fixed number of available rooms K, determine if the hotel can accommodate all guests without exceeding its capacity. A guest checking out on the same day another guest checks in is assumed to vacate the room in time for the new guest. Provide an efficient algorithm and discuss its time and space complexity.

</details>

---

## [Award Top K Hotels](https://interviewgpt.deepchill.app/blogs/coding/award-top-k-hotels-uhPN7xjqK48Yt2V2qrzJej)
> 📅 *3/12/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a set of positive and negative keywords, and a collection of hotel reviews associated with specific hotel IDs, implement a system to rank and return the top K hotels. A positive keyword match increases a hotel's score by a fixed weight, while a negative match decreases it. In case of tie scores, hotels should be ordered by their ID. The solution should handle text normalization and provide efficient ranking for large datasets.

</details>

---

## [First-Fit Decreasing Variation with Baskets](https://interviewgpt.deepchill.app/blogs/coding/first-fit-decreasing-variation-with-baskets-1NSH3XrJadWkgYcu5GTkY1)
> 📅 *3/11/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

You are given two integer arrays, 'fruits' representing the sizes of fruits and 'baskets' representing the capacities of available baskets. You must process each fruit in the order they appear and place each fruit into the first (leftmost) available basket that has a capacity greater than or equal to the fruit's size. Each basket can only be used once. Implement an efficient solution to determine the total number of fruits that remain unplaced after all fruits have been processed, assuming the number of elements can be up to 10^5.

</details>

---

## [First Fit Fruit Placement](https://interviewgpt.deepchill.app/blogs/coding/first-fit-fruit-placement-cPPu5UzooikvNWr8kmKJyD)
> 📅 *3/11/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array 'fruits' representing the size of fruits and an array 'baskets' representing the capacity of baskets, simulate the following process: for each fruit in the order they appear, place it in the first available basket (lowest index) that has a capacity greater than or equal to the fruit's size. Once a fruit is placed, that basket is no longer available. Return the total number of fruits that could not be placed in any basket. Optimize the solution to handle arrays of size up to 10^5.

</details>

---

## [Matrix-based Correlation Calculation](https://interviewgpt.deepchill.app/blogs/coding/matrix-based-correlation-calculation-wq1pCkDbdwmHJmLSnHxEkZ)
> 📅 *3/9/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Implement a function in Python using NumPy to compute the Pearson correlation matrix for a given 2D array X. The function should optionally accept a second 2D array Y to compute the cross-correlation matrix between the features of X and Y. Ensure the implementation handles centering, normalization, and potential edge cases like zero variance features.

</details>

---

## [K-Means Clustering Implementation](https://interviewgpt.deepchill.app/blogs/coding/k-means-clustering-implementation-ccDtkZK6JzsbyWJ72go6tu)
> 📅 *3/9/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Implement the k-Means clustering algorithm from scratch. Given a set of n-dimensional points, an integer k, and a set of initial centroids, perform the assignment and update steps for a maximum of 'max_iterations'. Return the final centroid coordinates rounded to four decimal places. Ensure the implementation handles convergence (early exit) and accounts for potential empty clusters.

</details>

---

## [Subarray Product Less Than K](https://interviewgpt.deepchill.app/blogs/coding/subarray-product-less-than-k-mfJQ9iUg5Vgbfkqt4RJVkm)
> 📅 *3/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array of positive integers `nums` and an integer `k`, return the number of contiguous subarrays where the product of all the elements in the subarray is strictly less than `k`. Optimize for $O(n)$ time complexity and $O(1)$ space complexity.

</details>

---

## [Subarrays with K Distinct Integers](https://interviewgpt.deepchill.app/blogs/coding/subarrays-with-k-distinct-integers-f1hb1UPoP2WYsiFqBSaBB5)
> 📅 *3/7/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer array and an integer k, implement an efficient algorithm to calculate the total number of subarrays that contain at most k distinct integers. Discuss the time and space complexity, and explain how this approach can be extended to find the number of subarrays with exactly k distinct integers.

</details>

---

## [Minimum Swaps for Couple Pairing](https://interviewgpt.deepchill.app/blogs/coding/minimum-swaps-for-couple-pairing-7rGg6qMY4DjVbE7Rbx3ofq)
> 📅 *3/4/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array of $2n$ integers representing $n$ couples $(2k, 2k+1)$ sitting in $2n$ seats, find the minimum number of swaps required so that every couple sits in adjacent seats (indices $(0,1), (2,3), \dots$). A swap allows exchanging the seats of any two people.

</details>

---

## [String Transformation via Character Mapping](https://interviewgpt.deepchill.app/blogs/coding/string-transformation-via-character-mapping-fSas3gpM8w51ayEDW28iNd)
> 📅 *3/4/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two strings str1 and str2 of equal length consisting of lowercase English letters, determine if str1 can be transformed into str2. A transformation consists of replacing all occurrences of a specific character with another lowercase letter. You may perform any number of such transformations sequentially. Note that a transformation must apply to all instances of the chosen character simultaneously.

</details>

---

## [Redundant Connection in Directed Graph](https://interviewgpt.deepchill.app/blogs/coding/redundant-connection-in-directed-graph-k6XyNRK6EeHR9ErUMussux)
> 📅 *3/2/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a directed graph that was originally a rooted tree but now contains one additional directed edge, identify the edge that should be removed to restore its rooted tree structure. If multiple edges could be removed to satisfy this condition, return the one that appears latest in the input sequence.

</details>

---

## [Thread-Safe Versioned Key-Value Store](https://interviewgpt.deepchill.app/blogs/coding/thread-safe-versioned-key-value-store-itgupcqbQgtwh57PLpbyPH)
> 📅 *3/1/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design and implement a high-performance, thread-safe versioned key-value storage system. The system must provide two operations: one to record a value for a specific key at a given point in time, and another to retrieve the most recent state of a key at or before a specified timestamp.

</details>

---

## [Median Maintenance in Data Streams](https://interviewgpt.deepchill.app/blogs/coding/median-maintenance-in-data-streams-aNHicJ1bZewZBdT7aDZDUM)
> 📅 *3/1/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a system that efficiently calculates the median of a continuous stream of incoming numerical data. The system must support adding a new number and retrieving the current median at any point in time, optimizing for high-frequency updates.

</details>

---

## [Optimize Water Distribution Costs](https://interviewgpt.deepchill.app/blogs/coding/optimize-water-distribution-costs-ksiw1FbgJBQz2DEfQ8JKeE)
> 📅 *3/1/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

You are tasked with providing water to a neighborhood of n houses. For each house, you can either build a well directly on-site for a specific cost or lay a pipe to connect it to another house that already has access to water, incurring a pipe-laying cost. Given the costs for digging a well at each house and the costs of connecting pairs of houses via pipes, design an algorithm to determine the minimum total expenditure required to ensure every house is supplied with water.

</details>

---

## [Optimize Water Distribution Costs](https://interviewgpt.deepchill.app/blogs/coding/optimize-water-distribution-costs-enDbyzK6Vzr9BhqZTAKH1x)
> 📅 *3/1/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a set of $n$ locations, you need to provide water to every location at the minimum possible cost. You have two options for each location: either build an onsite water source at a specific local cost or lay a pipeline to connect it to another location that already has access to water, where each pipe has an associated construction cost. Multiple pipes can exist between the same two locations. Design an algorithm to determine the minimum total expenditure required to ensure every location is supplied.

</details>

---

## [Jump Game Reachability](https://interviewgpt.deepchill.app/blogs/coding/jump-game-reachability-6Y2a8EcbcN6CvYNFRUeDY1)
> 📅 *2/28/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array of non-negative integers where each element represents your maximum jump distance from that position, write a function to determine if you can successfully travel from the start of the array to the final index.

</details>

---

## [Regex Pattern Matcher](https://interviewgpt.deepchill.app/blogs/coding/regex-pattern-matcher-1wg2msa9eKPJqdkr61XDVB)
> 📅 *2/20/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a system to determine if a given text string matches a specific formatting pattern. The pattern supports two special markers: a single-character wildcard that represents any individual character, and a repetition wildcard that allows the immediately preceding character to appear zero or more times. Your implementation must validate if the pattern matches the entire text string, not just a portion of it.

</details>

---

## [Median of Two Sorted Arrays](https://interviewgpt.deepchill.app/blogs/coding/median-of-two-sorted-arrays-vhHb1ig3jjhzE5w2BXob4j)
> 📅 *2/17/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two sorted numerical arrays of potentially different lengths, implement an efficient algorithm to find the median of the combined sorted set without merging them into a new array. The solution should ideally run in logarithmic time relative to the size of the smaller array.

</details>

---

## [Trapping Rain Water](https://interviewgpt.deepchill.app/blogs/coding/trapping-rain-water-kbFQ74M3UKnrJEm3jLpgPM)
> 📅 *2/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a non-negative integer array representing the heights of vertical bars on a 2D map where each bar has a width of 1, compute the total volume of water that can be contained within the structures after a rainfall.

</details>

---

## [Merge Overlapping Intervals](https://interviewgpt.deepchill.app/blogs/coding/merge-overlapping-intervals-dRAB8DJT27AMkqvdFb8b8C)
> 📅 *2/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a collection of time intervals, consolidate all overlapping or adjacent ranges into a single continuous interval. The goal is to produce a simplified set of disjoint intervals that covers the same total span as the original input. Provide an implementation that handles unsorted input efficiently and accounts for varying interval lengths.

</details>

---

## [LRU Cache Implementation](https://interviewgpt.deepchill.app/blogs/coding/lru-cache-implementation-pXmXhUFmnzDD6MfjAJFyYp)
> 📅 *2/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design and implement a system that functions as a Least Recently Used (LRU) cache. The system should support retrieving values by key and inserting or updating key-value pairs. If the cache reaches its predefined capacity, it must automatically discard the item that has not been accessed for the longest period. Ensure that both retrieval and insertion operations are optimized to perform in constant time on average.

</details>

---

## [Median of Two Sorted Arrays](https://interviewgpt.deepchill.app/blogs/coding/median-of-two-sorted-arrays-8WCGwB6QDwWqH17VUyug3p)
> 📅 *2/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two separate sorted collections of numerical data, design a highly efficient algorithm to compute the median value of the combined dataset. Your solution should achieve logarithmic time complexity relative to the size of the smaller collection, avoiding a full merge of the data.

</details>

---

## [Median of Two Sorted Arrays](https://interviewgpt.deepchill.app/blogs/coding/median-of-two-sorted-arrays-o3nETvyvYPQkyrjozKbT4w)
> 📅 *2/13/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two separate, sorted data collections, design an algorithm to compute the median value of the combined dataset. Your solution should achieve logarithmic time complexity relative to the size of the smaller collection, avoiding a full merge of the data.

</details>

---

## [Merge Intervals](https://interviewgpt.deepchill.app/blogs/coding/merge-intervals-jrtCETF53sbmCSBay6QX2u)
> 📅 *2/13/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array of intervals, merge all overlapping intervals and return the resulting array of non-overlapping intervals in sorted order.

</details>

---

## [Minimum Cost to Connect Cities](https://interviewgpt.deepchill.app/blogs/coding/minimum-cost-to-connect-cities-6NXLUS7rUMvsbxmRN2e9ex)
> 📅 *2/12/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given n cities and a list of weighted edges between them, find the minimum cost to connect all cities such that there is a path between every pair of cities, or return -1 if it is impossible.

</details>

---

## [Median of Two Sorted Arrays](https://interviewgpt.deepchill.app/blogs/coding/median-of-two-sorted-arrays-sHpiHNbXVubtccpizC8q1z)
> 📅 *2/10/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two independently sorted arrays, find the median of the merged dataset in O(log(m+n)) time without explicitly merging the arrays.

</details>

---

## [LRU Cache Design](https://interviewgpt.deepchill.app/blogs/coding/lru-cache-design-rqZ9EmCj4AhhwbKWkDRi7w)
> 📅 *2/9/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design and implement an LRU cache that supports get and put operations in O(1) time, evicting the least recently used key when capacity is exceeded.

</details>

---

## [Trapping Rain Water](https://interviewgpt.deepchill.app/blogs/coding/trapping-rain-water-4f69rPxpgx2aQp1PKi26Yj)
> 📅 *2/9/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an elevation map represented as an integer array where each element is the height of a bar of width 1, compute the total amount of water that can be trapped between the bars after rainfall.

</details>

---

## [Sliding Window Maximum](https://interviewgpt.deepchill.app/blogs/coding/sliding-window-maximum-5LiHS5X6bwK6SQGRnr13dh)
> 📅 *2/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer array and a sliding window of size k, return the maximum value in each window position as the window moves from left to right.

</details>

---

## [Minimum Train Platforms](https://interviewgpt.deepchill.app/blogs/coding/minimum-train-platforms-cyLt5DrpThDw8F66FUCTCD)
> 📅 *2/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given the arrival and departure times of all trains at a station, determine the minimum number of platforms required so that no train has to wait.

</details>

---

## [Robot Room Cleaner](https://interviewgpt.deepchill.app/blogs/coding/robot-room-cleaner-tjDi5J8djyUUJKnp8RnbVw)
> 📅 *2/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a robot in an unknown grid that can move, turn, and clean, design an algorithm using only the robot's API to clean all reachable empty cells.

</details>

---

## [Maximal Rectangle in Binary Matrix](https://interviewgpt.deepchill.app/blogs/coding/maximal-rectangle-in-binary-matrix-gwZx5i4degr3diRvVPkCc3)
> 📅 *2/5/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a binary matrix filled with 0s and 1s, find the area of the largest rectangle containing only 1s.

</details>

---

## [Reverse Linked List in K-Groups](https://interviewgpt.deepchill.app/blogs/coding/reverse-linked-list-in-k-groups-mcePmTiQyKH6P2zH9RcucQ)
> 📅 *2/4/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given the head of a linked list and an integer k, reverse the nodes of the list k at a time and return the modified list. If the remaining nodes are fewer than k, leave them as-is.

</details>

---

## [Two Sum](https://interviewgpt.deepchill.app/blogs/coding/two-sum-rr958fa1bnREM1n2Rg6m7W)
> 📅 *2/3/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an array of integers and a target sum, return the indices of the two distinct elements that add up to the target. Assume exactly one valid answer exists.

</details>

---

## [Health Anomaly Detection](https://interviewgpt.deepchill.app/blogs/coding/health-anomaly-detection-sCCpwf8h4Lt5hyPcRMLAXS)
> 📅 *2/3/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a stream of health metric readings and a threshold, identify all contiguous time windows where the metric continuously exceeds the threshold for a specified minimum duration.

</details>

---

## [Trapping Rain Water](https://interviewgpt.deepchill.app/blogs/coding/trapping-rain-water-1N4N5obu8erqSDyUK9jZqP)
> 📅 *1/29/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given n non-negative integers representing the heights of an elevation map where each bar has width 1, compute how much water can be trapped between the bars after it rains.

</details>

---

## [N-Queens Problem](https://interviewgpt.deepchill.app/blogs/coding/n-queens-problem-8u2XbEWXpzvUNGXBmEuNgA)
> 📅 *1/28/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer n, return all distinct solutions to the N-Queens puzzle, where n queens must be placed on an n×n chessboard such that no two queens attack each other.

</details>

---

## [3Sum](https://interviewgpt.deepchill.app/blogs/coding/3sum-xu3nUJYXm9Xp5bjEu8dYPH)
> 📅 *1/26/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer array, return all unique triplets that sum to zero, ensuring no duplicate triplets appear in the result.

</details>

---

## [N-Queens Problem](https://interviewgpt.deepchill.app/blogs/coding/n-queens-problem-rLXQeowKj76bY2sAz9V24D)
> 📅 *1/26/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer n, find all distinct arrangements of n queens on an n×n chessboard such that no two queens share the same row, column, or diagonal.

</details>

---

## [Palindrome Number](https://interviewgpt.deepchill.app/blogs/coding/palindrome-number-tgo1hJg95eXv7xZafavKGt)
> 📅 *1/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer, determine whether it is a palindrome without converting it to a string, handling negative numbers and numbers ending in zero as edge cases.

</details>

---

## [Add Two Numbers as Linked Lists](https://interviewgpt.deepchill.app/blogs/coding/add-two-numbers-as-linked-lists-iCMeTUXCKDpBvMMMHUeyZp)
> 📅 *1/21/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two non-empty linked lists representing non-negative integers stored in reverse order, return a linked list representing the sum of the two numbers, also in reverse order.

</details>

---

## [Median of Two Sorted Arrays](https://interviewgpt.deepchill.app/blogs/coding/median-of-two-sorted-arrays-smfCaUhskhEZNAcJycvBJ5)
> 📅 *1/19/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given two sorted arrays of sizes m and n, find the median of the combined array in O(log(m+n)) time without merging them.

</details>

---

## [Two Sum](https://interviewgpt.deepchill.app/blogs/coding/two-sum-aNvzJ1HDd4gv3ByRtN8E6w)
> 📅 *1/19/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given an integer array and a target value, return the indices of the two numbers that add up to the target. Each input has exactly one solution and the same element may not be used twice.

</details>

---

*Generated by [InterviewGPT](https://interviewgpt.ai) on Thu Apr 16 2026*
