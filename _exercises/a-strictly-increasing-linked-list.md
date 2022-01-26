---
title: "A Strictly Increasing Linked List"
tags: ["linked list"]
---

Given the head of a singly linked list `head`, return whether the values of the nodes are sorted in a strictly increasing order.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the number of nodes in `head`

[https://binarysearch.com/problems/A-Strictly-Increasing-Linked-List](https://binarysearch.com/problems/A-Strictly-Increasing-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- head =

<div id="example1Head" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Head { 0 [label = 1]; 1 [label = 5]; 2 [label = 9]; 3 [label = 9]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Head").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `False`

**Explanation**

Even though this list is sorted, it's not strictly increasing since `9` is repeated.

### Example 2

**Input**

- head =

<div id="example2Head" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Head { 0 [label = 1]; 1 [label = 5]; 2 [label = 8]; 3 [label = 9]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Head").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

**Explanation**

The values 1, 5, 8, 9 are strictly increasing.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=A-Strictly-Increasing-Linked-List.cpp"></script>
