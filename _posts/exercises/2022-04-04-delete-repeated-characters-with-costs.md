---
title: "Delete Repeated Characters with Costs"
---

You are given a lowercase alphabet string `s` and a list of non-negative integers `costs`, both of which have the same length. You can remove character `s[i]` for cost `costs[i]`, after which both `s[i]` and `costs[i]` is removed.

Return the minimum cost needed to delete all consecutively repeating characters.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s` and `costs`

[https://binarysearch.com/problems/Delete-Repeated-Characters-with-Costs](https://binarysearch.com/problems/Delete-Repeated-Characters-with-Costs){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `aabba`
- nums = `[1, 2, 9, 3, 5]`

**Output**

- answer = `4`

**Explanation**

We can remove `s[0]` and `s[3]` for a total cost of `1 + 3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Delete-Repeated-Characters-with-Costs.py"></script>
