# Object and Data Structures

## Summary

| Name | Type | Description |
| :--- | :--- | :--- |
| Integers | int | Whole numbers, such as: `3 300 200` |
| Floating point | float | Numbers with a decimal point: `2.3 4.6 100.0` |
| Strings | str | Ordered sequence of characters: `"hello" 'Caleb' "awe" '2020'` |
| Lists | list | Ordered sequence of objects: `[10,"hello",200.3]` |
| Dictionaries | dict | Unordered Key:Value pairs: `{"mykey":"value","name","Caleb"}` |
| Tuples | tup | Ordered immutable sequence of objects: `(10,"hello",200.3)` |
| Sets | set | Unordered collection of unique objects: `{"a","b"}` |
| Booleans | bool | Logical value indicating `True` or `False` |

## Numbers

### Basic math

```python
# Addition
2+1

# Subtraction
2-1

# Multiplication
2*2

# Division
3/2

# Preposition (exponentials)
2 ** 3
```

#### Modulo or "Mod" Operator

```python
## Mod
# Give the remainder of 7/4
7 % 4

# This gives 0 (nothing left over)
50 % 5

# This results in 1, telling us it's odd
23 % 2
```

#### BODMAS

```python
# Result of 105
2 + 10 * 10 + 3

# Result of 156
(2 + 10) * (10 + 3)
```

## Variable Assignment

### Rules for Variable Names

* Names can't start with a number
* There can be no spaces in the name, use `_`instead.
* Can't use any of these symbols: `:'",<>/?|\()!@#$%^&*~-+`
* Best practice \(PEP8\) that names are lowercase.
* Avoid using words that have special meaning in Python like "list" and "str"

### Dynamic Typing

* Python uses **Dynamic Typing**
* You can reassign variables to different data types
* This makes Python very flexible in assigning data types, this is different than other languages that are **"Statically-Typed"**

#### **Example of Dynamic Typing in Python**

```python
# Assigning a var a different data type (eg) from number to list works in Python,
# but not in other languages, as described above
my_cats = 2
my_cats = ["Coco", "Frosty"]
```

#### Example of Static Typing in C++

```cpp
int my_dog = 1;
my_dog = "Sammy"; //results in error - no longer integer
```

### Pros & Cons of Dynamic Typing

* Pros of Dynamic Typing:
  * Very easy to work with
  * Faster development time
* Cons of Dynamic Typing:
  * May result in bugs of unexpected data types!
  * You need to be aware of `type()`

### Assigning Variables

```python
# assign a as 5
a = 5

# take the current value of a,
# add it to itself and assign its new value
a = a + a

# See value is now 10
a

# assign the new value
a = a + a

# See the value is now 20
a

# see that a is an int
type(a)

# assign a a new data type
a = 30.1

# See that a is now a float
type(a)

int = 4
```

#### Example of variable assignment

```python
# Do some math to find your taxes
my_income = 100
tax_rate = 0.1
my_taxes = my_income * tax_rate

# See the value of my taxes
my_taxes
```

## Strings

Strings are sequences of characters, using the syntax of either single quotes or double quotes:

* 'howzit'
* "hello"
* " some stuff written here "



## Print Formatting with Strings

## Lists

## Dictionaries

## Tuples

## Sets and Booleans

## Files



