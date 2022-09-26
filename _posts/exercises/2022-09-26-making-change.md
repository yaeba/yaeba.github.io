---
title: "Making Change"
tags: ["greedy"]
---

Find the minimum number of coins required to make `n` cents.

You can use standard American denominations, that is, 1¢, 5¢, 10¢, and 25¢.

**Constraints**

- `0 ≤ n < 2 ** 31`

[https://binarysearch.com/problems/Making-Change](https://binarysearch.com/problems/Making-Change){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `6`

**Output**

- answer = `2`

**Explanation**

You can make this with a 5 cent coin and a 1 cent coin.

### Example 2

**Input**

- n = `5`

**Output**

- answer = `1`

**Explanation**

You can make this with a 5 cent coin.

### Example 3

**Input**

- n = `3`

**Output**

- answer = `3`

**Explanation**

You can make this with 3 pennies.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Making-Change.cpp"></script>
