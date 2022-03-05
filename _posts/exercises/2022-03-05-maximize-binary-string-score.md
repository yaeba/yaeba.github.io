---
title: "Maximize Binary String Score"
tags: ["string"]
---

You are given a binary string `s` containing `"1"`s and `"0"`s. Consider splitting the string into two non-empty substrings such that `a + b = s`. The score of this split is defined to be the sum of the number of `"0"`s in `a` plus the number of `"1"`s in `b`. Return the maximum score possible.

**Constraints**

- `2 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Maximize-Binary-String-Score](https://binarysearch.com/problems/Maximize-Binary-String-Score){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `001001110111`

**Output**

- answer = `10`

**Explanation**

We can split the string into `"00100" + `"1110111"`. Then, the score is `4 + 6 = 10`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Maximize-Binary-String-Score.py"></script>
