# Code 301 - Class 3 - Reading Notes

## React Docs - Forms

**1. What is a ‘Controlled Component’?**

- They are components where the form data is handled by the component's state.

**2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

- We should update the state with their responses as soon as they enter them. This is because handleChange will run with every single keystroke the user types to update the React state.

**3. How do we target what the user is entering if we have an event handler on an input field?**

- We use setState and target the value inside of the function handling the event.

## The Conditional (Ternary) Operator Explained

**1. Why would we use a ternary operator?**

- It allows us to write shorter, cleaner, and more efficient code.

**2. Rewrite the following statement using a ternary statement.**

- x===y ? 'true' : 'false';

References:

1. [React.js Forms](https://reactjs.org/docs/forms.html)

2. [JavaScript — The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

