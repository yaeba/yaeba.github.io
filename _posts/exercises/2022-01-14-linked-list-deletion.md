---
title: "Linked List Deletion"
tags: ["linked list"]
---

Given a singly linked list `node`, and an integer `target`, return the same linked list with all nodes whose value is `target` removed.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Linked-List-Deletion](https://binarysearch.com/problems/Linked-List-Deletion){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 0]; 1 [label = 1]; 2 [label = 1]; 3 [label = 2]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `1`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 0]; 1 [label = 2]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-Deletion.cpp"></script>
