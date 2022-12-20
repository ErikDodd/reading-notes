# Code 401 - Class 2 - Reading Notes

## In Tests we Trust - TDD with Python

This topic is important because Test Driven Development is critical to writing better code. It will help you test that your code is behaving in the way you expect, or alternatively, it will help you fix/improve your code.

- Unit tests: pieces of code that test the input/output and the behavior of the code you've written
- Test Driven Development (TDD): A strategy used that helps you think and write tests first.
- Be sure to be descriptive about test names
- Test names should be based off the module name (ex. module = gender.py, test = test_gender.py)- AAA: Arrange, Act and Assert.
- Arrange: you need to organize the data needed to execute that piece of code (input)
- Act: here you will execute the code being tested (exercise the behaviour)
- Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

## If Name Equals Main

This is an important topic because it talks about how the Python interpreter works prior to executing code and what happens with special name variable depending on what the source file is.

- Before a code is executed, the Python interpreter reads the source file in order to define a few special variables.
- If the source file is the main program, the python interpreter will set the special_name_variable to be "__main__"
- If the source file is being imported from elsewhere, the python interpreter will set assign it to the name of module 
- Module: A file that has Python definitions and statements, the file name is the module name with .py placed at the end of it
- To execute the module: python script.py (or whatever the module name is)

## Recursion

This is an important topic because Recursion is a useful way to problem solve in coding and can help you improve your code, improve readability, and also make code easier to write.

- Recursion: Occurs when a function calls itself
- Very important to establish a case for when to stop the recursion
- Recursion can help with reducing the length of our code, improve readability, and make code easier to write
- Recursion uses more memory since each recursive call is added to the stack and kept there until the recursion is finished
- Stack Overflow: Occurs when the base case is undefined or not reached, and recursive continues
- There is direct and indirect recursion
- Direct recursion: A function calls itself
- Indirect recursion: A function calls another function either directly or indirectly
- Recursion is used with functions, iteration is used with loops

## References

1. [In Tests we Trust - TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)

2. [If Name Equals Main](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

3. [Introduction to Recursion – Data Structure and Algorithm Tutorials](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)
