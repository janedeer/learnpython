The first lesson for almost any programming language is to create a Hello World program.
This program will teach you several things:
- How to define a function
- How to print a statement
- How to represent a [string][string-def]
- How to call a function

```python
def hello():
    print("Hello World!")
hello()
```
Here are the main components to look at:
- **def** hello(): Defines the function called hello. Notice the (): after hello
- **print()** This statement tells the computer to display the content between the parantheses.
- **"Hello World!"** The double quotes indicate that the data type is a [string][string-def].
- **hello()**  This statement _calls_ the hello function. Try running your program without this statement and see what happens - nothing! This is because you have created a function called hello, and defined what this function will do, but you have not yet told the computer to execute the function. Typing the funciton name followed by () will execute the function.

Let's look at some more print statements.

```python
def printing():
    print("hello")
    print("5")
    print("True")
    print(5)
    print(True)
printing()
```
- Line 1 creates a function called printing
- Line 2 prints a string "hello"
- Line 3 prints a string "5"
- Line 4 prints a string "True"
- Line 5 prints an [int][int-def] 5
- Line 6 prints a boolean or [bool][bool-def] True




<!-- Identifiers -->
[bool-def]: https://github.com/melaniesifen/learnpython/definitions "A boolean expression evaluates to either True or False."
[int-def]: https://github.com/melaniesifen/learnpython/definitions "An integer or whole number."
[string-def]: https://github.com/melaniesifen/learnpython/definitions "An immutable data type consisting of a sequence of characters."

