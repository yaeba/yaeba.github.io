---
title: "Tic Tac Toe"
tags: ["hash table", "data structure"]
---

Implement the tic-tac-toe game with the following methods:

- `TicTacToe(int n)` which instantiates an `n x n` game board. A player wins a game if their pieces either form a horizontal, vertical, or diagonal line of length `n`.
- `int move(int r, int c, boolean me)` which places the next move at row `r` and column `c`. `me` indicates whether it's my move (`me = true)` or it's your opponent's (`me = false`) move. If this move makes you win, return `1`, if your opponent wins, return `-1`, and otherwise return `0`.

**Constraints**

- `1 ≤ n ≤ 100,000`
- `0 ≤ m ≤ 100,000` where `m` is the number of calls to `move`

[https://binarysearch.com/problems/Tic-Tac-Toe](https://binarysearch.com/problems/Tic-Tac-Toe){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'move', 'move', 'move', 'move', 'move']`
- arguments = `[[3], [0, 0, True], [2, 0, False], [0, 1, True], [2, 1, False], [0, 2, True]]`

**Output**

- answer = `[None, 0, 0, 0, 0, 1]`

**Explanation**

```
t = TicTacToe(3)
t.move(0, 0, True) == 0 # I place piece (0, 0)
t.move(2, 0, False) == 0 # Opponent places piece (2, 0)
t.move(0, 1, True) == 0 # I place piece (0, 1)
t.move(2, 1, False) == 0 # Opponent places piece (2, 1)
t.move(0, 2, True) == 1 # I place piece (0, 2) to win
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Tic-Tac-Toe.py"></script>
