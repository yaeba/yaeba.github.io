---
title: "Condo Developers"
tags: ["hash table"]
---

You are given a two-dimensional integer `matrix`, where `matrix[r][c]` represents the height of a condominium in a city.

The west-east skyline can be seen by taking the maximum of each row in the `matrix`. Similarly, the north-south skyline can be seen by taking the maximum of each column.

Return a new matrix where each condominium's height is increased to the maximum possible height while keeping the same west-east and north-south skyline.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Condo-Developers](https://binarysearch.com/problems/Condo-Developers){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[1, 2, 3], [4, 5, 6], [7, 8, 9]]`

**Output**

- answer = `[[3, 3, 3], [6, 6, 6], [7, 8, 9]]`

**Explanation**

The west-east skyline is `[3, 6, 9]` and north-south skyline is `[7, 8, 9]`. We can increase everything in the first row to `3` and everything in the second row to `6` without changing the skylines.

### Example 2

**Input**

- matrix = `[[4, 4, 3], [5, 5, 3], [7, 8, 3]]`

**Output**

- answer = `[[4, 4, 3], [5, 5, 3], [7, 8, 3]]`

**Explanation**

The west-east skyline is `[4, 5, 8]` and north-south skyline is `[7, 8, 3]`. We can't increase any condominium's height without changing the skyline, so we return the same matrix.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Condo-Developers.py"></script>
