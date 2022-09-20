# Code 301 - Class 2 - Reading Notes

## React Lifecycle

**1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

- The 'render' happens first.

**2. What is the very first thing to happen in the lifecycle of React?**

- static getDerivedStateFromProps

**3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

- constructor, render, componentDidMount, React Updates, componentWillUnmount

**3. What does componentDidMount do?**

- It allows you to execute react code when the component is already placed in the DOM.

## React State vs. Props

**1. What types of things can you pass in the props?**

- displaying a title and subtitle to the user

**2. What is the big difference between props and state?**

- State is handled in the component and you can update it inside the component. Props are handled outside of the component and must be updated outside of the component.

**3. When do we re-render our application?**

- When you change the state inside of the application, it will re-render that section of your application

**4. What are some examples of things that we could store in state?**

- A counter that needs to be updated. Or inside of a form.
