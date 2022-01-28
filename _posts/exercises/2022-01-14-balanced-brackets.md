---
title: "Balanced Brackets"
tags: ["string", "stack", "prefix sum"]
---

You're given a string `s` consisting solely of `"("` and `")"`. Return whether the parentheses are balanced.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`.

[https://binarysearch.com/problems/Balanced-Brackets](https://binarysearch.com/problems/Balanced-Brackets){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `()`

**Output**

- answer = `True`

### Example 2

**Input**

- s = `()()`

**Output**

- answer = `True`

### Example 3

**Input**

- s = `)(`

**Output**

- answer = `False`

### Example 4

**Input**

- s = ``

**Output**

- answer = `True`

### Example 5

**Input**

- s = `((()`

**Output**

- answer = `False`

### Example 6

**Input**

- s = `((()))`

**Output**

- answer = `True`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Balanced-Brackets.py"></script>
