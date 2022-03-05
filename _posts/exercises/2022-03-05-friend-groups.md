---
title: "Friend Groups"
tags: ["union find", "graph"]
---

You are given an undirected graph `friends` as an adjacency list, where `friends[i]` is a list of people `i` is friends with. Friendships are two-way. Two people are in a friend group as long as there is some path of mutual friends connecting them.

Return the total number of friend groups.

**Constraints**

- `n ≤ 250` where `n` is the length of `friends`

[https://binarysearch.com/problems/Friend-Groups](https://binarysearch.com/problems/Friend-Groups){:target="\_blank"}

## Examples

### Example 1

**Input**

- friends = `[[1], [0, 2], [1], [4], [3], []]`

**Output**

- answer = `3`

**Explanation**

The three friend groups are

- [0, 1, 2]
- [3, 4]
- [5]

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Friend-Groups.py"></script>
