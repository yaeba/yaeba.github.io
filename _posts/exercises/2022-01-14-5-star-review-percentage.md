---
title: "5-Star Review Percentage"
---

You are given a two-dimensional list of integers `reviews` and a positive integer `threshold`. Each element `reviews[i]` contains `[x, y]` meaning product `i` had `x` number of 5-star reviews and a total of `y` reviews. All reviews are for one store.

Return the minimum number of additional 5-star reviews we need such that the percentage of 5-star reviews in the store is at least `threshold`. You can assume that it's possible to reach `threshold`% of 5-star reviews.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `reviews`
- `0 ≤ threshold ≤ 100`

[https://binarysearch.com/problems/5-Star-Review-Percentage](https://binarysearch.com/problems/5-Star-Review-Percentage){:target="\_blank"}

## Examples

### Example 1

**Input**

- reviews =

```
[[4,4],
 [1,2],
 [3,6]]
```

- threshold = `77`

**Output**

- answer = `6`

**Explanation**

So in total there were `8` 5-star reviews and a total of `12` reviews. To reach `77`% 5-star reviews, we need `6` more 5-star reviews.

### Example 2

**Input**

- reviews =

```
[[1,1]]
```

- threshold = `100`

**Output**

- answer = `0`

**Explanation**

We're already at `100`% 5-star reviews.

### Example 3

**Input**

- reviews =

```
[[10,20]]
```

- threshold = `50`

**Output**

- answer = `0`

**Explanation**

We're already at `50`% 5-star reviews.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=5-Star-Review-Percentage.cpp"></script>
