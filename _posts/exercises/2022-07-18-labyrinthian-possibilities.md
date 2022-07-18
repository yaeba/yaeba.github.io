---
title: "Labyrinthian Possibilities"
tags: ["dynamic programming"]
---

You are given an N by M matrix of `0`s and `1`s. Starting from the top left corner, how many ways are there to reach the bottom right corner? Mod the result by `10 ** 9 + 7`.

You can only move right and down. `0` represents an empty space while `1` represents a wall you cannot walk through. The top left corner and bottom right corner will always be `0`.

**Constraints**

- `1 ≤ n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Labyrinthian-Possibilities](https://binarysearch.com/problems/Labyrinthian-Possibilities){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[0,0,1],
 [0,0,1],
 [1,0,0]]
```

**Output**

- answer = `2`

**Explanation**

There are two ways to get to the bottom right:

- Right, down, down, right
- Down, right, down, right

### Example 2

**Input**

- matrix =

```
[[0,0,0],
 [0,0,0],
 [0,0,0]]
```

**Output**

- answer = `6`

**Explanation**

There are 6 ways here:

- Right, right, down, down
- Down, down, right, right
- Right, down, right, down
- Down, right, down, right
- Right, down, down, right
- Down, right, right, down

### Example 3

**Input**

- matrix =

```
[[0,0,0],
 [1,1,1],
 [0,0,0]]
```

**Output**

- answer = `0`

**Explanation**

There is a wall in the middle preventing us from getting to the bottom right.

### Example 4

**Input**

- matrix =

```
[[0,0,0,0],
 [1,1,1,0],
 [0,0,0,0]]
```

**Output**

- answer = `1`

### Example 5

**Input**

- matrix =

```
[[0,0,0,0,0],
 [1,1,1,0,0],
 [0,0,0,0,0]]
```

**Output**

- answer = `3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Labyrinthian-Possibilities.cpp"></script>
