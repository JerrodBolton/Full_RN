# Readings: Game of Greed 2

## [Python Scope](https://realpython.com/python-scope-legb-rule/)

`NOTE This is a long reading. The portion to make sure you cover is on global and nonlocal keywords. You can skim the rest.`

- What is Python Scope
  It is the LEGB rule ( Local, Enclosing, Global, and Built-in )

The scope of a variable or name defines its visibility throughout your code. In Python, scope is implemented as either a Local, Enclosing, Global, or Built-in scope. Python searches for a Variable using this rule.

This go In depth over...

- Understanding Scope
- Using the LEGB Rule for Python Scope
  - Local (or function) scope `Means that you can only see this is a function`
  - Enclosing (or nonlocal) scope is a special scope that only `exists for nested functions.`
  - Built-in scope is a special Python scope that’s `created or loaded whenever you run a script or open an interactive session.`
- Modifying the Behavior of a Python Scope
- Using Enclosing Scopes as Closures
- Bringing Names to Scope With import
- This is a example

    ```python
            dir()
            ['__annotations__', '__builtins__',..., '__spec__']
            import sys
            dir()
            ['__annotations__', '__builtins__',..., '__spec__', 'sys']
            import os
            dir()
            ['__annotations__', '__builtins__',..., '__spec__', 'os', 'sys']
            from functools import partial
            dir()
            ['__annotations__', '__builtins__',..., '__spec__', 'os', 'partial', 'sys']

    ```

- Discovering Unusual Python Scopes
- Using Scope Related Built-In Functions
  Conclusion

## Videos

[Don’t be CONFUSED by BIG O notation anymore!](https://www.youtube.com/watch?v=5Uqawfl0VHQ)
