Binary Search
Problem Statement
Given an array of integers nums which is sorted in ascending order, and an integer target, return the index of target if it exists in the array. Otherwise, return -1.

You must write an algorithm with O(log n) runtime complexity.

Approach
Use Binary Search
Maintain two pointers: left and right
Calculate mid index
Compare nums[mid] with target and reduce search space
Time Complexity
O(log n)

Space Complexity
O(1)