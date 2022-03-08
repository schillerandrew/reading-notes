## HTML
> ## Chapter 2: Text

- whitespace collapsing = two or more sequential spaces are condensed into one space; two or more sequential line breaks are condensed into one break

- `<br>` = line break
- `<hr>` = horizontal rule (line)

- `<strong>` = `<bold>` by default
- `<em>` = `<i>` by default
- `<blockquote>` = block quote -- alternatively: `<q>`

> ## Chapter 10: Introducting CSS

### External CSS
-use empty tag `<link>` with the attributes `href`, `type="text/css"`, and `rel="stylesheet"`

### Internal CSS
- use tag `<style>` with attribute `type="text/css"` and type out CSS rules

### CSS selectors

- universal selector `*` = all elements in the document
- type selector `h1` = all elements with that name/type
- class selector `.note` = all elements where `class` attribute has a value of `note`
  - period followed by a value specifically used/repeated in certain class attribute(s)
- id selector `#note` = all elements where `id` attribute has a value of `note`
  - pound sign followed by a value specifically used/repeated in certain id attribute(s)
- `!important` after a value will give it precedence to other rules that apply to the same element

## JS
> ## Chapter 2: Basic JavaScript Instructions

- statement = individual line or step in a JavaScript script; ends with a semicolon `;`
- single-line comment = start with `//`
- multi-line comment = suround with `/*` and `*/`
- variable = container for values that can vary
  - declare variable before or while assigning it a value
  - variable names often use camelCase = no spaces, lowercase first word, uppercase later words
  - variable names must begin with: a letter, dollar sign (`$`), or underscore (`_`)
  - variable names can contain: letters, numbers, dollar signs (`$`), or underscores (`_`)
  - variable names can't contain: keywords or reserved words

### Arrays

- array = type of variable for holding an unknown number of related values in a list
  -values don't need to be of the same type
  - ex: `var colors = ['white', 'black', 'custom']`
- each value is assigned an index number, starting at 0
  -value can be retrieved by using it's index = `ARRAY-NAME[NUMBER]` or `colors[2]`
  -`ARRAY-NAME.length` = the number of values in the array

### Operators

- putting quotes around a number makes it a string
- using addition operator with a number and a string concatenates the number to the string
- using other arithmetic operators on a string results in the value `NaN` ("not a number")

> ## Chapter 4: Decisions and Loops

### Operators

#### Comparison operators
- `==` = `true` if same value
- `===` = `true` if same value and data type
- `!=` = `true` if not the same value
- `!==` = `true` if not the same value, and not the same data type
- `>`, `<`, `>=`, `<=`

#### Logical operators
- `&&`, `||`, `!`

### if statements

- if statement = if the condition evaluates to true, the code block executes
- if-else statement = if condition is true, that code block executes; if the condition is false, then the other code block (after the `else`) executes
  