# Chapter 13: Circles and Dots

Everything you have drawn so far is made of straight lines. It is time to learn curves.

### 1. The Problem

If you try to draw a circle using only `forward()` and `right()`, you would need dozens of tiny steps and tiny turns. That is tedious and impractical without tools we have not learned yet.

### 2. The Tool

Python's Turtle has two built-in commands for round shapes:

* `circle(50)` Draws a circle with a radius of 50 pixels. The Turtle traces the circle starting from its current position.
* `dot(20)` Stamps a filled dot with a diameter of 20 pixels at the Turtle's current position. Unlike `circle()`, the Turtle does not move.
* `dot(20, "red")` Stamps a filled red dot.

**Example:**
`circle(75)`

The number inside the Parentheses is the radius. A bigger number draws a bigger circle. A negative number draws the circle in the opposite direction.

### 3. The Task

Draw a circle with a radius of 60.

* [Chapter 13 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-13/chapter-13.ipynb)

### 4. Challenge

Draw a bullseye using three `dot()` commands of decreasing size, layered on top of each other. Use alternating colors (for example: red, white, red).

### 5. Solution

* [Chapter 13 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-13/chapter-13-solution.ipynb)
