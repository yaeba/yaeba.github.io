---
title: "Detect the Only Duplicate in a List"
tags: ["two pointers", "array", "math"]
---

You are given a list `nums` of length `n + 1` picked from the range `1, 2, ..., n`. By the [pigeonhole principle](https://en.wikipedia.org/wiki/Pigeonhole_principle), there must be a duplicate. Find and return it. There is guaranteed to be exactly one duplicate.

Bonus: Can you do this in $$\mathcal{O}(n)$` time and `$\mathcal{O}(1)$$ space?

**Constraints**

- `n ≤ 10,000`

[https://binarysearch.com/problems/Detect-the-Only-Duplicate-in-a-List](https://binarysearch.com/problems/Detect-the-Only-Duplicate-in-a-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 1]`

**Output**

- answer = `1`

**Explanation**

### Example 2

**Input**

- nums = `[4, 2, 1, 3, 2]`

**Output**

- answer = `2`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Detect-the-Only-Duplicate-in-a-List.cpp"></script>
