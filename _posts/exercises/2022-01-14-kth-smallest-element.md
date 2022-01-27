---
title: "Kth Smallest Element"
tags: ["divide and conquer", "array"]
---

Given a list of unsorted integers `nums`, and an integer `k`, return the `k`th (0-indexed) smallest element in the list.

This should be done in $$\mathcal{O}(n)$$ time on average.

**Constraints**

- `0 ≤ k < n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Kth-Smallest-Element](https://binarysearch.com/problems/Kth-Smallest-Element){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[5, 3, 8, 2, 0]`
- k = `2`

**Output**

- answer = `3`

**Explanation**

When sorted the numbers are `[0, 2, 3, 5, 8]` and index `2`'s value is `3`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Kth-Smallest-Element.cpp"></script>
