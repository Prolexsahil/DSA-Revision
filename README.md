# DSA-Revision
DSA revision for placements

## Goal

Prepare for big-tech placement interviews over the remaining ~2 months with a focus on:

> **Pattern recognition → optimal approach → implementation speed → edge cases → interview communication.**

The objective is not to simply finish a DSA sheet. The goal is to recognize the correct pattern quickly, derive the optimal solution, implement it cleanly, and explain it like an interview candidate.

---

# 1. Problem-Solving Procedure

For every problem, use this process.

## Round 1 — Recognition

Before coding, answer:

1. What pattern is this?
2. What is the brute-force approach?
3. Why is brute force too slow?
4. What invariant/property allows optimization?
5. What is the target time and space complexity?

## Round 2 — Implementation

Code the optimal approach without looking at the solution.

## Round 3 — Interview Explanation

Be able to explain:

> "The key observation is ___, therefore we maintain ___, which lets us reduce ___ from O(...) to O(...)."

## Round 4 — Re-solve

Re-solve important problems after:

- 1 day
- 7 days
- 21 days

The objective is to convert recognition into interview-level recall.

---

# 2. Complete DSA Pattern Roadmap

## 2.1 Arrays + Hashing

**12 problems**

1. Two Sum
2. Contains Duplicate
3. Valid Anagram
4. Group Anagrams
5. Product of Array Except Self
6. Longest Consecutive Sequence
7. Majority Element
8. Subarray Sum Equals K
9. Longest Subarray with Sum K
10. Sort Colors
11. Maximum Subarray
12. Maximum Product Subarray

### Must Know

- HashMap / HashSet
- Frequency counting
- Prefix sum + hashmap
- Kadane's algorithm
- In-place array manipulation

---

## 2.2 Two Pointers

**12 problems**

1. Valid Palindrome
2. Two Sum II
3. 3Sum
4. 4Sum
5. Container With Most Water
6. Trapping Rain Water
7. Remove Duplicates from Sorted Array
8. Remove Duplicates from Sorted Array II
9. Move Zeroes
10. Squares of a Sorted Array
11. Backspace String Compare
12. Boats to Save People

### Must Recognize

- Left/right pointers
- Slow/fast pointers
- Sorted array + two pointers
- Opposite-direction pointers
- Same-direction pointers

---

## 2.3 Sliding Window

**12 problems**

1. Best Time to Buy and Sell Stock
2. Longest Substring Without Repeating Characters
3. Longest Repeating Character Replacement
4. Permutation in String
5. Find All Anagrams in a String
6. Minimum Window Substring
7. Maximum Average Subarray I
8. Max Consecutive Ones III
9. Fruit Into Baskets
10. Minimum Size Subarray Sum
11. Subarray Product Less Than K
12. Sliding Window Maximum

### Must Know

- Fixed window
- Variable window
- Frequency map
- Shrinking condition
- Monotonic deque

---

## 2.4 Prefix Sum / Difference Array

**12 problems**

1. Range Sum Query
2. Subarray Sum Equals K
3. Continuous Subarray Sum
4. Find Pivot Index
5. Product of Array Except Self
6. Corporate Flight Bookings
7. Car Pooling
8. Range Addition
9. Subarray Sums Divisible by K
10. Contiguous Array
11. Maximum Size Subarray Sum Equals k
12. Path Sum III

### Critical Concepts

- `prefix[i] - prefix[j]`
- Prefix remainder
- Prefix + hashmap
- 2D prefix sum
- Difference array

---

## 2.5 Binary Search

**12 problems**

1. Binary Search
2. Search Insert Position
3. First Bad Version
4. Find First and Last Position
5. Search in Rotated Sorted Array
6. Search in Rotated Sorted Array II
7. Find Minimum in Rotated Sorted Array
8. Find Peak Element
9. Koko Eating Bananas
10. Capacity To Ship Packages Within D Days
11. Split Array Largest Sum
12. Median of Two Sorted Arrays

### Must Master

#### Type A — Normal Binary Search

```text
Search in sorted data.
