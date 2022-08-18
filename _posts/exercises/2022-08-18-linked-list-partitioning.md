---
title: "Linked List Partitioning"
tags: ["two pointers", "linked list"]
---

You are given a singly linked list `node` and an integer `k`. Order the linked list so that all nodes whose values are less than `k` come first, all nodes whose values are equal to `k` next, and then other nodes last.

The relative ordering of the nodes should remain the same.

Bonus: Can you do it in $$\mathcal{O}(n)$` time and `$\mathcal{O}(1)$$ space?

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Linked-List-Partitioning](https://binarysearch.com/problems/Linked-List-Partitioning){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 3]; 1 [label = 2]; 2 [label = 1]; 3 [label = 2]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `2`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 1]; 1 [label = 2]; 2 [label = 2]; 3 [label = 3]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-Partitioning.cpp"></script>
