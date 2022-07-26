---
title: "Shipping and Receiving"
tags: ["graph"]
---

You are given a two-dimensional list of integers `ports` where `ports[i]` represents the list of ports that port `i` is connected to. You are also given another two-dimensional list of integers `shipments` where each list of the form `[port_i, port_j]` which means there is a shipment request from `port_i` to `port_j`.

Given that the cost to ship `port_i` to `port_j` is the length of the shortest path from the two ports, return the total cost necessary to send all the shipments. If there's not a path between two ports, the cost is `0`.

**Constraints**

- `p ≤ 100` where `p` is the length of `ports`
- `s ≤ 10,000` where `s` is the length of `shipments`

[https://binarysearch.com/problems/Shipping-and-Receiving](https://binarysearch.com/problems/Shipping-and-Receiving){:target="\_blank"}

## Examples

### Example 1

**Input**

- ports =

```
[[list([2, 3]),list([2]),list([1, 0]),list([4]),list([])]]
```

- shipments =

```
[[2,4]]
```

**Output**

- answer = `3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shipping-and-Receiving.py"></script>
