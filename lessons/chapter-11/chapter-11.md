# Chapter 11: Digital Ink

You can draw shapes, but the Turtle draws a continuous line everywhere it goes. If you want to draw two separate shapes, the Turtle drags a line between them.

### 1. The Problem

If you draw a square and then try to move the Turtle to a new position to draw a second square, a visible line will connect the two shapes. The Turtle's pen is always touching the paper.

### 2. The Tool

To lift the pen off the paper, use `penup()`. To put it back down, use `pendown()`. While the pen is up, the Turtle can move without drawing anything.

You can also control the pen's appearance:

* `penup()` Lifts the pen. Movement will not draw a line.
* `pendown()` Puts the pen back down. Movement will draw again.
* `pensize(5)` Changes the thickness of the line to 5 pixels.
* `pencolor("red")` Changes the color of the line to red.

**Example (moving without drawing):**
`penup()`
`forward(100)`
`pendown()`

### 3. The Task

Draw two separate squares side by side with no line connecting them. Use `penup()` and `pendown()` to lift the pen when moving between shapes.

* [Chapter 11 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-11/chapter-11.ipynb)

### 4. Challenge

Draw three separate lines of different thicknesses and different colors, spaced apart with no connecting lines between them.

### 5. Solution

* [Chapter 11 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-11/chapter-11-solution.ipynb)
