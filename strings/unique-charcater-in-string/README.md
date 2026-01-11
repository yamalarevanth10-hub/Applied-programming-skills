Problem Statement

Given a string, find the index of the first non-repeating (unique) character in the string.
If no unique character exists, return -1.

🧠 Approach / Logic

Traverse the string and count the frequency of each character.

Traverse the string again from left to right.

Return the index of the first character whose frequency is exactly 1.

If no such character is found, return -1.

This two-pass approach ensures both correctness and order preservation.

⏱️ Time Complexity

O(n)

One pass to count frequencies

One pass to find the first unique character

🧮 Space Complexity

O(1)

Fixed-size frequency array (for English lowercase letters)

Does not grow with input size