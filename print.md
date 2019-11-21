## Print

In the [Hello World][hello-world-page] program, we introduced the print statment. This command allows you to display contents on the screen. Let's look at some examples:

```python
print("hello")
print("5")
print("True")
print(5)
print(True)
```

- Line 1 prints a string "hello"
- Line 2 prints a string "5"
- Line 3 prints a string "True"
- Line 4 prints an [int][int-def] 5
- Line 5 prints a boolean or [bool][bool-def] True
These different data types will be discussed further in the [data types][data-types] section.

**Output:**

    hello
    5
    True
    5
    True

The print() statement can print multiple objects on separate lines or on the same line separated by a space (by default) or some other character.
Some examples:

```python
print("this is a string.")
print("this is another string on a separate line.")
```
Here we use two print statements to display these strings on separate lines.

**Output:**
    
    this is a string.
    this is another string on a separate line.

We can achieve the same result by putting both of these strings into one print() statement, and separating them with a [newline character][newline-def] \n.

```python
print("this is a string.", "this is another string on a separate line.", sep = "\n")
```

**Output:**

    this is a string.
    this is another string on a separate line.

If we put these strings together in a print statement without the newline character, they will be printed on the same line separated by a space by default, or by another specified character using sep = " ".

```python
print("this is a string.", "this is another string on the same line.")
print("this is a string.", "this is another string separated by an asterisk.", sep = "*")
```

**Output:**

    this is a string. this is another string on the same line.
    this is a string.*this is another string separated by an asterisk.

Finally, you can end the print statement with a specifed character using end = " ". This will be more useful when using [loops][loops]

```python
print("this is a string.", "this is another string.", end = "&")
print("this is a string.", 5, True, "this is another string.", sep = " yellow ", end = "blue")
```

**Output:**
    
    this is a string. this is another string.&
    this is a string. yellow 5 yellow True yellow this is another string.blue

Also take note that the whitespace or blank space between the objects in the print() statement does not affect the output.

```python
print(1, 2, 3, 4, 5)
print(1,      2,     3,  4,   5)
print(     1, 2, "hello"   , True    )
print(     "hello"     )
print("     hello  ")
```

**Output:**
    
    1 2 3 4 5
    1 2 3 4 5
    1 2 hello True
         hello  

In the last print statement, the output is affected because the whitespace is inside of the string that is being printed, so the whitespace gets printed along with the letters.



<!-- Identifiers -->
[hello-world-page]: https://github.com/melaniesifen/learnpython/blob/master/helloworld.md
[newline-def]: https://github.com/melaniesifen/learnpython/blob/master/helloworld.md "\n starts a new line"
[loops]: https://github.com/melaniesifen/learnpython/blob/master/helloworld.md