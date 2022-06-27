### 1. List all the Escape Sequences characters in javascript.
### Answer: There are some reserved single character escape sequences for use in strings:
### \b: backspace (U+0008 BACKSPACE)
### \f: form feed (U+000C FORM FEED)
### \n: line feed (U+000A LINE FEED)
### \r: carriage return (U+000D CARRIAGE RETURN)
### \t: horizontal tab (U+0009 CHARACTER TABULATION)
### \v: vertical tab (U+000B LINE TABULATION)
### \0: null character (U+0000 NULL) (only if the next character is not a decimal digit; else it’s an octal escape sequence)
### \': single quote (U+0027 APOSTROPHE)
### \": double quote (U+0022 QUOTATION MARK)
### \\: backslash (U+005C REVERSE SOLIDUS)

### 2. Explain with example length and substring methods in javascript.
### Answer: The length method is used to determine the length of the string or an array. The substring method is used to get the substring from a string.
```
const str = 'JavaScript';
console.log(str.length); // 10
console.log(str.substring(4,9)); // 'Scrip'
console.log(str.substr(4,9)); // 'Script'
```

### 3. What are padStart and padEnd in javascript, explain with an example.
### Answer: padStart and padEnd are two new methods available on JavaScript strings. As their name implies, they allow for formatting a string by adding padding characters at the start or the end.
```
const numbers = '01234';
console.log(numbers.padStart(10,'x')); // 'xxxxx01234'
console.log(numbers.padEnd(10,'x')); // '01234xxxxx'
```

### 4. Define Global Object in javascript along with the global scope.
### Answer: A global object is an object that always exists in the global scope. In JavaScript, there's always a global object defined. In a web browser, when scripts create global variables, they're created as members of the global object.

### 5. List all the names of Javascript engines present currently. 
### Answer: 1) V8 developed by Google, it is in the Chrome web browser and other Chromium based web browsers. Node and Deno the JavaScript run-times are also built on the V8. 2) Chakra developed by Microsoft. It is used in the Internet Explorer/Edge web browser. 3) SpiderMonkey is the first JavaScript engine, written by Brendan Eich at Netscape Communications, later released as open-source and currently maintained by the Mozilla Foundation. It is still used in the Firefox web browser. 4) WebKit is developed by Apple and  used in its Safari web browser, as well as all iOS web browsers. 5) PixiJS is an amazingly flexible and fastest 2D rendering library. 6)Phaser. 7)Babylon. 8)PlayCanvas WebGL Game Engine. 9)Melon. 10)GDevelop. 11)Kiwi. 12)Three.