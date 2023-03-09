Reading
JavaScript Object Basics
How would you describe an object to a non-technical friend you grew up with?
State the outcome. However technical the problem, that’s usually as simple as ‘costs more’, ‘miss the deadline’, ‘needs more staff’ and so on
Create analogies based on things I know they know. ‘Bandwidth is like how fat the hosepipe is, and ours isn’t fat enough’
Add the missing pieces of knowledge, explained at a suitable level.
What are some advantages to creating object literals?
The advantages of using object literals to create objects include convenience, flexibility in declaration, and less code during declaration.
How do objects differ from arrays?
Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable.
Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
An object property can only be accessed using the bracket notation when/if a property name: Has a space or a hyphen; Starts with a number;

Evaluate the code below. What does the term this refer to and what is the advantage to using this?*
It hones problem-solving and analysis skills, such as finding errors and thinking logically.
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
Introduction To The DOM
What is the DOM?
The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web.
Briefly describe the relationship between the DOM and JavaScript.
The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.

