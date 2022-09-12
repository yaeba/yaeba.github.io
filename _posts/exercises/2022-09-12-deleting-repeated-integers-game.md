---
title: "Deleting Repeated Integers Game"
---

Alice and Bob are playing a game with a sorted list of positive integers `nums`. In a single turn, Alice selects any three integers. Bob deletes one of them, and then Alice deletes one of them. The list starts out with an odd number of integers.

Alice wishes to minimize the number of turns needed to make the list contain no repeated integers, Bob wishes to maximize the number of turns. Assuming Alice and Bob act optimally, return how many turns the game takes.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Deleting-Repeated-Integers-Game](https://binarysearch.com/problems/Deleting-Repeated-Integers-Game){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 2, 3, 3]`

**Output**

- answer = `1`

**Explanation**

If Alice selects `[1, 1, 3]`, then regardless of whether Bob selects `1` or a `3`, Alice can select the other number to get rid of all repeating numbers.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Deleting-Repeated-Integers-Game.py"></script>
