# Code 401 - Class 8 - Reading Notes

## List Comprehension

- List Comprehension is a more concise way method for dealing with lists than loops or nested for loops.
- List comprehension includes the expression, the object that expression will do something to and an iterable list of objects to build a new list from
- Essentially it is performing an expression on each item in the list
- Conditional statements (aka filters) can be applied in LC and provide for a higher level of accuracy
- You can do list comprehension in one line. See below for example:
- squares = [ x**2 for x in range(10)]
- The first x = expression, the second x = each item in the list created by the range method
- Example of a filter: even = [x for x in range (1,20) if x % 2
- List comprehension can be used in lots of ways like you can capitalize letters in a list, print out the first letter in a string, print out each letter in a string, etc.
- You can read files in python using LC

## References

1. [List Comprehensions in Python
](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)
2. [Debugging Python Projects With PySnooper - Episode 241
](https://www.pythonpodcast.com/pysnooper-python-debugging-episode-241/)