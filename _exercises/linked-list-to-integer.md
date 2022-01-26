---
title: "Linked List to Integer"
tags: ["linked list", "math"]
---

Given a single linked list `node`, representing a binary number with most significant digits first, return it as an integer.

**Constraints**

- `n ≤ 30` where `n` the number of nodes in `node`

[https://binarysearch.com/problems/Linked-List-to-Integer](https://binarysearch.com/problems/Linked-List-to-Integer){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 1]; 1 [label = 0]; 2 [label = 0]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `4`

**Explanation**

The linked list represented `100` in binary.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-to-Integer.cpp"></script>
