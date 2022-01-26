---
title: "Removing Triple Successive Duplicates"
---

Given a string `s` containing `"0"`s and `"1"`s, consider an operation where you pick a character and toggle its value from `"0"` to `"1"` or from `"1"` to `"0"`. Return the minimum number of operations required to obtain a string containing no instances of three identical consecutive characters.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Removing-Triple-Successive-Duplicates](https://binarysearch.com/problems/Removing-Triple-Successive-Duplicates){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `0001000`

**Output**

- answer = `2`

**Explanation**

We can toggle the first and the last characters to get `"1001001"`

### Example 2

**Input**

- s = `1100011`

**Output**

- answer = `1`

**Explanation**

We can toggle the middle `"0"` to a `"1"`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Removing-Triple-Successive-Duplicates.py"></script>
