---
title: "Characters in Each Bracket Depth"
tags: ["hash table", "string"]
---

You are a given a string `s` containing `"X"`, `"("`, and `")"`. The string has balanced brackets and in between there are some `"X"`s along with possibly nested brackets recursively.

Return the number of `"X"`s at each depth of brackets in `s`, from the shallowest depth to the deepest depth.

**Constraints**

- `2 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Characters-in-Each-Bracket-Depth](https://binarysearch.com/problems/Characters-in-Each-Bracket-Depth){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `(XX(XX(X))X)`

**Output**

- answer = `[3, 2, 1]`

**Explanation**

There's three `"X"`s at depth `0`. Two `"X"`s at depth `1`. And one `"X"` at depth `2`.

### Example 2

**Input**

- s = `(())`

**Output**

- answer = `[0, 0]`

**Explanation**

There's no `"X"`s but depth goes to `1`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Characters-in-Each-Bracket-Depth.py"></script>
