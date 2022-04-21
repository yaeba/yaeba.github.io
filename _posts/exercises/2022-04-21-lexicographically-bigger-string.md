---
title: "Lexicographically Bigger String"
---

Given lowercase alphabet strings `s` and `t` of the same length, return whether there's some anagram of `s`, say `a`, and some anagram of `t`, say `b`, such that:

- `a[i] ≤ b[i]` for all `0 ≤ i < n` or
- `b[i] ≤ a[i]` for all `0 ≤ i < n`.

**Constraints**

- `1 ≤ n = m ≤ 100,000` where `n` and `m` are the lengths of `s` and `t`.

[https://binarysearch.com/problems/Lexicographically-Bigger-String](https://binarysearch.com/problems/Lexicographically-Bigger-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `adc`
- t = `bec`

**Output**

- answer = `True`

**Explanation**

We can have `a = "acd"` and `b = "bce"` and we have:

- `"a" ≤ "b"`
- `"c" ≤ "c"`
- `"d" ≤ "e"`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Lexicographically-Bigger-String.py"></script>
