---
title: "Compressed Vector Product"
---

You are given two integer lists `a` and `b` where each list represents a vector in run-length encoded form. For example, a vector `[1, 1, 1, 1, 2, 2, 2, 2, 2]` is represented as `[4, 1, 5, 2]`. (There are `4` ones and `5` twos.)

Return the dot product of the two vectors `a` and `b`.

The dot product of a vector `[x1, x2, ..., xn]` and `[y1, y2, ..., yn]` is defined to be `x1 * y1 + x2 * y2 + ... + xn * yn`.

**Constraints**

- `1 ≤ n ≤ 200,000` where `n` is the length of `a`
- `1 ≤ m ≤ 200,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Compressed-Vector-Product](https://binarysearch.com/problems/Compressed-Vector-Product){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `[4, 1, 5, 2]`
- b = `[9, 2]`

**Output**

- answer = `28`

**Explanation**

`a • b = [1, 1, 1, 1, 2, 2, 2, 2, 2] • [2, 2, 2, 2, 2, 2, 2, 2, 2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Compressed-Vector-Product.py"></script>
