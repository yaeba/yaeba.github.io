---
title: "Cell Fusion"
tags: ["heap"]
---

You are given a list of integers `cells`, representing sizes of different cells. In each iteration, the two largest cells `a` and `b` interact according to these rules:

- If `a = b`, they both die.
- Otherwise, the two cells merge and their size becomes `floor((a + b) / 3)`.

Return the size of the last cell or return `-1` if there's no cell is remaining.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `cells`

[https://binarysearch.com/problems/Cell-Fusion](https://binarysearch.com/problems/Cell-Fusion){:target="\_blank"}

## Examples

### Example 1

**Input**

- cells = `[10, 30, 30, 20]`

**Output**

- answer = `10`

**Explanation**

In the first iteration, the two largest cells both have the size of `30` so they both die. In the second iteration, cells `10`, and `20` merge to become `10`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Cell-Fusion.py"></script>
