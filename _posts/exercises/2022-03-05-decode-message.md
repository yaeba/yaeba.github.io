---
title: "Decode Message"
tags: ["dynamic programming"]
---

Given the mapping `"a" = 1`, `"b" = 2`, ... `"z" = 26`, and an encoded message `message` (as a string), count the number of ways it can be decoded.

**Constraints**

- `n ≤ 100,000` where `n` is the length of message

[https://binarysearch.com/problems/Decode-Message](https://binarysearch.com/problems/Decode-Message){:target="\_blank"}

## Examples

### Example 1

**Input**

- message = `111`

**Output**

- answer = `3`

**Explanation**

This can be decoded 3 ways: `aaa`, `ak`, and `ka`.

### Example 2

**Input**

- message = `8`

**Output**

- answer = `1`

**Explanation**

This can be only decoded one way, as `h`.

### Example 3

**Input**

- message = `12`

**Output**

- answer = `2`

**Explanation**

This can be decoded 2 ways: `ab` or `l`.

### Example 4

**Input**

- message = `60`

**Output**

- answer = `0`

**Explanation**

There's no way to decode this message.

### Example 5

**Input**

- message = `0012`

**Output**

- answer = `0`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Decode-Message.py"></script>
