---
title: "Shift to Create Range"
---

You are given a list of integers `nums` of length `n`. Return whether you can make a list `[1, 2, ..., n]` or `[n, n - 1, ..., 1]` by shifting `nums` to the right any number of times.

For example, shifting `[1, 2, 4, 3]` right once gives us `[3, 1, 2, 4]`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Shift-to-Create-Range](https://binarysearch.com/problems/Shift-to-Create-Range){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[4, 1, 2, 3]`

**Output**

- answer = `True`

**Explanation**

We can make `[1, 2, 3, 4]` by shifting to the right `3` times.

### Example 2

**Input**

- nums = `[1, 4, 2, 3]`

**Output**

- answer = `False`

**Explanation**

There's no way to make `[1, 2, 3, 4]` or `[4, 3, 2, 1]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shift-to-Create-Range.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shift-to-Create-Range.py"></script>
