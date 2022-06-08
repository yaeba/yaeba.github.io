---
title: "Movie Theatres"
tags: ["line sweep"]
---

Given a list of time exclusive `intervals` for different movie showings (possibly overlapping), find the minimum number of theatres required to be able to show all movies.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `intervals

[https://binarysearch.com/problems/Movie-Theatres](https://binarysearch.com/problems/Movie-Theatres){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals =

```
[[0,1],
 [0,1],
 [0,1]]
```

**Output**

- answer = `3`

**Explanation**

The three intervals happen all at the same time so we need `3`.

### Example 2

**Input**

- intervals =

```
[[ 30, 75],
 [  0, 50],
 [ 60,150]]
```

**Output**

- answer = `2`

**Explanation**

`[30, 75]` and `[0, 50]` overlap. `[30, 75]` and `[60, 150]` also overlap but later on. So the max number here is `2`.

### Example 3

**Input**

- intervals =

```
[[10,20],
 [20,30]]
```

**Output**

- answer = `1`

**Explanation**

Boundaries are exclusive so these intervals are not considered overlapping.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Movie-Theatres.py"></script>
