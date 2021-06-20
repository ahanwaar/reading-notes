# Programming with JavaScript
## JavaScript Functions
### What is Java script Function?
JavaScript Function is a reusable set of step-by-step instructions, potentially based on input, to potentially provide some output.  

### What's the advantages of using JS function?
1. **Code reusability:** We can call a function several times so it save coding.
2. **Less coding:** It makes our program compact. We don’t need to write many lines of code each time to perform a common task.

### What is JavaScript Function Syntax?
![JS sybtax](https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.3-functions/master/images/functions.png?size=100)

### Function Expression VS. Function Statement
- Function declarations load before any code is executed while Function expressions load only when the interpreter reaches that line of code.
- Similar to the `var` statement, function declarations are hoisted to the top of other code. Function expressions aren’t hoisted, which allows them to retain a copy of the local variables from the scope where they were defined.

*Example: Function Expression*
```
alert(foo()); // ERROR! foo wasn't loaded yet
var foo = function() { return 5; }
```

*Example: Function Declaration*

```
alert(foo()); // Alerts 5. Declarations are loaded before any code can run.
function foo() { return 5; }
```

### Ways of Function Invocation
The code inside the function will execute when "something" invokes/calls the function, as the following:
- When an event occurs (when a user clicks a button)
- When it is invoked from JavaScript code
- Automatically (self invoked)

### Function Return
- When JavaScript reaches a `return` statement, the function will stop executing.
- If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
- Not all functions must have a return statement, but it's preferable to include it.


### So, what's the corrct way to invoke the function?
The () Operator Invokes the Function as the following example:
If we wrote this function:
```
var findVoltage = function(current, resistance) {
  var voltag = 0;
  voltage = current * resistance;
  
  return voltage;
}
```

we can invoke it using the following code:
```
findVoltage(2,5);

```







