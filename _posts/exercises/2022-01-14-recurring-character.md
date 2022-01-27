---
title: "Recurring Character"
tags: ["string"]
---

Given a lowercase alphabet string `s`, return the index of the first recurring character in it. If there are no recurring characters, return `-1`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Recurring-Character](https://binarysearch.com/problems/Recurring-Character){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abcde`

**Output**

- answer = `-1`

**Explanation**

No recurring characters in this string.

### Example 2

**Input**

- s = `aaaaa`

**Output**

- answer = `1`

**Explanation**

We want the first recurring character.

### Example 3

**Input**

- s = `abcda`

**Output**

- answer = `4`

**Explanation**

The `a` at index 4 is the first recurring character.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Recurring-Character.cpp"></script>
