---
title: "Contained Interval"
---

You are given a two-dimensional list of integers `intervals` where each element is an inclusive interval `[start, end]`. Return whether there's an interval which contains another interval.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `intervals`.

[https://binarysearch.com/problems/Contained-Interval](https://binarysearch.com/problems/Contained-Interval){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals =

```
[[ 1, 3],
 [ 4,10],
 [ 4, 8],
 [ 9, 9]]
```

**Output**

- answer = `True`

**Explanation**

`[4, 10]` contains `[4, 8]`.

### Example 2

**Input**

- intervals =

```
[[ 1, 3],
 [ 4,10],
 [ 7,12]]
```

**Output**

- answer = `False`

**Explanation**

No interval completely contains another.

### Example 3

**Input**

- intervals =

```
[[1,5],
 [1,5]]
```

**Output**

- answer = `True`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Contained-Interval.py"></script>
