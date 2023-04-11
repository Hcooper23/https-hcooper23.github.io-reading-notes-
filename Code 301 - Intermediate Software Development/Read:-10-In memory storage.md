## Understanding the JavaScript Call Stack

- What is a ‘call’? [The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

- How many ‘calls’ can happen at once?

JavaScript is a single-threaded language, which means that only one call can happen at a time.

- What does LIFO mean?

LIFO stands for "last in, first out." It is a method of organizing data in which the most recently added item is the first to be removed.

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function multiply(a, b) {
  return a * b;
}

function square(n) {
  return multiply(n, n);
}

function printSquare(n) {
  const squared = square(n);
  console.log(squared);
}

printSquare(5);

The call stack would look like this:

printSquare(5)
  square(5)
    multiply(5, 5)

- What causes a Stack Overflow?

A stack overflow occurs when the call stack exceeds its maximum size. This happens when a function recursively calls itself without terminating, creating an infinite loop. It can also happen when a function creates too many nested functions, or when there is not enough memory available to handle the call stack.

## JavaScript error messages

- What is a ‘reference error’? [TJavaScript error messages && debugging](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

A 'reference error' in JavaScript occurs when a code attempts to reference a variable that does not exist or is not in scope. For example, if you try to use a variable that has not been declared, you will get a reference error.

console.log(foo) // Uncaught ReferenceError: foo is not defined

- What is a ‘syntax error’?

A 'syntax error' occurs when the code is not written correctly according to the syntax rules of the language. This error can occur when a statement is not properly terminated, or when the code includes an incorrect operator or a misspelled variable name.

JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1

- What is a ‘range error’?

A 'range error' occurs when a code tries to manipulate a number outside of the range of acceptable values. For example, if you try to create an array with a length of -1, you will receive a range error.

var foo= []
foo.length = foo.length -1 // Uncaught RangeError: Invalid array length

- What is a ‘type error’?

A 'type error' occurs when a code tries to perform an operation on a value of the wrong type. For example, if you try to call a method on a string that doesn't exist, you'll get a TypeError.

var foo = {}
foo.bar // undefined
foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined

- What is a breakpoint?

A 'breakpoint' is a point in the code where execution will pause so that the developer can inspect the state of the program. Breakpoints are useful for debugging complex code, as they allow you to examine variables, and the call stack at specific points in the program's execution.

- What does the word ‘debugger’ do in your code?

A 'debugger' is a tool that allows developers to step through code and examine the state of the program at each step. Debuggers allow developers to set breakpoints, step through code, and examine the call stack, making it easier to locate and fix errors in the code.

## Things I want to know more about
