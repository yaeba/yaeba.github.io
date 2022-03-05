---
title: "Central Linked List"
tags: ["linked list"]
---

Given a singly linked list `node`, return the value of the middle node. If there's two middle nodes, then return the second one.

Bonus: Solve using $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Central-Linked-List](https://binarysearch.com/problems/Central-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 0]; 1 [label = 1]; 2 [label = 2]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `1`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Central-Linked-List.cpp"></script>
