---
title: "Edit Distance"
tags: ["string", "dynamic programming"]
---

Given two strings `a` and `b`, find the minimum edit distance between the two. One edit distance is defined as

- Deleting a character or
- Inserting a character or
- Replacing a character

**Constraints**

- `n ≤ 1,000` where `n` is the length of `a`
- `m ≤ 1,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Edit-Distance](https://binarysearch.com/problems/Edit-Distance){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `zhello`
- b = `helli`

**Output**

- answer = `2`

**Explanation**

"z" is removed and the "o" is replaced with "i"

### Example 2

**Input**

- a = `dycare`
- b = `daycare`

**Output**

- answer = `1`

**Explanation**

"a" is inserted into the first string to get "daycare".

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Edit-Distance.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Edit-Distance.py"></script>
