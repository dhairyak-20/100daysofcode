# JS for Loop.
Loops can execute a block of code a number of times. Loops are handy, if we want to run the same code over and over again, each time with a different value. <br>
For loop is primarily preferred when the number of iterations are well known in advanced

### The ‘for‘ loop is the most compact form of looping. It includes the following three important parts −

1. The loop initialization where we initialize our counter to a starting value. The initialization statement is executed before the loop begins.
1. The test statement which will test if a given condition is true or not. If the condition is true, then the code given inside the loop will be executed, otherwise the control will come out of the loop.
1. The iteration statement where you can increase or decrease your counter.

### Syntax
```javascript
for (initialization condition; testing condition; increment/decrement)
{
    statement(s)
}
```
1. Initialization condition: Here, we initialize the variable in use. It marks the start of a for loop. An already declared variable can be used or a variable can be declared.
1. Testing Condition: It is used for testing the exit condition for a loop. It is also an Entry Control Loop as the condition is checked prior to the execution of the loop statements.
1. Statement execution: Once the condition is evaluated to true, the statements in the loop body are executed.
1. Increment/Decrement: It is used for updating the variable for next iteration.
1. Loop termination: When the condition becomes false, the loop terminates marking the end of its life cycle.

## Examples:
### Q1. Countdown
```javascript
var count;
            document.write("Starting Loop" + "<br />");
         
            for(count = 0; count < 10; count++){
               document.write("Current Count : " + count );
               document.write("<br />");
            }
         
            document.write("Loop stopped!");
```
Output:
```
Starting Loop
Current Count : 10
Current Count : 9
Current Count : 8
Current Count : 7
Current Count : 6
Current Count : 5
Current Count : 4
Current Count : 3
Current Count : 2
Current Count : 1
Current Count : 0
Loop stopped!
```

### Q2. Print first five even numbers.
```javascript
var count;
    document.write("Starting Loop" + "<br />");

for (var y = 2; y <= 10; y += 2) {
    document.write("<h2>" + y + "</h2>")
}
```
