# Reading 7
Functions in JS are blocks of code that can be reused throughout a program. 
They are defined using the "function" keyword, followed by a function name, and a set of parentheses that may contain parameters.
 Functions are invoked, or called, using the function name followed by parentheses. 
 
 For example:

 function add(a, b) {
  return a + b;
}

let result = add(3, 4);
console.log(result); // Output: 7

Operations in JS are actions that are performed on values or variables. The most common operations include mathematical operations such as 

addition (+), 
subtraction (-), 
multiplication (*), 
and division (/). 

For example:

let x = 5;
let y = 2;
let sum = x + y;
console.log(sum); // Output: 7

Expressions in JS are any valid unit of code that can be evaluated to a value. 
Expressions can include variables, values, and operators that are combined to produce a new value.

 For example:

 let x = 5;
let y = 2;
let expression = x + y * 3;
console.log(expression); // Output: 11

## To recap JS

Variables: Variables are used to store and manipulate data in JS.
 They are declared using the "var", "let" or "const" keyword, followed by a variable name and an assignment operator (=). 
 
 For example:

 let x = 5;

Data Types: JS has several data types, including numbers, strings, booleans, and objects. 
Numbers can be either integers or floating-point values, while strings are sequences of characters.

 For example:

 let num = 5;
let str = "hello";
let bool = true;

Arrays: Arrays are a type of object that can store a collection of elements.
 Elements can be of any data type and can be accessed using their index number. 
 
 For example:

 let arr = [1, 2, 3];
console.log(arr[1]); // Output: 2

Control Flow: Control flow statements are used to control the flow of execution in a program. 
The most common control flow statements include "if-else" statements and "for" and "while" loops. 

For example:

let x = 5;
if (x > 0) {
  console.log("x is positive");
} else {
  console.log("x is not positive");
}

Functions: Functions are blocks of code that can be reused throughout a program. 
They are defined using the "function" keyword, followed by a function name, and a set of parentheses that may contain parameters.

 For example:

 function add(a, b) {
  return a + b;
}
let result = add(3, 4);
console.log(result); // Output: 7

DOM (Document Object Model): The DOM is a programming interface for HTML and XML documents, it represents the structure of a document and allows the manipulation of its content and presentation.


Event Handling: JavaScript can respond to events, such as a button being clicked, a page finishing loading, or an element being hovered over. This is known as event handling, and it allows you to create interactive web pages.