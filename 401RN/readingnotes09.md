# Readings: Game of Greed 4

## [Dunder Methods](https://dbader.org/blog/python-dunder-methods)

### WHAT is Dunder Methods

- Dunder methods let you emulate the behavior of built-in types.
   You need to understand loop before getting this.
  This is a good example, to get the length of a string you can call len('string').
- I need a constructor which in Python is the **init** dunder:

```python
class Account:
    """A simple account class"""

    def __init__(self, owner, amount=0):
        """
        This is the constructor that lets us create
        objects from this class
        """
        self.owner = owner
        self.amount = amount
        self._transactions = []

```

With DM I can unlock these features

- Initialization of new objects
- Object representation
- Enable iteration
- Operator overloading (comparison)
- Operator overloading (addition)
- Method invocation
- Context manager support (with statement)

## [Statistics - Probability](https://www.dataquest.io/blog/basic-statistics-in-python-probability/)

### WHAT is probability

It is just chance of an event/ something happening.
In a coin toss the only events that can happen are:

- Flipping a heads
- Flipping a tails

  ▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽ Down below is a example of this happing ▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽▽

```python
import random
def coin_trial():
heads = 0
for i in range(100):
if random.random() <= 0.5:
heads +=1
return headsdef simulate(n):
trials = [] for i in range(n):
trials.append(coin_trial())
return(sum(trials)/n)
simulate(10)
>>> 5.4
simulate(100)
>>> 4.83
simulate(1000)
>>> 5.055
simulate(1000000)
>>> 4.999781
```

### Videos

[Intro to Statistics](https://www.youtube.com/watch?v=MdHtK7CWpCQ)
[AI Guru makes $238,800 with misleading paid course. doesn’t credit developers](https://www.youtube.com/watch?v=7jmBE4yPrOs)
