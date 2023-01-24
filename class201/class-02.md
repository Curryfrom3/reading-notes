# Read: Class 02


## continue reading Intro to Html

### Why is it important to use semantic elements in our HTML?

Semantic elements are HTML tags that provide a clear meaning and context to the content they enclose. 

They help to indicate the structure and hierarchy of the content, such as headings, paragraphs, lists, and links.

For example, using a < header> tag to indicate the main header of a webpage, a < nav> tag to indicate the navigation menu, and < article> tag to indicate a self-contained piece of content, and < footer> tag to indicate the footer of a webpage.

Using semantic elements also makes the webpage more accessible for users with disabilities, as it allows screen readers and other assistive technologies to understand the structure of the page and to navigate the content more easily.

### How many levels of headings are there in HTML?

in HTML, there are six levels of headings, which are represented by the < h1> to < h6> tags.

 the importance of the headings decreases as the number increases, meaning that < h1> is the most important heading and < h6> the least.

### What are some uses for the < sup> and < sub> elements?

< sup> (superscript) and < sub> (subscript) elements in HTML are used to indicate text that should be displayed as superscript or subscript.

Some common uses for the < sup> element include:

Footnotes or citations, where the superscript number or symbol is used to indicate the corresponding 

reference in the footer or endnotes.


Mathematical or scientific notation, where the superscript is used to indicate exponentiation or other 

mathematical operations.

Units of measurement, where the superscript is used to indicate the unit of measurement for a numerical 

value.


ome common uses for the < sub> element include:

Mathematical or scientific notation, where the subscript is used to indicate the element of a chemical 

compound, the index of a variable, or the base of a logarithm.

Language notation, where the subscript is used to indicate the phonetic or linguistic notation of a word 

or phrase.

Typographical conventions, where the subscript is used to indicate small letters in a publication or 

manuscript.

### When using the < abbr> element, what attribute must be added to provide the full expansion of the term?

When using the < abbr> element in HTML, the "title" attribute must be added to provide the full expansion of the term.

The < abbr> element is used to indicate an abbreviation or acronym and the "title" attribute is used to 

provide the full expansion of the term.


## Learn CSS

### What are ways we can apply CSS to our HTML?

inline styling: < p style="color: blue;">This is a blue paragraph.< /p>

Internal styling: This method involves placing CSS styles within the < head> section of an HTML document using a < style> tag. 

< head>
  < style>
    p {
      color: blue;
    }
  < /style>
< /head>

External styling: This method involves creating a separate CSS file with a .css extension and linking to it in the HTML document using the < link> tag within the < head> section. 

### Why should we avoid using inline styles?

Review the block of code below and answer the following questions:

**h2 {
     color: black;
     padding: 5px;
   }**

### What is representing the selector?

h2 heading

### Which components are the CSS declarations?

color: black;" and "padding: 5px;"

### Which components are considered properties?

The color/padding

## Learn JS Continue reading JavaScript Basics. Start at “Comments” and read through “Events” section.

### What data type is a sequence of text enclosed in single quote marks?

A sequence of text enclosed in single quote marks is considered a string data type in most programming languages, including CSS.

### List 4 types of JavaScript operators.

Arithmetic operators: 

These operators are used to perform mathematical operations such as addition (+), subtraction (-), multiplication 

(*), division (/), and modulus (%).

Comparison operators: 

These operators are used to compare values and return a Boolean value (true or false). Examples of comparison 

operators are: equal to (==), not equal to (!=), greater than (>), less than (<), greater than or equal to (>=), and less than or equal 

to (<=).

Logical operators:

 These operators are used to combine multiple conditions and return a Boolean value. Examples of logical operators are: and (&&), or (||), and not (!).

 Assignment operators: These operators are used to assign a value to a variable. 
 
 Examples of assignment operators are: 
 
 equal (=), add and assign (+=), subtract and assign (-=), multiply and assign (*=

### Describe a real world Problem you could solve with a Function.

A real-world problem that could be solved with a function is calculating the area of a circle.

A function can be created in JavaScript that takes a radius as an input and returns the area of the circle as an output.

### making decisions in your code

An if statement checks a __ and if it evaluates to ___, then the code block will execute

### what is the use of an else if?

An "else if" statement in JavaScript is used to test additional conditions after an initial "if" statement. 

It allows for multiple conditions to be checked in a logical order, and only one of the conditions will be executed if it's true, the rest will be skipped. 
This feature allows for more complex decision making in your code, and it is an efficient way to handle a variety of scenarios.

### List 3 different types of comparison operators.

Equality operator (==): This operator compares two values for equality and returns a Boolean value of true if the values are equal and false if they are not.

nequality operator (!=): This operator compares two values for inequality and returns a Boolean value of true if the values are not equal and false if they are.

Strict equality operator (===): This operator compares two values for both equality and type and returns a Boolean value of true if the values are equal and have the same type and false if they are not.

### What is the difference between the logical operator && and ||?

 the difference between the logical operator "&&" and "||" is that the "&&" operator requires both conditions to be true to return true, while the "||" operator requires only one of the conditions to be true to return true. The "&&" operator is used to check if both conditions are true, and the "||" operator is used to check if at least one of the conditions is true.


 (what is &&)

 The "&&" operator (also known as the logical "and" operator) is a logical operator in JavaScript that is used to combine multiple conditions and returns true only if all the conditions are true.

It evaluates the conditions on its left and right side and only returns true if both of them are true. If any of the conditions is false, the whole expression evaluates to false.

let x = 5;

console.log(x > 0 && x < 10); // true

In this example, the value of x is 5, which is greater than 0 and less than 10, so the expression x > 0 && x < 10 evaluates to true.



