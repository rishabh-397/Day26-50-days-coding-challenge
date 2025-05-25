# Day26-50-days-coding-challenge
🔸 Problem 1: Binary Tree Inorder Traversal

📌 Problem Statement:
Given the root of a binary tree, return its inorder traversal (left ➡ root ➡ right).

📌 Constraints:

0 <= number of nodes <= 100

-100 <= Node.val <= 100

📌 Approach:

Recursive Approach: Use recursion to traverse left, visit root, traverse right.

Iterative Approach: Use a stack to simulate recursion.

📌 Examples:
Input: [1,null,2,3]
Output: [1,3,2]

Input: [1,2,3,4,5,null,8,null,null,6,7,9]
Output: [4,2,6,5,7,1,3,9,8]

🔸 Problem 2: Find First and Last Position of Element in Sorted Array

📌 Problem Statement:
Given a sorted array nums and a target target, return the starting and ending position of the target value.
If target is not found, return [-1, -1].

📌 Constraints:

0 <= nums.length <= 10⁵

-10⁹ <= nums[i], target <= 10⁹

nums is sorted in non-decreasing order.

📌 Approach:

Use binary search twice:
1️⃣ First binary search for the leftmost index of target.
2️⃣ Second binary search for the rightmost index of target.

If target is not found, return [-1, -1].

📌 Examples:
Input: nums = [5,7,7,8,8,10], target = 8
Output: [3,4]

Input: nums = [5,7,7,8,8,10], target = 6
Output: [-1,-1]

📌 Time Complexity: O(log n)
📌 Space Complexity: O(1)

📌 Topics Covered:
Tree Traversals (DFS)

Stack-based traversal

Binary Search Algorithms

Edge Case Handling




