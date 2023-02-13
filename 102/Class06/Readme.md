Topic: Javascript

What is Javascipt?
Definition: an object-oriented computer programming language commonly used to create interactive effects within web browsers.

JavaScript's dynamic capabilities include runtime object construction, variable parameter lists, function variables, dynamic script creation (via eval), object introspection (via for...in and Object utilities), and source-code recovery.

Do not confuse JavaScript with the Java programming language — JavaScript is not "Interpreted Java". Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries.

## Things I want to know more about 
*Building Blocks of Javascript
*Exploring Javascript objects

Source: <https://developer.mozilla.org/en-US/docs/Web/JavaScript>

Topic: Introduction to JavaScript - basic output

Where can we run Javascript?
    Traditionally JavaScript was used inside web browsers such as Mozilla Firefox, Internet Explorer, Chrome, Opera, or Safari.

That JavaScript code would run in the browser (what we call "client side", as opposed to running on the web server which is called "server side").

We can distinguish 3 major parts of what we usually refer to as "JavaScript".

*The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.
*The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.
*The server API (or just API) provided by Node.js or one of the other server-side systems.

Three Major Components of Javascript
*Editor or IDE
*Embed or include
*Input Output

    Editor or IDe
    Any text editor can be used.

    Embed or include 
    You can either embed the JavaScript code directly inside the HTML file, or you can put a line in the HTML file that will include the external JavaScript file.

    Input Output
    The very first thing we need to learn is how to interact with the JavaScript code running in the browse. There are a number of way JavaScript can display text for the user (output). The most simple one is by using the alert function:

        Alert:
        This will show a pop-up in the browser with the text. (You can click on Try! that will open the specific script in a separate window.) The alert() function is actually rarely used, but it is an easy way to show the use of JavaScript.

Source: <https://code-maven.com/introduction-to-javascript>

Topic: JavaScript input with prompt and confirm

Two ways to receive input:
    *Prompt -  It will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. When the user presses OK, the value in the text box will be returned by the prompt() function. 
    *Confirm -  It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.

Source: <https://code-maven.com/javascript-input-with-prompt-and-confirm>

Topic: Javascript Variables 
Variables are containers for storing data (storing data values).

4 Ways to Declare a JavaScript Variable:
*Using var
*Using let
*Using const
*Using nothing

When to Use JavaScript var?
    Always declare JavaScript variables with var,let, orconst.
    The var keyword is used in all JavaScript code from 1995 to 2015.
    The let and const keywords were added to JavaScript in 2015.
    If you want your code to run in older browsers, you must use var.

When to Use JavaScript const?
    If you want a general rule: always declare variables with const.
    If you think the value of the variable can change, use let.

JavaScript Identifiers
All JavaScript variables must be identified with unique names. These unique names are called identifiers. Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:
    Names can contain letters, digits, underscores, and dollar signs.
    Names must begin with a letter.
    Names can also begin with $ and _ (but we will not use it in this tutorial).
    Names are case sensitive (y and Y are different variables).
    Reserved words (like JavaScript keywords) cannot be used as names.

The Assignment Operator
    In JavaScript, the equal sign (=) is an "assignment" operator, not an "equal to" operator.

JavaScript Data Types
    JavaScript variables can hold numbers like 100 and text values like "John Doe".
    In programming, text values are called text strings. JavaScript can handle many types of data, but for now, just think of numbers and strings. Strings are written inside double or single quotes. Numbers are written without quotes.

Source: <https://www.w3schools.com/js/js_variables.asp>

## Things I want to know more about:
How to use javascript function and identify data types. 
