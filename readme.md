## Basic Programming note

### A. JavaScript (JS)
#### #1. Variable
```js
// For global variables
var age = 10;
var isValid = true;
var studentName = "Rady"

// For block scope variables
let age = 18;
let isValid = true;
let studentName = "Rady"

// For block scope variables with cannot be reassigned
const SCHOOL_NAME = "PNC";
const PI = 3.14;
```
#### 2. Conditional (block)
```js
// IF condition
if (condition) {
    // your code here (work when condition is true)
}

// Example
let age = 18;
if (age == 18) {
    console.log("You are young");
}
```
```js
// IF-ELSE condition
if (condition) {
    // your code here (work when condition is true)
} else {
    // your code here (work when if condition is false)
}

// Example
let age = 18;
if (age > 18) {
    console.log("You are young");
} else {
    console.log("You are old")
}
```
```js
// IF-IF condition (work both when condition is true)
if (condition) {
    // your code here (work when condition is true)
} 
if (condition) {
    // your code here (work when condition is true)
}

// Example
let age = 18;
if (age < 18) {
    console.log("You are young");
} 
if (age > 18){
    console.log("You are old")
}
```
```js
// IF-ELSE IF  condition (work only 1 when condition is true)
if (condition) {
    // your code here (work when condition is true)
} else if (condition) {
    // your code here (work when condition is true)
}

// Example
let age = 18;
if (age > 18) {
    console.log("You are young");
} else if (age < 18) {
    console.log("You are old")
}
```
```js
// IF-ELSE IF - ELSE condition (work only 1 when condition is true)
if (condition) {
    // your code here (work when condition is true)
} else if (condition) {
    // your code here (work when condition is true)
} else {
    // your code here (work when all condition is false)
}

// Example
let age = 18;
if (age < 18) {
    console.log("You are young");
} else if (age > 18) {
    console.log("You are old")
} else {
    console.log("You are adult")
}
```
