# JS Operations.
JavaScript operators are symbols which are used to assign values, compare values, perform arithmetic operations, and more.
1. The variables (operations) are called operands.
1. The operation (to be performed between the two operands) is defined by an operator.

### JavaScript supports the following types of operators:

* Arithmetic Operators
* Comparison Operators
* Logical (or Relational) Operators
* Assignment Operators
* Conditional (or ternary) Operators
* String Operators
* Type Operators
* Bitwise Operators
## JavaScript Arithmetic Operators:
|Operator|Description         |
|--------|--------------------|
|+       | Addition           |
|–       | Subtraction        |
|*       | Multiplication     |
|/       | Division           |
|%       | Modulus (Remainder)|
|++      | Increment          |
|—       |Decrement           |
---
Examples:
```javascript
// Addition
var a = 4;
var b = 3; 
var x = a + b; // adding 2 variables

// Subtraction
var x = 5;
var y = 2;
var z = x - y;

// Multiplication
var x = 5;
var y = 2;
var z = x * y;

// Division
var x = 5;
var y = 2;
var z = x / y;

// Modulo
var x = 5;
var y = 2;
var z = x % y;

// Increment
var x = 5;
x++;
var z = x;

// Decrement
var x = 5;
x--;
var z = x;
```
### Associativity.
Associativity determines the way in which operators of the same precedence are parsed. <br>
For example:
```javascript
a * b + c;
```
Left-associativity (left-to-right) means that it is processed as (a * b) + c, while right-associativity (right-to-left) means it is interpreted as a * (b + c).

### Operator Precedence.
Operator precedence describes the order in which operations are performed in an arithmetic expression. <br>
For Example:
```javascript
var x = 100 + 50 * 3;
```
Output:
```javascript
var x = 250;
``` 
As in traditional school mathematics, the multiplication is done first. Multiplication (*) and division (/) have higher precedence than addition (+) and subtraction (-).

### JavaScript Comparison Operators
Comparison and Logical operators are used to test for true or false.  Comparison operators are used in logical statements to determine equality or difference between variables or values.

|Operator|	Description|	Comparing|	Returns|
|--------|-------------|-------------|---------|
|==      |equal to     |x == 8       |false    |
|        |             |x == 5	     |true     |
|        |             |x == “5”	 |true     |
|===     |equal value and equal type|x === 5|true|
|        |             |x === “5”	 |false    |
|!=	     |not equal    |x != 8       |true     |
|!==     |not equal value or not equal type|x !== 5|false|
|        |             |x !== “5”    |true      |
|        |             |x !== 8	     |true      |
|>       |greater than |x > 8        |false     |
|<	     |less than	   |x < 8	     |true      |
|>=	     |greater than or equal to|x >= 8|false |
|<=	     |less than or equal to|x <= 8|true     |
---

### JavaScript Logical Operators
Comparison and Logical operators are used to test for true or false.   Logical operators are used to determine the logic between variables or values.

|Operator|Description|Example                     |
|--------|-----------|----------------------------|
|&&      |and        | (x < 10 && y > 1) is true  |
|  \|\|  |or         | (x == 5 || y == 5) is false|
|!       |not	     | !(x == y) is true          |
----

### JavaScript Assignment Operators
Assignment operators assign values to JavaScript variables.

|Operator|Example |Same As     |
|--------|--------|------------|
|=       |x = y	  |x = y       |
|+=	     |x += y  |x = x + y   |
|-=      |x -= y  |x = x – y   |
|*=      |x *= y  |x = x * y   |
|/=      |x /= y  |x = x / y   |
|%=      |x %= y  |x = x % y   |
|<<=     |x <<= y |x = x << y  |
|>>=	 |x >>= y |x = x >> y  |
|>>>=    |x >>>= y|	x = x >>> y|
|&=	     |x &= y  |x = x & y   |
|^=	     |x ^= y  |x = x ^ y   |
|\|=     |x \|= y |x = x \| y  |
|**=	 |x **= y |x = x ** y  |
---
### JavaScript String Operators
```javascript
var abc = "How";
var xyz = "are";
var pqr = "you?";
var txt = abc + " " + xyz + " " pqr;
console.log(txt);
```
Output:
~~~
How are you?
~~~
----
### Adding Strings and Numbers
Adding two numbers, will return the sum, but adding a number and a string will return a string. <br>
For example:
```javascript
var x = 4 + 3;
var y = "10" + 7;
var z = "Hello" + 1;
var a = 5 + 5 + "Hello";
var b = 5 + 5 + "Hello" + 5 +5;
var c = "Hello" + 5 + 5;
```
Output:
~~~
7
107
Hello1
10Hello
10Hello55
Hello55
~~~
----
### JavaScript Type Operators
|Operator  |Description                   |
|----------|------------------------------|
|typeof    |Returns the type of a variable|
|instanceof|Returns true if an object is an instance of an object type|
---
