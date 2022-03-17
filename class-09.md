> # Forms and JS Events

## *HTML*

## Chapter 7 Forms

- form control uses `<form>` elements, usually with an `action` attribute
- `method` attribute specifies either `"get"` or `"post`
  - `get` is better for small/short forms, or retrieving information from a database
  - `post` is better for anything else: file uploads, long forms, sensitive data, or updating a database
    - if `method` attribute isn't used, then the `get` method is used

- `<input>`
  - `type="text"`, `type="password"`
    - `name=`
    - `maxlength=`
- `<textarea>` = multi-line input field

## Chapter 14 Lists, Tables & Forms

- `list-style-type:`, `list-style-image: url("URL")`, `list-style-position:`
- `list-style:` = shorthand to define a) style b) image and c) position in any order

- `cursor:` = cursor style (`auto`, `crosshair`, `default`, `pointer`, `move`, `text`, `wait`, `help`, `url("URL")`)

## *JS*

## Chapter 6 Events

### Event categories

- user interface (UI) event -- ex: `scroll`, `resize`
- keyboard event
- mouse event -- ex: `click`
- focus event
- form event
- mutation event

### Event handling

- select element node
- specify event
- give it code