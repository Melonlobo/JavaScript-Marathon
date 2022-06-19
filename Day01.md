### 1. Explain the use of JavaScript ( or What you can do using a JavaScript)
### Answer: JavaScript is a dynamic language, initially developed for the browser by Brendon Eich, in 1995. But now JavaScript has been used in various places such as 1)To build build web pages/web apps. 2)To build backend servers, using nodeJs 3)To build mobile apps. (eg:using React-native) 4)In Machine Learning and Artificial Intelligence. 5)Game development. 6)In IOT devices.

### 2. What is the difference between client-side and server-side?
### Answer: Client-side is the front-end/website, which is viewed in the browser. Server-side is which stores the data and source code of the website, and serves to the client when a particular page or data is requested.

### 3. What is Nodejs?
### Answer: Nodejs is a JavaScript runtime built on Chrome's V8 engine. It is used to build server-side applications. It was built by Ryan Dahl,in 2009. The Nodejs run-time is written in C/C++.

### 4. Explain Scope in JavaScript.
### Answer: In JavaScript the variables are lexically scoped, meaning that we can access the variable depending on where the variable is declared in the source code. If we declare the variable in the top level of the script, it is in global scope, that way we can access that variable from any part of the code. `var` is function scoped(not block scoped). i.e. variables declared using `var` can only be accessed inside the function it is declared, `let` and `const` are block scoped. i.e. variables declared using `let` and `const` can only be accessed inside the block(inside the curly braces) it is declared, a block could be if statement, a for or a while loop or a function or anything inside the curly brackets. In case of `let` and if the variable is declared inside the block(function in case of `var`) and if we try to access the variable outside the block, it'll give us a reference error (variable is not defined).

```
var num1 = 1;
let num2 = 2;
var num3 = 3;

function sayHi() {
	const greet = "Hi";
    var food = "pizza";
    let price = 100;

    if (condition) {
        var firstName = 'Melon';
        let lastName = 'Lobo';
        const age = 100;

        console.log(greet); // "Hi"
	    console.log(food); // "pizza"
	    console.log(price); // 100
	    console.log(num1); // 1
	    console.log(num2); // 2
	    console.log(num3); // 3
    }

    console.log(greet); // "Hi"
    console.log(food); // "pizza"
	console.log(price); // 100
	console.log(num1); // 1
	console.log(num2); // 2
	console.log(num3); // 3
    console.log(firstName); // 'Melon'
    console.log(lastName); // Uncaught ReferenceError: lastName is not defined
    console.log(age); // Uncaught ReferenceError: age is not defined
}

console.log(num1); // 1
console.log(num2); // 2
console.log(num3); // 3
console.log(greet); // Uncaught ReferenceError: greet is not defined
console.log(food); // Uncaught ReferenceError: food is not defined
console.log(price); // Uncaught ReferenceError: price is not defined
console.log(firstName); // Uncaught ReferenceError: firstName is not defined
console.log(lastName); // Uncaught ReferenceError: lastName is not defined
console.log(age); // Uncaught ReferenceError: age is not defined
```

### 5. JavaScript is asynchronous or synchronous.
### Answer:JavaScript is synchronous programming language but can be made to work asynchronously using Promises and Web APIs like `setTimeout()`, and while making network requests using `fetch()` and browser events like clicks, etc...

### 6. JavaScript is Single-threaded or Multi-threaded.
### Answer: JavaScript is a single-threaded language, meaning it has a single call stack to execute all the functions. This means JavaScript can execute only task at a time.

### 7. Explain DOM in your own word.
### Answer: The Document Object Model(DOM) is a Web API used to build and manipulate the websites, it is not a part JavaScript language but of the browser. The DOM represents the document as nodes and objects, such that programming languages like JavaScript can manipulate its structure, content and style.
