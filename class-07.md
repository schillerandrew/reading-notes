> # HTML Tables & JS Constructor Functions

> ## HTML

### Tables

- `<table>`
- `<tr>` = (*t*able *r*ow) a new row in a table
- `<td>` = (*t*able *d*ata) a cell in a table
- `<th>` = (*t*able *h*eader) heading for a cell or row
  - `scope="row"` or `="col"` = specify if for a row or column
  - `rowspan="NUMBER"` = stretch a `<td>` or `<th>` across multiple rows
  - even if a cell is empty, use a `<td>` or `<th>` to represent the empty cell

  - `<thead>`, `<tbody>`, `<tfoot>`

> ## JS

### Constructor notation

- `let OBJECT-NAME = new Object();`
- add or update properties and methods using dot notation, and end with semicolon: `OBJECT.PROPERTY-OR-METHOD = VALUE;`
- `delete` = remove the property: `delete OBJECT.PROPERTY-NAME;`

### Built-in objects
- browser object model: `window`, `document`, etc
- document object model (DOM): `document`, `section`, etc
- global JavaScript objects: `String`, `Math`, etc