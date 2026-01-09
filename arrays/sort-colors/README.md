Sort Colors
Problem Statement:
Given an array nums with n objects colored red, white, or blue, sort them in-place so that objects of the same color are adjacent.

We use the integers:

0 → Red
1 → White
2 → Blue
You must solve this problem without using the library sort function.

Approach:
Use the Dutch National Flag algorithm
Maintain three pointers: start, mid, and end
Place 0s at the beginning, 2s at the end, and 1s in the middle
Time Complexity:
O(n)

Space Complexity:
O(1)