---
title: "Stuck Keyboard"
tags: ["string", "two pointers"]
---

You are given two strings `typed` and `target`. You want to write `target`, but the keyboard is stuck so some characters may be written `1` or more times. Return whether it's possible that `typed` was meant to write `target`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `typed`
- `m ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Stuck-Keyboard](https://binarysearch.com/problems/Stuck-Keyboard){:target="\_blank"}

## Examples

### Example 1

**Input**

- typed = `aaabcccc`
- target = `abc`

**Output**

- answer = `True`

**Explanation**

Each of the `"a"`, `"b"`, and `"c"` were typed

### Example 2

**Input**

- typed = `abc`
- target = `ab`

**Output**

- answer = `False`

**Explanation**

`"c"` was not typed

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Stuck-Keyboard.cpp"></script>
