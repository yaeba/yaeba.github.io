---
title: "Validate Delivery Orders"
---

You are given a list of strings `orders`. Each element in `orders` starts with either `"P"` meaning pickup or `"D"` meaning delivery followed by the order id. For example, `"P12"` means pick up order `12`.

Return whether `orders` is valid given the following rules:

- A delivery cannot happen for an order before pickup
- Every pickup must be delivered
- An order that's already been picked up and delivered cannot be picked up or delivered again

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `orders`

[https://binarysearch.com/problems/Validate-Delivery-Orders](https://binarysearch.com/problems/Validate-Delivery-Orders){:target="\_blank"}

## Examples

### Example 1

**Input**

- orders = `['P1', 'P2', 'D2', 'D1']`

**Output**

- answer = `True`

**Explanation**

We first pick up orders `1` and `2` then we drop `2` and `1`.

### Example 2

**Input**

- orders = `['P1', 'P2', 'P3']`

**Output**

- answer = `False`

**Explanation**

The orders were not delivered.

### Example 3

**Input**

- orders = `['D1', 'P1']`

**Output**

- answer = `False`

**Explanation**

We must pick up the order first.

### Example 4

**Input**

- orders = `['P1', 'D1', 'P1', 'D1']`

**Output**

- answer = `False`

**Explanation**

We can't pick up an order again after it's already been picked up and dropped off.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Validate-Delivery-Orders.py"></script>
