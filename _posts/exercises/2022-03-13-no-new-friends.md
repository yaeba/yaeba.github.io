---
title: "No New Friends"
tags: ["graph"]
---

You are given `n` people represented as an integer from `0` to `n - 1`, and a list of `friends` tuples, where person `friends[i][0]` and person `friends[i][1]` are friends.

Return whether everyone has at least one friend.

**Constraints**

- `m ≤ 100,000` where `m` is the length of `friends`

[https://binarysearch.com/problems/No-New-Friends](https://binarysearch.com/problems/No-New-Friends){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `3`
- friends = `[[0, 1]]`

**Output**

- answer = `False`

**Explanation**

Person `2` is not friends with anyone.

### Example 2

**Input**

- n = `3`
- friends = `[[0, 1], [1, 2]]`

**Output**

- answer = `True`

**Explanation**

- Person `0` is friends with `1`
- Person `1` is friends with `0` and `2`
- Person `2` is friends with `1`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=No-New-Friends.py"></script>
