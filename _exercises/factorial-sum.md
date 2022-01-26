---
title: "Factorial Sum"
tags: ["math"]
---

Given a positive integer `n`, return whether `n` can be written as the sum of distinct positive factorial numbers.

**Constraints**

- `0 < n < 2 ** 31`

[https://binarysearch.com/problems/Factorial-Sum](https://binarysearch.com/problems/Factorial-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `31`

**Output**

- answer = `True`

**Explanation**

Since `31 = 4! + 3! + 1!`

### Example 2

**Input**

- n = `4`

**Output**

- answer = `False`

**Explanation**

Since `4 = 2! + 2!` but not distinct.

### Example 3

**Input**

- n = `6`

**Output**

- answer = `True`

### Example 4

**Input**

- n = `29`

**Output**

- answer = `False`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Factorial-Sum.py"></script>
