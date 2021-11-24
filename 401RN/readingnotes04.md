# Readings: Topic

## [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)

 We're are going to start by talking about objects what they are and how they work

- What is are objects?
      - Objects are multiple variables and functions into a single entity.  
- What do they do?
       - Objects get their variables and functions from classes.
Now let's talk about classes

- What are classes?
      - A template or blueprint to create your objects.

## [Thinking Recursively](https://realpython.com/python-thinking-recursively/)

- What is thinking Recursively
  - This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result
- What I'm thinking right now is that this function is somewhat like a loop b/c it's taking a condition and is going to continue until the condition is met.. 
- This is talking about state and how it matter in all of this. 

``` python

# Global mutable state
current_number = 1
accumulated_sum = 0

def sum_recursive():
    global current_number #  is  a Global variable  means that  it's  outside  the function 
    global accumulated_sum
    # Base case
    if current_number == 11:
        return accumulated_sum
    # Recursive case
    else:
        accumulated_sum = accumulated_sum + current_number
        current_number = current_number + 1
        return sum_recursive()


```
