# Code 401 - Class 42A - Reading Notes

## Dunder Methods:

- Predefined set of methods used to add different functionality to your classes
- __init__ and __str__ are two of the most common examples I've seen around before reading this
-__len__ is very similar to len( ), which lets you assign the length of class
- __getitem__ is a method that does the Python slicing syntax
- The whole element design is called Python Data Modeling and allows developers to do a lot of really cool stuff like iteration, attribute access, etc.
- __init__ is needed when creating a class almost right away
- Object representation is done with both __str__ and __repr__ but the former is for regular users of the app/website and the latter is for developers
- Iteration can be done with __len__, __getitem__, __reversed__,
- Dunder Methods allow you to make a class iterable
- Previously getting type error when you try to use len(ACC) or for t in ACC: or ACC[1], but we can use __len__ and __getItem__ to fix this 


## Iterators: 

- An Iterator like most things in Python is an object 
- With an iterator it produces a sequence of values one at a time kind of like a conveyer belt
- This occurs with next() being called
- __iter__() method returns the iterator object
- __next__ method returns the next value in the sequence until you raise a StopIteration exception
- yield keyword produces a sequence of values one at a time
- iterators are memory-efficient which makes them really great for using large data sets
- Examples of Python built-in iterators range(), enumerate(), zip()


## Generators:

- Generator is a special function that returns an iterator object
- Generators use the keyword 'yield' which helps them produce a sequence of values one at a time instead of giving you all the values at once
- Generators can be more memory efficient than lists/tuples when working with larger data sets
- You can even iterate over a for loop using a generator by calling the next() function and using the StopIteration exception
- Python has built-in generators like range(), map(), and filter()
- Generators are great for complex data sets because they provide developers with lots of flexibility


## References

1. [Python Iterators: A Step-By-Step Introduction](https://dbader.org/blog/python-iterators)
2. [Enriching Your Python Classes With Dunder (Magic, Special) Methods](https://dbader.org/blog/python-dunder-methods)
3. [What Are Python Generators?](https://dbader.org/blog/python-generators)