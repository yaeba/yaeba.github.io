---
title: "Shortest Sublist With Max Frequency"
tags: ["hash table", "array"]
---

You are given a list of integers `nums`. Let `k` be the frequency of a most frequent number in `nums`. Return the length of a shortest sublist such that the frequency of its most frequent number is also `k`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Shortest-Sublist-With-Max-Frequency](https://binarysearch.com/problems/Shortest-Sublist-With-Max-Frequency){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 3, 1]`

**Output**

- answer = `3`

**Explanation**

The most frequent numbers are `1` and `3` and each of them occur twice, so `k = 2`. And the sublist `[3, 4, 3]` is the shortest sublist such that the frequency of the most frequent number is equal to `k`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shortest-Sublist-With-Max-Frequency.py"></script>
