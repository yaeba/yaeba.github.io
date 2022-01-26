---
title: "Repeated Deletion"
tags: ["stack", "string"]
---

Given a string `s`, repeatedly delete the earliest consecutive duplicate characters.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`.

[https://binarysearch.com/problems/Repeated-Deletion](https://binarysearch.com/problems/Repeated-Deletion){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abbbaac`

**Output**

- answer = `c`

**Explanation**

- "bbb" are the earliest consecutive duplicate characters which gets deleted. So we have "aaac".
- "aaa" then gets deleted to end up with "c".

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Repeated-Deletion.py"></script>
