---
title: "Tree Traversal"
tags: ["stack", "tree"]
---

You are given a tree `root` and a list of strings `moves` consisting of `"RIGHT"`, `"LEFT"` and `"UP"`. Starting from `root`, traverse the tree by performing each move in `moves` where:

- `"RIGHT"` means to traverse to the right child.
- `"LEFT"` means to traverse to the left child.
- `"UP"` means to traverse to its parent.

Return the value of the last node after all moves. You can assume that the moves are valid.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Tree-Traversal](https://binarysearch.com/problems/Tree-Traversal){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 9]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 1]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 8]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 6]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 0]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 3]; C5 [style = invis, width = 0, label = \"\"]; 6 [label = 2]; C6 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> 5; 3 -> C3 [style = invis]; 3 -> 6; {rank = same; 5 -> C3 -> 6 [style = invis]}; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"]; 5 -> L5 [style = invis]; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; L5 -> C5 -> R5 [style = invis]}; L5 [style = invis, width = 0, label = \"\"]; R5 [style = invis, width = 0, label = \"\"]; 6 -> L6 [style = invis]; 6 -> C6 [style = invis]; 6 -> R6 [style = invis]; {rank = same; L6 -> C6 -> R6 [style = invis]}; L6 [style = invis, width = 0, label = \"\"]; R6 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- moves = `['RIGHT', 'RIGHT', 'UP', 'LEFT', 'RIGHT']`

**Output**

- answer = `2`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Tree-Traversal.py"></script>
