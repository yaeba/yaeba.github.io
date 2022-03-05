---
title: "Kth Last Node of a Linked List"
tags: ["two pointers", "linked list"]
---

Given a singly linked list `node`, return the value of the `kth` last node (0-indexed). `k` is guaranteed not to be larger than the size of the linked list.

This should be done in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `node`

[https://binarysearch.com/problems/Kth-Last-Node-of-a-Linked-List](https://binarysearch.com/problems/Kth-Last-Node-of-a-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 1]; 1 [label = 2]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `1`

**Output**

- answer = `1`

**Explanation**

The second last node has the `val` of `1`

### Example 2

**Input**

- node =

<div id="example2Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node { 0 [label = 0]; 1 [label = 1]; 2 [label = 2]; 3 [label = 3]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `2`

**Output**

- answer = `1`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Kth-Last-Node-of-a-Linked-List.cpp"></script>
