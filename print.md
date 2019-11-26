## Print()

In the [Hello World][hello-world-page] program, we introduced the print() statement. This command allows you to display content on the screen. Let's look at some examples:

```python
print("hello")
print("5")
print("True")
print(5)
print(True)
```

**Output:**

    hello
    5
    True
    5
    True

So what is the difference between the "5" and 5 and the "True" and True? In python, we represent different data types in this way. This will be discussed further in the [data types][data-types] section, but for now just know that a [string][definitions] is a sequence of characters inside of either single or double quotes: " " or ' ', an [int][definitions] is a whole number, and a boolean or [bool][definitions] is True or False.

<br>
<br>

The print() statement can print multiple objects on separate lines.

```python
print("this is a string.")
print("this is another string on a separate line.")
print("this is a string.", "this is another string on a separate line.", sep = "\n")
```

**Output:**
    
    this is a string
    this is another string on a separate line.
    this is a string.
    this is another string on a separate line.

First, we use two print statements to display these strings on separate lines. Then we achieve the same result by putting both of these strings into one print() statement, and separating them with a [newline character][newline-def] \n using the sep = " " attribute.

<br>
<br>

The print() statement can also print objects on the same line.

```python
print("this is a string.", "this is another string on the same line.")
print("this is a string.", "this is another string separated by an asterisk.", sep = "*")
```

**Output:**

    this is a string. this is another string on the same line.
    this is a string.*this is another string separated by an asterisk.

<br>
<br>

Finally, you can end the print statement with a specifed character using end = " ". This will be more useful when using [loops][loops]

```python
print("this is a string.", "this is another string.", end = "&")
print("this is a string.", 5, True, "this is another string.", sep = " yellow ", end = "blue")
```

**Output:**
    
    this is a string. this is another string.&
    this is a string. yellow 5 yellow True yellow this is another string.blue

<br>
<br>

Take note that the whitespace or blank space between the objects in the print() statement does not affect the output.

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

In the last print statement, the output includes whitespace because the spaces are inside of the string that is being printed.


<!-- Identifiers -->
[data-types]: https://github.com/melaniesifen/learnpython/blob/master/types.md
[hello-world-page]: https://github.com/melaniesifen/learnpython/blob/master/helloworld.md
[definitions]: https://github.com/melaniesifen/learnpython/blob/master/helloworld.md
[loops]: https://github.com/melaniesifen/learnpython/blob/master/loops.md
[newline-def]: https://github.com/melaniesifen/learnpython/blob/master/helloworld.md "\n starts a new line"
