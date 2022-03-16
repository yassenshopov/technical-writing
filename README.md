# Arrow Functions in JavaScript

- If you have been programming for a while, you must be aware of the concept of __functions__ so far.

```

function y(x) {
  return 2 * x;
}

```

- Since functions are so widely and commonly used, wouuldn't it be great if there was a way to make them shorter and more concise?
- Say "hi" to Arrow Functions


```

let y = (x) => y = 2*x;

```

- Definition of AF

---

## Syntax

- Resembles this of a normal function
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
