---
title: "Rate Limiter"
tags: ["data structure"]
---

Implement a rate limiter that limits users’ requests with the following methods:

- `RateLimiter(int expire)` constructs a new rate limiter with the given `expire` time.
- `limit(int uid, int timestamp)` represents a request from user `uid` at time `timestamp` and should return whether the given user’s request fails. It should fail if the user had a successful request less than `expire` time ago.

You can assume that `timestamp` is monotonically increasing between requests.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `limit`.

[https://binarysearch.com/problems/Rate-Limiter](https://binarysearch.com/problems/Rate-Limiter){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'limit', 'limit', 'limit', 'limit']`
- arguments = `[[0], [0, 1], [0, 1], [0, 2], [0, 3]]`

**Output**

- answer = `[None, False, False, False, False]`

**Explanation**

```
rl = RateLimiter(0)
rl.limit(0, 1) == False
rl.limit(0, 1) == False
rl.limit(0, 2) == False
rl.limit(1, 3) == False
```

### Example 2

**Input**

- methods = `['constructor', 'limit', 'limit', 'limit', 'limit']`
- arguments = `[[5], [0, 10], [0, 15], [0, 16], [1, 17]]`

**Output**

- answer = `[None, False, False, True, False]`

**Explanation**

```
rl = RateLimiter(5)
rl.limit(0, 10) == False
rl.limit(0, 15) == False
rl.limit(0, 16) == True
rl.limit(1, 17) == False
```

### Example 3

**Input**

- methods = `['constructor', 'limit', 'limit', 'limit']`
- arguments = `[[5], [0, 10], [0, 13], [0, 16]]`

**Output**

- answer = `[None, False, True, False]`

**Explanation**

```
rl = RateLimiter(5)
rl.limit(0, 10) == False
rl.limit(0, 13) == True
rl.limit(0, 16) == False
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rate-Limiter.py"></script>
