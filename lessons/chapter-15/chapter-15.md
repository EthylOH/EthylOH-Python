# Chapter 15: Custom Shapes

Every shape you have drawn so far has a hardcoded size. The square is always 100 pixels, the triangle is always the same. If you want a different size, you have to manually edit every single `forward()` command.

### 1. The Problem

If you want to draw a square with sides of 200 instead of 100, you have to go through your code and change four separate `forward(100)` lines to `forward(200)`. That is repetitive and easy to mess up.

### 2. The Tool

Use a Variable to store the size. Then pass that Variable into your `forward()` commands. If you want to let the user decide the size, combine it with `int(input())` from the earlier chapters.

**Example:**
`size = int(input("size?"))`
`forward(size)`
`right(90)`
`forward(size)`
`right(90)`
`forward(size)`
`right(90)`
`forward(size)`
`right(90)`

Now the user controls the size of the square.

### 3. The Task

Ask the user for a number using `input()`, convert it to an Integer, and draw a square where every side is that length.

* [Chapter 15 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-15/chapter-15.ipynb)

### 4. Challenge

Ask the user for a size and a color. Draw a filled square of that size in that color.

### 5. Solution

* [Chapter 15 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-15/chapter-15-solution.ipynb)
