---
title: "Remove Duplicates Occurring More Than Twice"
tags: ["array", "two pointers"]
---

Given a list of integers `nums` sorted in ascending order, remove in-place duplicates that appear more than twice.

This should be done in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Remove-Duplicates-Occurring-More-Than-Twice](https://binarysearch.com/problems/Remove-Duplicates-Occurring-More-Than-Twice){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1]`

**Output**

- answer = `[1, 1]`

### Example 2

**Input**

- nums = `[3, 3, 3, 3, 4, 4, 8]`

**Output**

- answer = `[3, 3, 4, 4, 8]`

**Explanation**

We remove the third and fourth `3` since they occur more than twice.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Remove-Duplicates-Occurring-More-Than-Twice.cpp"></script>
