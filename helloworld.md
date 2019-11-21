## Hello World

The first lesson for almost any programming language is to create a Hello World program.
This program will teach you several things:
- How to create a function
- How to print or display a statement on the screen
- How to represent a [string][string-def] and other data types
- How to call a function

```python
def hello():
    print("Hello World!")
hello()
```
**Output:**

    Hello World!

Here are the main components to look at:
- **def** hello():
    - The keyword "def" defines the function called "hello".
    - Notice the (): after the word hello. This is the syntax to name the function.
- **print()**
    - This statement tells the computer to display the content between the parantheses.
    - This line is indented in order to show that it is a command in the "hello" function.
- **"Hello World!"**
    - The double quotes indicate that the data type is a [string][string-def].
    - Alternatively, single quotes could have been used for the same result: 'Hello World!'.
    - Using single versus double quotes is a matter of preference, but it is important to stay consistent to avoid confusion or errors in your program.
- **hello()** 
    - This statement _calls_ the hello function.
    - Typing the funciton name followed by () is the syntax to execute the function.
    - Notice that this line is _not_ indented - this indicates that the "hello" function is complete and that this command is not part of the function.
    - Try running your program without this statement and see what happens - nothing! This is because you have created a function called hello, and defined what this function will do, but you have not yet told the computer to execute the function.
    

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
- Line 1 creates a function called "printing"
- Line 2 prints a string "hello"
- Line 3 prints a string "5"
- Line 4 prints a string "True"
- Line 5 prints an [int][int-def] 5
- Line 6 prints a boolean or [bool][bool-def] True
- Line 7 calls "printing"

**Output:**

    hello
    5
    True
    5
    True

These different data types will be useful later on, but you can read more on the [data types][data-types] section.

<!-- Identifiers -->
[bool-def]: https://github.com/melaniesifen/learnpython/definitions "A boolean expression evaluates to either True or False."
[data-types]: https://github.com/melaniesifen/learnpython/datatypes
[int-def]: https://github.com/melaniesifen/learnpython/definitions "An integer or whole number."
[string-def]: https://github.com/melaniesifen/learnpython/definitions "An immutable data type consisting of a sequence of characters."

