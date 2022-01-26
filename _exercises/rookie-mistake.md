---
title: "Rookie Mistake"
tags: ["string"]
---

You’re given a string `s` containing letters of three types, `R`, `B`, and `.`.

`R` represents your current position, `B` represents a blocked position, and `.` represents an empty position. In one step, you can move to any adjacent position to your current position, as long as it is empty. Can you reach either the leftmost position or the rightmost position?

Return `true` if you can reach either the leftmost or the rightmost position, or `false` if you cannot.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Rookie-Mistake](https://binarysearch.com/problems/Rookie-Mistake){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `......B....R..............`

**Output**

- answer = `True`

**Explanation**

We can reach the rightmost position since it's not blocked.

### Example 2

**Input**

- s = `B...B...R........BBBB`

**Output**

- answer = `False`

**Explanation**

We can't reach either side since they're both blocked.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rookie-Mistake.cpp"></script>
