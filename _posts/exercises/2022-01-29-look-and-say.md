---
title: "Look and Say"
---

The "look and say" sequence is defined as follows: beginning with the term `1`, each subsequent term visually describes the digits appearing in the previous term. The first few terms are as follows:

```
1
11             <- 1 one
21             <- 2 ones
1211           <- 1 two, 1 one
111221         <- 1 one, 1 two, 2 ones
312211         <- 3 ones, 2 twos, 1 one
```

Given an integer `n`, return the `n`th term of this sequence as a string.

**Constraints**

- `1 ≤ n ≤ 40`

[https://binarysearch.com/problems/Look-and-Say](https://binarysearch.com/problems/Look-and-Say){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `3`

**Output**

- answer = `21`

### Example 2

**Input**

- n = `4`

**Output**

- answer = `1211`

### Example 3

**Input**

- n = `5`

**Output**

- answer = `111221`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Look-and-Say.py"></script>
