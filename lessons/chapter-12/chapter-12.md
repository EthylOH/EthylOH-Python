# Chapter 12: Painting In

You can draw shapes and control the pen. But every shape you draw is hollow. There is no color inside.

### 1. The Problem

When you draw a square, you only get the outline. If you want to fill it with color, there is no way to do it with the tools you have so far.

### 2. The Tool

To fill a shape with color, you need to tell the Turtle when to start and stop paying attention to the shape it is drawing, and what color to fill it with.

* `fillcolor("blue")` — Set the fill color.
* `begin_fill()` — Start tracking the shape to fill.
* `end_fill()` — Stop tracking and fill the shape with color.
* `bgcolor("black")` — Change the background color of the entire canvas.
* `color("red", "yellow")` — Set both the pen color and fill color at once (the arguments are: `color("pencolor", "fill color")`.

**Example (filled square):**
```
fillcolor("blue")
begin_fill()
forward(100)
right(90)
forward(100)
right(90)
forward(100)
right(90)
forward(100)
right(90)
end_fill()
```

The order matters. You must call `begin_fill()` before you start drawing, and `end_fill()` after you finish the shape.

### 3. The Task

Draw a filled triangle. Pick any color you want.

* [Chapter 12 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-12/chapter-12.ipynb)

### 4. Challenge

Draw two filled shapes next to each other, each with a different fill color, on a non-white background.

### 5. Solution

* [Chapter 12 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-12/chapter-12-solution.ipynb)
