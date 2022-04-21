---
title: "Sort by Frequency and Value"
tags: ["hash table"]
---

Given a list of integers `nums`, order `nums` by frequency, with most frequent values coming first. If there's a tie in frequency, higher valued numbers should come first.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sort-by-Frequency-and-Value](https://binarysearch.com/problems/Sort-by-Frequency-and-Value){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 5, 5, 5, 2, 2, 2, 1, 1]`

**Output**

- answer = `[1, 1, 1, 1, 5, 5, 5, 2, 2, 2]`

**Explanation**

Since `1` occurs most frequently (4 times) they come first. `5` and `2` are then tied in terms of frequency (both 3 times) but `5` has higher value so it comes second.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sort-by-Frequency-and-Value.py"></script>
