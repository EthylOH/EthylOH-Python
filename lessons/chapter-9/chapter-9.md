# Chapter 9: Type Casting

The `input()` function is great for getting Strings, therefore it has a major blind spot when it comes to math.

### 1. The Problem

The `input()` function *always* captures the user's answer as a String, even if they type a number. 

If you ask for their birth year and try to do math with it:

`birth_year = input("What year were you born? ")`
`age = 2026 - birth_year`

The computer crashes. It thinks you are trying to subtract a word (the String "2005") from a number (the Integer 2026). 

### 2. The Tool

To fix this, you have to manually translate the text into a real number. This is called **Type Casting**.

* Use `int()` to translate text into a whole number.
* Use `float()` to translate text into a decimal.

**Example:**

`birth_year_text = input("What year were you born? ")`
`birth_year_num = int(birth_year_text)`
`age = 2026 - birth_year_num`
`print(age)`

*(Pro Tip: You can do this all on one line by wrapping the input function itself: `year = int(input("Year? "))`)*

### 3. The Task

Build a calculator.

👉 [Chapter 9 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-9/chapter-9.ipynb)
