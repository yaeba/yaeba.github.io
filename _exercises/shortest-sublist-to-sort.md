---
title: "Shortest Sublist to Sort"
tags: ["array"]
---

Given a list of integers `nums`, return the length of the shortest sublist in `nums` which if sorted would make `nums` sorted in ascending order.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Shortest-Sublist-to-Sort](https://binarysearch.com/problems/Shortest-Sublist-to-Sort){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[5, 4, 3, 2, 8, 9]`

**Output**

- answer = `4`

**Explanation**

Sorting the sublist `[5, 4, 3, 2]` would get us `[2, 3, 4, 5, 8, 9]`

### Example 2

**Input**

- nums = `[1, 2, 3, 5, 9, 8, 5]`

**Output**

- answer = `3`

**Explanation**

Sorting the sublist `[9, 8, 5]` would get us `[1, 2, 3, 5, 5, 8, 9]`

### Example 3

**Input**

- nums = `[0, 1, 4, 3, 8, 9]`

**Output**

- answer = `2`

**Explanation**

Sorting the sublist `[4, 3]` would get us `[0, 1, 3, 4, 8, 9]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shortest-Sublist-to-Sort.cpp"></script>
