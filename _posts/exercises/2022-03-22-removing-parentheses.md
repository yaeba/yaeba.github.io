---
title: "Removing Parentheses"
tags: ["string"]
---

Given a string of parentheses `s`, return the minimum number of parentheses to be removed to make the string balanced.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Removing-Parentheses](https://binarysearch.com/problems/Removing-Parentheses){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `)(`

**Output**

- answer = `2`

**Explanation**

We must remove all the parentheses.

### Example 2

**Input**

- s = `()())()`

**Output**

- answer = `1`

**Explanation**

We can remove the `")"` at index 4 to make it balanced.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Removing-Parentheses.cpp"></script>
