---
title: "Anagram Partitioning"
tags: ["string"]
---

You are given two non-empty strings `a` and `b` that are the same length. Partition them into substrings such that each pair of `a` and `b`'s substring is the same size and they are anagrams of each other. Return the cut indexes such that it results in the largest number of cuts of `a` and `b`. Return the empty list if no result exists.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `a` and `b`

[https://binarysearch.com/problems/Anagram-Partitioning](https://binarysearch.com/problems/Anagram-Partitioning){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `study`
- b = `dusty`

**Output**

- answer = `[0, 4]`

**Explanation**

We can cut the string into 2 partitions:

`a = ["stud", "y"]`

`b = ["dust", "y"]`

### Example 2

**Input**

- a = `catdogwolf`
- b = `actgodflow`

**Output**

- answer = `[0, 2, 3, 6]`

**Explanation**

We can cut the string into 4 partitions such that each string is an anagram of each other.

`a = ["ca", "t", "dog", "wolf"]`

`b = ["ac", "t", "god", "flow"]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Anagram-Partitioning.py"></script>
