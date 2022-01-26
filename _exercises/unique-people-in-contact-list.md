---
title: "Unique People in Contact List"
tags: ["hash table"]
---

You are given a two-dimensional list of strings `contacts`. Each element `contacts[i]` represents the list of emails for contact `i`. Contact `i` is considered a duplicate if there's a `j < i` such that contact `j` shares a common email with `i`. Return the number of unique people in `contacts`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the total number of strings in `contacts`

[https://binarysearch.com/problems/Unique-People-in-Contact-List](https://binarysearch.com/problems/Unique-People-in-Contact-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- contacts = `[['elon@tesla.com', 'elon@paypal.com'], ['elon@tesla.com', 'elon@spacex.com'], ['tim@apple.com']]`

**Output**

- answer = `2`

**Explanation**

Contact `0` and `1` are the same person since they share a common email `"elon@tesla.com"`. Then, contact `2` is another person.

### Example 2

**Input**

- contacts = `[['bill@microsoft.com'], ['jack@twitter.com'], ['jeff@amazon.com']]`

**Output**

- answer = `3`

**Explanation**

All `3` contacts represent `3` unique people.

### Example 3

**Input**

- contacts = `[['lawrence@gmail.com'], ['lawrence@gmail.com', 'larry@gmail.com'], ['larry@gmail.com']]`

**Output**

- answer = `1`

**Explanation**

Only contact `i = 0` is considered unique. The other two contacts are duplicates.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unique-People-in-Contact-List.py"></script>
