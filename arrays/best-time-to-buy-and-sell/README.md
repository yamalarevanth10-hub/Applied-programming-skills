Best Time to Buy and Sell Stock
Problem Statement:
You are given an array prices where prices[i] is the price of a given stock on the i-th day.

You want to maximize your profit by choosing a single day to buy one stock and choosing a different day in the future to sell that stock.

Return the maximum profit you can achieve. If you cannot achieve any profit, return 0.

Approachs:
Track the minimum price so far
For each day, calculate profit if sold on that day
Update maximum profit whenever a better profit is found
Time Complexity:
O(n)

Space Complexity:
O(1)