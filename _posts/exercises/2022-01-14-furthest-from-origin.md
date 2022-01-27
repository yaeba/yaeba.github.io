---
title: "Furthest From Origin"
---

You are given a string `s` where each character is `"L"` meaning you moved one unit left, `"R"` meaning you moved one unit right, or `"?"` meaning either `"L"` or `"R"`.

Given you are at position `0`, return the maximum possible distance you could be from `0` by replacing `"?"` with `"L"` or `"R"`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Furthest-From-Origin](https://binarysearch.com/problems/Furthest-From-Origin){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `LLRRR??`

**Output**

- answer = `3`

**Explanation**

We can replace the two `"?"` with `"R"` to move `5` units right and `2` units left, for a total distance of `3` units from `0`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Furthest-From-Origin.cpp"></script>
