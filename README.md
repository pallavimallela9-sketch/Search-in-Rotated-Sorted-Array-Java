# Search in Rotated Sorted Array - Java

## Problem Statement

Given a sorted array that has been rotated at an unknown
position, find the index of a target value.

If the target is not present, return -1.

## Example

Input:

[4, 5, 6, 7, 0, 1, 2]

Target:

0

Output:

4

## Explanation

The target `0` is present at index 4.

## Approach

This problem uses Binary Search.

At every step:

1. Find the middle element.
2. Check if the target is found.
3. Determine which half of the array is sorted.
4. Check whether the target belongs to the sorted half.
5. Search the appropriate half.

This reduces the search space by half each time.

## Complexity

- Time Complexity: O(log n)
- Space Complexity: O(1)

## Language

Java

## Algorithm

Binary Search

## Author

M. Pallavi
