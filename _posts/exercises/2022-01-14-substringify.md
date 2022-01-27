---
title: "Substringify"
---

Given two lowercase alphabet strings `s` and `t`, return the minimum amount of operations on `s` required to make `t` a substring of `s`. In each operation, you can choose any position in `s` and change the character at that position to any other character.

**Constraints**

- `0 ≤ m ≤ n ≤ 100` where `n` is the length of `s` and `m` is the length of `t`

[https://binarysearch.com/problems/Substringify](https://binarysearch.com/problems/Substringify){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `foobar`
- t = `oops`

**Output**

- answer = `2`

**Explanation**

We can take the substring `"ooba"` and change `'b'` to `'p'` and `'a'` to `'s'`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Substringify.cpp"></script>
