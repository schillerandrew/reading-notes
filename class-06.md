> # Problem Domain, Objects, and the DOM

### Eight JavaScript data types:

- `Boolean`
- `Null`
- `undefined`
- `number`
- `BigInt`
- `String`
- `Symbol`
- `Objects`

- arrays, functions and dates are all objects, not their own data types

### Primitive value vs reference

- primitive value = when assigned to a variable, the variable is set to that value directly
- reference = variable contains a reference to it

### Immutable vs mutable

- immutable = primitive values (string, etc)
- mutable = object references (array, etc)

- `const` keyword creates variables whose values can't be reassigned, but the values can still be mutated

## JS

### Chapter 3: Object Literals

- object = set of variables and functions grouped together
- property = a variable that's part of an object
- method = a function that's part of an object
- key = name part of a name-value pair in an object

- separate properties and methods with commas at the end, except for the final value
- `this.` indicates that a property from within the object is being used
- can add properties to an object using syntax `OBJECT-NAME.KEY-NAME =`...
- can reference a key name that is a string or number using syntax `OBJECT-NAME[KEY-NAME]`, but normally `OBJECT-NAME.KEY-NAME` is used (dot notation instead of bracket notation)

### Chapter 5: Document Object Model

- DOM (Document Object Model) = makes a model of an html page, and act as an API (application programming interface) between your script and the browser

- the model created by the DOM is the DOM tree, where each element, attribute and piece of content gets its own node on the tree
  - each node is an object