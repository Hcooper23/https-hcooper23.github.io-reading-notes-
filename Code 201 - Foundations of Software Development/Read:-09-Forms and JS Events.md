# Today's reading has allowed me to see and understand the structure of a webpage and allowed me to get a comprehension of different ways to add forms, and styles, and how to undertake the task of breaking down a new idea or concept to add to my tool belt for coding. 

## Your first Web Form How To Structure A Web Form
**Why are forms so important in web development?** [Learn Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface.

**When designing a form, what are some key things to keep in mind when it comes to user experience?** [10 Rules](https://uxplanet.org/10-rules-for-efficient-form-design-e13dc1fb0e03)

- Order the Form Logically and Only Ask What’s Required
- Present Fields in a Single Column Layout
- Minimize the Number of Input Fields and User Typing Effort
- Match Fields to the Size of the Input
- Place Labels Above the Corresponding Input Fields
- Use Forgiving Formatting
- Don’t Use Placeholder Text as Input Field Label
- Distinguish Optional And Required Fields
- Avoid ‘Reset’ Button
- Provide Highly Visible and Specific Error Messages

**List 5 form elements and explain their importance.** [Elements](https://www.w3schools.com/html/html_form_elements.asp)

- Fieldset: makes a group of widgets that will share the same purpose.
- Legend: this describes the purpose of text content when it is inside of a fieldset.
- Label: labels an HTML form widget, the most important element if you want to build an accessible form.
- Button: Makes a button clickable.
- Datalist: Specifies a list of pre-defined options for an <input> element.
Users will see a drop-down list of the pre-defined options as they input data.
The list attribute of the <input> element, must refer to the id attribute of the <datalist> element.

## Introduction To Events

**How would you describe events to a non-technical friend?**

JavaScript has events that provide a dynamic interface to web pages. These events are related to elements in the Document Object Model (DOM). Additionally, these events use bubble propagation by default, i.e. propagating the DOM up from child nodes to parent nodes. We can bind events either as inline or in an external script.

So think of an event as two objects such as a seed which we refer to as the child and the tomato being the parents, you can’t have one without the other and then you will see that the child is affected by the parent in the genetics. Therefor if you adjust the genetics of the child (seed) you will alter the parent.

**When using the addEventListener() method, what 2 arguments will you need to provide?** [Event Listner](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)

The method addEventListener() works by adding a function, or an object that implements EventListener, to the list of event listeners for the specified event type on the EventTarget on which it's called. If the function or object is already in the list of event listeners for this target, the function or object is not added a second time.

**Describe the event object. Why is the target within the event object useful?**

This is a property of the event object that refers to the element that triggered the event. This can be useful for identifying which element an event originated from, which is often necessary when working with event listeners.

**What is the difference between event bubbling and event capturing?**

Capture phase: The event moves down to the element. Target phase: The event reaches the target element. Bubbling phase: The event bubbles up from the element.

## Things I want to know more about
