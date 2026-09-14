# Chapter 10: The Blank Canvas

This unit is going to teach you the basics of visual outputs using Turtle. This is an introduction to the broader concept of machine thinking in programs and algorithms. We will use art and shapes to train you to think more logically about how a computer follows instructions.

So far, all our output has been text. It is time to make the computer draw.

### 1. The Problem

`print()` can only display text. If you want to draw a shape, a diagram, or anything visual, printing characters to the screen is not going to cut it. We need a drawing tool.

### 2. The Tool

Python has a built-in drawing library called **Turtle**. It works like a pen on a piece of paper. You give the pen (the Turtle) simple movement commands, and it draws a line wherever it goes.

The four basic movement commands are:

* `forward(100)` Moves the Turtle forward by 100 pixels, drawing a line.
* `backward(100)` Moves the Turtle backward by 100 pixels.
* `right(90)` Turns the Turtle 90 degrees to the right. This does not move it, it only changes the direction it is facing.
* `left(90)` Turns the Turtle 90 degrees to the left.

**Setup (run this first in every Turtle notebook):**
`!pip install -q ColabTurtlePlus`
`from ColabTurtlePlus.Turtle import *`
`clearscreen()`

**Example (drawing a straight line):**
`forward(100)`

### 3. The Task

Draw a square. A square has four equal sides and four 90-degree turns. Use `forward()` and `right()` to draw one.

* [Chapter 10 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-10/chapter-10.ipynb)

### 4. Challenge

Draw any polygon. Figure out what angle you need to turn.

### 5. Solution

* [Chapter 10 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-10/chapter-10-solution.ipynb)
