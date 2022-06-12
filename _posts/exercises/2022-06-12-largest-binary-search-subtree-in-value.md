---
title: "Largest Binary Search Subtree in Value"
tags: ["tree"]
---

Given a binary tree `root`, return the largest sum of a subtree that is also a binary search tree.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Largest-Binary-Search-Subtree-in-Value](https://binarysearch.com/problems/Largest-Binary-Search-Subtree-in-Value){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 6]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 7]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 2]; C5 [style = invis, width = 0, label = \"\"]; 6 [label = 4]; C6 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> 3; 1 -> C1 [style = invis]; 1 -> 4; {rank = same; 3 -> C1 -> 4 [style = invis]}; 2 -> 5; 2 -> C2 [style = invis]; 2 -> 6; {rank = same; 5 -> C2 -> 6 [style = invis]}; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"]; 5 -> L5 [style = invis]; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; L5 -> C5 -> R5 [style = invis]}; L5 [style = invis, width = 0, label = \"\"]; R5 [style = invis, width = 0, label = \"\"]; 6 -> L6 [style = invis]; 6 -> C6 [style = invis]; 6 -> R6 [style = invis]; {rank = same; L6 -> C6 -> R6 [style = invis]}; L6 [style = invis, width = 0, label = \"\"]; R6 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `9`

**Explanation**

The binary search tree rooted at `3` has the largest sum with `3 + 2 + 4 = 9`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Binary-Search-Subtree-in-Value.py"></script>
