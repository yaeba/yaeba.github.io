---
title: "Rotate a Box Under Gravity"
tags: ["array"]
---

You are given a two-dimensional list of strings `matrix`. Each element in matrix contains one of the following:

- `"."`, which means that the cell is empty.
- `"*"`, which means that the cell contains an obstacle.
- `"#"`, which means that the cell contains a small box.

You decide to rotate the matrix clockwise `90` degrees to see how the small boxes will fall under gravity. After rotating, each small box falls down until it lands on an obstacle, another small box, or the bottom of the big box. The obstacle does not fall under gravity.

Return the state of `matrix` after rotating it 90 degrees clockwise.

**Constraints**

- `0 ≤ n * m ≤ 100,000` where `n` is the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Rotate-a-Box-Under-Gravity](https://binarysearch.com/problems/Rotate-a-Box-Under-Gravity){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[['#','#','.','.','.','.','.'],
 ['#','#','#','.','.','.','.'],
 ['#','#','#','.','.','#','.']]
```

**Output**

- answer = `[['.', '.', '.'], ['.', '.', '.'], ['.', '.', '.'], ['#', '.', '.'], ['#', '#', '.'], ['#', '#', '#'], ['#', '#', '#']]`

### Example 2

**Input**

- matrix =

```
[['#','*','.'],
 ['*','.','.'],
 ['#','#','.'],
 ['.','.','.']]
```

**Output**

- answer = `[['.', '.', '*', '#'], ['.', '#', '.', '*'], ['.', '#', '.', '.']]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rotate-a-Box-Under-Gravity.py"></script>
