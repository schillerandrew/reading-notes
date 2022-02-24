> # Dynamic Webpages with JavaScript

## JavaScript variables
- *variable* is a container for storing data values

### Four ways to declare a JavaScript variable:
- using `var` -- might be needed in older browsers
- using `let` -- value can be changed; keyword was added in 2015
- using `const` -- value can't be changed; keyword was added in 2015
- using nothing (undeclared variable)

## JavaScript Identifiers
- all variables must be identified by *identifiers* (unique names)

### General rules for identifiers
- can contain: letters `abc`, digits `0123`, underscores `_`, dollar signs `$`
- must begin with a letter
 - can begin with `$` or `_` instead
- case sensitive (`y` and `Y` are different)
- can't used reserved word (ex: keywords like `var`, `let`, `const`)

## The assignment operator
- assignment operator = `=` (equal sign)
- assigns a value

## JavaScript data types
- *number* = digits/numbers (ex: `1`, `1.3`)
- *string* = characters/text (ex: `"a"`, `"apple"`, `"1"`)
    -put in quotes (putting a number in quotes makes it a string?)

## Declaring a JavaScript variable
- after declaration, a variable has no value (technically is `undefined`)
- value can be assigned during declaration, ex: `worldName = "Earth";`
- you can declare multiple variables in one statement, with each declaration separated by a comma
 - multiple declarations can span across multiple lines:
```
let person = "John Doe",
carName = "Volvo",
price = 200;
```
