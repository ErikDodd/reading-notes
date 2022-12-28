# Code 401 - Class 6 - Reading Notes

## How to Use Random Module in Python

- Random module: Helps you generate random numbers
- Used for picking random element from a list, flip a coin, creating random strings for passwords
- randint(): random integer function produces a random integer between a range of two values
- random(): Used to generate random numbers between 0 and 1. Returns a floating point between 0 and 1.
- choice(): Used to randomly select an element from a list,set, tuple, dictionary, etc. Takes in an objection as the input, and the output is a random element
- shuffle(): Used to shuffle the elements in a list.  Takes in a list as an input and then shuffles the list into a completely random order
- randrange(): Used to select a random element that is found in a range. Takes in 3 numbers, which are start, stop and step as arguments. Returns randomly selected element

## What is Risk Analysis in Software Testing

- Risk Analysis: the process of identifying risks in applications or software and prioritizing them to test.
- Risk Analysis is used to highlight and call out potential areas where problems can arise
- Examples of risks: use of new hardware, use of new tech, use of new automation tool, the sequence of code, availability of test resources for the application
- Risk Magnitude indicators are high, medium, and low. High means the company might face a loss, medium is tolerable but not desirable, low is tolerable.
- The perspective of Risk Assessment: Effect, Cause, Likelihood

## Test Coverage

- Test Code (Aka Code Coverage): Tool for finding untested parts of a codebase
- One problem with high coverage numbers is that people will reach them with low-quality testing
- The upper 80s and 90s is a quality coverage percentage assuming you are testing thoughtfully and not applying low-quality tests
- Be suspicious of 100% testing coverage, they are most likely just trying to make coverage numbers that sound amazing

## Big O
- Big O (Aka Algorithmic Efficiency): Equation that describes how the runtime will scale when considering time and space.
- Transferring data over the internet takes longer as the amount of data you transfer increases
- O(1): Constant time. The time is constant with respect to the size of input. Ex. Pigeon with USB sticks
- O(n): Linear time. The time scales linearly depending on the amount of input. Ex. Slow internet from the story
- Function that walks through array and sees if it contains a specific value = O(n). N would be the size of the array
- Don't have to use N for Big O, you can use other letters like a = area
- - Rule 1: If you have two steps in the algorithm, you add up those steps. O(a), O(b) = O (a+b)
- Rule 2: Drop constants

## References

1. [How to use the Random Module in Python](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)
2. [What is Risk Analysis in Software Testing and how to perform it?](https://www.edureka.co/blog/risk-analysis-in-software-testing/)
3.  [Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)
4.  [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw&ab_channel=HackerRank)
