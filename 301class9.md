# Code 301 - Class 9 - Reading Notes

## Functional Programming Concepts

**1. What is functional programming?**

- Functional programming is a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

**2. What is a pure function and how do we know if something is a pure function?**

- It is a function that returns the same result if given the same arguments (deterministic) and does not cause any observable side effects. It is pure if you are accessing parameters passed in the function without using an external object. It also can't read external files in order to be a considered a pure function.

**3. What are the benefits of a pure function?**

- The code becomes easier to test because we can expect the same results given the same arguments.

**4. What is immutability?**

- immutability is when the data doesn't change and state cannot change after the data is created.

**5. What is Referential transparency?**

- Referential transparency is if a function will consistently return the same results for the same input.

## Node.js 

**1. What is a module?**

- A module is when you split your code up into different sections that logically make sense. You create different modules for different bits of code. It is essentially another javascript file.

**2. What does the word ‘require’ do?**

- If you want to use a function in a different module than the one it was created in, you use require.

**3. How do we bring another module into the file the we are working in?**

- You would do module.exports property in the module you first created the function in. For example module.exports = counter;.

**4. What do we have to do to make a module available?**

- Then you need to add a variable that refers to that module in the other module which would be var counter = require('./count');.

## References

1. [Concepts of Functional Programming in Javascript](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

2. [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k&ab_channel=TheNetNinja)
