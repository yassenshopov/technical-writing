# Arrow Functions in JavaScript

If you have been programming for a while, you must be aware of the concept of __functions__. 
 
Functions can be defined as pieces of code that are designed to do one particular task. If you need this task to be done multiple times throughout your code, you can put it in a function and just call the function every time you need it, instead of repeatedly writing long pieces of code.

Let's say you want a function to calculate the square of whatever number you put as input. Typically, in JavaScript, a function looks like this:

```

function square(x) {
  return x ** 2;
}

```

Then you can just call your function inside your code anytime you need it, just like I did here

```

*insert code gif*

```

Since functions are so widely and commonly used, wouldn't it be great if there was a way to make them shorter and more concise? Thankfully, developers have been working hard on that front, and ever since ES6 (a newer version of JavaScript, released in 2015), there is now a way to write __shorter__ and __cleaner__ functions that do the same job as regular ones.

Say "hello" to Arrow Functions.


```

let square = (x) => square = x**2;

```

As you can see from just a glance, arrow functions look very similar to regular functions, but they are also much more straightforward, especially for basic calculations and operations. They are most commonly used for one-line operations.

In this article, we will go over the syntax of arrow functions, how they are different from regular functions, and their use of the *'this'* keyword.

---

## Syntax

As we already mentioned, the syntax of an arrow function resembles that of a normal function. It still consists of an output, input (arguments), and the expression that transforms the input into an output.

While regular functions have a single, set-in-stone syntax, arrow functions can look different to each other depending on the number of lines they take and the number of arguments they take as inputs.

We will start off with the most simple iteration - an arrow function which takes no arguments:

```



```

This type of function takes no inputs, and just uses previously declared variables for its calculations/operations. You can compare it with a traditional function that also takes no arguments, also known as an "anonymous function"":

```

let x = 5;
let y = 3;
function power() {
  return z = x ** y;
}
i = power(x,y) // i will be equal to 125 (x^y^ or 5^3^)

```

- Define output, input arguments, and the expression of the function
- Syntax depends on the number of arguments and expressions
1. No argument
2. 1 argument
3. Several args
4. 1 expression
5. Multiple expressions

## Usage of const/let

- Arrow functions and the removal of var are both new features of ES6
- The arrow function needs to be declared first, thus the usage of let/const => used to store the data as a variable

## Single-line Arrow Functions

## Multiple-line Arrow Functions

## Returning Objects in Particular

## Single Parameters

## Multiple Parameters

## Arrow Functions VS Regular Functions

## Absense of "function" keyword

## Can it be used as a function constructor?

## What does "this" reference to?

You may have seen the keyword *'this'* pop up occasionally in tutorials and example codes. And just like many other programming concepts, it is very context-dependent.

*'this'* is handled differently depending on the type of function that calls for it. In the case of regular functions, the keyword *'this'* represents the object called by the function. As you can see in the following example, when a button function calls for *'this'*, *'this'* represents the buttons, and the properties of *'this'* are the properties of the button. 

With regular functions, '*this'* could be anything - the body of the HTML DOM, the event-triggering element, or just the window itself.

With arrow functions, the situation is a little bit different.

While *'this'* in regular functions applies to the object that __calls__ the function, when *'this'* is used by arrow functions, *'this'* represents the object that is owning the arrow function. In JavaScript, since it is running on the browser's console, the owner will generally be the window.

- *insert code snippet*

## Binding a regular function?

---

## References

- [https://javascript.info/arrow-functions-basics](https://javascript.info/arrow-functions-basics)

- [https://www.javascripttutorial.net/es6/javascript-arrow-function](https://www.javascripttutorial.net/es6/javascript-arrow-function/)

- [https://www.programiz.com/javascript/arrow-function](https://www.programiz.com/javascript/arrow-function)
