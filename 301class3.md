# Code 301 - Class 3 - Reading Notes

## React Docs - lists and keys

**1. What does .map() return?**

- It returns a new array that has been altered as a result of the call back function

**2. If I want to loop through an array and display each value in JSX, how do I do that in React?**

- Using the curly brackets

**3. Each list item needs a unique ____.**

- key

**4. What is the purpose of a key?**

- Their purpose is to identify which items have been altered, either changed, added, or removed

## The Spread Operator

**1. What is the spread operator?**

- It is used to add items into an array, combining arrays or objects, and spreading an array into a function's arguments. Its syntax is three dots (...)

**2. List 4 things that the spread operator can do.**

- It can copy an array, using math functions, adding an item to a list, adding to state in React

**3. Give an example of using the spread operator to combine two arrays.**

- You can create two separate arrays filled with different emojis using the spread operator, define them as variables 'hello' and 'world' and then do a variable called helloWorld where you use the spread operator inside curly brackets to include {...hello,...world} and then console.log(helloWorld) to combine them.

**4. Give an example of using the spread operator to add a new item to an array.**

- You can create create two separate variables called 'fewFruit' and 'fewMoreFruit' with emojis in them. The second variable contains two emojis and then uses the spread operate and fewFruit like '...fewfruit'. When you console.log(fewMoreFruit) it will add the emojis in fewFruit to fewMoreFruit to have a completed list.

**5. Give an example of using the spread operator to combine two objects into one.**

- You can create 4 variables with emojis called objectOne, objectTwo, objectThree, and objectFour. ObjectThree uses the spread operator to combine objectOne and objectTwo with objectThree. For objectFour combines objectOne, and objectTwo and the last part of object 4 with a console.log and then repeats it 5 times. You than call objectFour.laugh() and it produces 5 laughing emojis.

## How to Pass Functions Between Components

**1. In the video, what is the first step that the developer does to pass functions between components?**

- Create the function wherever the state is that you want to change.

**2. In your own words, what does the increment function do?**

- it adds one each time something happens.

**3. How can you pass a method from a parent component into a child component?**

**4. How does the child component invoke a method that was passed to it from a parent component?** 
