---
title: "Sum of Digit Paths in a Tree"
tags: ["tree"]
---

You are given a binary tree `root` with each node containing single digits from `0` to `9`. Each path from the root to the leaf represents a number with its digits in order.

Return the sum of numbers represented by all paths in the tree.

[https://binarysearch.com/problems/Sum-of-Digit-Paths-in-a-Tree](https://binarysearch.com/problems/Sum-of-Digit-Paths-in-a-Tree){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `25`

**Explanation**

We have `12 + 13 = 25`.

### Example 2

**Input**

- root =

<div id="example2Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root { 0 [label = 3]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 2]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 1]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 4]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `680`

**Explanation**

We have the following numbers represented by paths:

- `35` (3 → 5)
- `321` (3 → 2 → 1)
- `324` (3 → 2 → 4)

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Digit-Paths-in-a-Tree.cpp"></script>
