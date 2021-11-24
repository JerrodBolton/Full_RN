# Readings: Game of Greed 3

## [List Comprehensions](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

Are powerful and concise method for creating lists in Python that becomes essential the more I work with lists, and lists of lists.

```python

# construct a basic list using range() and list comprehensions
# syntax
# [ expression for item in list ]
digits = [x for x in range(10)]

print(digits)
```

- first ‘x’ is our expression; it doesn’t do anything b/c we’re simply recording the number.
- we’re using the range() method to generate a list of numbers.

-Output

```python
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```

```python
# create a list using a for loop
squares = []

for x in range(10):
    # raise x to the power of 2
    squares.append(x**2)

print(squares)
```

This is b/c it is putting the numbers in the array/list "squares"

-Output

```python
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

This is just a good example of how to work with a string

```python
# a list of the names of popular authors
authors = ["Ernest Hemingway","Langston Hughes","Frank Herbert","Toni Morrison",
    "Emily Dickson","Stephen King"]

# create an acronym from the first letter of the author's names
letters = [ name[0] for name in authors ]
print(letters)
```

Output

```python
['E', 'L', 'F', 'T', 'E', 'S']
```

- In the end, this is just giving a good Explanation over a lot of all the methods and concepts we have used

## [Video](https://www.pythonpodcast.com/pysnooper-python-debugging-episode-241/)
