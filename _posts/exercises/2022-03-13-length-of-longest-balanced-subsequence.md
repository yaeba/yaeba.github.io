---
title: "Length of Longest Balanced Subsequence"
tags: ["stack", "string"]
---

Given a string `s` containing brackets `"("` and `")"`, return the length of the longest subsequence of balanced brackets.

**Constraints**

- `n ≤ 100,000` where `n` is length of `s`.

[https://binarysearch.com/problems/Length-of-Longest-Balanced-Subsequence](https://binarysearch.com/problems/Length-of-Longest-Balanced-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `())(()`

**Output**

- answer = `4`

**Explanation**

We can take the subsequence `"()()"`

### Example 2

**Input**

- s = `))()))()`

**Output**

- answer = `4`

**Explanation**

We can take the subsequence "()()". Note that characters in the subsequence do not have to be contiguous.

### Example 3

**Input**

- s = `))((`

**Output**

- answer = `0`

**Explanation**

We can't take any letters from `s` that's balanced, so the longest balanced subsequence is "" (empty string).

### Example 4

**Input**

- s = `((((())`

**Output**

- answer = `4`

**Explanation**

We can make the subsequence `(())`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Length-of-Longest-Balanced-Subsequence.cpp"></script>
