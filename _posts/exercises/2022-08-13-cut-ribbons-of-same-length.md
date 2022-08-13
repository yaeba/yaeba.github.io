---
title: "Cut Ribbons of Same Length"
---

You are given a list of positive integers `ribbons` and an integer `k`. Given that you can cut the ribbons as many times as you want, return the largest `r` such that you can have `k` ribbons of length `r`. If there is no solution, return `-1`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `ribbons`
- `1 ≤ k`

[https://binarysearch.com/problems/Cut-Ribbons-of-Same-Length](https://binarysearch.com/problems/Cut-Ribbons-of-Same-Length){:target="\_blank"}

## Examples

### Example 1

**Input**

- ribbons = `[8]`
- k = `4`

**Output**

- answer = `2`

**Explanation**

We can cut the ribbon into `4` pieces of size `2`.

### Example 2

**Input**

- ribbons = `[1, 2, 3, 4, 9]`
- k = `5`

**Output**

- answer = `3`

**Explanation**

We can cut the ribbon of size `9` into `3` pieces of size `3` each. Then cut the ribbon of size `4` into size `1` and `3`. Then we can achieve `5` ribbons of size `3`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Cut-Ribbons-of-Same-Length.py"></script>
