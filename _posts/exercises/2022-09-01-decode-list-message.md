---
title: "Decode List Message"
---

You are given a string `s` containing digits from `0 - 9` and an integer `k`. Return the number of different ways that `s` could represent a list of numbers from `[1, k]`.

Return the result mod `10 ** 9 + 7`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Decode-List-Message](https://binarysearch.com/problems/Decode-List-Message){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `123`
- k = `200`

**Output**

- answer = `4`

**Explanation**

`s` could represent `[1, 2, 3]`, `[12, 3]`, `[1, 23]`, `[123]`.

### Example 2

**Input**

- s = `120`
- k = `200`

**Output**

- answer = `2`

**Explanation**

`s` can represent `[1, 20]` and `[120]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Decode-List-Message.py"></script>
