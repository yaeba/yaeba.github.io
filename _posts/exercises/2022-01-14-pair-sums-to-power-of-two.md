---
title: "Pair Sums to Power of Two"
---

You are given a list of integers `nums`. Return the number of pairs `i < j` such that `nums[i] + nums[j]` is equal to `2 ** k` for some `0 ≤ k`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Pair-Sums-to-Power-of-Two](https://binarysearch.com/problems/Pair-Sums-to-Power-of-Two){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 3, 5]`

**Output**

- answer = `4`

**Explanation**

We can have the following pairs that sums to power of `2`

- `(1, 1)`
- `(1, 3)`
- `(1, 3)`
- `(3, 5)`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Pair-Sums-to-Power-of-Two.cpp"></script>
