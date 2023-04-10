## React Docs - Thinking in React

- What is the single responsibility principle and how does it apply to components? [SOLID Definition – the SOLID Principles of Object-Oriented Design Explained](https://www.freecodecamp.org/news/solid-principles-single-responsibility-principle-explained/)

The idea behind the SRP is that every class, module, or function in a program should have one responsibility/purpose in a program. As a commonly used definition, "every class should have only one reason to change". The class above violates the single responsibility principle.

- What does it mean to build a ‘static’ version of your application?

Building a static version of your application means creating a version of your UI that does not depend on user input or dynamic data. This can be done using mock data or static data that you hardcode into your component. The goal of this step is to identify the different components that make up your UI and how they relate to each other.

- Once you have a static application, what do you need to add?

Once you have a static version of your application, you need to add interactivity by introducing state and event handlers. This involves identifying which components need to manage state and which components can be stateless, and using props to pass data between them.

- What are the three questions you can ask to determine if something is state? [Identify the Minimal Complete Representation of the UI State](https://thamaliwijewardhana.wordpress.com/2019/05/07implementing-a-data-visualizer-using-react-js-and-d3/)


Is the data passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

- How can you identify where state needs to live?

You can identify where state needs to live by identifying which component or components need to be able to change the data and which ones only need to display the data. In general, state should live in the lowest common ancestor of the components that need to access it. This ensures that the state is updated correctly and consistently across all the components that depend on it.

## Higher-Order Functions

- What is a “higher-order function”?

A "higher-order function" is a function that either takes another function as an argument or returns a function as its result. In other words, it's a function that acts on other functions.

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

In the greaterThan function as defined in the reading, line 2 is defining and returning an inner function that takes one argument (number m) and checks if m is greater than n, which was defined as the argument of the outer function. This inner function is then returned as the result of the outer function.

- Explain how either map or reduce operates, with regards to higher-order functions.

Both map and reduce are higher-order functions in JavaScript. Map is used to transform an array into a new array by applying a function to each element of the original array. The function passed to map takes one argument (the current element of the array) and returns a new value that will be added to the new array. Reducereduce is used to reduce an array to a single value by applying a function to each element of the array and accumulating the results. The function passed to reduce takes two arguments (an accumulator and the current element of the array) and returns a new accumulator that will be passed to the next iteration.

## Things I want to know more about
