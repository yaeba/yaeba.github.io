---
title: "Linked List Jumps"
tags: ["linked list"]
---

You are given a singly linked list `node` containing positive integers. Return the same linked list where every node's `next` points to the node `val` nodes ahead. If there's no such node, `next` should point to null.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Linked-List-Jumps](https://binarysearch.com/problems/Linked-List-Jumps){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 2]; 1 [label = 1]; 2 [label = 4]; 3 [label = 1]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output { 0 [label = 2]; 1 [label = 4]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

Note that `2`'s next is `2` node ahead. `4`'s next is out of bounds, so it's set to null.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-Jumps.cpp"></script>
