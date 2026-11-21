# Best Time to Buy and Sell Stock

A Java solution to the Best Time to Buy and Sell Stock problem using the **Greedy Algorithm**.

## Problem Statement

Given an array `prices`, where `prices[i]` represents the stock price on the ith day, find the maximum profit possible by buying on one day and selling on a different future day.

You can complete only one transaction.

## Example

**Input:**
```text
prices = [7, 1, 5, 3, 6, 4]
```

**Output:**
```text
5
```

**Explanation:**

Buy the stock at price 1 and sell it at price 6.

Maximum Profit = 6 - 1 = 5.

## Approach: Greedy Algorithm

- Maintain the minimum stock price encountered so far.
- Calculate the profit at each day by subtracting the minimum price from the current price.
- Update the maximum profit whenever a better opportunity is found.
- Return the maximum profit.

## Complexity Analysis

- **Time Complexity:** O(n) — Traverse the array once.
- **Space Complexity:** O(1) — Only a few variables are used.

## Language

Java

## Topics

- Arrays
- Greedy Algorithm
- Single-pass Traversal
- Problem Solving