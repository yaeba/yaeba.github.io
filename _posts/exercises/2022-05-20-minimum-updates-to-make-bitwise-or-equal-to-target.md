---
title: "Minimum Updates to Make Bitwise OR Equal to Target"
tags: ["bit manipulation"]
---

You are given three positive integers `a`, `b` and `target`. Consider an operation where you take either `a` or `b` and update one of the bits to `1` or to `0`.

Return the minimum number of operations required to make `a | b = target`.

**Constraints**

- `1 ≤ a, b, target < 2 ** 31`

[https://binarysearch.com/problems/Minimum-Updates-to-Make-Bitwise-OR-Equal-to-Target](https://binarysearch.com/problems/Minimum-Updates-to-Make-Bitwise-OR-Equal-to-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `2`
- b = `4`
- target = `8`

**Output**

- answer = `3`

**Explanation**

```
  10 = a
 100 = b
1000 = target
```

We need to first unset `a` and `b`s `1` bits to make them zero. Then we can set `a` directly to `8`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Updates-to-Make-Bitwise-OR-Equal-to-Target.py"></script>
