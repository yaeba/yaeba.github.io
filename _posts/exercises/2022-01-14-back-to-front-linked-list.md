---
title: "Back to Front Linked List"
tags: ["linked list"]
---

Given a singly linked list `node`, reorder it such that we take: the last node, and then the first node, and then the second last node, and then the second node, etc.

Can you do it in $$\mathcal{O}(1)$$ space?

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Back-to-Front-Linked-List](https://binarysearch.com/problems/Back-to-Front-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 0]; 1 [label = 1]; 2 [label = 2]; 3 [label = 3]; 0->1->2->3; rankdir=LR }")
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
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 3]; 1 [label = 0]; 2 [label = 2]; 3 [label = 1]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Back-to-Front-Linked-List.py"></script>
