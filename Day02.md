### 1. What is lexical structure?
### Answer: A programming language's lexical structure specifies a set of some basic rules about how code should be written in it. How the variable should be named ,variable name cannot start with a number, the delimiter characters for comments, avoid using the reserved keywords for naming a variable

### 2. What is Unicode?
### Answer: Unicode is a 16-bit encoding system that can represent millions of different characters, letters and symbols commonly used in today's digital and print media. Unicode is a specification that aims to list every character used by human languages and give each character its own unique code. Unicode has become the top standard for identifying characters in text in nearly any language.

### 3. Explain all the keywords present in the JavaScript with examples.
### Answer: 
### `await` : Used to wait for javascript until the promise returns its result.
### `arguments` : Represents the list of parameters passed to the function when calling the function.
### `break` : Used into a loop to break or stop the execution of the loop.
### `byte` : Byte is aunit of data. One byte is 8 bits.
### `case` : Used in a switch-case construct, where the value of an expression compares with the case clause value and executes the statements associated with the case whose case value is matched.
### `catch` : Used in exception handling to handle the error.
### `class` : Used to define a class.
### `const` : Used to declare a variable (it cant be changed after defined).
### `continue` : Skips to the next iteration in the loop.
### `char` : Data type for strings and characters.
### `debugger` : Used to stop the execution of javascript code and call debugging function if define. Debugger keyword word the same as the break.
### `default` : Used in a switch expression to specify the actions to be performed if no case.
### `do` : Used to define a do-while loop, it will run the block of code once.
### `delete` : Used to remove properties from an object.
### `double` : Data type, it used to store a 64-bit(8 bytes) floating point number.
### `else` : Used in the if-else statement, the else indicates the block of statements to be executed if the expression evaluates false.
### `extends` : Used in class declarations to create a class that inherits another class.
### `export` : Used to export objects, functions or values from the module so that can be used in another program with the help of import statement.
### `enum` : Used to define a predefined list.
### `eval` : Used to evaluate a specified string. The eval use as a global function eval().
### `false` : primitive data type of Boolean value.
### `for` : Used to define a loop, for loop to repeatedly execute a block of code until a condition true.
### `finally` : Used in exception handling, finally block of code always execute regardless of whether the error is generating or not.
### `function` : Used to define a function to execute a block of code.
### `float` : Data type for floating point numbers.
### `goto` : Used to return execution control to a specific location. In general, the goto can be accomplished by the break and continue keywords.
### `if` : Used to define a conditioned construct. if the statement is used to run a block of code if the condition is true.
### `import` : Used to import the module/file in the javascript program.
### `in` : It is an operator returns true if the specified property is present in the specified object, else it returns false.
### `instanceof` : Returns true if the object is an instance of the class otherwise false.
### `implements` : Used to implement the interface in a class.
### `interface` : Used to define an interface (interface contains all abstract methods).
### `int` : Data type for integer.
### `let` : Used to declare a variable.
### `long` : Data type, it used to store a 32-bit(4 bytes) integer.
### `new` : Used to create an object.
### `null` : Data type.
### `return` : Used to return from the function or method with or without a value.
### `short` : Data type, it used to store a 16-bit(2 bytes) integer.
### `switch` : Used in a switch-case construct, where switch evaluates an expression.
### `super` : Used to call function or method of a parent class.
### `throw` : Used in a try block to explicitly throw an exception object.
### `this` : Used to refer to the current object.
### `try` : Used for exception handling to check a block of code for errors.
### `true` : primitive data type of Boolean value.
### `typeof` : Used to return the data type of an operand.
### `var` : Used to declare a variable.
### `while` : This loop runs until the condition becomes false.
### `with` : Used for iterating, just, in short, it is shortened for iteration.
### `yield` : Used to pause and resume a generator function. The generator function is the same as a normal function but for returning a value in  place of return it uses yield keyword.
### There are many more keywords.

### 4. What are shorthand operators, explain with a suitable example?
### Answer: 1)Short hand operator for `i = i + 1` would be `i += 1` or `i++`, 2)1)Short hand operator for `i = i - 1` would be `i -= 1` or `i--`, 3)Short hand operator for `i = i + 3` would be `i += 3`, 4)Short hand operator for `i = i - 5` would be `i -= 5`, 5)Short hand operator for `i = i * 2` would be `i *= 2`,

### 5. What is “use Strict” in JavaScript?
### Answer: In JavaScript, `"use strict";` states that the code should be executed in 'strict mode'. It is written at the top of the program. This makes it easier to write good and secure JS code. In strict mode 1)We cannot create a variable without declaring it. 2)Deleting an object is not allowed. 3)Duplicating a parameter name is not allowed. 4)Assigning to a non-writable property is not allowed. 5)Assigning to a getter-only property is not allowed. 6)Assigning to a new property on a non-extensible object is not allowed. 7) Octal syntax is not allowed. 8) Keywords cannot be used as indentifiers.