---
title: "Largest Number By Two Times"
---

Given a list of integers `nums`, return whether the largest number is bigger than the second-largest number by more than two times.

**Constraints**

- `2 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Largest-Number-By-Two-Times](https://binarysearch.com/problems/Largest-Number-By-Two-Times){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 6, 15]`

**Output**

- answer = `True`

**Explanation**

15 is bigger than 12 (2 \* 6).

### Example 2

**Input**

- nums = `[3, 6, 9]`

**Output**

- answer = `False`

**Explanation**

9 is not bigger than 2 \* 6.

### Example 3

**Input**

- nums = `[3, 6, 12]`

**Output**

- answer = `False`

**Explanation**

12 is not bigger than 2 \* 6, they're equal.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Number-By-Two-Times.cpp"></script>
