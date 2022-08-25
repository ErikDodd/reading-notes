# Code 201 - Class 9 - Reading Notes

## HTML Forms

**1. Why are forms so important in web development?**

- Forms are one of the most commonly used ways to interact with a user on a website or application. Forms allow you to have the user submit data like their personal information and then the form is sent to a web server for processing and storage.

**2. When designing a form, what are some key things to keep in mind when it comes to user experience?**

- Make sure to keep your form concise and make sure that your form contains questions for gathering the right set of data from the user. Longer forms run a higher risk of frustrating the user and them not completing the form.

**3. List 5 form elements and explain their importance.**

- **Form**: This is the main element that is required to make a form. It defines the form.
- **Label**: This is the element used to create the label for what the user inputs into that particular question. Like 'name' and the user inputs their name.
- **Input**: This is the element that creates the interactive controls for the form. It allows you to specify which type of input can be placed in a particular question like email or text, meaning one accepts only email and the other accepts only text.
- **Text Area**: It is an element that allows you to have users enter multi-line plain text into a question. This comes in handy for allowing the user to leave a comment or a review of something.
- **Button**: This element creates a button and allows the using to submit their data once the form is complete.

## Learn JS - Events

**1. How would you describe events to a non-technical friend?**

- Events are what happens when a user does something on a website like a click a button, then the system alerts you that a button was clicked, so you can trigger a different action on the website. Like if the user clicks a button that triggers them to complete a form or a pop-up box comes up.

**2. When using the addEventListener() method, what 2 arguments will you need to provide?**

- The name of the event you would like to register and the code that comprises the handler function that you want to run after that event happens.

**3. Describe the event object. Why is the target within the event object useful?**

- It is the item that is automatically passed to the event handler that also provides extra features or information to the user. For instance, it can turn a button green when you hover over it. The target is useful because it is a reference that is specific to that interaction, so turning the button green would target the button.

**4. What is the difference between event bubbling and event capturing?**

- It describes how the browser deals with events that are targeted inside of nested elements. Event capture is like when the user clicks a button located inside of a div tag. Event bubbling is when you click the same button but its located inside a body element and a div element. The bubbling captures that the user clicked the button, the div, and the button, inside of just the div like in event capture.
