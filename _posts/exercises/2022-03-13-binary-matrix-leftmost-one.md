---
title: "Binary Matrix Leftmost One"
tags: ["array"]
---

You are given a two-dimensional list of integers `matrix` which contains `1`s and `0`s. Given that each row is sorted in ascending order with `0`s coming before `1`s, return the leftmost column index with the value of `1`. If there's no row with a `1`, return `-1`.

Can you solve it faster than $$\mathcal{O}(nm)$$.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Binary-Matrix-Leftmost-One](https://binarysearch.com/problems/Binary-Matrix-Leftmost-One){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 0, 0, 0], [0, 0, 1, 1], [0, 0, 0, 1], [0, 1, 1, 1]]`

**Output**

- answer = `1`

**Explanation**

The last row contains the leftmost column with a one at index `1`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Binary-Matrix-Leftmost-One.py"></script>
