# Chapter 4: Variables

You now know how to ask the user a question. But there is a problem: the computer immediately forgets what the user typed.

### 1. Amnesia

If you run this code:

`input("What is your name? ")`

The computer will ask the question and wait for an answer. But the answer is not stored. We need a way to make the computer remember things.

### 2. The Tool

To make the computer remember data, we use **variables**. They are labeled memory boxes where the computer stores information. 

You create the variable name, then put an equals sign (`=`), and lastly the data inside.

**Example:** 
`name = input("What is your name? ")`

Now, the name is saved inside the `name`.

Variables can hold different types of data:
* **Strings** (Text): `color = "Blue"`
* **Integers** (Whole Numbers): `age = 15`
* **Floats** (Decimals): `price = 19.99`
* **Booleans** (True/False): `is_hungry = True`

### 3. The Task

Create a variable called `favorite_food` and use `input()` to ask the user what their favorite food is, saving their answer in the variable.

* [Chapter 4 Task](https://colab.research.google.com/github/EthylOH/EthylOH-Python/blob/main/lessons/chapter-4/chapter-4.ipynb)

### 4. Challenge

Create three different variables: one string for a superhero name, one integer for their age, and one boolean for whether they wear a cape.
