# Chapter 3: The Reciter

You now know how to make the computer talk (`print`) and how to leave notes for yourself (`#`). But there is a problem: the computer only says exactly what you hardcoded it to say. It is talking, but it is not listening.

### 1. The Trap

If you want the computer to ask the user a question, you might try using our old tool:

`print("What is your name?")`

If you run that, the computer will print the question out, but it will not wait for an answer. It will just keep going through the rest of the code. We need to make the computer listen.

### 2. The Tool

To make the computer wait for the user to type something back, we use the `input()` Function. 

Inside the Parentheses, you put the prompt you want the computer to display. 

**Example:**
`input("What is your name? ")`

When the computer hits this line, the program will stop. It will ask the question and wait for the user to answer and press `Enter` before it continues.

### 3. The Task

Use the `input()` Function to ask the user what their favorite color is.

* [Chapter 3 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-3/chapter-3.ipynb)

### 4. Challenge

Make a mini-survey. Write a program that asks the user different questions in a row.

### 5. Solution

* [Chapter 3 Solution](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-3/chapter-3-solution.ipynb)
