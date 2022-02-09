---
title: "Bubble Swap"
tags: ["array"]
---

Given two lists of integers `lst0` and `lst1`, each of length `n` and where each value is unique to its array and between `0` to `n - 1`, return the minimum number of adjacent swaps required to transform `lst0` to `lst1`.

**Constraints**

- `n ≤ 500` where `n` is the length of `lst0` and `lst1`.

[https://binarysearch.com/problems/Bubble-Swap](https://binarysearch.com/problems/Bubble-Swap){:target="\_blank"}

## Examples

### Example 1

**Input**

- lst0 = `[0, 1, 2]`
- lst1 = `[2, 0, 1]`

**Output**

- answer = `2`

**Explanation**

We can swap 1 with 2, and then 0 with 2.

### Example 2

**Input**

- lst0 = `[0, 1, 2]`
- lst1 = `[2, 1, 0]`

**Output**

- answer = `3`

**Explanation**

We can swap 0 with 1, then swap 0 with 2, then 1 with 2.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Bubble-Swap.py"></script>
