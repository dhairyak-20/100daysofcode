# JS Switch Case
The switch case statement in JavaScript is also used for decision making purposes. In some cases, using the switch case statement is more convenient over if-else statements. When we want to test a variable for hundred different values and based on the test we want to execute some task, using if-else statement will be less efficient over switch case statements and also it will make the code look messy.

## Examples
### Q1. Find the day of week by accepting its number.
```javascript
var day = 1;
        switch (day) {
            case 1:
                document.write("Monday");
                break;
            case 2:
                document.write("Tuesday");
                break;
            case 3:
                document.write("Wednesday");
                break;
            case 4:
                document.write("Thursday");
                break;
            case 5:
                document.write("Friday");
                break;
            case 6:
                document.write("Saturday");
                break;
            case 7:
                document.write("Sunday");
                break;
            default:        // when none of the above case are true.
                document.write("Wrong Input");
        }
```

### Q2. Find the number by accepting the day of week.
```javascript
 var day = "Monday";  //typing 'monday' will show wrong input.
        switch (day) {
            case "Monday":
                document.write("1");
                break;
            case "Tuesday":
                document.write("2");
                break;
            case "Wednesday":
                document.write("3");
                break;
            case "Thursday":
                document.write("4");
                break;
            case "Friday":
                document.write("5");
                break;
            case "Saturday":
                document.write("6");
                break;
            case "Sunday":
                document.write("7");
                break;
            default:         // when none of the above case are true.
                document.write("Wrong Input");
                break;
        }

```