---
title: "Large to Small Sort"
---

Given a list of integers `nums`, sort the list in the following way:

- First number is the maximum
- Second number is the minimum
- Third number is the 2nd maximum
- Fourth number is the 2nd minimum
- And so on.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Large-to-Small-Sort](https://binarysearch.com/problems/Large-to-Small-Sort){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 9, 9]`

**Output**

- answer = `[9, 1, 9]`

### Example 2

**Input**

- nums = `[5, 2, 9, 3]`

**Output**

- answer = `[9, 2, 5, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Large-to-Small-Sort.cpp"></script>
