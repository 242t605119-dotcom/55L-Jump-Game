# LeetCode 55 – Jump Game

## Problem

You are given an integer array `nums`. Each element represents the maximum number of steps you can jump forward from that position.

Starting from the first index, determine whether you can reach the last index.

## Example

### Input

```text
nums = [2,3,1,1,4]
```

### Output

```text
true
```

You can reach the last index by jumping from index `0` to index `1`, and then to the last index.

## Approach

I used a **Greedy Approach** to solve this problem.

While going through the array, I keep track of the farthest index that can be reached.

For every position:

1. Check whether the current position is reachable.
2. Calculate how far we can reach from that position.
3. Update the farthest reachable position.
4. If the last index becomes reachable, return `True`.
5. If we reach a position beyond the farthest reachable index, return `False`.

## Complexity

* **Time Complexity:** `O(N)`
* **Space Complexity:** `O(1)`

## Language

**Python**

## LeetCode

**Problem:** 55. Jump Game
**Difficulty:** Medium
**Topic:** Array, Greedy

## Author

T.Nandhini
