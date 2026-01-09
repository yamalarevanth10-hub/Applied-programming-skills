Contains Duplicate II
Problem Statement:
Given an integer array nums and an integer k, return true if there exist two distinct indices i and j such that:

nums[i] == nums[j]
|i - j| ≤ k
Approach:
Use a sliding window of size k
Maintain a set to store elements in the current window
If an element already exists in the set, return true
Time Complexity:
O(n)

Space Complexity:
O(k)