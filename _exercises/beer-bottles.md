---
title: "Beer Bottles"
---

You are given an integer `n` representing `n` full beer bottles. Given that you can exchange `3` empty beer bottles for `1` full beer bottle, return the number of beer bottles you can drink.

**Constraints**

- `0 ≤ n < 2 ** 31`

[https://binarysearch.com/problems/Beer-Bottles](https://binarysearch.com/problems/Beer-Bottles){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `9`

**Output**

- answer = `13`

**Explanation**

- In first round, we drink `9` beer bottles.
- We can exchange the `9` empty ones for `3` beer bottles.
- We can exchange the `3` empty ones for `1` beer bottle.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Beer-Bottles.cpp"></script>
