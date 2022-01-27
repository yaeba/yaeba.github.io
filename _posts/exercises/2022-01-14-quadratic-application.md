---
title: "Quadratic Application"
tags: ["two pointers", "array"]
---

You are given a list of integers `nums` sorted in ascending order, and integers `a`, `b`, and `c`. Apply the following function for each number `x` in `nums`: $$ax^2 + bx + c$$ and return the resulting list in ascending order.

This should be done in $$\mathcal{O}(n)$$ time.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Quadratic-Application](https://binarysearch.com/problems/Quadratic-Application){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[-2, 3]`
- a = `1`
- b = `-3`
- c = `2`

**Output**

- answer = `[2, 12]`

**Explanation**

We have

- `nums[0] = 1*-2**2 + -3*-2 + 2 = 4 + 6 + 2 = 12`
- `nums[1] = 1*3**2 + -3*3 + 2 = 9 + -9 + 2 = 2`

After we sort `[12, 2]`, we get `[2, 12]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Quadratic-Application.py"></script>
