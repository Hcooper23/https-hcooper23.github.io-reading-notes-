## React Docs - lists and keys

- What does .map() return? [map()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

The map() method returns a new array with the results of calling a provided function on every element in the array.

- If I want to loop through an array and display each value in JSX, how do I do that in React?

const myArray = ["apple", "banana", "orange"];

const myList = myArray.map((item, index) => {
  return <li key={index}>{item}</li>;
});

return <ul>{myList}</ul>;

- Each list item needs a unique ____.

key

- What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed. [Lists and Keys](https://legacy.reactjs.org/docs/lists-and-keys.html)

## The Spread Operator

- What is the spread operator? [Spread Operartor](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

- List 4 things that the spread operator can do. [Spread Operartor](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

  - Copy an array or an object
  - Concatenate arrays
  - Add an item to an array
  - Merge objects

- Give an example of using the spread operator to combine two arrays.

const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combinedArray = [...arr1, ...arr2];

console.log(combinedArray); // [1, 2, 3, 4, 5, 6]

- Give an example of using the spread operator to add a new item to an array.

const myArray = [1, 2, 3];

const newArray = [...myArray, 4];

console.log(newArray); // [1, 2, 3, 4]

- Give an example of using the spread operator to combine two objects into one.

const obj1 = { a: 1, b: 2 };
const obj2 = { c: 3, d: 4 };

const combinedObject = { ...obj1, ...obj2 };

console.log(combinedObject); // { a: 1, b: 2, c: 3, d: 4 }

## How to Pass Functions Between Components

- In the video, what is the first step that the developer does to pass functions between components?

The first step that the developer does to pass functions between components is to create a function in the parent component that will be passed down as a prop to the child component.

- In your own words, what does the increment function do?

Each time the increment function is called, the state value of the counter is incremented by 1.

- How can you pass a method from a parent component into a child component?

To pass a method from a parent component to a child component, the method needs to be defined in the parent component and then passed as a prop to the child component.

- How does the child component invoke a method that was passed to it from a parent component?

Once the method is passed as a prop to the child component, the child component can call it by calling it as a function using the this.props syntax. For example, if the passed method is called handleClick, you can call it in the child component using this.props.handleClick()

## Things I want to know more about
