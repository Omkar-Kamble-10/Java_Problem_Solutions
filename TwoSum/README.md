# Two Sum Problem

**Problem Link:** [https://leetcode.com/problems/two-sum/](https://leetcode.com/problems/two-sum/)

---

## Problem Description
Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

---

## Approach
- Use a HashMap to store numbers and their indices.
- For each number, check if `(target - number)` exists in the map.
- If found, return the pair of indices.
- Time Complexity: **O(n)**
- Space Complexity: **O(n)**

---

## Example
Input:  
nums = [2,7,11,15], target=9
Output = [0,1]