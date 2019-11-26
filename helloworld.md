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
    - This is the content that will be displayed in the output.
- **hello()** 
    - This statement _calls_ or executes the hello function.
    - Typing the funciton name followed by () is the syntax to call the function.
    - Notice that this line is _not_ indented - this indicates that the "hello" function is complete and that this command is not part of the function.
    - Try running your program without the hello() statement at the end and see what happens - nothing! This is because you have created a function called hello, and defined that the function will print the statement "Hello World!", but you have not yet told the computer to execute the function. Hence, we need the last line to call the function.
    


<!-- Identifiers -->
[bool-def]: https://github.com/melaniesifen/learnpython/definitions "A boolean expression evaluates to either True or False."
[data-types]: https://github.com/melaniesifen/learnpython/datatypes
[int-def]: https://github.com/melaniesifen/learnpython/definitions "An integer or whole number."
[string-def]: https://github.com/melaniesifen/learnpython/definitions "An immutable data type consisting of a sequence of characters."

