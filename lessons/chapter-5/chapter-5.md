# Chapter 5: Connecting Words (String Concatenation)

You now know how to save information in a variable. But what if you want to use that variable for a different purpose than intended?

### 1. The Problem

If you try to print words and a variable together like this:

`name = "Ethyl-OH"`
`print("Hello name")`

The computer will print `"Hello name"` instead of `"Hello Ethyl-OH"`. It printed the exact letters you typed inside the quotes instead of a mix between the given string and variable. We need a way to mix regular text and variables together.

### 2. The Tool

To attach a string (text) and a variable together, we use the plus sign (`+`). In programming, this is called **String Concatenation**. 

You just close your quotation marks, put a `+`, and then put your variable name.

**Example:**
`name = "Ethanol"`
`print("Hello " + name)`

*(Notice the space after `"Hello "`? The computer will glue the strings exactly as they are. If you don't add a space inside your quotes, the words will be attached together like `"HelloEthanol"`.)*

### 3. The Task

Create a variable called `food`, ask the user what their favorite food is, and then print a sentence that says: `"I like to eat"` followed by their food.

* [Chapter 5 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-5/chapter-5.ipynb)

### 4. Challenge

Ask the user for three different words (for example: a color, an animal, and a place). Then, use string concatenation (`+`) to turn them into one big sentence. 
