# Chapter 14: The Grid

So far, the Turtle can only move relative to wherever it currently is. If you want to place something at a specific spot on the canvas, you are stuck trying to figure out how many `forward()` and `right()` commands to chain together.

### 1. The Problem

If you draw a shape in the top-right corner and then want to draw another one in the bottom-left corner, you would have to carefully calculate every step and turn to get there. That is slow and error-prone.

### 2. The Tool

The Turtle canvas is a Coordinate Grid. The center of the screen is position `(0, 0)`. The X-axis goes left (negative) and right (positive). The Y-axis goes down (negative) and up (positive).

You can teleport the Turtle to any position on this grid:

* `goto(100, 50)` — Move the Turtle to the point X=100, Y=50. If the pen is down, it will draw a line from where it was to the new position.
* `setpos(100, 50)` — Same as `goto()`.
* `home()` — Move the Turtle back to the center `(0, 0)` and reset its direction to face right.

**Example (drawing a line from the center to a specific point):**
`goto(150, 100)`

To move without drawing, use `penup()` before `goto()`.

### 3. The Task

Use `goto()` to draw a triangle by moving the Turtle to three specific coordinate points. For example: `(0, 0)`, `(100, 0)`, and `(50, 80)`, then back to `(0, 0)`.

* [Chapter 14 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-14/chapter-14.ipynb)

### 4. Challenge

Draw a simple house shape using only `goto()` commands. A square base with a triangular roof on top. Use `penup()` and `pendown()` as needed.

### 5. Solution

* [Chapter 14 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-14/chapter-14-solution.ipynb)
