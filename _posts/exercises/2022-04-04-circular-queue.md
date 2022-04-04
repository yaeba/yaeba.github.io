---
title: "Circular Queue"
tags: ["data structure"]
---

Implement a circular queue with the following methods:

- `CircularQueue(int capacity)` which creates an instance of a circular queue with size `capacity`. Circular queues are implemented using an array which holds the enqueued values with pointers pointing to the start and end of the queue. When the queue reaches the end of the array, it will start to fill items from the start of the array if they were dequeued.
- `boolean enqueue(int val)` which adds `val` to the queue if it has space. If the queue is full, return `false` to denote it can't be added and return `true` otherwise.
- `boolean dequeue()` which removes the first element that was enqueued. If the queue is empty, return `false` to denote it can't be removed and return `true` otherwise.
- `int front()` which returns the first element that was enqueued. If the queue is empty, return `-1`.
- `int top()` which returns the last element that was enqueued. If the queue is empty, return `-1`.
- `boolean isFull()` which returns whether the queue has `capacity` elements.
- `boolean isEmpty()` which returns whether the queue has no elements.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of calls to the queue

[https://binarysearch.com/problems/Circular-Queue](https://binarysearch.com/problems/Circular-Queue){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'enqueue', 'enqueue', 'enqueue', 'top', 'front', 'isFull', 'isEmpty', 'dequeue', 'enqueue', 'dequeue', 'dequeue', 'dequeue', 'isEmpty']`
- arguments = `[[3], [1], [2], [3], [], [], [], [], [], [4], [], [], [], []]`

**Output**

- answer = `[None, True, True, True, 3, 1, True, False, True, True, True, True, True, True]`

**Explanation**

```
q = CircularQueue(3)
q.enqueue(1)
q.enqueue(2)
q.enqueue(3)
q.top() == 3
q.front() == 1
q.isFull() == True
q.isEmpty() == False
q.dequeue() == True
q.enqueue(4) == True
q.dequeue() == True
q.dequeue() == True
q.dequeue() == True
q.isEmpty() == True
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Circular-Queue.cpp"></script>
