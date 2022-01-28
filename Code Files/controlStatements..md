# Control Statements
Conditional statements are used to perform different actions based on different conditions.

## if statements
Q. Find if a number is positive.
```javascript
var x = 5;
if (x > 0) {
    document.write("Number is Positive");   
}
```
## if else statements
Q. Find if the number is even or odd.
```javascript
var x = 7;
if (x%2==0) {
    document.write("The number is Even");
}
else {
    document.Write("The number is odd");
}
```

## if else if statements
Q. Find if the number is positive, negative or zero.
```javascript
var x = 10;
if (x > 0) {
    document.write("The number is positive");
}
else if (x < 0) {
    document.write("The number is negative");
}
else {
    document.write("The number is neither negative nor positive");
}
```
## Nested if statements
Q. Find if the number is negative and odd.
```javascript
var x = -3;
if (x < 0) {
    if (x%2!=0) {
        document.write("The number is negative and odd");
    }
}
                        // OR
if (x<0 && x%2!=0) {
    document.write("The number is negative and odd");
}
```
