# Chapter 6: Words vs. Numbers

You now know how to use the `+` sign to attach strings. But what happens if you try to use it for math?

### 1. Data Types

If you run this code:

`print("5" + "5")`

Instead of printing `10` like expeected, it prints `55`. Because of the quotation marks around the numbers. The computer believes they are strings, so it just glues the characters together. 

### 2. The Tool

To make the computer do math, you must remove the quotation marks. This changes the **Data Type** from a string (text) to an integer (a whole number).

**Example:**
`print(5 + 5)`

Without the quotes, the computer knows these are integers. It will do the math and print `10`.

*(Note: The `input()` function always captures strings. If you want the user to type a number for math, you must convert their answer. Wrap it in `int()` for whole numbers, or `float()` for decimals. Example: `age = int(input("How old are you? "))` or `price = float(input("How much does it cost? "))`)*

### 3. The Task

Use `input()` to ask the user for a number. Convert their answer into an integer using `int()`, and then print out what their number multiplied by 100 would be.

* [Chapter 6 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-6/chapter-6.ipynb)
