---
title: "List Min Replacement"
tags: ["array"]
---

Given a list of integers `nums`, replace every `nums[i]` with the smallest integer left of `i`. Replace `nums[0]` with `0`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/List-Min-Replacement](https://binarysearch.com/problems/List-Min-Replacement){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[10, 5, 7, 9]`

**Output**

- answer = `[0, 10, 5, 5]`

**Explanation**

- `nums[0] = 0` by definition
- `nums[1] = min(10)`
- `nums[2] = min(5, 10)`
- `nums[3] = min(7, 5, 10)`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=List-Min-Replacement.cpp"></script>
