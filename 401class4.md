# Code 401 - Class 4 - Reading Notes

## Classes and Objects

This is important because objects are a cornerstone of programming. Using objects and classes is a great way to give similar functionality and create instances of something.

- Objects: Encapsulation of variables and functions in a single entity
- Classes: templates used for creating objects
- Use dot notation to access a variable in a class (ex. myobject.variable)
- You can change the variable in an object from a class
- To access the function inside an object use object.my_function()
- __init__: A special function that is called when a class is initiated.


## Thinking Recursively in Python
This topic is important because thinking recursively can help you break down more complex problems into smaller more solvable ones. Recursion is a helpful way to write elegant code and solve a problem in a more simple manner.

- Thinking recursively is breaking down problems into smaller more solvable problems that are easier to solve.
- Recursive function: a function that is defined in terms of itself via self-referential expressions.
- Recursive functions all have a base case and recursive case.
- To account for state with recursion, you need to either thread the state through the recursive call or keep the state in a global variable
- To go the global variable route, you need to add the keyword global in front of the variable inside the recursive function
- A data structure is recursive if it can be defined in terms of a smaller version of itself. Ex is a list, set, tree, dictionary, etc

## Pytest Fixtures and Coverage

Fixtures are important for more complex testing. Using fixtures and coverage will help make testing easier and improve the quality of your code.

- Test Suite: several tests that each check a different path through your code
- Fixtures: used for more complex testing where you want certain objects available to all your tests, or it involves a network or file system.
- Define a fixture using pytest.fixture (When using pytest) and a function definition
- Fixtures are used differently from global variables
- Scope can be passed as a parameter as well
- It include code coverage using the package called pytest-cov on PyPI
- You can add a fixture as a parameter and then access that fixture by name within the function
- Fixtures are functions under the hood, meaning that can make decisions and do calculations


## References

1. [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)

2. [Thinking Recursively in Python](https://realpython.com/python-thinking-recursively/)

3. [Python Testing with pytest: Fixtures and Coverage](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)
