---
title: "Reverse an Inner Linked List"
tags: ["linked list"]
---

Given a singly linked list `node`, and integers `i` and `j`, reverse the linked list from `i` to `j`th nodes, `0` indexed and inclusive.

You should return the head of the reversed list.

This should be done in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the number nodes in `node`

[https://binarysearch.com/problems/Reverse-an-Inner-Linked-List](https://binarysearch.com/problems/Reverse-an-Inner-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 0]; 1 [label = 1]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- i = `1`
- j = `2`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 0]; 1 [label = 3]; 2 [label = 1]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Reverse-an-Inner-Linked-List.cpp"></script>
