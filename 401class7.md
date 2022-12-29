# Code 401 - Class 6 - Reading Notes

## Python Scope

- LEGB rule: Local Enclosing Global and Built-in Scope - Scope concepts as it relates to Python
- LEGB rule refers to the order to examine scope in Python
- Scope: how variables and names can be seen or accessed inside your program. Visibility is the keyword here
- Global Scope and Local Scope are the two most common types
- Global Scope: Can be accessed/available to all of your code
- Local Scope: Only available or visible to code within the scope
- When you start a python program you are in global python scope.
- Python turns program's main script into a __main__ module
- dir() : inspect the names located in you main global scope
- Only one global python scope per program execution and it stays this way until the program terminates and the names are forgotten
- Use global statement to define global names inside a function
- When assigning value in python, you either create a new name or update an existing name
- nonlocal names can be accessed from inner functions
- nonlocal names can't be assigned or updated
- modifying nonlocal names requires a nonlocal statement and this statement consists of nonlocal keywords
- Can't use nonlocal outside of a nested or enclosed function
- Closures: special use case of the enclosing Python Scope

## References

1. [Python Scope & the LEGB Rule: Resolving Names in Your Code](https://realpython.com/python-scope-legb-rule/)
2. [Don't Be Confused By BIG O Notation Anymore](https://www.youtube.com/watch?v=5Uqawfl0VHQ