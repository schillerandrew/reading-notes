# HTML

## Chapter 5: Images

### Images

`<img>` with no closing tag

- #### Two required attributes

  - `src="URL"` not always a URL but usually
  - `alt="TEXT"` descriptive text for screen reader software

- #### Optional attributes

  - `title="TEXT"` additional info when hovered on
  - `height="NUMBER"` height in pixels
  - `width="NUMBER"` width in pixels

#### Image placement

- before a `p` element = paragraph is on new line after the image
- inside the beginning of a `p` element = paragraph is after the image, aligned with bottom of image
- middle of a `p` element = image breaks up paragraph, with words only wrapping closely on left and right near the bottom of the iamge

> - images should be saved in the correct format (often .jpg, .gif, or .png) and in the same pixel height and width that they will display as on the website

- jpg = best for images with many different colors and transitions (pictures)
- png = best with fewer colors and/or large areas of the same color (logos, graphics, etc.), or for use of transparency
- gif = best with fewer colors and/or large areas of same color, or with animations

## Chapter 11: Color

- CSS property `color:` works on text inside an element
  - RGB (red, green blue)
  - hex
  - color names (147 pre-set names)
  - `rgba` = RGB with opacity as the fourth value (alpha value -- the a)
  - `hsl` and `hsla` = hue, saturation, lightness (alpha)
- `background-color:`
- `opacity:`

## Chapter 12: Text

- CSS property `font-family:`
- `font-size:`
- `font-weight:` = bold (or normal)
- `font-style:` = italics or oblique (or normal)
- `text-transform:` = uppercase, lowercase, capitalize each word
- `text-decoration:` = underline, overline, strikethrough, etc.

- `line-height:`
- `letter-spacing;`, `word-spacing:`
- `text-align:` = `left`, `right`, `center`, `justify`
- `vertical-align:`
- `text-indent:`
- `text-shadow:`

- pseudo-elements `:first-letter` and `:first-line`
- pseudo-classes `:link` and `:visited`
- pseudo-classes `:hover`, `:active` and `:focus`
