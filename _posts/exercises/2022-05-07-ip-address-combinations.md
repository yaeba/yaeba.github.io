---
title: "IP Address Combinations"
tags: ["recursion"]
---

Given a string of digits `ip`, generate all possible valid IP address combinations and return them in sorted order.

IP addresses must follow the format `A.B.C.D`, where A, B, C, and D are integers between 0 and 255. Zero-prefixed numbers, such as 01 and 065, are not allowed, except for 0 itself.

**Constraints**

- `4 ≤ n ≤ 12` where `n` is the length of `ip`.

[https://binarysearch.com/problems/IP-Address-Combinations](https://binarysearch.com/problems/IP-Address-Combinations){:target="\_blank"}

## Examples

### Example 1

**Input**

- ip = `2542540123`

**Output**

- answer = `['254.25.40.123', '254.254.0.123']`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=IP-Address-Combinations.py"></script>
