# Chapter 16: Text and Finishing Touches

You can draw shapes, control colors, and use coordinates. But sometimes you need to put actual words on the canvas, or clean up the look of your final drawing.

### 1. The Problem

You might want to label parts of a diagram or write your name on your artwork. `print()` only outputs to the text console, not onto the Turtle canvas.

### 2. The Tool

Turtle has a `write()` Function that places text directly on the canvas at the Turtle's current position. It also has commands to control the Turtle's speed and visibility.

* `write("Hello")` Writes the text "Hello" on the canvas at the current position.
* `hideturtle()` Hides the Turtle arrow so it does not appear in your drawing.
* `showturtle()` Shows the Turtle arrow again.
* `speed(0)` Sets the drawing speed. `0` is the fastest (instant). `1` is the slowest. `6` is the default.
* `shape("turtle")` Changes the Turtle's arrow icon to an actual turtle shape. Other options include "circle", "square", "triangle", and "arrow".

**Example:**
```python
hideturtle()
write("This text is on the canvas")
```

### 3. The Task

Write your name on the center of the canvas, then hide the Turtle so only the text is visible.

* [Chapter 16 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-16/chapter-16.ipynb)

### 4. Challenge

Create a simple labeled drawing. Draw any shape you want and use `write()` to label it. For example, draw a square and write "Square" underneath it. Hide the Turtle when you are done.

### 5. Solution

* [Chapter 16 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-16/chapter-16-solution.ipynb)
