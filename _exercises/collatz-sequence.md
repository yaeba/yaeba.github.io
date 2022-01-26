---
title: "Collatz Sequence"
---

Given a positive integer `n`, find the length of its Collatz sequence. The Collatz sequence is generated sequentially where

- `n = n / 2` if n is even
- `n = 3 * n + 1` if n is odd
- And the sequence ends if `n = 1`

[https://binarysearch.com/problems/Collatz-Sequence](https://binarysearch.com/problems/Collatz-Sequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `11`

**Output**

- answer = `15`

**Explanation**

The Collatz sequence is: `[11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]` and its length is 15.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Collatz-Sequence.cpp"></script>
