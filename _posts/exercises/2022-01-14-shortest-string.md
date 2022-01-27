---
title: "Shortest String"
tags: ["string"]
---

Given a string `s` consisting only of `"1"`s and `"0"`s, you can delete any two adjacent letters if they are different.

Return the length of the smallest string that you can make if you're able to perform this operation as many times as you want.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Shortest-String](https://binarysearch.com/problems/Shortest-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `11000`

**Output**

- answer = `1`

**Explanation**

After deleting `"10"` we get `"100"` and we can delete another `"10"` to get `"0"` which has a length of 1.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shortest-String.cpp"></script>
