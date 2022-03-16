> # HTML Tables & JS Constructor Functions

## *HTML*

### Tables

- `<table>`
- `<tr>` = (**t**able **r**ow) a new row in a table
- `<td>` = (**t**able **d**ata) a new cell in a table
- `<th>` = (**t**able **h**eader) a new heading for a cell or row
  - even if a cell is empty, use a `td` or `th` to represent the empty cell
  - `scope="row"` or `="col"` = specify if for a row or column
  - `rowspan="NUMBER"` = stretch a `td` or `th` across multiple rows
  

  - `<thead>`, `<tbody>`, `<tfoot>`

## *JS*

### Constructors

> - constructor = function that creates object instances

- similar syntax as declaring a function, but with a capitalized name, rather than camelCase:

    ``` js
    function Person (aName, bName) {
    this.firstName = aName;
    this.lastName = bName;
    }
    ```

- parameters are unique property values (vary from object to object)
  - non-unique values can be hard-coded
- `this` refers to the object that will be created, not to the constructor that the `this` keyword sits within

- `let VARIABLE = new CONSTRUCTOR(PARAM1, PARAM2...);`

> - prototype = inherits

### Objects

- `let OBJECT-NAME = new Object();`
- add or update properties and methods using dot notation, and end with semicolon: `OBJECT.PROPERTY-OR-METHOD = VALUE;`
- `delete` = remove the property: `delete OBJECT.PROPERTY-NAME;`

### Built-in objects

- browser object model: `window`, `document`, etc
- document object model (DOM): `document`, `section`, etc
- global JavaScript objects: `String`, `Math`, etc
