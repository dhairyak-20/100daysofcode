# Variables
## Creating Variable in JavaScript
```javascript
var length = 5;   // Number
var lastName = "Simple Snippets";   // String
var flag = true;   // boolean
```
---
## Variable Scope in Javascript
1. Global Scope – Scope outside the outermost function attached to Window.
1. Local Scope – Inside the function being executed.

Example:
```javascript
var globalVar = "This is a global variable"; 
  
function fun() { 
  var localVar = "This is a local variable"; 
  
  console.log(globalVar); 
  console.log(localVar); 
} 
fun();
console.log(localVar);
```
Output:
```javascript
This is a global variable
This is a local variable
Uncaught reference error: localVar is not defined
```
