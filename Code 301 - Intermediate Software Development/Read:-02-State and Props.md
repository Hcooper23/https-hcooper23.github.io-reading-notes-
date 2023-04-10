## React lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render

- What is the very first thing to happen in the lifecycle of React?

Constructor method

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, Render, ComponentDidMount, React Updates, ComponentWillUnmount

- What does componentDidMount do?

ComponentDidMount is a lifecycle method that is called immediately after a component is mounted. It is primarily used to perform any DOM manipulations or data fetching operations that are needed for the component.

## React State Vs Props

- What types of things can you pass in the props?

You can pass all kinds of things as props in React, including strings, numbers, booleans, arrays, objects, and even functions. Essentially, any type of data that can be passed as a parameter can be passed as a prop.

- What is the big difference between props and state?

The main difference between props and state in React is that props are passed from parent to child components, while state is managed within the component itself.itself. Props are read-only and should not be changed by the child component, whereas the state can be changed using setState().

- When do we re-render our application?

React will re-render the application when there is a change in either props or state. In other words, any time the setState() method is called or new props are passed to a component, React will re-render the component and its child components as needed.

- What are some examples of things that we could store in state?

Examples of things that can be stored in a state include user input values, the current state of a checkbox or radio button, and any other dynamic information that needs to be tracked and updated as the user interacts with the component or the application. Additionally, you can store information about the loading status of API requests, error messages, or any other data that is fetched dynamically and needs to be displayed in the UI.

## Things I want to know more about
