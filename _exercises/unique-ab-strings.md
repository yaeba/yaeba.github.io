---
title: "Unique Ab Strings"
tags: ["string"]
---

You are given a string `s` of `"a"` and `"b"`s. `"a"`s can stay `"a"` or turn into `"b"`, but `"b"`s can't change.

Return the number of unique strings that can be made.

**Constraints**

- `1 ≤ n ≤ 10,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Unique-Ab-Strings](https://binarysearch.com/problems/Unique-Ab-Strings){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abba`

**Output**

- answer = `4`

**Explanation**

We can make these strings:

- `"abba"`
- `"abbb"`
- `"bbba"`
- `"bbbb"`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unique-Ab-Strings.cpp"></script>
