## Functional Programming Concepts

- What is functional programming? [Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)/ [What is functional programming?](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia

- What is a pure function and how do we know if something is a pure function?

A pure function is a function that always returns the same output given the same input and does not have any side effects. This means that it does not modify any state outside of its own scope, such as changing a global variable or making an API call. We can determine if a function is pure by checking if it meets these criteria.

- What are the benefits of a pure function?

The benefits of pure functions are that they are predictable, easier to reason about, and do not have unintended consequences. Since they always produce the same output given the same input, they can be easily and reliably tested. They also make it easier to reason about the flow of data in a program, since they do not depend on or modify any external state.

- What is immutability?

Immutability refers to the idea that once a value is created, it cannot be changed. In functional programming, it is common to use immutable data structures, meaning that once a data structure is created, it cannot be modified. Instead, any operation on the data structure returns a new, modified copy.

- What is Referential transparency?

Referential transparency means that given the same input, a function will always return the same output, and we can replace a function call with its output without changing the behavior of the program. This makes it easier to reason about the behavior of a program, since we can replace function calls with their outputs and be sure that the program will behave the same way.

## Node JS Tutorial for Beginners #6 - Modules and require()

- What is a module?

In JavaScript, a module is a self-contained piece of code that encapsulates related functionality, such as variables, functions, classes, etc. Modules help organize code and prevent naming conflicts by keeping variables and functions local to the module, making them unavailable outside the module unless explicitly exported.

- What does the word ‘require’ do?

In Node.js, the require() function is used to include modules in a file. The require() function takes the path to the module file as an argument and returns the exported module object.

- How do we bring another module into the file the we are working in?/ What do we have to do to make a module available?

  - module.exports = (insert function name)/(on main file for the count)
  - var (insert function name) = require('./path to js file') Then set a variable to return to the file you want to use it in

## Things I want to know more about
