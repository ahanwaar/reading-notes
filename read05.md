# Operators and Loops
## Operators
### Logical Operators
Logical operators are typically used with Boolean (logical) values; 
when they are, they return a Boolean value. 
However, the && and || operators actually return the value of one of the specified operands, 
so if these operators are used with non-Boolean values, they may return a non-Boolean value. 
The logical operators are described in the following table.

| Operator    | symbol      |
| ----------- | ----------- |
| And         | `&&`        |
| Or          | `\|\|`        |
| Not         | `=!`        |

- Truth table:
 
| A | B |And| Or|
|---|---|---|---|
| 1 | 1 | 1 | 1 |
| 1 | 0 | 0 | 1 |

> 1 = true, 0 = false

## Loops and iteration
Loops offer a quick and easy way to do something repeatedly.

### for statement
- A for loop repeats until a specified condition evaluates to false.

- A for statement looks as follows:

```
for ([initialExpression]; [conditionExpression]; [incrementExpression]){
  statement
 }
```

- When a for loop executes, the following occurs:

![for loop](https://i.ytimg.com/vi/iI6T7quAqXw/maxresdefault.jpg)

### While statment
A while statement executes its statements as long as a specified condition evaluates to true.


- A while statement looks as follows:

```
while (condition) {
  statement
}
```

- When a while loop executes, the following occurs:

![while loop](https://www.codingeek.com/wp-content/uploads/2017/01/while-loop.png)


















