---
title: "Grammar Rules"
---

Given an integer `n`, return the number of strings of length `n` that can be formed under the following rules:

- Each character is a lower case vowel `"a"`, `"e"`, `"i"`, `"o"`, `"u"`

- `"a"` may only be followed by an `"e"`

- `"e"` may only be followed by an `"a"` or an `"i"`

- `"i"` may **not** be followed by another `"i"`

- `"o"` may only be followed by an `"i"` or a `"u"`

- `"u"` may only be followed by an `"a"`

Return the result mod `10 ** 9 + 7`.

**Constraints**

- `1 ≤ n ≤ 100,000`

[https://binarysearch.com/problems/Grammar-Rules](https://binarysearch.com/problems/Grammar-Rules){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `2`

**Output**

- answer = `10`

**Explanation**

We can make the following two letter strings:

`["ae", "ea", "ei", "ia", "ie", "io", "iu", "oi", "ou", "ua"]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Grammar-Rules.py"></script>
