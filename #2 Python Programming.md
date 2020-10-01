# #2 Python Tutorial
![enter image description here](https://camo.githubusercontent.com/8dbae7dcd9e42eeccc8991ad901108adce95713a/68747470733a2f2f7777772e707974686f6e2e6f72672f7374617469632f636f6d6d756e6974795f6c6f676f732f707974686f6e2d6c6f676f2d67656e657269632e737667)

The topics covered in this tutorial - 

- Data Types
- Print Statements
- Comments

## Data Types
In Python there are many data types, but the two basic data types are -

- **Strings**
	Strings are textual data types and enclosed by doubles 			quotes `" "` or single quotes `' '`.
- **Integers and Floats**
	Integers and Floats are numeric data types.
	Floats contain decimal values.
	**Ex. -  23.7, 4.23, 156.0**
	Integers does not contain decimal values.
	**Ex. -  34, 904, 2**
### More Data Types - 
There are many data types, all of them are shown below -
|Categories|Data Types|
|--|--|
|Text|`str`  |
|Numeric|`int`, `float`, `complex` |
|Sequence|`list`, `tuple`, `range` |
|Mapping| `dict`|
|Set| `set`, `frozenset`|
|Boolean| `bool`|
|Binary| `bytes`, `bytearray`, `memoryview`|

	
## Print Statements

The print statement prints out the value specified in the parentheses `()`.
#### Syntax - 
```python
print()
```
#### Print Strings - 
```python
print("Hello World!!")
print("How do you do?")
```
**Output** - 
```
Hello World!!
How do you do?
```

#### Print Numbers - 
```python
print(23)
print(23.45)
```

**Output** - 
```
23
23.45
```
## Comments
Comments are lines of code which the compiler completely ignores.
### Writing Comments -
In Python, comments are shown with the hash symbol `#`.

#### For Example - 
```python
# This program prints the value provided in the double quotes.
print("Let's learn Python Comments")
```

**Output** -
```
Let's learn Python Comments
```

You see the compiler only display the values inside the print statements and ignores the line with the `#` symbol.

### Multi-Line Comments
Unlike other programming languages like Javascript, **Python doesn't have a syntax for multiline comments.**
So, two write multiline comments there are two methods. 

- Use a hash symbol `#` in every line.
**For Example -**  
```python
# This 
# is 
# a 
# multiline 
# comment.
```
- Otherwise, we can write the comments inside three double quotes `""" """` or three single quotes `''' '''`.
**For Example -**
```python
"""
This 
is 
a 
multiline 
comment.
"""

'''
This 
is 
also
a 
multiline 
comment.
'''
```

### Uses of Comments
- Comments are used to help others read and understand your code easily.
- We can prevent the code from running with the help of comments.
