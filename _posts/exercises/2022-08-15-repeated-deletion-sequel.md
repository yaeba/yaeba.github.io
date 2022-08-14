---
title: "Repeated Deletion Sequel"
tags: ["string", "stack"]
---

Given a string `s` and an integer `k`, repeatedly delete the earliest `k` consecutive duplicate characters.

**Constraints**

- `k, n ≤ 100,000` where `n` is the length of `s`.

[https://binarysearch.com/problems/Repeated-Deletion-Sequel](https://binarysearch.com/problems/Repeated-Deletion-Sequel){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `baaabbdddd`
- k = `3`

**Output**

- answer = `d`

**Explanation**

First we delete the `"a"`s to get `"bbbdddd"`. Then we delete the `"b"`s to get `"dddd"`. Then we delete three of the four `"d"`s to get `"d"`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Repeated-Deletion-Sequel.py"></script>
