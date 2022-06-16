---
title: "Vertical Word Arrangement"
tags: ["string"]
---

You are given a string `s` containing lowercase alphabet characters separated by spaces `" "`. After splitting the string on spaces, return all the words in vertical order, top to bottom. If there's no character on a column, use a space.

**Constraints**

- `1 ≤ n ≤ 1,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Vertical-Word-Arrangement](https://binarysearch.com/problems/Vertical-Word-Arrangement){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abc def ghij`

**Output**

- answer = `['adg', 'beh', 'cfi', ' j']`

**Explanation**

After splitting the string we get

```
[
  "abc",
  "def",
  "ghij"
]
```

Then, traversing vertically we can group them into `"adg"`, `"beh"`, `"cfi"`, `" j"`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Vertical-Word-Arrangement.py"></script>
