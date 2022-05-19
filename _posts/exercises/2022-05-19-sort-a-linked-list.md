---
title: "Sort a Linked List"
tags: ["linked list"]
---

Given a singly linked list of integers `node`, sort the nodes by their values in ascending order.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Sort-a-Linked-List](https://binarysearch.com/problems/Sort-a-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 14]; 1 [label = 13]; 2 [label = 10]; 0->1->2; rankdir=LR }")
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

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 10]; 1 [label = 13]; 2 [label = 14]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sort-a-Linked-List.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sort-a-Linked-List.py"></script>
