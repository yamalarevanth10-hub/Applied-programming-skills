Problem Statement

Given a character array, reverse the string in-place.

🧠 Approach / Logic

Initialize two pointers:

One at the beginning of the string

One at the end of the string

Swap the characters at both pointers.

Move the start pointer forward and the end pointer backward.

Repeat until the pointers meet.

This approach reverses the string without using extra space.

⏱️ Time Complexity

O(n)

Each character is visited once

🧮 Space Complexity

O(1)

In-place swapping without extra memory