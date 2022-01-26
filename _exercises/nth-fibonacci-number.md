---
title: "Nth Fibonacci Number"
---

The Fibonacci sequence goes like this: 1, 1, 2, 3, 5, 8, 13, 21, 34, ...

The next number can be found by adding up the two numbers before it, and the first two numbers are always 1.

Write a function that takes an integer `n` and returns the `n`th Fibonacci number in the sequence.

**Constraints**

- `n ≤ 30`

[https://binarysearch.com/problems/Nth-Fibonacci-Number](https://binarysearch.com/problems/Nth-Fibonacci-Number){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `7`

**Output**

- answer = `13`

**Explanation**

Since `13` is the seventh number: `1`, `1`, `2`, `3`, `5`, `8`, `13`

### Example 2

**Input**

- n = `6`

**Output**

- answer = `8`

**Explanation**

Since `8` is the `6`th fibonacci number: `1`, `1`, `2`, `3`, `5`, `8`.

### Example 3

**Input**

- n = `1`

**Output**

- answer = `1`

**Explanation**

This is the base case and the first fibonacci number is defined as `1`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Nth-Fibonacci-Number.cpp"></script>
