## HTML

### Chapter 3: Lists

- definition lists
  - `<dl></dl>` = definition list
  - `<dt></dt>` = definition term
  - `<dl></dl>` = definition itself

- lists can be nested

### Chapter 13: Boxes

#### CSS properties

- `height:` or `width:` = height or width of the element, in pixels (px), percentage (%), or ems (em)
- ems base the size of the box on the size of the text within it (can be useful for different-sized screens)
- `min-width:`, `max-width:`, `min-height:`, `max-height:`
- `overflow: hidden;` = hide additional content that doesn't fit within its box
- `overflow: scroll;` = add a scrollbar so user can slide around to view content even though all of it doesn't fit in box

#### Border, margin, Padding

- border = border that around every box (visible or not)
- margin = area around the border
- padding = area inside the box, between the box and its content

- `border-width:` = in pixels, or `thin`, `medium`, `thick`
  - `border-top-width:`, `border-right-width:`, `border-bottom-width:`, `border-left-width:`
- `border-style:`, `border-color:`
- `border:` property can handle width, style and color all at once by listing the values in that order with just spaces between -- ex: `border: 1px dotted blue;`

- `padding:` (`-top`, `-right`, `-bottom`, `-left`)

- `margin:` (`-top`, `right`, `-bottom`, `-left`)

- setting left and right margins to auto centers something
- `text-align:` property is inherited by child elements

- `display: inline;` = block-level element will act like an inline element
- `display: block;` = inline element will act like a block-level element
- `display: inline-block;` = block-level element will flow like an inline element but otherwise behave like a block-level element
- `display: none;` = hides the element
- `visibility: hidden;` = hides the element (similar to `display: none;`) but leaves blank space
- `visibility: visible;` = shows the element

- `border-image:`
- `box-shadow:`
- `border-radius:`

## JS

### Chapter 4: Decisions and Loops (switch statements onward)

#### Switch statement

- similar to if-else statement, but can be faster because it only checks 'conditions' until it finds a match, whereas with a bunch of if statements they are all checked, even after a match
- start with a variable called a switch value that is checked against each case
- if no match is found then the default case is used
- each code block ends with `break;` (to prevent additional cases from being checked?)

- truthy values = `false`, `0`, empty string `''`
- falsy values = `true`, `1`, string with content `'bears'`

- unary operator = has just one operand
  -can use an `if` statement to check for an element and if the element is there the condition resolves as truthy; and it not then falsy to go into `else` code block

- logical operators don't always return true or false, because:
  - they return the value that ended the processing of the logical operator
  - the returned value might be truthy or falsy, instead of `true` or `false`

#### Loops

- loop = checks a condition, if it's `true`, a code block runs, and the process repeats; once the condition is `false`, the loop ends and the code block is not run again

- `for` loop = three parts before the code block: initialization (`i = 0;`), condition (`i < 10`;), update (`i++`

- `break` = stops a loop and goes to next statement of code outside of the loop (also used in switch statements)

- `continue` = stops and restarts the loop (if condition is `true` it will run code block as per normal)

- declare variables outside of loops when possible, because each pass of a loop recalculates the variables inside it

- `while` loop = loops *while* the condition is `true`
- `do while` loop = similar to while loop but has at least one guaranteed run before checking the condition
