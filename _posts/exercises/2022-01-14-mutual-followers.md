---
title: "Mutual Followers"
tags: ["hash table", "graph"]
---

You are given a two-dimensional list of integers `relations`. Each element `relations[i]` contains `[a, b]` meaning that person `a` is following person `b` on Twitter.

Return the list of people who follow someone that follows them back, sorted in ascending order.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `relations`

[https://binarysearch.com/problems/Mutual-Followers](https://binarysearch.com/problems/Mutual-Followers){:target="\_blank"}

## Examples

### Example 1

**Input**

- relations =

```
[[0,1],
 [2,3],
 [3,4],
 [1,0]]
```

**Output**

- answer = `[0, 1]`

**Explanation**

`0` follows `1` and `1` follows `0`.

### Example 2

**Input**

- relations =

```
[[0,1],
 [1,2],
 [2,3],
 [3,0]]
```

**Output**

- answer = `[]`

**Explanation**

There aren't any mutual followers.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Mutual-Followers.cpp"></script>
