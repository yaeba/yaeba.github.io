---
title: "Highest Volume Stocks"
---

Implement a data structure `StockMarket` which has the following methods:

- `StockMarket(String[] stocks, int[] amounts)` which creates a new instance. `stocks` and `amounts` has the same length and each stock `stocks[i]` initially has `amounts[i]` volume in the market
- `add(String stock, int amount)` which accumulatively adds `stock` with volume `amount`
- `top(int k)` which returns the top `k` highest volume stocks, sorted in descending order by volume. If there are ties in volume, return the lexicographically smallest stocks first.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `add` and `top`.

[https://binarysearch.com/problems/Highest-Volume-Stocks](https://binarysearch.com/problems/Highest-Volume-Stocks){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'add', 'add', 'add', 'top']`
- arguments = `[[['NFLX'], [300]], ['AMZN', 100], ['GOOG', 300], ['AMZN', 300], [2]]`

**Output**

- answer = `[None, None, None, None, ['AMZN', 'GOOG']]`

**Explanation**

```
s = StockMarket(["NFLX"], [300])
s.add("AMZN", 100)
s.add("GOOG", 300)
s.add("AMZN", 300)
s.top(2) == ["AMZN", "GOOG"]
```

At the end `"AMZN"`'s volume is `400`, `"GOOG"`'s volume is `300`, and `"NFLX"`'s volume is `300`. Since `"AMZN"` has the most volume we return it first. Then, since `"GOOG"` and `"NFLX"` are tied in terms of volume, we return the lexicographically smaller stock which is `"GOOG"`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Highest-Volume-Stocks.cpp"></script>
