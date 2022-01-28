# Data Types in JavaScript.

![dataTypes](https://i.ibb.co/JRkmY24/Untitled-design.jpg)

----

## Primitive Data Types:

|Data Type|Description                                   |
|---------|----------------------------------------------|
|String   |Represents sequesnce of characters eg. "hello"|
|Numbers  |Represents numberic value eg. "100"           |
|Boolean  |Represents boolean value either true or false |
|Undefined|Represents undefined value                    |
|Null     |Represents null i.e. no value at all          |
----
### JS Strings
Strings are written with quotes. Can use single or double quotes.
```javascript
var carName = "Mercedes"; //uing doble quotes
var carName = 'BMW';      // using single quotes
```
```javascript
var name = "It's Alright."; //single quotes under double quotes
var name = 'He said, "he will be alright".' // double quotes under single quotes
var name = 'Here\'s your book.' //escaping
```
---
### JS Numbers
JavaScript has only one type of numbers. Numbers can be written with, or without decimals. Extra large or extra small numbers can be written with scientific exponential.

```javascript
var x1 = 34.00;     // Written with decimals
var x2 = 34;        // Written without decimals
var y = 123e5;      // 12300000
var z = 123e-5;     // 0.00123
```
---
### JS Booleans
Booleans can only have two values: true or false.
```javascript
var flag1 = true;
var flag2 = false;
```
---
## JavaScript Non-Primitive
|Data Type|Description                                     |
|---------|------------------------------------------------|
|Object	  |Represents instance through which we can access members|
|Array	  |represents group of similar values              |
---
---
## JavaScript is  LOOSELY/WEAKLY TYPED.
Javascript is known as untyped/loosely/weakly typed language. This means that we do not have to specify the data type in advance unlike other languages.<br>
For Eg.
```javascript
var x;
x = 5;
```
---
## JavaScript is DYNAMICALLY TYPED.
Javascript is known as dynamically typed language. This means, that once a variable is created in javascript using the keyword var, we can store any type of value in this variable supported by javascript.<br>
For eg:
```javascript
// creating variable to store a number
var num = 5;

// store string in the variable num
num = "Simple Snippets";
```
In this example above, the data type of the variable num changes from number to string as we pass string data.