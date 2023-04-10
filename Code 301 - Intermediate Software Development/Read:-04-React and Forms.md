## React Docs - Forms

- What is a ‘Controlled Component’? [Difference Between Controlled and Uncontrolled Components](https://www.altogic.com/blog/difference-between-controlled-and-uncontrolled-component)

In React, a controlled component is a component that is controlled by React state, while an uncontrolled component is a component that maintains its own internal state. Controlled components receive their current values and update callbacks via props, and the parent component manages the state of the component.

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

We should update the state with the user's responses as soon as they enter them because that way, the state is kept in sync with the user input in real-time, and any changes to the input are immediately reflected in the component's state. This also allows us to perform validation on the input as the user types, and if the input is invalid, we can display an error message or disable the submit button until the input is corrected.

- How do we target what the user is entering if we have an event handler on an input field?

We can target what the user is entering by using the onChange event handler on the input field. The onChange handler is called every time the value of the input field changes, and it receives an event object that contains the updated value of the input field. We can access the updated value of the input field using event.target.value.

## The Conditional (Ternary) Operator Explained

- Why would we use a ternary operator?

We use the ternary operator as a shorthand way of writing simple conditional statements, especially when we need to assign a value or execute a function based on a condition. The ternary operator can make our code more concise and easier to read.

- Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x === y ? console.log(true) : console.log(false);

## Things I want to know more about
