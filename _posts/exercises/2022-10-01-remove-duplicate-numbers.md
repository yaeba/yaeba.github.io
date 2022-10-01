---
title: "Remove Duplicate Numbers"
tags: ["two pointers", "array", "hash table"]
---

Given a list of integers `nums`, remove numbers that appear multiple times in the list, while maintaining order of the appearance in the original list.

It should use $$\mathcal{O}(k)$$ space where `k` is the number of unique integers.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Remove-Duplicate-Numbers](https://binarysearch.com/problems/Remove-Duplicate-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 5, 0, 3, 5, 8]`

**Output**

- answer = `[1, 0, 8]`

**Explanation**

Only [1, 0, 8] are unique in the list and that's the order they appear in.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Remove-Duplicate-Numbers.py"></script>
