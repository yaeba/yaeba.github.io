---
title: "Latin Square"
tags: ["hash table"]
---

Given an `n` by `n` matrix of letters `matrix`, return whether there are exactly `n` different letters that appear in the matrix and each letter appears exactly once in each row and exactly once in each column.

**Constraints**

- `1 ≤ n ≤ 250` where `n` is the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Latin-Square](https://binarysearch.com/problems/Latin-Square){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[['a','b','c'],
 ['c','a','b'],
 ['b','c','a']]
```

**Output**

- answer = `True`

**Explanation**

There are 3 different letters and each letter appears exactly once in each row and column.

### Example 2

**Input**

- matrix =

```
[['a','b','c'],
 ['d','a','a'],
 ['b','b','a']]
```

**Output**

- answer = `False`

**Explanation**

There are 4 different letters, and also "a" and "b" appear twice in the same row.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Latin-Square.py"></script>
