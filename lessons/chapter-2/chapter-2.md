# Chapter 2: Leaving Notes

You now know how to make the computer speak. But what happens when you write a program and need to remind yourself what it does? You just want to leave a note for yourself, which the computer should ignore. 

### 1. The Broken Note

If you try to leave a normal English note for yourself in your code like this:

`This next line prints my username`
`print("Ethanol")`

Your computer will try to read your note as a programming command. It will get confused, crash, and report an error. We need a way to leave notes that the computer ignores.

### 2. The Tool

To leave a note for yourself that the computer will completely skip over, we use the hashtag symbol (`#`). This is called a **comment**. Anything on the line after the `#` is invisible to the computer.

**Example:**
`# This is a comment. The computer will completely ignore this.`
`print("Hello, World!")`

Sometimes you have a lot to say and don't want to put a `#` at the start of every single line. You can use triple quotes (`"""` or `'''`) to create multi-line text blocks. 

**Example:**
```
"""
This looks like a multi-line comment.
I can write as many lines as I want here.
Python will just ignore this block.
"""
print("hello world")
```

### 3. The Task

Use the `#` symbol to "comment out" the comments so the computer ignores them and only runs the actual Python code.

* [Chapter 2 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-2/chapter-2.ipynb?v=3)

### 4. Challenge

Combine what you know. Write `print()` statements to draw ASCII art. Above some lines of code, write a `# comment` explaining exactly what that specific line is drawing.
