## HTML

### Chapter 4: Links

- standard URL element = `<a href="URL">DISPLAYED-TEXT</a>`
- same folder = `FILENAME</a>`
- child folder = `CHILD/FILENAME</a>`
- grandchild folder = `GRANDCHILD/CHILD/FILENAME</a>`
- parent folder = `../FILENAME</a>`
- grandparent folder = `../../FILENAME</a>`
- standard email element = `<a href="mailto:EMAIL-ADDRESS">DISPLAYED-TEXT</a>`
- open link in new window = attribute and value `target="_blank"`
- open link at specific part of page = link to `id` attribute with syntax `<a href="#ID-NAME">DISPLAYED-TEXT</a>`

### Chapter 15: Layout

- all HTML elements have their own "box", either block-level or inline
- block-level boxes start a new line and are the main pieces of a page (`<h1>`, `<p>`, `<ul>`)
- inline boxes flow around text (`<img>`, `<b>`, `<i>`)

- if one element is nested within another, the outside element is called the parent (containing) element

#### Types of positioning/flow

- normal flow = block-level elements never appear side by side
- relative positioning = moves an element in a direction (top, right, bottom, left) away from where it normally would be
- absolute positioning = places an element in relation to its parent element, and the element doesn't affect position of any surrounding elements; element moves when user moves the page
- fixed positioning = type of absolute positioning that orients the element to the browser window instead of the parent element; element doesn't move when user moves the page
- floating elements = element goes to far left or far right of its box and becomes block-level (inline things can flow around it)

- `z-index` property = allows you to control the display order of overlapping boxes due to elements not being in normal flow

## JS

### Chapter 3: Functions, Methods and Objects (pp 86-99)

- calling a function, or function call = writing down the function's name (identifier), and possibly also values, so that function will run the code inside of it
- parameter = value or variable passed to a function
- return value = a value that is generated at the end of, or as a result of, a function completing
- a function can be called before it's declared
