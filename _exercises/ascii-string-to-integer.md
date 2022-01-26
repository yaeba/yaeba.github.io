---
title: "ASCII String to Integer"
tags: ["greedy", "string"]
---

You are given a string `s` containing digits from `"0"` to `"9"` and lowercase alphabet characters. Return the sum of the numbers found in `s`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/ASCII-String-to-Integer](https://binarysearch.com/problems/ASCII-String-to-Integer){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `11aa32bbb5`

**Output**

- answer = `48`

**Explanation**

Since `11 + 32 + 5 = 48`.

### Example 2

**Input**

- s = `1a2b30`

**Output**

- answer = `33`

**Explanation**

Since `1 + 2 + 30 = 33`.

### Example 3

**Input**

- s = `abc`

**Output**

- answer = `0`

**Explanation**

There's no digits so it defaults to `0`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=ASCII-String-to-Integer.py"></script>
