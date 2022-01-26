---
title: "Smallest Number With No Adjacent Duplicates"
tags: ["string", "greedy"]
---

You are given a string `s` containing `"1"`, `"2"`, `"3"` and `"?"`. Given that you can replace any `“?”` with `"1"`, `"2"` or `"3",` return the smallest number you can make as a string such that no two adjacent digits are the same.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Smallest-Number-With-No-Adjacent-Duplicates](https://binarysearch.com/problems/Smallest-Number-With-No-Adjacent-Duplicates){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `3?2??`

**Output**

- answer = `31212`

### Example 2

**Input**

- s = `???`

**Output**

- answer = `121`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Smallest-Number-With-No-Adjacent-Duplicates.java"></script>
