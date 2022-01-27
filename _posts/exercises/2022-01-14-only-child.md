---
title: "Only Child"
tags: ["tree"]
---

Given a binary tree `root`, return the number of nodes that are an only child. A node `x` is an only child if its parent has exactly one child (`x`).

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Only-Child](https://binarysearch.com/problems/Only-Child){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 0]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 4]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 2]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 1]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 3]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; 3 -> C2 -> R2 [style = invis]}; R2 [style = invis, width = 0, label = \"\"]; 3 -> 4; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; 4 -> C3 -> R3 [style = invis]}; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
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

Node `1` is an only child and `3` is an only child.

### Example 2

**Input**

- root =

<div id="example2Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 1]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 1]; C3 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> 1; {rank = same; L0 -> C0 -> 1 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; 1 -> 2; 1 -> C1 [style = invis]; 1 -> 3; {rank = same; 2 -> C1 -> 3 [style = invis]}; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `1`

**Explanation**

Node `3` is an only child

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Only-Child.cpp"></script>
