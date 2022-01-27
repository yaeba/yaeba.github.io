---
title: "Palindrome Linked List"
tags: ["two pointers", "linked list"]
---

Given a singly linked list `node` whose values are integers, determine whether the linked list forms a palindrome.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `node`

[https://binarysearch.com/problems/Palindrome-Linked-List](https://binarysearch.com/problems/Palindrome-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 5]; 1 [label = 3]; 2 [label = 5]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

**Explanation**

5 -> 3 -> 5 is a palindrome.

### Example 2

**Input**

- node =

<div id="example2Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node { 0 [label = 12]; 1 [label = 8]; 2 [label = 12]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

**Explanation**

The values of the linked list are the same forwards and backwards.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Palindrome-Linked-List.cpp"></script>
