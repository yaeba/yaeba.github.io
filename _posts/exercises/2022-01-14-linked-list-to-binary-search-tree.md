---
title: "Linked List to Binary Search Tree"
tags: ["divide and conquer", "linked list", "tree"]
---

Given a sorted linked list `node` of size `n`, construct a binary search tree by

- Taking the value of the `k = floor(n / 2)`(0-indexed) smallest node and setting it as the root.
- Recursively constructing the left subtree using the linked list left of the `kth `node.
- Recursively constructing the right subtree using the linked list right of the `kth `node.

**Constraints**

- `n ≤ 100,000`

[https://binarysearch.com/problems/Linked-List-to-Binary-Search-Tree](https://binarysearch.com/problems/Linked-List-to-Binary-Search-Tree){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 1]; 1 [label = 3]; 2 [label = 4]; 3 [label = 6]; 0->1->2->3; rankdir=LR }")
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
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 4]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 6]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 1]; C3 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> 3; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 3 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-to-Binary-Search-Tree.py"></script>
