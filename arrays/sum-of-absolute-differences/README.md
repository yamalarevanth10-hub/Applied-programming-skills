Sum of Absolute Differences in a Sorted Array
Problem Statement
Given a sorted integer array nums, return an array result such that:

result[i] = sum of |nums[i] - nums[j]| for all j where 0 ≤ j < n.

Approach
Since the array is sorted, use prefix sums
Maintain:
leftSum: sum of elements to the left of index i
rightSum: sum of elements to the right of index i
Compute result using mathematical formula to avoid nested loops
Formula
result[i] = (nums[i] * i - leftSum) + (rightSum - nums[i] * (n - i - 1))

Time Complexity
O(n)

Space Complexity
O👎