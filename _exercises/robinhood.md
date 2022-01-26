---
title: "Robinhood"
---

You are given integers `n`, `e`, `o`, `t`. You have `n` dollars in principal that you invested in the stock market. Given the stock market alternates between first returning `e` and then `o` percent interest per year, return how many years it would take to reach at least`t` dollars.

[https://binarysearch.com/problems/Robinhood](https://binarysearch.com/problems/Robinhood){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `100`
- e = `20`
- o = `10`
- t = `130`

**Output**

- answer = `2`

**Explanation**

- In the first year we earn interest of `20`% and end up with $`120`.
- In the second year we earn interest of `10`% and end up with $`132`, which is above the target $`130`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Robinhood.java"></script>
