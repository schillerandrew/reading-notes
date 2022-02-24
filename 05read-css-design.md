> # Design Webpages with CSS

## CSS (Cascading Style Sheets)
- CSS controls some of the basic aesthetics of webpages, the style, the layout, etc
- CSS runs on rules: groups of styles that should be applied to particular HTML elements or groups of elements
  - a rule begins with a *selector*, which selects the HTML element that will be styled
  - next is a set of curly braces `{ }`, and inside are one or more *declarations*, which are *property* and *value* pairs, separated by a semicolon `;`
- CSS is broken down into *modules*, to make it easier to learn about and find properties that you want to apply to elements
- Browsers usually have different levels of compatibility for a feature because the feature is rolled out unevenly over time across the different browsers -- keep this in mind

## Three Types of Style Sheets
- external = one or more pages (entire website)
  - defined in a link element, ex: `<link rel="stylesheet" href="mystyle.css">`
- internal = one page
  - defined in a style element, ex:
 ```
 <style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
```
- inline = one element
  - defined in the element it's styling

When multiple styles are specified for the same element, one of the styles will win out, according to a cascading order:
1. inline style
2. external or internal (in the head section)
3. browser default
- If external and internal (and no inline style) are competing to style the same element(s), whichever style sheet is placed lower (in the head element?) will win out.