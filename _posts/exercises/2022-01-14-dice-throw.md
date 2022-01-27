---
title: "Dice Throw"
---

Given integers `n`, `faces`, and `total`, return the number of ways it is possible to throw `n` dice with `faces` faces each to get `total`.

Mod the result by `10 ** 9 + 7`.

**Constraints**

- `1 ≤ n, faces, total ≤ 100`

[https://binarysearch.com/problems/Dice-Throw](https://binarysearch.com/problems/Dice-Throw){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `2`
- faces = `6`
- total = `7`

**Output**

- answer = `6`

**Explanation**

There are 6 ways to make 7 with 2 6-sided dice:

- 1 and 6
- 6 and 1
- 2 and 5
- 5 and 2
- 3 and 4
- 4 and 3

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Dice-Throw.py"></script>
