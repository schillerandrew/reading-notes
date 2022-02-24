# Structure Webpages with HTML

> ## Wireframes
wireframe = a blueprint for the hierarchy/flow of a website/product and how users will interact with and use the website/product
- wireframes are meant to be bare-bones and easy to change – paper can be good for newbies or for working with clients, whereas online wireframes can be better for devs
- decisions about wireframing and planning are influenced by the end goal; more visual product might be conducive to paper wireframe

> ### Six steps to make a wireframe
1. Do your research: who are your users, how/why will they use your product, what are your end goals
1. Make sure your research can be referenced, or have a cheatsheet/summary of main research points
1. Map out user flow: have a strong understanding of how and why users will use your product – this can avoid structural problems down the road
1. Aesthetics can come later: wireframes need to be comprehensive, but not aesthetically pleasing – they outline and represent what will come later
1. Create pre-prototypes for initial testing
1. Build more complete prototypes

> ### Three wireframing principles
- Clarity
- Confidence: if the design is too unpredictable or non-intuitive, that can affect user confidence
- Simplicity

> ## HTML (HyperText Markup Language)
- HTML = a markup language that defines the structure of website content
- element = a part of a webpage, usually with an opening tag, attributes, and closing tag
  - elements can be nested, but most be closed in the same order that they are opened
- empty elements have no content and don’t necessarily have an opening and closing tag
- tag = does something with content
- attribute = extra information/configuration about an element

> ### Foundational elements
- `<!DOCTYPE html>` = doctype – a required preamble with not much other use
- `<html></html>` = html/root element – wraps around all content on the page
- `<head></head>` = head element – all content that isn’t displayed to the page’s viewers; ex: CSS, character set declarations, etc
- `<meta charset="utf-8">` = simply defines the character set; similar to doctype in that it’s an old but established practice
- `<title></title>` = title element – sets the title of this page, which will show in a browser tab and also a bookmark/favorite
- `<body></body>`= body element – all content that is displayed to the page’s viewers; sort of the opposite of the head element

> ### Common elements
- img element = `<img src=“URL/PATH” alt=“DESCRIPTIVE TEXT”>`
- headings = `<h1></h1>`, `<h2></h2>`, `<h3></h3>`, `<h4></h4>`, `<h5></h5>`, `<h6></h6>`
- HTML comment = `<!--COMMENT-->`
    - HTML comments are not rendered – they are a way to comment on your HTML code within the codebase itself
- p element = `<p>TEXT</p>`

> ### Lists
Unordered lists are used when the order of items in the list doesn’t matter, and ordered lists are used when the order does matter.
- ul element = `<ul>LI ELEMENT(S)</ul>`
- ol element = `<ol>LI ELEMENT(S)</ol>`
- li (list item) element = `<li>TEXT</li>`

> ### Semantics
When coding, we have to keep in mind semantics -- the meaning of specific pieces of code. There are many ways to code a website or even a single webpage, and using semantic elements helps make HTML code clearer and more effective. Here are some benefits:

- SEO is more impacted by the contents of semantic elements to determine search enging rankings

- Semantic elements can be 'signposts', for someone who is visually impaired, for someone trying to navigate your code for the first time -- anyone!

- Semantic naming is a best practice that is used across all programming languages, to more easily understand what certain chunks of code accomplish

- Examples of semantic elements are: `<header>`, `<footer>`, and `<article>`

> ### [Back to homepage](https://schillerandrew.github.io/reading-notes/)