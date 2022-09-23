# Code 301 - Class 5 - Reading Notes

## React Docs - Thinking in React

**1. What is the single responsibility principle and how does it apply to components?**

- It is the idea that a component should only be doing one thing. Ideally you don't want your component to be doing too many things, if it does, it is better to break it down to subcomponents.

**2. What does it mean to build a ‘static’ version of your application?**

- It means to build a version of the application that renders the UI but doesn't have any interactivity. It has no state.

**3. Once you have a static application, what do you need to add?**

- You want to add state to make your website or application interactive.

**4. What are the three questions you can ask to determine if something is state?**

- Is it passed in from a parent using props? If so, it probably doesn't have state.
- Does it remain unchanged? If so, it probably doesn't have state.
- Can you compute it based on any other state or props  in your component? If so, it probably doesn't have state.

**5. How can you identify where state needs to live?**

- Identify ever component that renders something based on that state.
- Find a common owner component above all other components that needs state.
- Either the common owner component or another component higher up in the hierarchy should own state.
- If you can't find a common owner component to own state, make a new component responsible for holding state and make sure it is above the common owner component in the hierarchy.

## Higher-Order Functions

**1. What is a “higher-order function”?**

- It is a function that operates on other function by either taking them as arguments or returning them.

**2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

- It is checking to see if a number is greater than another number, and it will return either true or false.

**3. Explain how either map or reduce operates, with regards to higher-order functions.**

- The map methods will transform the data by applying a function to all the elements and it will build a new array from the new returned values.

References: 

1. [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

2. [Eloquent Javascript](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
