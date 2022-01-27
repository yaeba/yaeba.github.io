---
title: "String Isomorphism"
tags: ["string", "hash table"]
---

Given lowercase alphabet strings `s`, and `t` return whether you can create a 1-to-1 mapping for each letter in `s` to another letter (could be the same letter) such that `s` could be mapped to `t`, with the ordering of characters preserved.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`
- `m ≤ 100,000` where `m` is the length of `t`

[https://binarysearch.com/problems/String-Isomorphism](https://binarysearch.com/problems/String-Isomorphism){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `coco`
- t = `kaka`

**Output**

- answer = `True`

**Explanation**

We can create this mapping:

- "c" -> "k"
- "o" -> "a"

### Example 2

**Input**

- s = `cat`
- t = `foo`

**Output**

- answer = `False`

**Explanation**

We can't transform both "a" and "t" into "o" since it has to be a 1-to-1 mapping.

### Example 3

**Input**

- s = `hello`
- t = `hello`

**Output**

- answer = `True`

**Explanation**

The mapping can just map each letter to itself.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=String-Isomorphism.py"></script>
