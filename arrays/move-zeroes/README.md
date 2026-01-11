Problem Statement

Given an integer array, move all 0s to the end of the array while maintaining the relative order of non-zero elements.
The operation must be done in-place.

🧠 Approach / Logic

Use a pointer to track the position for the next non-zero element.

Traverse the array:

When a non-zero element is found, place it at the pointer index.

Increment the pointer.

After traversal, fill the remaining positions with 0.

This ensures all non-zero elements stay in order and zeroes are pushed to the end.

⏱️ Time Complexity

O(n)

Single traversal of the array

🧮 Space Complexity

O(1)

No extra data structures used