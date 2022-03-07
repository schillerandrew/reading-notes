> ## Introduction
### How people access the Web
- web browser <--> web server (web hosting common, less so for big companies that self-host)

> ## Chapter 1: Structure
### HTML
-attributes tell us more about an element
-attributes contain two parts: its name, and its value
-the terms "element" and "tag" are interchangeable, though technically they are different things

> ## Chapter 8: Extra Markup
- HTML comment = `<!-- -->`
- id attribute = global attribute for hooking up a single element to CSS, JS, etc
- class attribute = global attribute for grouping elements and hooking them up to CSS, JS, etc
- block element = always appears to start on new line -- ex: h1, p, ul, li
  - div element group text and non-text into a block
- inline element = always appears to continue on same line -- ex: a, b, em, img
  - span element = sort of the inline equivalent of the div element
  - iframe element = little windows into another website -- ex: Google Maps
  - meta element = extra information about a page, for search engines, etc
  - escape characters = allow special characters to be displayed -- ex: `<`, `>`, `&`

>  ## Chapter 17: HTML5 Layout
- HTML5 has many special elements that replace certain uses of div elements:
  - header
  - footer
  - nav = major navigational links, not necessarily at the bottom of the page?
  - article = sections off something that could be syndicated (blog, article, forum post)
  - aside = separates something from an article element or entire page
  - section = groups parts of a page together
  - hgroup = groups multiple headings together, especially a heading with a subheading
  - figure & figcaption = optional visual content -- ex: image, video, pullquote
- using a element to link to entire blocks is ok
- include CSS style and HTML conditional comment that tells browsers to see these new elements as block elements

> ## Chapter 17: Process & Design

### Website design questions
- **Who** visits your site?
- **Why** do you they visit your site?
- **What** do visitors do?
- **What information** do your visitors need?
- **When** exactly do visitors go to your site?

### Website design considerations
- site maps
- wireframes

> ## Chapter 1: The ABC of Programming
- a script is a list of instructions
- often, you must organize and plan out parts of a script before they become code
- property = aspect of an "object" (variable?)
- event = triggers based on user input or other conditions
- method = can make changes to properties