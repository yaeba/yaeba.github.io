---
title: "Consecutive Duplicates"
---

Given a string `s`, consisting of `"X"` and `"Y"`s, delete the minimum number of characters such that there's no consecutive `"X"` and no consecutive `"Y"`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Consecutive-Duplicates](https://binarysearch.com/problems/Consecutive-Duplicates){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `YYYXYXX`

**Output**

- answer = `YXYX`

**Explanation**

One solution is to delete the first two "Y"s and the last "X".

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Consecutive-Duplicates.cpp"></script>
