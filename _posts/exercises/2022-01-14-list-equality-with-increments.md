---
title: "List Equality with Increments"
tags: ["math"]
---

You are given a list of integers `nums`, and want to make the values equal. Consider an operation where you pick an integer in the list and increment every other value .

Return the minimum number of operations required to make integer values equal.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/List-Equality-with-Increments](https://binarysearch.com/problems/List-Equality-with-Increments){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 4]`

**Output**

- answer = `5`

**Explanation**

Here are the operations we can use:

- `[2, 4, 4]`
- `[3, 5, 4]`
- `[4, 5, 5]`
- `[5, 6, 5]`
- `[6, 6, 6]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=List-Equality-with-Increments.cpp"></script>
