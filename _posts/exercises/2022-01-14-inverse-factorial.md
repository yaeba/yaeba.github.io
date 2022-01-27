---
title: "Inverse Factorial"
---

The factorial of a number `n` is defined as `n! = n * (n - 1) * (n - 2) * ... * 1`.

Given a positive integer `a`, return `n` such that `n! = a`. If there is no integer `n` that is a factorial, then return `-1`.

**Constraints**

- `0 < a < 2 ** 31`

[https://binarysearch.com/problems/Inverse-Factorial](https://binarysearch.com/problems/Inverse-Factorial){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `6`

**Output**

- answer = `3`

**Explanation**

3! = 6

### Example 2

**Input**

- a = `10`

**Output**

- answer = `-1`

**Explanation**

10 is not any integer factorial.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Inverse-Factorial.cpp"></script>
