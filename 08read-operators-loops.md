> # Operators and Loops

## Operators
- three classes of operators: *binary*, *unary*, and *ternary* (conditional operator)
- binary operator has two operands, before and after the operator (`1+1`)
- unary operators have one operand, either before or after the operator (`++1` `1++`)

### Assignment operators
- *assignment operator* assigns a value to its left operand based on the value of its right operand
- assignment `=`
- addition `+=`
- subtraction `-=`
- multiplicaiton `*=`
- division `/=`
- remainder `%=`
- exponentiation `**=`
- left shift `<<=`
- right shift `>>=`
- unsigned right shift `>>>=`
- bitwise AND `&=`
- bitwise XOR `^=`
- bitwise  OR `|=`
- logical AND `&&=`
- logical  OR `||=`
- logical nullish `??=`

- if a variable refers to an object, then the left-hand side of an assignment expression may make assignments to properties of variable

- *destructuring assignment* syntax is an expression for extracting data from arrays or objects, with a syntax that mirrors the construction of array and object literals

- an assigment expression can be nested in any place where expressions are generally allowed
  - for example, if `x = f()` is an assignment expression, it can be nested as an array element `console.log([ 0, x = f(), 0 ]);` or a function call argument `console.log(f(0, x = f(), 0));`

## Loops and Iteration

### for statement/loop
- a for loop repeats until a specified condition evalutes to `false`:
```
for ([INITIALexpression]; [CONDITIONexpression]; [INCREMENTexpression])
  STATEMENT
```

How a for loop executes:
1. The initializing expression `INITIALexpression`, if present, excecutes
 - this expression usually initializes at least one loop counter, but the expression can be much more complex, and it can decare variables
1. The `CONDITIONexpression` expression, if present, is evaluted
 - if the value is true, the loop statements execute
 - if the value is false, the entire for loop terminates
  - if the condition expression is omitted, the condition is assumed to be true (loop might keep looping)
1. The `STATEMENT` executes, as long as the condition was true.
1. The `INCREMENTexpression`, if present, is executed.
1. Step 2 (checking/evaluating the condition expression) is repeated.

### while statement/loop
- a while statement loops as long as a specified condition evalutes to `true`:
```
while (CONDITION)
  STATEMENT
```

> ### [Back to homepage](https://schillerandrew.github.io/reading-notes/)