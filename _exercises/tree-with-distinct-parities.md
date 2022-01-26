---
title: "Tree with Distinct Parities"
tags: ["tree"]
---

Given a binary tree `root`, return the number of perfect nodes. A perfect node has two properties:

- Has both children
- The sum of one subtree is even and the sum of the other subtree is odd

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Tree-with-Distinct-Parities](https://binarysearch.com/problems/Tree-with-Distinct-Parities){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 4]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 7]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `2`

**Explanation**

Nodes `1` and `3` meet the criteria.

### Example 2

**Input**

- root =

<div id="example2Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> R0 [style = invis]; {rank = same; 1 -> C0 -> R0 [style = invis]}; R0 [style = invis, width = 0, label = \"\"]; 1 -> 2; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 2 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `0`

**Explanation**

No node has both a left and a right child.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Tree-with-Distinct-Parities.cpp"></script>
