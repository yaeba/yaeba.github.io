---
title: "Bulk Shift Letters"
tags: ["string"]
---

You are given a lowercase alphabet string `s` and a list of integers `shifts`. Each element `shifts[i]` means to shift the first `i + 1` letters of `s` by `shifts[i]` positions. Shifting a letter should wrap over `"z"` to `"a"`. For example, shifting `“z”` by `2` results in `“b”`.

Return the resulting string after applying `shifts` to `s`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `s` and `shifts`

[https://binarysearch.com/problems/Bulk-Shift-Letters](https://binarysearch.com/problems/Bulk-Shift-Letters){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `afz`
- shifts = `[1, 2, 1]`

**Output**

- answer = `eia`

**Explanation**

- We shift the first `1` letter by `1` position to get: `"bfz"`
- We shift the first `2` letters by `2` position to get: `"dhz"`
- We shift the first `3` letters by `1` position to get: `"eia"`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Bulk-Shift-Letters.py"></script>
