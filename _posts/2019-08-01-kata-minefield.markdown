---
layout: post
title: Kata - Mine Field
tags: [kata]
---

In the game Minesweeper, the goal of the game is to find all the mines within a field. To help you, the game shows a number in a square which tells you how many mines there are adjacent to that square. For instance, take the following 4x4 field with 2 mines, one at [column 1, row 1], and another at [column 2, row 3].

```
* . . .
. . . .
. * . .
. . . .
```

The same field including the hint numbers described above would look like this:

```
* 1 0 0
2 2 1 0
1 * 1 0
1 1 1 0
```

You should write a program that takes input as follows:

The input will consist of the dimensions of the grid (width x height), and the list of coordinates (base 1) where the mines are.

Following the example above, the inputs would be:

```
Length: 4
Height: 4
Mines: (column 1, row 1), (column 2, row 3)
```

Your program’s output should be the grid with hint numbers.

```
* 1 0 0
2 2 1 0
1 * 1 0
1 1 1 0
```

### Stretch goal:

If you manage to finish early, you can add some randomization to the game. Instead of assigning fixed coordinates for where the mines are, specify the number of mines in the field instead.

Length: 4
Height: 4
Mines: 2

And have the game randomly assign where the mines will be.