# The reading today is teaching us some new principles inside of javascript and producing us an idea of how DOM is used inside of a javascript file and helps with understanding and purpose behind the idea of that. 

## JavaScript Object Basics

**How would you describe an object to a non-technical friend you grew up with?**

In JavaScript, an object is a self-contained entity, with properties and types. Contrast it with a cup, for example. A cup is an object and has properties. A cup has a color, a design, weight, a material it is made of, etc. In the same way, JavaScript objects can have properties, which define their characteristics.

**What are some advantages to creating object literals?**

Convenience, flexibility in a declaration, and less code during declaration,

**How do objects differ from arrays?**

The difference between an object and an array is that arrays will create and store a list of data in single variables, but an object represents things as characteristics which can also be referred to as properties. 

**Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**

If an object property name would be held in a variable, you are limited to using bracket notation versus dot notation.

**Evaluate the code below. What does the term this refer to and what is the advantage to using this?**

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

this= an object, it is in reference to an object and helps with executing the current piece of code.

In the code, this is saying to take the variable of the name which is Spot, and age which is 2 then multiply age x 7 and console log out the following statement “Spot is 14 in human years.”

## Introduction To The DOM

**What is the DOM?** [DOM Reading](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

The Document Object Model (DOM) is the data representation of the objects that constitute the structure and content of a document on the web. This guide will introduce the DOM, look at how the DOM represents an HTML document in memory, and how to use APIs to create web content and applications.

**Briefly describe the relationship between the DOM and JavaScript.** [Stack Overflow](https://stackoverflow.com/questions/2726554/what-is-the-difference-between-javascript-and-dom)

The DOM also provides an API to manipulate the DOM, with functions like getElementsByTagName and createElement. JavaScript is a programming language that web browsers can execute. JavaScript can interact with the DOM with DOM scripting.

## Things I want to know more about
 Is there a standard DOM file structure used industry-wide to allow for uniformity that we should become familiar with?
