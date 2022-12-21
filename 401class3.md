# Code 401 - Class 3 - Reading Notes

## Read & Write Files in Python

This ireading relates to us because it teaches what files are, how to open and close them, read and write files, and other techniques to utilize when working with files.

- File: a contiguous set of bytes used to store data
- Can be a text file or even a program executable
- Files are composed of a header, data, and EOF (End of File)
- File Path: String that contains the location of a file. Broken into folder path, file name, extension
- Encoding: Is a translation from byte data into characters that can be read by humans
- To open a file: open ( ) or ex file  = open ('dog_breeds.txt')
- To close a file: use a try block that starts with try: and ends with finally: reader.close( ) or using a with statement
- Using with statements is recommended
- File object: “an object exposing a file-oriented API (with methods such as read() or write()) to an underlying resource.”
- Text files are the most common type of file you will run into
- Raw File Types: building blocks for binary text streams
- To read a file: .read(size = -1), .read(size = 1), .readlines( )
- To write a file: .write(string), .writelines(seq)
- __file__ : the pathname of a file where the module was loaded

## Python Exceptions: An Introduction

This is important because it helps us with error handling in Python and how to write exceptions to errors and more.

- Python program terminates as soon it runs into an error (syntax or exception)
- Syntax error: when the parser finds an incorrect statement
- Exception error: when correct code results in an error
- Assert: Assert a condition is met, if false, you receive an AssertionError exception
- Try and Except block: used for catching and handling exceptions
- Try clause are executed until the first exception is reached
- Except clause deals with how the program handles exceptions
- You can have multiple exceptions and have the program handle them differently
- Else: can be used to tell a program to run a specific block of code only if there are no exceptions
- Finally: Allows you to run a type of action after code is executed

## References

1. [Reading and Writing Files in Python (Guide)](https://realpython.com/read-write-files-python/)

2. [Python Exceptions: An Introduction](https://realpython.com/python-exceptions/)
