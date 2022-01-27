---
title: "Fixed Point"
tags: ["binary search", "array"]
---

Given a list of unique integers `nums` sorted in ascending order, return the minimum `i` such that `nums[i] == i`. If there's no solution, return `-1`.

This should be done in $$\mathcal{O}(log(n))$$ time.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Fixed-Point](https://binarysearch.com/problems/Fixed-Point){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[-5, -2, 0, 3, 4]`

**Output**

- answer = `3`

**Explanation**

Both `nums[3] == 3` and `nums[4] == 4` but `3` is smaller.

### Example 2

**Input**

- nums = `[-5, -4, 0]`

**Output**

- answer = `-1`

**Explanation**

There's no `i` such that `nums[i] = i`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Fixed-Point.cpp"></script>
