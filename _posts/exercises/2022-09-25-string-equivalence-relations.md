---
title: "String Equivalence Relations"
tags: ["string", "graph", "union find"]
---

You are given three lowercase alphabet strings `a`, `b` and `target`. Strings `a` and `b` have the same length and are defined to be equivalent: `a[i] = b[i]`. For example, if `a = "abc"` and `b = "xyz"`, then `"a" = "x"`, `"b" = "y"` and `"c" = "z"`.

Also, we can make the following kinds of inferences for characters:

- `c = c`
- `a = b` implies `b = a`
- `a = b` and `b = c` implies `a = c`

Return the smallest lexicographically equivalent string for `target`.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `a` and `b`
- `m ≤ 1,000` where `m` is the length of `target`

[https://binarysearch.com/problems/String-Equivalence-Relations](https://binarysearch.com/problems/String-Equivalence-Relations){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `axc`
- b = `xdz`
- target = `ddxz`

**Output**

- answer = `aaac`

**Explanation**

We know that `"a" = "x"` and `"x" = "d"`, so `"a" = "d"`. So we can replace the `"d"`s and `"x"` with `"a"`s. Then we can directly replace `"z"` with `"c"`.

### Example 2

**Input**

- a = `abc`
- b = `def`
- target = `xyz`

**Output**

- answer = `xyz`

**Explanation**

There's no inferences we can make here.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=String-Equivalence-Relations.py"></script>
