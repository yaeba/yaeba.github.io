---
title: "Tree Coloring"
tags: ["tree"]
---

You are given a binary tree `root` where the value of each node represents its color. In the tree there are at most `2` colors. Return whether it's possible to swap the colors of the nodes any number of times so that no two adjacent nodes have the same color.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Tree-Coloring](https://binarysearch.com/problems/Tree-Coloring){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 1]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 1]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 0]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 0]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 0]; C5 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> 5; {rank = same; L3 -> C3 -> 5 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"]; 5 -> L5 [style = invis]; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; L5 -> C5 -> R5 [style = invis]}; L5 [style = invis, width = 0, label = \"\"]; R5 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

**Explanation**

We can color the root with `0`, the next level `1`s, third level `0`s and fourth level `1`s

### Example 2

**Input**

- root =

<div id="example2Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root { 0 [label = 5]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 9]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 5]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 9]; C3 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> 1; {rank = same; L0 -> C0 -> 1 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; 1 -> 2; 1 -> C1 [style = invis]; 1 -> 3; {rank = same; 2 -> C1 -> 3 [style = invis]}; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `False`

**Explanation**

There's no way to color the nodes so that no two adjacent nodes have the same color.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Tree-Coloring.py"></script>
