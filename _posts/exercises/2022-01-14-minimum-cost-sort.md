---
title: "Minimum Cost Sort"
tags: ["array"]
---

Given a list of integers `nums`, return the minimum cost of sorting the list in ascending or descending order. The cost is defined as the sum of absolute differences between any element's old and new value.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Minimum-Cost-Sort](https://binarysearch.com/problems/Minimum-Cost-Sort){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 4, 3]`

**Output**

- answer = `2`

**Explanation**

The cost to change the list to ascending order is `2`:

- Change `4` to `3` for a cost of `1`
- Change `3` to `4` for a cost of `1`

### Example 2

**Input**

- nums = `[7, 3, 5]`

**Output**

- answer = `4`

**Explanation**

The cost to change the list to descending order is `4`:

- Change `3` to `5` for a cost of `2`
- Change `5` to `3` for a cost of `2`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Cost-Sort.py"></script>
