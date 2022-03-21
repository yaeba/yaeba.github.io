---
title: "Longest Tree Sum Path From Root to Leaf"
tags: ["tree"]
---

Given a binary tree `root`, return the sum of the longest path from the root to a leaf node. If there are two equally long paths, return the larger sum.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Longest-Tree-Sum-Path-From-Root-to-Leaf](https://binarysearch.com/problems/Longest-Tree-Sum-Path-From-Root-to-Leaf){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 4]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 7]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 12]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 4]; C5 [style = invis, width = 0, label = \"\"]; 6 [label = 8]; C6 [style = invis, width = 0, label = \"\"]; 7 [label = 2]; C7 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> 5; 3 -> C3 [style = invis]; 3 -> 6; {rank = same; 5 -> C3 -> 6 [style = invis]}; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"]; 5 -> 7; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; 7 -> C5 -> R5 [style = invis]}; R5 [style = invis, width = 0, label = \"\"]; 6 -> L6 [style = invis]; 6 -> C6 [style = invis]; 6 -> R6 [style = invis]; {rank = same; L6 -> C6 -> R6 [style = invis]}; L6 [style = invis, width = 0, label = \"\"]; R6 [style = invis, width = 0, label = \"\"]; 7 -> L7 [style = invis]; 7 -> C7 [style = invis]; 7 -> R7 [style = invis]; {rank = same; L7 -> C7 -> R7 [style = invis]}; L7 [style = invis, width = 0, label = \"\"]; R7 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `18`

**Explanation**

The longest path here is 5 nodes long: 1 -> 4 -> 7 -> 4 -> 2.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Tree-Sum-Path-From-Root-to-Leaf.cpp"></script>
