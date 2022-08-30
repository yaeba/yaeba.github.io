---
title: "Sort by Permutation"
tags: ["array", "two pointers"]
---

Given a list of strings `lst` and a list of integers `p`, reorder `lst` so that every `lst[i]` gets placed to `p[i]`.

This should be done in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `lst`

[https://binarysearch.com/problems/Sort-by-Permutation](https://binarysearch.com/problems/Sort-by-Permutation){:target="\_blank"}

## Examples

### Example 1

**Input**

- lst = `['a', 'b', 'c', 'd']`
- p = `[3, 0, 1, 2]`

**Output**

- answer = `['b', 'c', 'd', 'a']`

**Explanation**

- a goes to index 3
- b goes to index 0
- c goes to index 1
- d goes to index 2

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sort-by-Permutation.cpp"></script>
