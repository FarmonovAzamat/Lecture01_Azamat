![Tux, the Linux mascot](/img/Readme.logo.png)
# Lecture1
## Table of contents
1. Introduction
3. Variables: local & global
3. Data types: primitive and object
4. Operators: math, arithmetic, comparison, assignment
5. Conditions:if/else, ternary operator, switch statement
6. Loops: loop for, loop while, loop do/while
7. Functions: function declaration, function expression, function IIFE

## **Introduction**
![Tux, the Linux mascot](/img/js.png)
### **The founder of JavaScript**
![Tux, the Linux mascot](/img/Brandan.jpg)
Brendan Eich is an American entrepreneur who is credited with inventing the widely-used JavaScript scripting language.

## **Differences between Html Css and JavaScript**
![Tux, the Linux mascot](/img/differences%20btw%20html%20css%20js.png)
## **Variables**
![Tux, the Linux mascot](/img/variables.png)
A JavaScript variable is simply a name of storage location.
![Tux, the Linux mascot](/img/let%20var%20const.jpg) <br>

There are two types of variables in JavaScript : local variable and global variable.
- the local variable is declared inside block or function
- the global variable is accessible from any function
 <br>
 Rules of declaring the variables: <br>
 - Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.
 - After first letter we can use digits (0 to 9), for example value1.
 - JavaScript variables are case sensitive, for example x and X are different variables.
 <br>
 
 let x = 10;

 let _x = 10;

 let $ = 10;

## **Data types: primitive and object**
JavaScript provides different data types to hold different types of values. There are two types of data types in JavaScript.

Primitive data type
Non-primitive (reference) data type <br>
![Tux, the Linux mascot](/img/data%20types.jpg)
![Tux, the Linux mascot](/img/non-primitive.png)

## **Operators: arithmetic, logical, comparison, assignment**
![Tux, the Linux mascot](/img/JavaScript-Arithmatic-Operators.png)
![Tux, the Linux mascot](/img/JavaScript-Logical-Operator.png)
![Tux, the Linux mascot](/img/comparison%20operations.jpg)
![Tux, the Linux mascot](/img/assignment.png)

## **Conditions:if/else, switch statement, ternary operator**
#### if/else
Conditional Statements
Very often when you write code, you want to perform different actions for different decisions.
You can use conditional statements in your code to do this.
In JavaScript we have the following conditional statements:
<br>
 if, if/else <br>
if (condition) { <br>
  code to run if condition is true <br>
} else { <br>
  run some other code instead <br>
}

 #### switch case
![Tux, the Linux mascot](/img/swi.png)
![Tux, the Linux mascot](/img/switch.png)

 #### ternary
![Tux, the Linux mascot](/img/ternary.png)

## **Loops: for loop, while loop, do while loop**
Loops can execute a block of code as long as a specified condition is true.
### for Loop
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop. <br>
#### Syntax
for (expression 1; expression 2; expression 3) { <br>
  // code block to be executed <br>
} <br>

### The While Loop
The while loop loops through a block of code as long as a specified condition is true.
#### Syntax
while (condition) { <br>
  // code block to be executed <br>
} <br>
In the following example, the code in the loop will run, over and over again, as long as a variable (i) is less than 10: <br>
while (i < 10) { <br>
  text += "The number is " + i; <br>
  i++; <br>
} <br>

### The do while loop
Execute a code block once, an then continue if condition (i < 5) is true: <br>
let text = ""; <br>
let i = 0; <br>
do { <br>
  text += i + "<br>";
  i++; <br>
} <br>
while (i < 5); <br>

## Functions: function declaration, function expression, function IIFE
A JavaScript function is a block of code designed to perform a particular task. <br>
A JavaScript function is executed when "something" invokes it (calls it).
<br>

function myFunction(p1, p2) { <br>
  return p1 * p2; <br>
} <br>



