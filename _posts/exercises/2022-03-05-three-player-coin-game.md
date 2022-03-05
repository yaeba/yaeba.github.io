---
title: "Three Player Coin Game"
tags: ["array", "greedy"]
---

You are given a list of non-negative integers `piles` where each `piles[i]` represents the number of coins on pile `i`. In each move, you can do the following until there's no more coins:

- Pick any `3` piles from `piles`
- A friend will take the pile with the maximum number of coins
- You will take the next highest pile
- A friend will take the last pile

Return the maximum number of coins you can acquire.

**Constraints**

- `3 ≤ n ≤ 100,000` where `n` is the length of `piles
- `n % 3 = 0`

[https://binarysearch.com/problems/Three-Player-Coin-Game](https://binarysearch.com/problems/Three-Player-Coin-Game){:target="\_blank"}

## Examples

### Example 1

**Input**

- piles = `[2, 4, 1, 3, 5, 6]`

**Output**

- answer = `8`

**Explanation**

First, we can pick the coins `[6, 5, 1]`, yielding us `5` coins. Then we can pick `4, 3, 2` which yields us `3` coins.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Three-Player-Coin-Game.py"></script>
