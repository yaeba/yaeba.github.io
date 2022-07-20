---
title: "Unique String Frequencies"
tags: ["greedy", "string"]
---

Given a lowercase alphabet string `s`, return the minimum number of characters that we need to delete such that the frequency of each character occurs a unique number of times.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Unique-String-Frequencies](https://binarysearch.com/problems/Unique-String-Frequencies){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `aabb`

**Output**

- answer = `1`

**Explanation**

Both `"a"` and `"b"` occur twice, so we can remove say `"a"` once to make the frequencies unique.

### Example 2

**Input**

- s = `abbccc`

**Output**

- answer = `0`

**Explanation**

The string already has unique frequencies for `"a"`, `"b"` and `"c"`: `[1, 2, 3]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unique-String-Frequencies.py"></script>
