## Variables

The technical definition of a Python **variable** is a reserved memory location to store values. What does this mean? Variables are essentially names that represent an object. The object can be a [string][string-def], [int][int-def], [float][float-def], or any other data type.

Some examples:
```python
x = 5
y = "this is a string"
b = True
```
We can [print][print-page] these variables to see the result.
```python
print(x)
print(y)
print(b)
```

**Output:**

    5
    this is a string
    True

There are a few rules about creating variables:
- Variable names must start with a letter or underscore, followed by any series of numbers, letters, or underscores.
- Variable names cannot start with a number.
- Variable names cannot be a **reserved** word in python.
    - A reserved word, or keyword, has a predefined meaning in the python language.
    - A few examples are "and", "or", "break", "else", and "True". Python has 33 keywords in total. To see them all, run this command in your terminal.
        ```
        $ python3
        >>> from keyword import kwlist
        >>> kwlist
        ```
- Variables are case sensitive, so the variables x and X are different.

When creating variables for a program, it's important to give the variables meaningful names. This is useful not only for the readers of your program, but also for you so that you can easily reread and understand your program later on.

Compare this will the example given above:
```python
my_integer = 5
my_float = 5.0
my_float2 = 5.4
my_string = "this is a string"
bool1 = True
bool2 = False
print(my_integer, my_float, my_float2, my_string, bool1, bool2)
```

**Output:**

    5 5.0 5.4 this is a string True False

In this example, we can clearly see what each variable represents because of the name.

<!-- Identifiers-->
[int-def]: https://github.com/melaniesifen/learnpython/definitions "An integer or whole number."
[float-def]: https://github.com/melaniesifen/learnpython/definitions "Real numbers represented with a decimal."
[print-page]: https://github.com/melaniesifen/learnpython/printstatement.md "print()"
[string-def]: https://github.com/melaniesifen/learnpython/definitions "An immutable data type consisting of a sequence of characters."