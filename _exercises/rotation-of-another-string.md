---
title: "Rotation of Another String"
tags: ["string"]
---

Given two alphabet (can be lower and/or uppercase) strings `s0` and `s1`, determine if one is a rotation of the other.

**Constraints**

- `1 ≤ n ≤ 200,000` where `n` is the length of `s0`
- `1 ≤ m ≤ 200,000` where `m` is the length of `s1`

[https://binarysearch.com/problems/Rotation-of-Another-String](https://binarysearch.com/problems/Rotation-of-Another-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s0 = `Cattywampus`
- s1 = `sCattywampu`

**Output**

- answer = `True`

**Explanation**

### Example 2

**Input**

- s0 = `Gardyloo`
- s1 = `dylooGar`

**Output**

- answer = `True`

**Explanation**

This string is rotated on `Gar` and `dyloo`

### Example 3

**Input**

- s0 = `Taradiddle`
- s1 = `diddleTara`

**Output**

- answer = `True`

**Explanation**

### Example 4

**Input**

- s0 = `Snickersnee`
- s1 = `Snickersnee`

**Output**

- answer = `True`

**Explanation**

This one is tricky but it's still a rotation, between ``and`Snickersnee`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rotation-of-Another-String.cpp"></script>
