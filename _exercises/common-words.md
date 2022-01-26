---
title: "Common Words"
tags: ["hash table"]
---

Given two strings `s0` and `s1`, each representing a sentence, return the number of unique words that are shared between the two sentences.

Note: words are case-insensitive so "hello" and "Hello" are the same word.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s0`
- `m ≤ 100,000` where `m` is the length of `s1`

[https://binarysearch.com/problems/Common-Words](https://binarysearch.com/problems/Common-Words){:target="\_blank"}

## Examples

### Example 1

**Input**

- s0 = `hello world hello oyster`
- s1 = `world is your oyster`

**Output**

- answer = `2`

**Explanation**

Only "world" and "oyster" are shared between the two sentences.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Common-Words.py"></script>
