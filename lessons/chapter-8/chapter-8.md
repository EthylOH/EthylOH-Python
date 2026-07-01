# Chapter 8: Decimals & Rounding

Division in Python often produces massive, unreadable decimal numbers.

### 1. The Problem

If you run `print(10 / 3)`, the output is `3.3333333333333335`. In programming, this data type is called a **Float** (floating-point number). If you are building a financial application or a user interface, displaying 16 decimal places is unacceptable.

### 2. The Tool

Use the `round()` function to control the number of decimal places. 

The function takes two arguments separated by a comma: `round(the number you want to round, and how many decimal places to keep)`.

**Example:**
```python
price = 10 / 3
print(round(price, 2))
```
The output would be: `3.33`

### 3. The Task 

Divide 22 by 7. Round the result to exactly 4 decimal places and print it.

### 4. Challenge

Build a calculator that rounds the answer to a user-specified number of decimal places.
