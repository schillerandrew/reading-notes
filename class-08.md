> # CSS Layout

## *CSS*

- `display` property = specify if something is inline or block, and possibly also control children elements (via `display: flex`, which makes the element block-level and converts children elements to flex also, or `display: grid`)

- inline elements can't have specific width and height, it will be ignored

### Flexbox

- used for one-dimensional layouts (horizontal or vertical)
- Flexbox aligns child elements next to each other along inline axis, and stretches along block axis
- elements won't wrap and will try to stay together and squeeze into alloted spaces

### Grid

- used for multi-axis layouts
- unlike Flexbox, elements aren't grouped as much, and there is much more precision control over height, width, and overall placement

### Page size

- as of 2010, page size was a least 960-1000 pixels wide and 570-600 pixels long for initial page load ("above the fold") -- might be much higher now a decade later