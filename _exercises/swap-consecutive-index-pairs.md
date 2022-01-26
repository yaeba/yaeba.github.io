---
title: "Swap Consecutive Index Pairs"
tags: ["array"]
---

Given a list of integers `nums`, swap each consecutive even indexes with each other, and swap each consecutive odd indexes with each other.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Swap-Consecutive-Index-Pairs](https://binarysearch.com/problems/Swap-Consecutive-Index-Pairs){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[0, 1, 2, 3, 4, 5, 6, 7, 8]`

**Output**

- answer = `[2, 3, 0, 1, 6, 7, 4, 5, 8]`

**Explanation**

- 0 and 2 gets swapped
- 1 and 3 gets swapped
- 4 and 6 gets swapped
- 5 and 7 gets swapped
- 8 remains the same

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Swap-Consecutive-Index-Pairs.cpp"></script>
