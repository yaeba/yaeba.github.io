---
title: "Separate People Given Dislike Relations"
tags: ["graph"]
---

You are given an integer `n` and a two-dimensional list of integers `enemies`. Integer `n` means there's `n` people labeled from `[0, n - 1]`. Each element in `enemies` contains `[person_a, person_b]` which means that `person_a` and `person_b` are enemies.

Return whether it's possible to partition the `n` people into two groups such that no two people that are enemies are in the same group.

**Constraints**

- `n ≤ 1,000`
- `m ≤ 10,000` where `m` is the length of `enemies`

[https://binarysearch.com/problems/Separate-People-Given-Dislike-Relations](https://binarysearch.com/problems/Separate-People-Given-Dislike-Relations){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `4`
- enemies =

```
[[0,1],
 [1,2]]
```

**Output**

- answer = `True`

**Explanation**

We can have these two groups `[0, 2, 3]` and `[1]`.

### Example 2

**Input**

- n = `3`
- enemies =

```
[[0,1],
 [0,2],
 [1,2]]
```

**Output**

- answer = `False`

**Explanation**

No matter how we split the two groups, there will be two people that are enemies in a group.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Separate-People-Given-Dislike-Relations.py"></script>
