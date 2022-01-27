---
title: "Integer to Roman Numeral"
tags: ["string"]
---

Given an integer `n`, return its corresponding Roman numeral.

Roman numerals contain the symbols representing values in the following list:

- `"I" = 1`
- `"V" = 5`
- `"X" = 10`
- `"L" = 50`
- `"C" = 100`
- `"D" = 500`
- `"M" = 1000`

Symbols are typically written largest to smallest, from left to right, and can be computed by summing the values of all the symbols. However, in some cases, when a symbol of lower value is to the left of a symbol of higher value, then the lower value is subtracted from the higher one.

There are 6 cases where this is possible:

- When `"I"` is before `"V"`, we get `4`.
- When `"I"` is before `"X"`, we get `9`.
- When `"X"` is before `"L"`, we get `40`.
- When `"X"` is before `"C"`, we get `90`.
- When `"C"` is before `"D"`, we get `400`.
- When `"C"` is before `"M"`, we get `900`.

Roman numerals must also follow these rules:

- No symbol is repeated more than 3 times.
- The symbols `"V"`, `"L"`, and `"D"` are not repeated.

**Constraints**

- `1 ≤ n ≤ 3000`

[https://binarysearch.com/problems/Integer-to-Roman-Numeral](https://binarysearch.com/problems/Integer-to-Roman-Numeral){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `12`

**Output**

- answer = `XII`

**Explanation**

"XII" = 10 + 1 + 1 = 12

### Example 2

**Input**

- n = `14`

**Output**

- answer = `XIV`

**Explanation**

"XIV" = 10 + 4 = 14

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Integer-to-Roman-Numeral.py"></script>
