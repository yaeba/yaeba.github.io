---
title: "Vertical Cipher"
tags: ["string"]
---

Given a string `s` and an integer `k`, rearrange `s` into `k` rows so that `s` can be read vertically (top-down, left to right).

**Constraints**

- `n ≤ 10,000` where `n` is the length of `s`
- `k ≤ 1,000`

[https://binarysearch.com/problems/Vertical-Cipher](https://binarysearch.com/problems/Vertical-Cipher){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abcdefghi`
- k = `5`

**Output**

- answer = `['af', 'bg', 'ch', 'di', 'e']`

**Explanation**

This reads vertically as:

```
["af",
 "bg",
 "ch",
 "di",
 "e"]
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Vertical-Cipher.py"></script>
